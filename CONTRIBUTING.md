# Contributing to NuvyraHub

Thanks for helping improve NuvyraHub. These guidelines apply across our repositories unless a project has more specific instructions.

## Before you start

1. Search existing issues and pull requests to avoid duplicates.
2. For a substantial change, open an issue or discussion first to align on scope.
3. Never include secrets, private keys, seed phrases, production credentials, customer data, or real funds in code, logs, screenshots, or tests.

## Development workflow

1. Fork the repository or create a branch according to your access level.
2. Keep changes focused and use descriptive commit messages.
3. Add or update tests and documentation when behavior changes.
4. Run the project's formatter, linter, tests, and relevant security checks.
5. Open a pull request using the template and explain the motivation, approach, and trade-offs.

## Smart contracts and Web3 changes

- Treat contract changes as security-sensitive.
- Include tests for access control, reentrancy-sensitive flows, authorization, boundary cases, and failure paths where applicable.
- Document storage-layout, upgradeability, and migration implications.
- Do not claim an audit or security guarantee unless it has been independently verified.
- Use local chains, testnets, and mock assets for development. Never test with production funds.
- Explain gas or transaction-cost implications when relevant.

## AI and inference changes

- Document model inputs, outputs, limitations, dependencies, and expected resource requirements.
- Avoid logging sensitive prompts, credentials, or user data.
- Add tests for validation, error handling, timeouts, and rate limits where applicable.

## Pull request checklist

- [ ] The change has a clear purpose and appropriate scope.
- [ ] Tests and checks pass, or known failures are explained.
- [ ] Documentation is updated.
- [ ] No secrets or sensitive data are included.
- [ ] Security, licensing, and backward-compatibility implications are described.

By contributing, you agree that your contributions are provided under the license specified by the target repository. If a repository has no license, ask maintainers before contributing.
