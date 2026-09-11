# Contributing to Garama HQ

First off, thank you for considering contributing to Garama HQ projects! Contributors help build better tooling, robust architectures, and dependable software for the entire community.

To ensure a smooth collaboration, please review the following guidelines before submitting your contributions.

---

## 🗺️ How to Contribute

### 1. Find or Report an Issue
* Check the [Garama HQ Repositories](https://github.com/garamahq) to see if the bug or feature is already being discussed in the relevant repository's issue tracker.
* If not, open a new issue using the appropriate template (Bug Report or Feature Request).
* For security-related issues, please refer directly to our [Security Policy](https://github.com/garamahq/.github/blob/main/SECURITY.md) instead of opening a public issue.

### 2. Fork & Create a Branch
Fork the repository and create a branch off `main` (or the default branch of the repository). Use a clear and descriptive branch naming pattern:
* `feat/your-feature-name` for new features.
* `fix/bug-description` for bug fixes.
* `docs/doc-topic` for documentation updates.

Example:
```bash
git checkout -b feat/add-caddy-tls-metrics
```

### 3. Development & Standards
* **Code Style:** Adhere to the established styling, linting, and formatting rules of the specific repository (e.g., Prettier, ESLint, TypeScript compiler configs, or PHP CodeSniffer).
* **Testing:** Ensure all existing tests pass and write new tests covering your added features or bug fixes.
* **Documentation:** Update relevant markdown files, inline documentation, and comments if you introduce new configuration parameters, API options, or workflows.

### 4. Commits & Conventional Commits
We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification across all repositories. Ensure your commit messages use the following structure:

```
<type>(<scope>): <short imperative summary>

[optional body describing the 'why']
```

**Common Types:**
* `feat`: A new feature
* `fix`: A bug fix
* `docs`: Documentation changes
* `style`: Formatting, missing semi-colons, etc. (no production code changes)
* `refactor`: Refactoring production code (no new features or bug fixes)
* `test`: Adding missing tests or correcting existing tests
* `chore`: Updating build tasks, dependencies, package manager configs, etc.

**Example Commits:**
```bash
feat(router): integrate automatic failover mechanism
fix(auth): prevent token refresh drift on unauthorized routes
```

### 5. Submit a Pull Request
When your changes are ready, push your branch and open a Pull Request (PR) against the `main` branch.
* Fill out the PR template completely.
* Ensure the CI/CD pipeline builds successfully and passes all status checks.
* Reference the related issue(s) using GitHub's auto-linking keywords (e.g., `Closes #12`).

### 6. Code Review & Rebasing
A maintainer will review your Pull Request. If updates are requested:
1. Make the changes in your local branch.
2. If the default branch has advanced, rebase your branch:
   ```bash
   git checkout main
   git pull origin main
   git checkout feat/your-feature-name
   git rebase main
   git push --force-with-lease origin feat/your-feature-name
   ```

---

Thank you for your time and effort in helping build Garama's platforms and tools!
