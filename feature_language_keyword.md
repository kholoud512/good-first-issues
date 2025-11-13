# Proposal: Add --language and --keyword flags

This change introduces two new CLI flags:
- `--language`: filters issues by programming language (e.g., Python, JavaScript)
- `--keyword`: searches for specific keywords in issue titles/descriptions

Example usage:
```bash
good-first-issues --language Python --keyword documentation
