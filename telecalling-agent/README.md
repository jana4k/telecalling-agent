# Telecalling Agent

A voice agent solution for telecalling workflows, built with FastAPI and Pipecat.

## Prerequisites

- Python 3.11+
- uv (for dependency management)
  
## Installation

1. Clone the repository (already done)
2. Install dependencies:
   ```bash
   uv sync
   ``` 

## Usage

Run the application:

```bash
uvicorn inbound.main:app --reload --host [IP_ADDRESS] --port 5000
```