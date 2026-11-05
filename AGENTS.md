# do not edit — managed by intent-os (intent: b20bd0ac-7619-41bf-acc3-94ca679c4007, version: v1)
# AGENTS.md — [teste] Validacao do novo GitHub App - pode fechar

> Vendor-neutral agent instructions managed by intent-os.

## Scope

Teste de ponta a ponta do Intent OS com o novo App. O PR rascunho sera fechado em seguida.

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
