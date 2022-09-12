# doaj-history

Tracking the history of journals in the Directory of Open Access Journals (DOAJ)

This repository [uses GitHub Actions](https://github.com/rafguns/doaj-history/actions) to retrieve the [CSV file of journals in DOAJ](https://doaj.org/csv) once a day and track any changes to it over time using the git commit history.

It uses [csv-diff](https://github.com/simonw/csv-diff) to generate human-readable commit messages.

You can see recent changes to the CSV file here: https://github.com/rafguns/doaj-history/commits/main.

Both the idea and implementation were based on [Simon Willison](https://simonwillison.net)'s git scraping work, especially the [sf-tree-history](https://github.com/simonw/sf-tree-history) repository.
