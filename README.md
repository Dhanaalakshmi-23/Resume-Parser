# Resume Parser Generator

## Overview
The Resume Parser Generator is a powerful tool designed to extract and categorize relevant information from resumes in various formats (PDF, DOCX, etc.). This tool can automatically parse essential details such as personal information, education, skills, work experience, and more, providing structured output that can be used for analytics or application screening purposes.

## Features
- **File Upload**: Upload resumes in PDF, DOCX, or TXT format.
- **Information Extraction**: Automatically extracts key information, including:
  - Personal details (Name, Email, Phone Number)
  - Education background
  - Skills (Technical, Soft skills)
  - Work experience (Company, Position, Duration)
- **Customizable Output**: Extracted information can be output as JSON or displayed on a user interface.
- **Scalable**: Can handle bulk uploads and process multiple resumes simultaneously.

## Technologies Used
- **Python**: The core language for backend development.
- **Natural Language Processing (NLP)**: Used to extract text and categorize relevant information.
- **spaCy**: For named entity recognition (NER) and text extraction from resumes.
- **PyPDF2 or pdfminer.six**: For parsing and extracting text from PDF files.
- **docx**: For reading and extracting text from DOCX files.
  
## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/resume-parser-generator.git
