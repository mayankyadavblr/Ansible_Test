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
```
Or just run the first code cell in the Colab notebook.

---

## Running in Colab

1. Open the main.ipynb notebook in Google Colab
    * Either download the file and upload to Colab
    * Or use the 'Open in Colab' button on top of the file when opened in GitHub
2. Run the cells from top to bottom
    * First cell installs required libraries
    * Next we import the required modules
    * Third cell authenticates your google account
          * Give access all required services for the code to work
    * Then you can customize the markdown text stored in the variable 'content'. Default is what was provided in the assessment doc
    * The next cell converts the markdown string into an html doc as they have a one-to-one translation which in turn has a one-to-one translation to google docs
    * The last cell creates a google doc in the root directory of you google drive and uploads the required content to it
        * You will be prompted to enter the filename you wish to store the google doc under

