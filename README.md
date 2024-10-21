# ATS Resume Expert - Applicant Tracking System (ATS)

This project is an AI-powered Applicant Tracking System (ATS) designed to evaluate resumes against job descriptions. The system helps HR professionals and recruiters by providing detailed insights into how well a candidate's resume aligns with a job posting. The application is built using **Streamlit** for the interface and utilizes **Google Gemini** AI model **gemini-1.5-flash** to generate responses.

## Features
- **Resume Evaluation**: Upload a PDF resume, and the system analyzes it in comparison to the provided job description.
- **Professional Review**: Provides strengths and weaknesses of the candidate’s profile based on the job description.
- **Percentage Match**: Calculates the match percentage between the job description and the resume, identifying missing keywords and providing final thoughts.
- **Live Deployed**: The system is live and hosted on Render for public access.

## How it Works
1. **Upload Resume**: The user uploads their resume in PDF format through the user-friendly Streamlit interface.
2. **Input Job Description**: The user enters the job description text into the provided text area.
3. **AI-Powered Analysis**: The uploaded PDF is processed, and the AI model (gemini-1.5-flash) generates the analysis based on predefined prompts:
   - For strengths and weaknesses (Professional Review).
   - For percentage match and missing keywords (ATS Scan).
4. **Response Generation**: The application outputs the AI-generated insights to the user, displaying the evaluation results in real-time.

## Technologies Used
- **Streamlit**: For building the web interface.
- **Python**: For the backend logic.
- **pdf2image**: To convert the PDF resume into images for processing.
- **Google Gemini Model**: For generating the AI-based evaluations.
- **Render**: For deploying the application.

## Installation

To run this project locally, follow these steps:

```bash
1. Clone the repository:
   git clone https://github.com/yourusername/ats-resume-expert.git
   cd ats-resume-expert
```
2. Install dependencies:
```bash   
   pip install -r requirements.txt
```
3. Set up your environment variables:
```bash 
   # Create a `.env` file and add your **Google API Key**:
   GOOGLE_API_KEY=your-google-api-key
```
4. Run the application:
```bash
   streamlit run app.py
```


## Deployment

This application is deployed on Render and can be accessed.



## Acknowledgements

- **Google Gemini AI** for powering the resume analysis.
- **Streamlit** for providing a simple yet powerful framework for building the UI.

