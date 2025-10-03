# Contributing

Thanks for helping improve Vaidya projects! Small, focused contributions are welcome.

## Ways to contribute
- File issues with clear repro steps
- Improve docs/readmes/examples
- Small PRs fixing bugs or adding tests
- Propose changes via a short design note (issue → discussion → PR)

## Ground rules
- No secrets/PII in code or issues.
- Keep PRs small and single-purpose.
- Follow style/linting and add tests when code changes.

## Dev quick refs
**Go**: Go 1.22+  
- `go fmt ./... && go vet ./...`  
- (if configured) `golangci-lint run`  
- `go test ./...`

**Elixir**: OTP 26+/Elixir 1.16+  
- `mix format && mix credo`  
- `mix test`

**TypeScript**  
- `npm run lint && npm run test` (or project scripts)  
- Prettier/ESLint where configured

## Commits & PRs
- Use **Conventional Commits** (e.g., `feat: …`, `fix: …`, `docs: …`).
- Branch: `topic/short-description`.
- Include: tests, docs/README updates, and a brief rationale.
- Checklist:
  - [ ] Lint/format pass
  - [ ] Unit tests added/updated
  - [ ] No secrets/credentials
  - [ ] README or comments updated

## Issue triage
We aim to **respond within 3 business days**. Tag “good first issue” and “help wanted” are beginner-friendly.

## Security
If you suspect a vulnerability, follow **SECURITY.md** (private report). Please do not open a public issue.

## License
By contributing, you agree your contributions are licensed under the repository’s stated license.
