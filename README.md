# Resume_ATS_Analysis


## Streamlit Resume Score App
### Overview
This Streamlit application, named Resume Score, is designed to assist job seekers in evaluating and optimizing their resumes. The app has two main features: Job Matcher and Resume Checker. It utilizes Google's Generative AI (Gemini Pro) for generating responses and analyzing resumes.

### Technologies Used
Streamlit: A Python library for creating web applications with minimal effort.
Google Generative AI: Leveraged for generating responses and insights for both Job Matcher and Resume Checker functionalities.
PyPDF2: Used for extracting text content from uploaded PDF resumes.
dotenv: Used for loading environment variables, particularly the Google API key.
### Features
#### Home Page
The app starts with a home page presenting two main options: Job Matcher and Resume Checker.
Each option provides a brief description of its purpose.
#### Job Matcher
Upload Resume: Users can upload their resume (PDF format) and input a job description.
The app then generates an analysis of how well the resume aligns with the provided job description.
The analysis includes an ATS (Applicant Tracking System) score, overview, strengths, areas of improvement, skills, keywords, and final thoughts.
#### Resume Checker
Upload Resume: Users can upload their resume (PDF format) for a comprehensive analysis.
The app provides an ATS score based on criteria such as keyword relevance, quantifiable achievements, grammar, length, and conciseness.
Additionally, the app generates detailed feedback on each criterion and provides a final summary.

### Usage
Clone the repository.
Install the required libraries using pip install -r requirements.txt.
Create a .env file and provide the Google API key.
Run the application with streamlit run app.py.
### How to Run
Execute the app.py file using the Streamlit command (streamlit run app.py).
The app will open in your default web browser.
