# Bear Metal Docs

The knowledge base website for Bear Metal 2046, built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

![last commit](https://img.shields.io/github/last-commit/bear-metal-2046/bear-metal-2046.github.io?style=for-the-badge&label=last%20commit%3A)

![last website update](https://img.shields.io/github/last-commit/bear-metal-2046/bear-metal-2046.github.io/gh-page?style=for-the-badge&label=last%20website%20update%3A)

![commit activity](https://img.shields.io/github/commit-activity/w/bear-metal-2046/bear-metal-2046.github.io?style=for-the-badge&label=commit%20activity%3A%20)

![website status](https://img.shields.io/website?url=https%3A%2F%2Fbear-metal-2046.github.io&style=for-the-badge)

## Getting Started

### Prerequisites

- [Python 3.10+](https://www.python.org/)
- [pnpm](https://pnpm.io/) (`npm install -g pnpm`)

### Local Development

```bash
# Clone the repo
git clone https://github.com/bear-metal-2046/bear-metal-2046.github.io.git
cd bear-metal-2046.github.io

# Install Node dependencies (linting, spell check)
pnpm install

# Install Python dependencies (MkDocs, plugins)
pip install -r requirements.txt

# Start the dev server
pnpm dev
```

The site will be available at `http://127.0.0.1:8000`.

### Linting & Spell Check

```bash
pnpm test
```

This runs both `markdownlint-cli2` and `cspell` across all docs. Run this before pushing.

## Project Structure

```
.
├── docs/               # Site content (Markdown files)
│   ├── design/
│   ├── hardware/
│   ├── programming/
│   └── ...
├── includes/           # Auto-appended snippets (e.g. abbreviations)
├── mkdocs.yml          # MkDocs configuration & navigation
├── requirements.txt    # Python dependencies
├── Dockerfile          # Builds and deploys to gh-pages
└── package.json        # Node scripts (dev, build, lint, test)
```

## Contributing

See [BUILDING.md](BUILDING.md) for deployment details.

To add or edit content, create/edit Markdown files under `docs/` and update the `nav:` section in `mkdocs.yml`. See the [MkDocs Material docs](https://squidfunk.github.io/mkdocs-material/) for syntax reference (admonitions, tabs, grids, etc.).
