#    MkDocs

MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file.

## Getting Started

To get started with MkDocs, follow these steps:

1. Install MkDocs:

```
pip install mkdocs
```

2. Create a new directory for your project:

```
mkdir myproject
```

3. Initialize a new MkDocs project:

```
cd myproject
mkdocs new .
```

4. Start the development server:

```
mkdocs serve
```

5. Open your browser and go to `http://127.0.0.1:8000/` to view your new documentation site.

## Writing Your First Page

To create a new page, create a new file in the `docs` directory with a `.md` extension. For example, create a new file called `about.md` in the `docs` directory:

```
docs
├── about.md