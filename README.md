# npm Documentation

[![Publish](https://github.com/npm/documentation/actions/workflows/publish.yml/badge.svg)](https://github.com/npm/documentation/actions/workflows/publish.yml)

This repository contains the content and build workflow for the [official npm documentation site](https://docs.npmjs.com/).

## Quick Start

1. **Install dependencies:**
   ```bash
   npm install
   ```
2. **Start the local development server:**
   ```bash
   npm run develop
   ```
   The site will be available at [http://localhost:8000](http://localhost:8000).
3. **Edit documentation content:**
   - The documentation is written in [MDX](https://mdxjs.com/) (Markdown + JSX).
   - Make changes in the `content` directory.
4. **Preview changes:**
   - Gatsby watches for file changes and hot-reloads the site instantly.
   - Review your edits at [http://localhost:8000](http://localhost:8000).
5. **Submit your changes:**
   - Commit your updates and open a pull request at [https://github.com/npm/documentation](https://github.com/npm/documentation/pulls).
   - The CI workflow will publish your PR to a GitHub Preview Page for review.
6. **Deploy:**
   - Once your PR is approved and merged, the site will be automatically deployed via [GitHub Actions](https://github.com/npm/documentation/actions/workflows/publish.yml).

## Contributing

We welcome contributions! Please read our [contributing guide](CONTRIBUTING.md) for instructions and best practices.

## Repository Structure

- `content/` — All documentation pages (MDX format)
- `src/` — Site configuration, custom components, and theme overrides
- `.github/workflows/publish.yml` — CI/CD workflow for building and deploying the site

## Resources

- [npm documentation site](https://docs.npmjs.com/)
- [Contributing guide](CONTRIBUTING.md)
- [Open pull requests](https://github.com/npm/documentation/pulls)
- [GitHub Actions workflow](https://github.com/npm/documentation/actions/workflows/publish.yml)

---

© npm, Inc.
