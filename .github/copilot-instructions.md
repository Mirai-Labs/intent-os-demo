# do not edit — managed by intent-os (intent: 8959be40-baeb-4042-b0f6-d9a613ce75db, version: v1)
# GitHub Copilot Instructions — [teste] Validacao da consolidacao - pode fechar

> This file is managed by intent-os. Do not edit manually.

## Intent Summary

Teste de ponta a ponta apos consolidar as imagens. O PR rascunho sera fechado em seguida.

## Control-Plane Artifacts

This repository is governed by an intent-os harness. Key artifacts:

- `AGENTS.md — vendor-neutral agent instructions (read this first)`
- `.controlplane/manifest.yaml — list of all managed artifacts`
- `.controlplane/constraints.md — allowed/denied tools and active policies`
- `.controlplane/acceptance.md — acceptance criteria and definition of done`
- `.controlplane/PRD.md — product requirements document`
- `.controlplane/TASK.md — actionable task checklist`
- `.controlplane/guardrails.json — machine-readable tool guardrails`
- `.controlplane/context-map.json — retrieved code/symbol/doc context`

## Key Constraints

Allowed tools: `read`, `write`, `grep`, `run`

Denied tools: `network_egress`

Do not modify files listed in `.controlplane/manifest.yaml` — they are regenerated on every bundle pull.
