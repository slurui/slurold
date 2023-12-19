# Contributing to Slur

Thank you for your interest in contributing to Slur! Your contributions are greatly appreciated and we strive to make this process as smooth and accessible as possible. Here are the guidelines for contributing to our project.

## Our Development Process

We use GitHub to host code, track issues and feature requests, as well as review and merge pull requests.

## Contributing via Pull Requests

We enthusiastically welcome your pull requests. To contribute:

1. Fork the repository and create your branch from `master`.
2. If you add new code, please include tests and ensure they pass.
3. Update the documentation to reflect any changes.
4. Ensure all tests in the suite pass after your changes.
5. Check that your code adheres to our linting standards.
6. Submit your pull request for review.

## Licensing

Your contributions will be licensed under the [MIT License](https://github.com/slurui/slur/blob/master/LICENSE), which is the license covering this project. Please contact the maintainers if you have any concerns.

## Reporting Bugs

We use GitHub issues to track public bugs. Report a bug by [opening a new issue](https://github.com/slurui/slur/issues/new). Good bug reports are detailed and precise. Ideally, they include:

- A concise summary and background.
- Steps to reproduce the issue, being as specific as possible.
- What you expected to happen and what actually happened.
- Any additional notes or theories about the issue.

## Code Style Guidelines

Our project adheres to strict coding standards to ensure readability and maintainability. Here are the key points you should follow when contributing:

- **Indentation and Formatting**: Use 2 spaces for indentation. Run `pnpm run prettier` to automatically format your code according to our style guidelines.
- **ESLint with Airbnb Style Guide**: We follow the Airbnb style guide enforced through ESLint. Ensure your code passes ESLint checks by running `pnpm run eslint`.
- **CommitLint for Commit Messages**: Our project uses CommitLint to enforce structured and readable commit messages. Follow the pattern specified in our CommitLint configuration. The key rules include:
  - Commit types should be in lower-case (e.g., `feat`, `fix`, `docs`).
  - The commit subject should be in sentence-case.
  - The maximum header length is 50 characters.

These guidelines help maintain our code's consistency and quality. Before submitting your pull request, ensure your code adheres to these standards.

## Questions or Suggestions?

If you have any questions or suggestions regarding our contribution process, please feel free to reach out to the project maintainers.

---

This contribution guide is inspired by and adapted from [Facebook's Draft](https://github.com/facebook/draft-js/blob/master/CONTRIBUTING.md) contribution guidelines.
