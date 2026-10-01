# Law Agent

Law Agent is an experimental legal assistant built with FastAPI and a local LLM.

The application allows users to organize cases, upload PDF documents, and interact with their content through a RAG-based chat interface.

## Technologies

- FastAPI
- Svelte
- Agno
- Ollama
- Sentence Transformers
- SQLite / sqlite-vec
- PyMuPDF4LLM
- Tailwind CSS

## Current Architecture

Documents are converted to Markdown, split into chunks, embedded locally, and stored in a SQLite vector database.

During a conversation, relevant document chunks are retrieved and provided as context to a locally hosted LLM through Ollama.

## Status

The project is functional but requires architectural refactoring and further improvements.
