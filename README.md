# n8n_projects

This repository contains a collection of advanced [n8n](https://n8n.io/) workflow JSON files for automating a variety of tasks, including AI-powered document generation, RAG (Retrieval-Augmented Generation) with vector stores, Telegram voice/text bots, Google Drive/Docs/Sheets integrations, and more.

## Key Workflows

- **Motivation letter**: Generates personalized motivation letters  using Pinecone vector search and Google Docs automation. Integrates AI agents for context-aware letter drafting.
- **Email final / Email**: Automates the creation of professional emails and drafts, leveraging Pinecone for profile data retrieval, Google Drive for file management, and Gmail for sending.
- **Rag agent supabase**: Implements a RAG pipeline using Supabase as a vector store, Google Drive for document ingestion, and Gemini embeddings for semantic search.
- **Assitant AI Agent**: A Telegram chatbot workflow that uses LLMs for conversational assistance and can interact with Google Sheets.
- **agent vocal telegram / agent vocal telegram22**: Telegram bots that handle voice-to-text and text-to-speech, integrating AssemblyAI for transcription and external TTS APIs for audio responses.
- **vector store wael**: Automates ingestion of Google Drive files into a Pinecone vector store with Gemini embeddings for semantic search and retrieval.
- **Rdv**: Manages appointment scheduling via forms and Google Calendar integration.

## Features

- **AI Agents**: Uses OpenRouter and Gemini models for text generation, extraction, and conversational flows.
- **Vector Search**: Integrates Pinecone and Supabase for semantic search and retrieval-augmented generation.
- **Google Workspace Automation**: Automates Google Docs, Drive, Sheets, and Calendar operations.
- **Telegram Bots**: Handles both text and voice interactions, including file and audio message processing.
- **Document Processing**: Supports PDF and Google Docs workflows, including conversion and upload/download automation.

## Usage

1. Import any JSON workflow into your n8n instance.
2. Configure the required credentials (Google, Pinecone, Supabase, OpenRouter, AssemblyAI, Telegram, etc.).
3. Activate the workflows as needed.

## Requirements

- [n8n](https://n8n.io/) (self-hosted or cloud)
- Accounts and API keys for integrated services (Google, Pinecone, Supabase, OpenRouter, AssemblyAI, Telegram, etc.)

## Structure

- Each `.json` file is a standalone n8n workflow.
- Workflows are modular and can be customized or combined as needed.

## License

This repository is for personal and educational use. Please ensure you comply with the terms of service for all third-party APIs used.

---

**Note:** Sensitive credentials are not included. Set up your own API keys and OAuth connections in your n8n instance.