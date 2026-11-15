# Local agent notes

## Public repo rules

- Never include private business goals, internal strategy or non-public objectives in commit messages, PR titles or bodies, issues or any other public artifacts.
- Keep public-facing explanations neutral and implementation-focused.

## Linting

- Run `npx awesome-lint` locally before committing changes to `README.md`. CI runs it and blocks PRs that fail.
- The `awesome-spell-check` rule enforces the casing of known terms (for example "GitHub", "JavaScript").

## README structure

- Entries use `- [Name](https://url) - One-sentence description ending with a period.`
- New entries go at the end of their section, before the next `##` heading.
- Descriptions are concise and factual, with no marketing language or superlatives.
