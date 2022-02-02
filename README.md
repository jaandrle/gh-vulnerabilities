# gh-vulnerabilities
GitHub cli extension to see vulnerabilities in current reository.

ℹ️ contributions welcome

A [GitHub CLI](https://cli.github.com/) extension to work with projects.

## Installation

Make sure you have at least version 2 of the GitHub CLI installed. Internaly use [jq](https://stedolan.github.io/jq/).

Install this extension with:
```bash
gh extension install jaandrle/gh-vulnerabilities
```

## Synopsis
- basic
  ```text
    Prints vulnerabilities list for current reository.

    USAGE
        gh vulnerabilities [all|active|dismissed] [FLAGS]
        - active                [default] pritns out active (not dismissed)
        - all                   prints all
        - dismissed             prints only dismissed

    FLAGS
        --web   open Dependabot web page for current repository
        --help  prints this text
  ```
