# Interview-Question-Creator-Project

This FastAPI web app allows users to upload PDF files, process them, and generate a CSV file with questions and answers extracted from the PDF. The app consists of two main endpoints: one for uploading PDFs and another for analyzing the uploaded PDF. Upon upload, the PDF is saved to the server, and analysis is performed using a helper function (llm_pipeline), which generates questions and answers. The results are then saved in a CSV file. The app uses FastAPI, Jinja2 for templates, and aiofiles for handling file uploads asynchronously. It involves building an intuitive interface, setting up AI models for natural language generation, and ensuring output quality and diversity. This project can help streamline the interview process for recruiters, HR professionals, and candidates by providing a comprehensive set of tailored questions for technical and non-technical roles.

### How to run?

1. Create an environment

```bash
conda create -n interview python=3.10 -y


conda activate interview

```

2. install requirements

```bash
pip install -r requirements.txt
```
