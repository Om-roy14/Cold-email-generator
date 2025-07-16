GenAI Cold Email Composer for Job Applications

This project automates the process of generating personalized cold emails based on job application posts. By inputting a job post URL, the system scrapes the job description, extracts key details, and generates a tailored cold email suitable for direct outreach.

What it does:

Scrapes job descriptions from a given URL

Uses AI to understand role, company, and key requirements

Generates a custom, professional cold email

Provides an intuitive web interface for seamless use

Tech Stack:

LangChain: Orchestrates prompt construction and flow

Groq API + LLaMA 3.3 70B Versatile: Generates the email content with high speed and accuracy

ChromaDB: Stores and retrieves vectorized context chunks

Streamlit: Provides a clean and simple user interface

Workflow:

User inputs a job post URL

Job post is scraped and cleaned

LangChain processes and chunks the data

Relevant context is embedded and stored in ChromaDB

The model receives a customized prompt

Groq API returns a polished cold email tailored to the job

Installation:

Clone the repository

Install dependencies with pip

Add your Groq API key to a .env file

Run the Streamlit app
