![Logo](./book/logo.png)

# LabBook

A streamlined and simple template for a project documentation using the *relatively* new `jupyter-book` project.

Sections are written in markdown or as Jupyter notebooks. This allows both code and research can be quickly written and disseminated through an auto-publishing model.

## Building

Building the project requires two steps:

1. Constructing the table of contents using ```jupyter-book toc book```.
2. Building the guide using ```jupyter-book build book```.

Markdown files are saved under `book/<section_name>/<page_name>.md` and are compiled in alphabetical order.

For more information on how to customise and edit these pages see the `jupyter-book` project documentation.

## Auto Publish

The repository includes a Github Action to auto-publish the content of the lab book to the gh-pages branch of the repository.
In practise this can be replaced by publishing to a centralised static internal/external web host.