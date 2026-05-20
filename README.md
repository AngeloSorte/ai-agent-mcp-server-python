# AI Agent MCP Server (Python)

Lightweight MCP-style DevOps Tool Server built with Python and FastAPI.

## Features

- Modular AI-agent tool architecture
- GitHub repository info tool
- Log analyzer tool
- SQLite query tool
- FastAPI backend
- Easy to extend

## Technologies

- Python
- FastAPI
- SQLite
- Uvicorn

## Run Locally

Install dependencies:

bash
pip install fastapi uvicorn pydantic nest_asyncio

Run:

python server.py

Server runs on:

http://localhost:8000

## Available Tools

github_repo_info

Returns mock GitHub repository information.

log_analyzer

Analyzes logs and counts errors/warnings.

db_query

Runs SQLite queries on an in-memory database.

## Example Request

POST /run

{
  "tool": "github_repo_info",
  "payload": {
    "repo": "example-repo"
  }
}

## Future Improvements

Real GitHub API integration
Authentication
Docker support
MCP protocol compatibility
Streaming responses

## Roadmap

- GitHub API integration
- Authentication layer
- Docker deployment
- Real MCP protocol support

## Author

Angelo Sorte - Computer Engineer focused on AI systems, backend engineering and ethical technology.
