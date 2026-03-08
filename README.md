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

- **PDF Extraction with Multiple Libraries** — Extracted text, word tokens, and blocks from real mortgage worksheets, title reports, and a resume using PyMuPDF, PyPDF2, and pdfplumber, comparing each library's strengths.
- **Resume Parser & Spatial Intelligence** — Built a resume parser that retrieves exact bounding box coordinates for every word on a page, then uses OpenCV to draw visual overlays on the rendered PDF — connecting text extraction to computer vision.
- **Structured Data Export** — Organized extracted word tokens and bounding boxes into Python dictionaries and exported them to JSON, ready for downstream ML and NLP models.
- **Regex for Noisy Document Text** — Applied regex patterns to a messy loan application to extract names, addresses, phone numbers, emails, and loan IDs — including PII redaction and whitespace normalization.
