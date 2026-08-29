# Email Tone and Action Coach for Microsoft Copilot Studio

A source bundle for creating a recipient-aware email drafting and review agent in Microsoft Copilot Studio.

## What it does
- Clarifies the requested action, owner, timing, dependencies, and next steps.
- Adapts formality, directness, technical detail, and structure to the recipient.
- Preserves the sender's substantive meaning and commitments.
- Flags wording that may imply authorization, acceptance, waiver, added scope, or commitments.
- Requires human review before sending.

## Repository contents
- `INSTALL.md`: setup and native solution-export guidance.
- `manifest.json`: source-bundle metadata.
- `agent-instructions.md`: instructions to paste into the agent.
- `examples/example-prompts.md`: test and starter prompts.
- `references/persona-playbook.md`: recipient-specific drafting guidance.
- `references/review-checklist.md`: final quality and risk checks.



## Important packaging note
This repository ZIP is a source bundle, not a native Power Platform solution. For one-step import into another Copilot Studio environment, build the agent and export it from Copilot Studio as a Power Platform solution ZIP, then attach that unmodified ZIP to a GitHub Release.

## Version
1.0.0
