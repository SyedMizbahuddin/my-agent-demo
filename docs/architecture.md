# Architecture

## Overview

This is a placeholder for the project architecture description.

When the implementation is added, document:

- What the agent does (primary purpose)
- Key components (modules/classes/services)
- Data flow (how requests move through the system)
- External dependencies (LLM provider, vector DB, webhooks, etc.)

## Suggested structure

- **Agent Core**: orchestration, tool calling, prompt management
- **Tools/Integrations**: adapters for external APIs
- **State/Storage**: persistence, caching, conversation state
- **Interfaces**: CLI / HTTP API / SDK

## Non-goals

List what the project intentionally does *not* do (e.g., authentication, multi-tenant, billing).
