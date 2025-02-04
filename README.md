# Chat-with-multi-csv-using-groq

Multiple-CSV ChatApp powered by LLM

Overview

This Streamlit application allows users to upload multiple CSV files and interact with them using natural language queries. It leverages the power of Large Language Models (LLMs) from GROQ, specifically the llama3-70b-8192 model, to analyze and interpret data.

Features

Upload multiple CSV files simultaneously.

Select a specific CSV file from the uploaded files.

Display a preview of the selected CSV file.

Input natural language queries to analyze the data.

Get responses powered by the llama3-70b-8192 LLM from GROQ.

Technologies Used

Python

Streamlit (for UI and interaction)

Pandas (for data processing)

PandasAI (for intelligent DataFrame querying)

LangChain (for LLM integration)

GROQ API (for language model processing)

dotenv (for environment variable management)

Installation

Prerequisites

Ensure you have Python installed (version 3.7 or later).

Steps

Clone this repository:

git clone <repo-url>
cd <repo-directory>

Create and activate a virtual environment:

python -m venv env
source env/bin/activate   # On macOS/Linux
env\Scripts\activate      # On Windows

Install dependencies:

pip install -r requirements.txt

Create a .env file in the project directory and add your GROQ API key:

GROQ_API_KEY=your_groq_api_key_here

Usage

Run the Streamlit app:

streamlit run app.py

Upload one or more CSV files from the sidebar.

Select a CSV file from the dropdown.

View a preview of the CSV file.

Enter a natural language query in the text area.

Click Chat with CSV to get an AI-generated response based on the data.
