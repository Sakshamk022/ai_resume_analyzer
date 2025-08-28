# Resumind: AI Resume Analyzer

## Description

Resumind is an AI-powered resume analyzer designed to provide smart feedback for job applications. It allows users to upload their resumes, track applications, and receive AI-powered feedback. The application reviews submissions and provides detailed feedback and ratings.

## Features

  * **Resume Upload**: Users can upload PDF files up to 20MB.
  * **AI-Powered Feedback**: The application provides an overall resume score and scores for specific categories:
      * **Overall Score**: Calculated based on various variables.
      * **ATS Score**: A score out of 100 that indicates how well a resume performs in Applicant Tracking Systems. The score's grading is as follows:
          * 70+ points: Great Job\!
          * 50-69 points: Good Start
          * Below 50 points: Needs Improvement
      * **Category Scores**: Separate scores for Tone & Style, Content, Structure, and Skills.
  * **Application Tracking**: Users can review their resume submissions and check their AI-powered feedback on a dashboard.
  * **File Handling**: `react-dropzone` for file uploads and `pdfjs-dist` for PDF processing.

## Installation & Running the Project

To set up the project locally, follow these steps:

1.  **Clone the repository**.
2.  **Install dependencies**:
    ```bash
    npm install
    ```
    This command will install all required dependencies listed in `package.json`.
3.  **Run the development server**:
    ```bash
    npm run dev
    ```
    This command starts the development server.
4.  **Build the project**:
    ```bash
    npm run build
    ```
    This command builds the project for production.
5.  **Run the production server**:
    ```bash
    npm run start
    ```
    This command serves the built application.

