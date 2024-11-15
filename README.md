# PDF Data Extraction

This Python script processes PDF files in the `./pdfs` folder to extract useful information. It uses **PyPDF2** to read PDF content and metadata (such as title, author, and creation date). **langdetect** detects the document's language, while **pandas** structures and organizes the extracted data. The script calculates the total word count, identifies the most common word, counts the number of links, and measures the file size. **re** (regular expressions) is used to extract URLs from the text and filter out short words (at least 4 characters).

The output is a DataFrame containing structured data for each PDF file.

