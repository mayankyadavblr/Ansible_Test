# Markdown to Google Doc Converter

This Python script is designed to convert markdown meeting notes into a well-formatted Google Doc and upload it directly to your Google Drive. It is optimized for execution in Google Colab.

## Features
- Converts Markdown content to HTML.
- Uploads the converted content as a Google Doc to Google Drive.

---

## Setup Instructions

### Prerequisites
1. A Google account to authenticate with Google Drive.
2. Google Colab environment (recommended for easy execution).

---

## Required Dependencies
The script requires the following Python libraries:
- `PyDrive2`: To authenticate and interact with Google Drive.
- `pypandoc`: For handling markdown conversions.
- `markdown`: To convert Markdown content to HTML.

Install them using the following commands:
```bash
%pip install PyDrive2
%pip install pypandoc_binary
%pip install markdown

Or just run the first code cell in the Colab notebook.
