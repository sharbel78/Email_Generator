

Email Generator for Services Company
A streamlined tool for generating personalized cold emails to target companies with job openings, built using GROQ, LangChain, and Streamlit.

Features
URL Input: Enter the URL of a company's careers page.
Job Extraction: Automatically extracts job listings from the provided page.
Cold Email Generation: Creates tailored cold emails for business development purposes.
Portfolio Integration: Integrates relevant portfolio links from a vector database based on job descriptions for enhanced personalization.

How It Works
Input URL: Paste the URL of the target company's careers page.
Data Extraction:
Uses GROQ to extract structured data from the webpage.
Extracted information includes job titles, descriptions, and requirements.
Email Personalization:
Leverages LangChain for contextual text generation.
Matches job descriptions with entries from a vector database to provide relevant portfolio links.
Cold Email Output:
Outputs a professionally crafted email ready to be sent.

Tech Stack
GROQ: Extracts structured job data from web pages.
LangChain: Powers the natural language processing for email generation.
Streamlit: Provides an interactive and user-friendly web interface.
Vector Database: Stores and retrieves relevant portfolio links based on job descriptions.
