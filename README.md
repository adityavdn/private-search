# 🔒 Private Search

A search engine for your own files that runs entirely in your browser.

**Live:** https://adityavdn.github.io/private-search/

- Drop in notes, PDFs, CSVs, JSON, Markdown, code or other text files and search across all of them instantly.
- **Private:** your files are never uploaded. They're indexed and stored in your browser (IndexedDB) and stay there between visits.
- Ranks results with **BM25** (the algorithm behind Elasticsearch and Lucene) using an inverted index built in the browser.
- Search as you type, with highlighted snippets and a full-text viewer.

It's a single `index.html` with no build step, no server and no dependencies. PDF text extraction uses pdf.js, which is loaded only when you add a PDF.
