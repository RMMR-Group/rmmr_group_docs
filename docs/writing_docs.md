---
title: Writing Documentation
---

## What to document

The general philosophy is to document anything that you think someone else might have to do after you, and that took you more than a simple google search to figure out. In general, it's better to err on the side of writing a sketchy note, rather than waiting until you have time to write perfect documentation (and then never getting around to writing the perfect document).

If you find documentation that is out of date, please do try to update it. Everything is version controlled, so no information is ever lost when you make an edit. Be bold!

## Forking the repo

The repos for the documentation is here: [https://github.com/RMMR-Group/rmmr_group_docs](https://github.com/RMMR-Group/rmmr_group_docs)

You can fork this repo to your personal github space in order to make changes to it, and file pull requests when you've got an update ready to contribute.

## Structure of the docs

We're using `mkdocs` to generate the documentation. You can find the manual for `mkdocs` here:
[https://www.mkdocs.org](https://www.mkdocs.org)

Documentation is written in Markdown, which is designed to be pretty lightweight. You can find a description of the syntax here:
[https://www.markdownguide.org](https://www.markdownguide.org)

At the root level you'll find a file named `mkdocs.yml`, which defines the table of contents for the documentation. If you add a new file, be sure to add it here so it becomes part of the docs.

## Local testing

Local testing uses `nix` to setup the environment. You can find more info on setting up `nix` in the ["Using nix Package Manager"](using_nix.md) section.

Local testing can be done by simply running `nix-shell` in the root directory of the repo, and then running `mkdocs serve`. This starts a basic web server, which you can then access in your web browser at `127.0.0.1`. This will dynamically update as you modify your local copy of the docs.

## Uploading a change
