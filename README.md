# Resume Matching with Job Descriptions
This script demonstrates the process of matching resumes with job descriptions using cosine similarity based on DistilBERT embeddings.        

## Overview
The code reads job descriptions and resumes from specified datasets.         
It processes the job descriptions to generate embeddings using DistilBERT.        
For each resume, it calculates cosine similarity with the job descriptions based on embeddings.       
It identifies the top matching job description for each resume.          

## Files
resume_job_matching.py: Python script containing the code for resume matching.   
Resume.csv: CSV file containing the resume data.      
README.md: This file, providing an overview of the script.     

## Dependencies
os: Library for interacting with the operating system.   
fitz (PyMuPDF): For PDF parsing.   
transformers: Hugging Face Transformers library for DistilBERT.   
sklearn.metrics.pairwise: For calculating cosine similarity.   
pandas: For data manipulation and analysis.   
datasets: Hugging Face Datasets library.   
numpy: For numerical operations.   


The script generates output displaying the top matches for each resume, including the company, role, job description, and similarity scores.
