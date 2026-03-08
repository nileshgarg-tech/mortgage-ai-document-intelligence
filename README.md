# mortgage-ai-document-intelligence

> Making messy, complex documents readable, searchable, and useful — one project at a time.

---

## Project 2: Python for Document Intelligence

Built the Python foundation needed to work with real-world data — from raw text and structured datasets to noisy images. This project spans three tracks:

- **Python Basics** — Mastered variables, data types, operators, control flow, data structures, and functions through progressive exercises and a graded assignment.
- **Data Preparation with Python** — Used Pandas to load, clean, and analyze CSV and JSON datasets; applied NLP text-preprocessing pipelines (whitespace normalization, encoding fixes, contraction expansion, stop-word removal) to turn unstructured text into AI-ready input.
- **Image Processing with Python** — Used OpenCV and PIL to build end-to-end image cleaning pipelines applying median blur, Non-Local Means Denoising, and CLAHE contrast enhancement to real-world noisy images.

---

## Project 3: Data Extraction from Documents

Tackled real-world data extraction from mortgage worksheets, title reports, and resumes — turning raw PDFs into structured, queryable data:

- **PDF Text & Structure Extraction** — Extracted plain text, word tokens, and paragraph blocks from real mortgage documents and a resume using PyMuPDF, PyPDF2, and pdfplumber side-by-side, learning the strengths of each library across different document types.
- **Spatial Document Intelligence** — Retrieved exact pixel coordinates `(x0, y0, x1, y1)` for every word and block on a page, then used OpenCV to draw bounding box overlays directly on rendered PDF images — connecting textual extraction to computer vision.
- **Structured Data Export Pipeline** — Built an extraction pipeline that organizes word tokens and their bounding boxes into Python dictionaries and exports them to JSON, producing a reusable format ready for downstream ML and NLP models.
- **Regex for Noisy Document Text** — Applied 12+ regex patterns to a messy loan application to extract names, addresses, phone numbers, emails, loan IDs, and dollar amounts — including named capture groups, section-scoped matching, PII redaction with `re.sub`, and whitespace normalization.
