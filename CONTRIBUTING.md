# Contributing to Nexar Chat

Thank you for considering contributing to Nexar Chat.

We aim to build a modular, secure, and hybrid communication platform with a strong focus on architecture, maintainability, and self-hostability.

Please read this document carefully before contributing.

---

## Development Principles

- Strict TypeScript usage (no implicit any)
- Clear separation of concerns
- Modular architecture
- No tightly coupled cross-repository logic
- Clean commit history
- Explicit typing over magic behavior

---

## Branching Strategy

- `main` → stable branch
- `dev` → active development
- feature branches → `feature/<name>`
- fix branches → `fix/<name>`
- refactor branches → `refactor/<name>`

---

## Commit Convention

We follow conventional commits:

- `feat:` new feature
- `fix:` bug fix
- `refactor:` structural change
- `docs:` documentation
- `chore:` maintenance
- `test:` testing changes

Example:

```

feat(auth): implement JWT token rotation

```

---

## Pull Request Process

1. Fork the repository
2. Create a feature branch
3. Write clean, typed, documented code
4. Ensure it builds without errors
5. Open a Pull Request

PRs must:
- Have a clear description
- Explain architectural impact
- Not introduce unnecessary dependencies

---

## Code Quality

- Avoid global state
- Avoid hidden side effects
- No business logic inside controllers
- No untyped external API responses
- No silent error swallowing

---

## Security

Security vulnerabilities should **not** be opened publicly as issues.  
Instead, contact: `security@nexar.dev`
