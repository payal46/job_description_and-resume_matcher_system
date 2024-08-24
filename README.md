# Job Description and Resume Matcher System
##  Overview
The Job Description and Resume Matcher System is an intelligent tool designed to help recruiters and job seekers by automatically matching resumes with job descriptions. This system uses natural language processing (NLP) techniques to analyze job descriptions and resumes, providing a compatibility score that indicates how well a candidate's resume matches a specific job description.

## Key Features
* Resume Parsing: Supports PDF, DOCX, and TXT file formats for extracting text from resumes.
* Job Description Analysis: Analyzes the text of the job description to match it against the resumes.
* Similarity Scoring: Uses TF-IDF vectorization and cosine similarity to rank resumes based on their relevance to the job description.
* Top Resume Matching: Displays the top 10 matching resumes along with their similarity scores.

## Technology Stack
* Backend Framework: Flask (Python)
* Natural Language Processing: Scikit-learn (TF-IDF, Cosine Similarity)
* File Parsing: PyPDF2 for PDFs, docx2txt for DOCX files
* Frontend: HTML (with Jinja2 templating)
* Deployment: Flask’s built-in development server

## How It Works
1. Upload Resumes: Users can upload multiple resumes in supported formats.
2. Input Job Description: A job description is entered directly into the web interface.
3. Process and Match: The system processes the text from both the resumes and the job description to determine their similarity.
4. View Results: The top matching resumes are displayed with their respective similarity scores, helping you to quickly identify the best candidates.

## About Me
I’m deeply passionate about the intersection of data and technology. As a dedicated data science enthusiast, I love diving into data, uncovering patterns, and building solutions that drive meaningful insights. My journey is fueled by curiosity, a love for tackling complex problems, and an eagerness to contribute to the data science field. From participating in competitions to developing innovative tools, I'm committed to pushing the boundaries of what's possible with data.
