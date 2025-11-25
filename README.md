# LegalAI -- Automated Legal Summary System

LegalAI is an AI-powered web application that analyzes legal documents,
extracts important clauses, generates simplified summaries, highlights
risks, and provides interactive insights using NLP and Google Gemini.

## Short Description

An AI-driven legal document analyzer that performs clause extraction,
summarization, risk evaluation, and document comparison with a clean,
user-friendly interface.

## Features

### Clause Extraction

Automatically detects key legal elements: - Confidentiality -
Termination - Indemnity - Liability - Obligations - Penalties

### AI-Based Summarization

-   Generates concise summaries\
-   Simplifies complex legal language\
-   Provides extractive + abstractive insights

### Risk Assessment

-   Detects risky terms\
-   Assigns Low / Medium / High risk scores\
-   Highlights sentences using a color-coded heatmap

### Document Comparison

-   Upload two PDFs\
-   Compare summaries, clauses, and risks\
-   Highlights differences clearly

### Document Q&A

Ask natural questions like:\
- "Is there a penalty clause?"\
- "What is the notice period?"

AI responds based on the document content.

### PDF Report Generation

Export professional reports containing: - Summary\
- Clauses\
- Risk scoring\
- Highlighted risk areas\
- Key insights

## Technology Used

-   Backend: Flask (Python)\
-   AI Model: Google Gemini\
-   NLP Tools: Regex, tokenization, keyword-based analysis\
-   PDF Processing: pdfplumber\
-   PDF Export: ReportLab\
-   Frontend: HTML, CSS, JavaScript

## How It Works

1.  User uploads a PDF or enters text\
2.  Text is extracted and cleaned\
3.  Clauses are detected using rule-based + AI reasoning\
4.  Risk score is calculated\
5.  Summary is generated\
6.  Heatmap and insights are displayed\
7.  User can download the PDF report or compare two documents

## Future Enhancements

-   Multi-language support\
-   Voice-based interaction\
-   Integration with legal databases\
-   Advanced clause-specific AI models\
-   Real-time collaboration for teams

## Disclaimer

This system provides AI-generated legal insights for assistance.\
It does not replace professional legal advice.

It is successfully deployed by My Friend Somath darling on Rendor
link : https://legal-document-analyzer-5ll5.onrender.com


