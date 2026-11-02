# Ebook cover agent workflow

This repository versions the reusable instructions and any future scripts or configuration for creating ebook covers with the agent. The current workflow is defined in `AGENTS.md`; it is not a standalone software application.

For a new batch, supply an Excel file and identify it in this project's chat. The agent reads the book information, researches genre cover references, writes English prompts, creates and checks each cover, and uploads the finished images to the configured Google Drive folder.

Generated covers and other batch files stay outside Git version control. GitHub updates are for changes to the workflow or software, not for each batch of books. Existing covers are revised only on request.

The Drive destination and upload verification rules are in `AGENTS.md`. Local inputs, generated assets, and upload records are ignored by Git. Covers committed before this policy remain in earlier Git history; the policy does not rewrite that history.
