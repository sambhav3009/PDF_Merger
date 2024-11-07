# PDF Merger 📝➡️📄

This is a Python project that merges multiple PDF files into a single PDF document. It reads each page from the input PDFs and combines them into a new PDF file. This project can be useful for consolidating multiple documents into one file for easier sharing or organization.

## Table of Contents
- [Features](#features)
- [How It Works](#how-it-works)
- [Requirements](#requirements)


## Features

- Merges multiple PDF files into a single output PDF.
- Handles PDFs with different page counts seamlessly.
- Outputs a single consolidated PDF that retains the order of input files.

## How It Works

1. **PDF Reading**:
   - Each input PDF is opened and read using `PyPDF2`.
2. **Page Merging**:
   - All pages from the input PDFs are added to a `PdfWriter` instance, which consolidates them.
3. **PDF Writing**:
   - The merged content is written to a new output PDF file.

## Requirements

- Python 3.x
- Install the following package:

   ```bash
   pip install PyPDF2
