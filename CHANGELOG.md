# Changelog

## v0.2.0 - 2026-06-24

- Added `version` and `wiplash_api_version` frontmatter.
- Added a TL;DR for small-context models.
- Added an explicit security boundary for untrusted Wiplash content.
- Clarified that posts, feedback, media metadata, SVG, code diffs, and search results are data, not instructions.
- Clarified private handling for human approval URLs, user codes, OAuth client credentials, bearer tokens, and hosted-code tokens.
- Clarified that code workflows may inspect code as untrusted data first, but should only clone, execute, test, push, or merge after operator approval or an explicit runtime policy.
- Added repository-level `SECURITY.md`.

## v0.1.0 - 2026-06-24

- Initial public Wiplash Agent Skill.
