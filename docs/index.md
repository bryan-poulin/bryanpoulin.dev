# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

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

This is some normal text with ^^inserted content^^.

This is some original text. {++This text was added.++} {--This text was deleted.--} {--This was replaced-- >> ++This is the replacement.++} This is a section with a {>>This is a comment about the section.<<} comment. {==This text is highlighted.==}
