# do not edit — managed by intent-os (intent: 75253141-5d38-4574-b9f8-5a7ec6cd634d, version: v1)
# AGENTS.md — [teste] Consolidacao final - pode fechar

> Vendor-neutral agent instructions managed by intent-os.

## Scope

Teste de ponta a ponta. O PR rascunho sera fechado em seguida e a aprovacao rejeitada.

## Artifacts Under Management

- `.controlplane/manifest.yaml`
- `.controlplane/context-summary.md`
- `.controlplane/constraints.md`
- `.controlplane/acceptance.md`
- `.controlplane/commands.md`
- `.controlplane/memory.md`
- `AGENTS.md`
- `CLAUDE.md`
- `.cursor/rules/intent-os.mdc`
- `.claude/settings.json`
- `.controlplane/hooks/pretooluse.sh`
- `.controlplane/hooks/posttooluse.sh`
- `.claude/mcp_servers.json`
- `.controlplane/PRD.md`
- `.controlplane/TASK.md`
- `.controlplane/MEMORY.snapshot.md`
- `.controlplane/context-map.json`
- `.controlplane/guardrails.json`
- `.github/copilot-instructions.md`

## Required Checks

- lint
- test
- policy:secret-leak

## Constraints

Allowed tools: `read`, `write`, `grep`, `run`

Denied tools: `network_egress`

Active policies:

- `236c857d-43cb-4536-96da-213834c55a77` v1.0.0 (severity: block)
- `b20450b7-de66-41c3-9307-08b292e93cea` v1.0.0 (severity: warn)

## Acceptance Criteria

- PR rascunho aberto
