# Contributing

This guide applies only to Vaidya Solutions repositories that explicitly accept public contributions. Private and proprietary repositories — including Gideon — are not open to external contribution through ordinary forks or pull requests.

External work for private repositories requires an approved, scoped engagement and must not be inferred from this document.

## Ways to contribute

- File focused issues with clear reproduction steps in public repositories that accept them.
- Submit small, single-purpose pull requests with tests and documentation.
- Propose larger changes through an issue or discussion before writing code.

## Ground rules

- Do not submit secrets, credentials, private keys, customer data, production identifiers, private logs, or unapproved copied code.
- Disclose material third-party dependencies and any licensing implications.
- Follow repository-local setup, validation, and style guidance.
- Keep pull requests small and single-purpose.

## Development quick reference

**Go**: follow the repository's `Makefile` or documented validation commands. Typical targets: `make test`, `make lint`, `make build`.

**TypeScript**: follow the repository's `package.json` scripts or documented commands. Common targets: `lint`, `typecheck`, `test`, `build`.

## Commits and pull requests

- Use [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`, etc.).
- Include tests, documentation updates, and a brief rationale.
- Verify lint, format, and tests pass before submitting.

## Security

Report suspected vulnerabilities privately under the repository's `SECURITY.md`. Do not open a public issue for sensitive reports.

## License

By contributing to a public repository, you agree your contributions are licensed under that repository's stated license.
