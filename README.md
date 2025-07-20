# Learning Path Generator with Model Context Protocol (MCP)

This project is a Streamlit-based web application that generates personalized learning paths using the Model Context Protocol (MCP). It integrates with various services including YouTube, Google Drive, and Notion to create comprehensive learning experiences.

## Features

- 🎯 Generate personalized learning paths based on your goals
- 🎥 Integration with YouTube for video content
- 📁 Google Drive integration for document storage
- 📝 Notion integration for note-taking and organization
- 🚀 Real-time progress tracking
- 🎨 User-friendly Streamlit interface

## Prerequisites

- Python 3.10+
- Google ai Studio API Key
- Pipedream URLs for integrations (YouTube and either Drive or Notion)

## Installation

1. Clone the repository:

2. Create and activate a virtual environment:

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## Configuration

Before running the application, you'll need to set up:

1. Google API Key
2. Pipedream URLs for:
   - YouTube (required)
   - Google Drive or Notion (based on your preference)

## Running the Application

To start the application, run:
```bash
streamlit run app.py
```

The application will be available at `http://localhost:8501` by default.

## Usage

1. Enter your Google ai studio API key and Pipedream URLs in the sidebar
2. Select your preferred secondary tool (Drive or Notion)
3. Enter your learning goal (e.g., "I want to learn python basics in 3 days")
4. Click "Generate Learning Path" to create your personalized learning plan

## Project Structure

- `app.py` - Main Streamlit application
- `utils.py` - Utility functions and helper methods
- `prompt.py` - Prompt template
- `requirements.txt` - Project dependencies

  ## Images
  <img width="1291" height="857" alt="Image" src="https://github.com/user-attachments/assets/f8e300a0-9c80-42ad-8625-c2544543af2a" />
<img width="1919" height="956" alt="Image" src="https://github.com/user-attachments/assets/3215af92-f1d6-42fc-b8b2-a193cdb906df" />
<img width="1915" height="953" alt="Image" src="https://github.com/user-attachments/assets/e0b2b1f6-2fb5-4f85-b064-b2ae5f4b88b5" />
<img width="1917" height="955" alt="Image" src="https://github.com/user-attachments/assets/f9d3c399-fed2-48ee-9a23-0897be95955c" />
<img width="1911" height="1079" alt="Image" src="https://github.com/user-attachments/assets/bd6252be-12a1-497d-93b7-3803cde9f6e5" />
