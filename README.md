
# Document Translator

## Introduction
This Python script automates the process of translating text content in a Microsoft Word document (.docx) from one language to another. It utilizes the docx library to read and create Word documents and the Google Translate API for translation. The translated content is saved into a new Word document.

## Requirements

Install the required libraries:

```bash
pip install python-docx
pip install googletrans==4.0.0-rc1
Run the script and follow the instructions.
```

## Usage
- Launch the script.

- Enter the source document name, which should be a .docx file.

- Enter the source language code. You can use the language codes provided in the script for reference.

- Enter the target document name, which will be the translated document.

- Enter the target language code for translation.

The script will read the source document, translate its content paragraph by paragraph, and create a new Word document with the translated content.

**Note:** The script may take some time to translate large documents.
