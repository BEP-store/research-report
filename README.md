# BEP-store Research Report

This repository contains the research report for team BEP-store. It is a Gitbook,
which can be found in a nice readable format [here](https://www.gitbook.com/read/book/bep-store/research-report).

## Editing locally
To see the gitbook locally, run `gitbook run` followed by `gitbook serve`. If you want to generate a pdf locally you'll first need to install [Callibre](https://calibre-ebook.com/) followed by `gitbook pdf`.

## Bibtex support
This gitbook supports bibtex references. Place them in the literature.bib file and link to them by `{{"Kalliamvakou:2015:OSC" | cite}}`. APA support will be added soon.

## Automatic footnote numbering
When using footnotes `[^footnote]` and `[^footnote]: This is a footnote`, `footnote` will be converted to `#number`.