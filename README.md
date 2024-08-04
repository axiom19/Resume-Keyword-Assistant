# Resume-Keyword-Assistant
Resume Tailor Machine is an AI-powered tool that enhances resumes by intelligently incorporating specific keywords, improving their relevance for targeted job applications.

## Description
Motivation: Applying to a job makes you use Jobscan, which lists missing keywords. Sometimes, it's hard to incorporate keywords without changing the sense of the statement. 
So, the following project will assist you in adding the keyword to your resume.

This project uses the Gemma 2B language model and Gradio to create an interactive web interface where users can upload their resumes and input keywords. The AI then analyzes the resume and naturally integrates the keyword, providing suggestions on improving the resume's match to specific job requirements.

## Features

- PDF resume upload functionality
- Keyword input for resume tailoring
- AI-powered resume analysis and modification
- User-friendly Gradio interface
- Detailed output explaining changes and their benefits

## Installation

## Usage

1. Clone the repository: git clone https://github.com/yourusername/resume-tailor-machine.git
cd resume-tailor-machine

2. Run the Jupyter notebook or Python script: jupyter notebook ResumeAssistant-Inference.ipynb

3. Once the Gradio interface is launched, upload a PDF resume and enter a keyword.

4. The AI will process the resume and provide suggestions on how to incorporate the keyword effectively.

## How it Works

1. The user uploads a PDF resume and inputs a keyword.
2. The system extracts text from the PDF.
3. The AI model analyzes the resume content and the given keyword.
4. The model suggests modifications to naturally incorporate the keyword.
5. The system returns the suggested changes, including:
- The section where the change was made
- The full modified line
- An explanation of how this change improves the resume

## Contributing

Contributions to improve the Resume Tailor Machine are welcome. Please feel free to submit a Pull Request.
