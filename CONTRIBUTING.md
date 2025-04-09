# Contributing to terminal-emulator 

Thank you for considering contributing to this project! We appreciate your help and effort. Please take a moment to review the guidelines below to ensure a smooth contribution process.

## General Guidelines
- **Respect the Code of Conduct**: Please be respectful to others when interacting with the community.
- **Fork the repo**: Always fork the repository and create your branch from `main`.
- **Don’t push directly to `main`**: All changes should be made via pull requests (PRs).
  
## Commit Message Guidelines
We use the following prefixes to categorize commits:
- **`[feat]`**: For new features.
- **`[fix]`**: For bug fixes.
- **`[wip]`**:  Use for commits that are unfinished or in progress. These should not be merged into the main branch until the work is completed.
- **`[chore]`**: For tasks like dependency updates, build changes, or other non-functional tasks like project configuration updates.
- **`[hotfix]`**: Quick fix for a critical issue.
- **`[docs]`**: For changes to documentation.
- **`[style]`**: For code style changes (e.g., formatting).
- **`[refactor]`**: For refactoring code.
- **`[perf]`**: For performance improvements.
- **`[build]`**: For changes to build scripts or tools.
- **`[test]`**: For changes to tests.
- **`[revert]`**: Reverts a previous commit.
- **`[ci]`**: For changes related to CI/CD, like modifying the build pipeline or deployment scripts.

We recommend using **up to 2 prefixes maximum per commit** for clarity. If more than one prefix is used, they should be separated by a comma (e.g., `[hotfix], [perf]`). **Avoid using more than 3 prefixes per commit** to maintain readability and organization.
## Branching Strategy
- Feature branches should be named in the format: `feature/branch-name`.
- Bugfix branches should be named in the format: `bugfix/branch-name`.
- Do not push directly to the `main` branch. Always create a pull request to merge changes.

## Pull Request Guidelines
- **Always create a PR**: Every change should be made via a pull request.
- **Provide a detailed description**: In your PR description, include a summary of the changes made, and reference any issues related to the PR.
- **Peer review**: All code changes must be peer-reviewed before merging.

## Code Style & Quality
- Follow the coding conventions for **`C`**.
- Ensure your code is well-documented and easy to read.
- **Write tests**: All new features or bug fixes should include corresponding tests.
- **Ensure code quality**: Lint your code and run all tests before submitting a PR.

## Continuous Integration/Continuous Deployment (CI/CD)
- Ensure that your changes pass all tests before submitting the PR.
- Our CI system will automatically run tests on your PR.

## Issue Tracking
- Always create an issue if you find a bug or need a feature.
- Link your PR to the relevant issue (e.g., “Fixes #123”).

## License
By contributing, you agree that your contributions will be licensed under the project’s license. See the LICENSE file for more details.
