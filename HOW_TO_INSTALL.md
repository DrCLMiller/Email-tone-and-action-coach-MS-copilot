# How to Install in Microsoft Copilot Studio

This repository is a source bundle. It is not a native Power Platform solution export. This means you have to set up your agent one piece at a time...as described below.

## Build the agent
1. In your Microsoft Copilot Studio, create a new agent in the target environment.
2. Name it **Email Tone and Action Coach**.
3. Copy the contents of `agent-instructions.md` from this github repository into your agent instructions field.
4. Download the `references/persona-playbook.md` and `references/review-checklist.md` files from this github
5. Add them to your agent as knowledge files (or incorporate them as copy/paste additions into the agent instructions if file knowledge is not appropriate for your environment).
6. Use `examples/example-prompts.md` for your starter prompts.
7. Be sure to test all response types and the make sure the human-review reminder is working.
