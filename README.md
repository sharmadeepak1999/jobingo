# Arbeit AI

**Arbeit AI** simplifies job applications by generating personalized cover letters, LinkedIn connection requests, and referral templates based on your resume and the job description. It also analyzes your resume, providing a matching score and suggestions for improvement.

## Key Features

- **Custom Cover Letters**: Generate tailored cover letters for job applications.
- **Referral & LinkedIn Templates**: Create personalized referral notes and LinkedIn connection requests.
- **Resume Analysis**: Get a matching score and suggestions to optimize your resume.

## Technologies

- **Streamlit**: For building the UI.
- **Together AI & Llama-3.3-70B-Instruct-Turbo**: For AI-powered document generation and analysis.

## Setup Environment Variables

To configure the API key and model for **Arbeit AI**, create a `.env` file in the root directory of the project and add the following lines:

    ```env
    TOGETHER_API_KEY="your_api_key_here"
    TOGETHER_MODEL="your_model_name_here"

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/sharmadeepak1999/arbeit-ai.git

2. Navigate to the project directory:

   ```bash
   cd arbeit-ai

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

4. Run the Streamlit app:

   ```bash
   streamlit run app.py
