---

### File 2: Save as `CONTRIBUTING.md`

```markdown
# Contributing Guidelines

Thank you for contributing to the Student Management CRUD project! To maintain code quality, clear history, and smooth collaboration, all contributors must adhere to the following standards.

---

## 1. Branch Naming Conventions

Always develop features or fixes in a dedicated branch. Never commit directly to the `main` branch. Use the following naming convention:

- `feature/<issue-id>-<short-description>`: For new features or UI additions.
  * *Example:* `feature/12-add-student-search`
- `fix/<issue-id>-<short-description>`: For bug fixes and error resolution.
  * *Example:* `fix/23-fix-sql-syntax-error`
- `docs/<issue-id>-<short-description>`: For documentation improvements or setup guides.
  * *Example:* `docs/10-update-installation-steps`
- `refactor/<short-description>`: Code cleanups without feature changes.
  * *Example:* `refactor/modularize-db-routes`

---

## 2. Commit Message Standards (Conventional Commits)

Commit messages must follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```text
<type>(<scope>): <subject description in present tense>
