# Resume Skills Matching Tool

This Python script extracts skills from a resume and matches them with a given job description using Jaro Similarity. The script uses the NLTK library for text processing and the PDFMiner library for PDF text extraction.

## How it works

1. The script extracts text from a specified resume PDF file.

2. It then prompts the user to enter a job description.

3. The script calculates the Jaro Similarity score between the job description and the skills extracted from the resume.

4. The Jaro Similarity score is displayed as the result.

## Example Output

```python
0.871424
