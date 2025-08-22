# Welcome to the ZeusDB Contribution Guide

Thank you for investing your time in contributing to our project! Thanks for your interest in contributing! This guide applies to **all repositories** in the ZeusDB organization.

We welcome all sorts of different contributions. Before making any type of contribution, please read our [Code of Conduct](https://github.com/ZeusDB/.github/blob/main/CODE_OF_CONDUCT.md) to keep our community approachable and respectable.

In this guide you will get an overview of the contribution workflow from opening an issue and creating a Pull Request (PR).

## New contributor resources

To get a good overview of the project, please first read the README document in the specific repository you're interested in contributing to.

In addition, here are some great general resources to help you get started with open-source contributions:
- [Finding ways to contribute to open source on GitHub](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)
- [Collaborating with pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests)

## Ways to contribute

There are multiple ways in which you can contribute to ZeusDB projects including:
- Reporting a Bug
- Analyzing the current code base
- Submitting a fix
- Suggest new features or improvements
- Becoming a maintainer
- Add or update documentation
- Writing integration guides
- Improving performance
- Adding tests
- Anything else we may have forgotten

## Getting started

### Reporting a Bug

We utilize GitHub Issues to raise, track and manage bugs. All open, pending, and closed cases for each project can be found in the Issues section of the respective repository.

Should you identify a bug in any ZeusDB project, please search if the issue already exists in the GitHub Issues page for that repository. You may be able to add more information or your own experience to an existing issue.

If a related issue doesn't exist, you can open a new issue using the repository's issue form.

To assist in fixing any issues raised more rapidly, please ensure that any bug reports include the following components (where necessary):
- A quick summary and/or background
- Any steps helpful to reproduce the bug
- Code or sample codes that were used
- What you expected to happen vs. what happened
- Exact error messages received (you can upload de-identified screenshots as well)
- Environment details (OS, Python version, package versions, etc.)


### Proposing Changes (code or docs)

We welcome contributions to the codebase of ZeusDB projects from everyone who is interested in making the projects better. If you want to propose a codebase change, please follow these steps:

1. **Fork** the repository and **create a branch** from `main`.  
   Use a descriptive name (e.g., `fix/hnsw-ef-search-default`, `feat/metadata-contains-operator`).
2. Make focused commits with clear messages  
   (Conventional Commits welcome but not required, unless the repo mandates it).
3. **Add/Update tests** and documentation as needed.
4. **Run linting and tests** locally; ensure CI passes.
5. Push your branch and open a **Pull Request** against `main`.
6. In the PR description, explain **what** changed and **why** (link issues).

### PR checklist

- [ ] Linked related issues (`Fixes #123`, `Closes #456`)  
- [ ] Tests added/updated and passing  
- [ ] Lint/format checks passing  
- [ ] Docs/README updated for user-visible changes  
- [ ] Backwards compatibility considered / migration notes included (if any)

> Tip: Small, focused PRs are easier to review and merge quickly.

Our team will review your PR and provide feedback as soon as possible. We may ask you to make additional changes, so please be prepared to iterate on your changes until they are ready to be merged.

We appreciate your contributions to the project and thank you for your time in submitting a pull request.

### Documentation Contributions

Documentation improvements are always welcome! This includes:
- Fixing typos or grammatical errors
- Clarifying existing documentation
- Adding examples or use cases
- Improving API documentation
- Creating new guides or tutorials

### Integration Contributions

We welcome contributions for new framework integrations:
- LangChain enhancements
- New framework integrations (LlamaIndex, Haystack, etc.)
- Example applications and demos
- Performance benchmarks

## Development Guidelines

### Code Quality
- Write clear, readable code with appropriate comments
- Follow existing code style and conventions
- Add tests for new functionality
- Ensure all tests pass before submitting PR
- Update documentation as needed

### Performance
- Consider performance implications of changes
- Add benchmarks for performance-critical code
- Profile code when making optimization changes

### Compatibility
- Maintain backward compatibility when possible
- Document any breaking changes clearly
- Consider impact across different Python versions and platforms

## Community

- Join our discussions in GitHub Discussions
- Follow us for updates and announcements
- Connect with other contributors and users

## Support

If you need help with contributing or have questions:
- Check existing GitHub Issues and Discussions
- Create a new Discussion for general questions
- Email us at contact@zeusdb.com for specific inquiries

## License

By contributing to any ZeusDB repository, you agree to license your contributions under the license specified in that repository's LICENSE file. Any contributed code or content must be your original work, and you warrant that you have the right to license it under the terms of the applicable license.

By contributing, you also acknowledge that your contribution will be included in the project under the same license as the rest of the repository.
