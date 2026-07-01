# Bull AI Agent Core

This repository is the Bull AI local working tree for `Bull-AI/agent-core`.

## Baseline

- Upstream source: `openai/codex`
- Baseline commit: `db887d0`
- Local branch: `bull-ai-main`
- Hosted default branch: `bull-ai-main`
- Created: `2026-07-01`

## Remotes

- `origin`: `git@github.com:Bull-AI/agent-core.git`
- `upstream`: `https://github.com/openai/codex.git`
- `research-source`: `/Users/avinashsinha/Work/tmp/agent-research/codex`

Hosted repo:

- `https://github.com/Bull-AI/agent-core`

## Fork Policy

- Keep upstream runtime patches small and rebaseable.
- Put Bull AI product logic in the separate `bull-ai-agent-runtime` repo as skills, MCP contracts, gateway code, UI code, and evaluations.
- Use this fork for runtime integration only: client identity, permission defaults, provider adapter hooks, skill-root/MCP bootstrap defaults, and event/storage hooks when the gateway cannot do them cleanly.
- Do not embed Bull AI business logic directly in runtime core.
- Do not put Supabase, Qdrant, or production service credentials into shell environments.

## Sibling Repo

Bull AI product/control-plane repo:

- `/Users/avinashsinha/Work/bull-ai-agent-runtime`
