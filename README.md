# Smart ATS (Application Tracking System)

## This Streamlit application leverages the power of Google's Gemini Large Language Model (LLM) to create a sophisticated Application Tracking System (ATS) tailored for the tech industry. By analyzing resumes against provided job descriptions, the ATS offers comprehensive feedback, including:

JD Match Percentage: Quantifies the alignment between the resume and job description.

Missing Keywords: Identifies crucial keywords absent from the resume.

Profile Summary: Provides a concise overview of the candidate's qualifications.

Improvements: Offers actionable suggestions to enhance the resume's effectiveness.

Key Features:

1) Gemini LLM Integration: Employs the advanced capabilities of the Gemini LLM for accurate and insightful analysis.
 
2) User-Friendly Interface: Offers a simple and intuitive Streamlit-based interface for easy interaction.

3) PDF Resume Support: Accepts PDF resumes as input for seamless processing.

4) Detailed Feedback: Provides comprehensive insights to help candidates optimize their resumes.

Prerequisites :

Python environment with required libraries: streamlit, google-generativeai, PyPDF2, dotenv
A Google Cloud Platform project with the Generative AI API enabled
A Google Cloud API key with necessary permissions

Install required libraries: using requriments.txt file

Create a .env file in the project directory and add our Google Cloud API key:

GOOGLE_API_KEY=YOUR_API_KEY

How to Use :

1) Paste the job description in the provided text area.

2) Upload our resume in PDF format.

3) Click the "Submit" button.

The ATS will process the resume and job description, providing detailed feedback.

## Gemini LLM :

Gemini is a large language model developed by Google AI. It excels at understanding and generating text, translating languages, writing different kinds of creative
content, and answering questions in an informative way. In this application, Gemini is used to analyze resumes and job descriptions, providing valuable insights 
for candidates to improve their job applications or resumes
