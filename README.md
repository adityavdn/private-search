# Private Search

A browser-based private search engine for your own files, built to keep data local and searchable without uploading content anywhere.

## Overview

Private Search is a client-side search tool for notes, PDFs, markdown files, CSVs, JSON and other text-based files. It indexes local files in the browser using IndexedDB and ranks results with BM25-style relevance scoring.

## Why it matters

- files stay in the browser
- no server-side upload is required
- search works quickly on local collections
- results include snippets and a full-text viewer

## Tech Stack

- HTML
- JavaScript
- IndexedDB
- PDF.js

## How to run

Open the app in a browser and add files from your local machine. The project is designed as a static front-end with no backend requirement.

Live demo:

- https://adityavdn.github.io/private-search/

## Project structure

```text
.
├── index.html
├── app logic and UI files
├── README.md
└── assets or library files
```

