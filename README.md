# Book

A Quarto book project template with chapters organized as separate markdown files.

## Project Structure

- `_quarto.yml` - Quarto book configuration
- `index.qmd` - Book homepage/preface
- `intro.md` - Introduction chapter
- `chapter1.md` - First chapter
- `chapter2.md` - Second chapter
- `references.md` - References section
- `references.bib` - Bibliography file
- `pixi.toml` - Pixi environment configuration with dependencies

## Getting Started

### Prerequisites

Install [pixi](https://pixi.sh/) if you haven't already:

```bash
curl -fsSL https://pixi.sh/install.sh | bash
```

### Setup

Install dependencies using pixi:

```bash
pixi install
```

### Preview the Book

Preview the book locally with live reload:

```bash
pixi run preview
```

### Render the Book

Render the book to HTML and PDF:

```bash
pixi run render
```

The output will be generated in the `_book/` directory.

### Clean Build Artifacts

Remove generated files:

```bash
pixi run clean
```

## Adding New Chapters

1. Create a new markdown file (e.g., `chapter3.md`)
2. Add your content using markdown syntax
3. Add the file to the `chapters` list in `_quarto.yml`

## Learn More

- [Quarto Books Documentation](https://quarto.org/docs/books)
- [Pixi Documentation](https://pixi.sh/)