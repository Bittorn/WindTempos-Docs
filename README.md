# Wind Tempos Documentation

[Mkdocs documentation](https://www.mkdocs.org/)

[Theme documentation](https://asiffer.github.io/mkdocs-shadcn/)

## Project init (no-brain)

```sh
uv init myproject 
cd myproject
uv add --dev mkdocs mkdocs-shadcn pymdown-extensions Pygments
uv run mkdocs new .
echo -e "theme:\n  name: shadcn" >> mkdocs.yml
uv run mkdocs serve --livereload
```

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
