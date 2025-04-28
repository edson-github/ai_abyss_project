# AI Abyss Project

An intelligent AI-powered customer service system designed for Abyss Precision's DeepDive 1000M watch support and maintenance tracking.

## Overview

The AI Abyss Project is a sophisticated customer service platform that combines artificial intelligence with technical support capabilities. This system provides automated assistance for Abyss Precision watch owners, handling inquiries about product specifications, warranty information, and maintenance status tracking.

## Features

- **Intelligent Chat Interface**: Web-based chat interface for customer interactions
- **Service Status Tracking**: Real-time tracking of watch maintenance and repair status
- **Technical Documentation**: Integrated access to product manuals and specifications
- **Warranty Management**: Automated warranty information handling
- **Authorized Service Centers**: Information about worldwide service locations
- **Multi-Context Understanding**: Smart context retention for improved conversation flow

## Technical Architecture

### Backend Components
- Flask-based REST API
- LangChain integration for AI processing
- FAISS vector store for efficient document retrieval
- SQLite database for service record management
- OpenAI integration for natural language processing

### Frontend Components
- Streamlit-based user interface
- Real-time chat functionality
- Dynamic response handling
- Session management

## Setup and Installation

1. Install required dependencies:
```bash
pip install -r requirements.txt
```