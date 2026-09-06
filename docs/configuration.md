# Configuration

This section describes how to configure the project.

## Environment variables

> Add the actual variables used by the codebase once implementation exists.

| Variable | Required | Default | Description |
|---|---:|---|---|
| `OPENAI_API_KEY` | No | — | API key for the OpenAI provider (if used). |
| `MODEL_NAME` | No | — | Model identifier (e.g., `gpt-4o-mini`). |

## Configuration files

If your project supports configuration files (e.g., `.env`, `config.yaml`, `config.json`), document:

- expected file name(s)
- required/optional keys
- example config

## Secrets

Recommend using environment variables or a secrets manager; avoid committing keys to the repo.
