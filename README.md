# Agentic Medical AI

An advanced agentic AI medical research and education assistant combining Retrieval-Augmented Generation (RAG), multi-agent orchestration, medical literature research, and evidence-grounded responses.

## Project Overview

Agentic Medical AI aims to provide an intelligent assistant that can retrieve medical knowledge from trusted reference materials, search biomedical literature, analyse evidence, and generate structured responses with source references.

The project explores modern AI engineering techniques, including:

- Advanced Retrieval-Augmented Generation (RAG)
- Multi-agent orchestration using LangGraph
- Medical document processing and knowledge retrieval
- Vector databases and semantic search
- Biomedical literature research
- Evidence-grounded response generation
- AI safety and response validation
- Multimodal AI capabilities (vision and voice)

**Project status:** Initial development — project structure and environment setup.

## Architecture

The application is organised into modular components:

| Component | Responsibility |
|---|---|
| FastAPI backend | Application entry point and API endpoints |
| Agent system | Specialised medical, research and safety agents |
| Knowledge system | Document ingestion, chunking, embeddings and retrieval |
| Tools | External research and biomedical search integrations |
| Workflows | Multi-agent coordination using LangGraph |
| Frontend | User interface for interacting with the assistant |

## Technology Stack

- **Language:** Python
- **Backend:** FastAPI
- **AI orchestration:** LangChain and LangGraph
- **LLM integration:** OpenAI / local models
- **RAG:** Document processing, embeddings and semantic retrieval
- **Vector database:** Pinecone
- **External research:** Tavily, PubMed and NCBI resources
- **Frontend:** HTML, CSS and JavaScript
- **Testing:** Pytest

Technologies will be introduced progressively as the project develops.

## Knowledge Sources

The initial knowledge base includes medical reference materials such as:

- Gale Encyclopedia of Medicine, Volume 1 (A–B)
- Open educational medical textbooks and reference materials

Future integrations may include:

- PubMed biomedical research
- NCBI Bookshelf
- MedlinePlus
- World Health Organization publications

Each source will be tracked using document metadata, including publication date, source type and licensing information.

## Project Structure

```text
agentic-medical-ai/
│
├── app/
│   ├── agents/
│   ├── knowledge/
│   ├── tools/
│   ├── workflows/
│   ├── schemas/
│   ├── config.py
│   └── main.py
│
├── data/
│   ├── raw/
│   └── processed/
│
├── frontend/
│   └── templates/
│       └── index.html
│
├── tests/
├── docs/
├── notebooks/
│
├── .env.example
├── .gitignore
├── requirements.txt
└── README.md
```

## Development Roadmap

- [ ] Project foundation and configuration
- [ ] Medical PDF ingestion and text extraction
- [ ] Document chunking and metadata management
- [ ] Embedding generation and vector database integration
- [ ] Semantic and hybrid retrieval
- [ ] Advanced RAG and retrieval evaluation
- [ ] LangGraph multi-agent architecture
- [ ] PubMed and external research integration
- [ ] Evidence analysis and citation generation
- [ ] Safety and response validation
- [ ] Frontend and FastAPI integration
- [ ] Multimodal capabilities (vision and voice)
- [ ] Evaluation, monitoring and deployment

## Installation

Clone the repository:

```bash
git clone https://github.com/ammohamedds/agentic-medical-ai.git
cd agentic-medical-ai
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows CMD:

```cmd
.venv\Scripts\activate.bat
```

Install dependencies:

```bash
python -m pip install -r requirements.txt
```

Configure environment variables by creating a `.env` file based on `.env.example`.

## Important Disclaimer

This project is intended for educational, research and medical information purposes. It is not a substitute for professional medical advice, diagnosis or treatment. Its outputs are not clinically validated.

## Author

Ahmed Mohamed

GitHub: [@ammohamedds](https://github.com/ammohamedds)