High-level package planning
================
2016-12-23

-   [Package vision](#package-vision)
    -   [Purpose](#purpose)
    -   [Questions to resolve](#questions-to-resolve)
    -   [Priorities](#priorities)

<!-- README.md is generated from README.Rmd. Please edit that file -->
This page is for planning the janitor package, at a high level. More-finite questions and ideas can be handled via GitHub issues. This is for say, articulating what the package does or doesn't do, and how it should be organized. If it turns out we need a more discussion- and comment-friendly format, we can move to Google Docs, but let's try commenting and editing here.

Package vision
--------------

### Purpose

Provide a framework and associated functions for checking and cleaning dirty data.

#### In scope:

#### Out of scope:

-   A thorough set of alerting functions for assertive data cleaning in production (instead, recommend assertr or other package)

### Questions to resolve

1.  Where should the organizing framework go - vignette? Bookdown? Main page?

### Priorities

1.  Establish organizing framework for the package
    1.  Write up documentation/vignette showing check/clean iterative cycle
    2.  Rename functions to fit schema
    3.  Redo vignette
    4.  Redo homepage

2.  New function: fuzzy dupes
3.  New function family: bindability issues