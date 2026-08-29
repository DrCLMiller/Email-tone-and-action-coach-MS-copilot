# Install in Microsoft Copilot Studio

This repository is a source bundle. It is not a native Power Platform solution export.

## Build the agent
1. In Microsoft Copilot Studio, create a new agent in the target environment.
2. Name it **Email Tone and Action Coach**.
3. Copy the contents of `agent-instructions.md` into the agent instructions field.
4. Add `references/persona-playbook.md` and `references/review-checklist.md` as knowledge files, or incorporate them into the instructions if file knowledge is not appropriate for your environment.
5. Use `examples/example-prompts.md` for starter prompts and testing.
6. Test all required response sections and the exact human-review reminder.
7. Review authentication, sharing, data-loss-prevention, and governance settings before publishing.

## Create the native cross-tenant package
After the agent works in your development environment:
1. Add the agent to a custom Power Platform solution in Copilot Studio.
2. Include all required agent components and dependencies.
3. Export the solution as a ZIP file.
4. Test importing that ZIP into a separate environment.
5. Publish the tested exported ZIP as a GitHub Release asset.

Do not rename or alter files inside the exported Power Platform solution ZIP.
