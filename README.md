# Resume Parser App (Gen AI + Flask)

## Objective

Creating a resume parser app using Flask is a great way to help job seekers test the ATS (Applicant Tracking System) friendliness of their resumes. The app allows users to upload their resumes in PDF format, which are then parsed to extract various pieces of information such as full name, email ID, GitHub portfolio, LinkedIn ID, employment details, technical skills, and soft skills. The extracted information is then presented in JSON format, providing users with valuable insights into the effectiveness of their resumes.

To build such an app, you can leverage various tools and libraries, including Python, Flask, Pyresparser, pdfminer.six, docx2txt, and NLP (natural language processing) libraries such as nltk and spacy. These tools enable the extraction of essential information from resumes in PDF and DOCx formats, making the process automated and efficient.

The app's functionality aligns with the growing need for streamlined recruitment processes and the increasing reliance on technology to evaluate and process job applications. By providing users with a detailed analysis of their resumes, the app empowers job seekers to optimize their resumes for better visibility and compatibility with ATS.

## Overview: 
This App is created for job seekers to test whether their resumes are ATS friendly or not, if our App is able to parse your details and show it, then assume that everything is good.

![ezgif-5-8b5c092ee2](https://github.com/user-attachments/assets/6fe17d0b-8dcf-4ef3-b63c-489eee944702)

## Features: 
Ability to extract specific information from resumes, the use of JSON format for presenting the extracted data, and the integration of various libraries and tools for parsing resumes.

## Usage: 
Just upload your resume in pdf format, and see for yourself :)

## Running the program

### 1. Clone the Repository and Navigate to Directory

```bash
git clone https://github.com/FYT3RP4TIL/LLM-Resume-Parser.git
cd LLM-Resume-Parser
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

- On Windows:
```bash
venv\Scripts\activate
```
- On macOS and Linux:
```bash
source venv/bin/activate
```
### 4. Install Dependencies
```bash
pip install -r requirements.txt
```
### 5. Provide your Open AI API key in the .yaml file
```bash
OPENAI_API_KEY: "YOUR KEY HERE"
```

### 6. Run the App
```bash
python main.py
```
Open your web browser and go to http://127.0.0.1:5000/ to see the app in action.

## Conclusion
    
Overall, the development of a resume parser app using Flask represents a significant advancement in leveraging technology to support job seekers in optimizing their resumes for the modern recruitment landscape. This app aligns with the increasing demand for efficient and technology-driven solutions in the job application process, ultimately benefiting both job seekers and recruiters.
