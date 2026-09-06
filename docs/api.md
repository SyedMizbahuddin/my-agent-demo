# API reference

> This project is currently a placeholder (no code has been detected in the repository). Update this file once API endpoints/SDK methods are implemented.

## High-level overview

Document the interfaces your agent exposes:

- CLI commands
- HTTP endpoints (REST)
- SDK usage (language-specific)

## Suggested HTTP API (if applicable)

### `POST /v1/agent/run`

Runs the agent with the provided input.

**Request body**

```json
{
  "input": "string",
  "session_id": "string (optional)",
  "config": {
    "model": "string (optional)",
    "temperature": 0.7
  }
}
```

**Response**

```json
{
  "output": "string",
  "session_id": "string",
  "meta": {
    "tokens": 123,
    "latency_ms": 45
  }
}
```

## Errors

Describe error formats and common HTTP status codes.

- `400 Bad Request`
- `401 Unauthorized`
- `500 Internal Server Error`
