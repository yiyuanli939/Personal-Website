# Overview of My Website 

First, if you want to understand this website, you may view the `_quarto.yml` file. The file `_quarto.yml` is the project-level configuration file that tells Quarto how to build the site. 

The directory `posts/` stores all the blogs that I wrote. The file in the root directory `blog.qmd` is the listing page that gatheres everything under posts

## Some Quarto Commands

`quarto render` — build the project (or pass a file name) into _site/; use --profile prod or --output-dir to customize.

`quarto preview` — live-reload server for the project; auto-renders on save and opens a local URL.

`quarto check` — sanity-check your install, project metadata, and rendering capabilities; add check project to focus on the current folder.

`quarto inspect` — dump the final metadata that Quarto sees after all inheritance; handy to debug _metadata.yml.

`quarto format` — reflow/clean markdown and code fences; good for tidying shared posts.

`quarto help <command>` — built-in docs for any subcommand; e.g. quarto help render lists all flags.
