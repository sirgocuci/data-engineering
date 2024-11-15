# PDF Data Extraction

This project processes PDF files from the `./pdfs` folder and extracts structured data for analysis.

## Requirements

- Python 3.7+
- Libraries: PyPDF2, pandas, langdetect

## Setup

1. Install dependencies by running the following in a Jupyter Notebook cell:
   ```python
   !pip install PyPDF2 pandas langdetect
   ```

2. Place your PDF files in the `./pdfs` folder.

## Running the Solution

To run the extraction, open the `extract_pdf.ipynb` notebook in Jupyter and execute the cells.

The notebook will process all PDF files in the `./pdfs` folder and generate a structured DataFrame with the extracted information, such as word count, language, most common word and more.
