# hn-popularity-contest-data

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/mtlynch/hn-popularity-contest-data/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/mtlynch/hn-popularity-contest-data/tree/master)

Metadata for the [HN Popularity Contest](https://refactoringenglish.com/tools/hn-popularity/)

## Domain metadata

Metadata about each domain like author name and topics appear in `data/domains-meta.csv`.

Domains should have a short blurb about the author and a list of up to three topics that the author blogs about.

## Excluded domains

A list of excluded domains appears in `data/excludes.txt`.

We exclude domains if they are:

- Do not contain a blog
- Contain blog posts authored by multiple people

See the full details on the HN Popularity Contest's [methodology page](https://refactoringenglish.com/tools/hn-popularity/methodology/).
