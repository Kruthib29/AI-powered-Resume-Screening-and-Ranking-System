# AI-Powered Resume Screening and Ranking System

## Overview

This AI-powered system leverages Streamlit, Natural Language Processing (NLP), and Machine Learning (ML) techniques to automate resume screening and ranking based on job descriptions. It uses TF-IDF vectorization and cosine similarity to evaluate resume relevance efficiently.

## Features

- **Resume Parsing:** Extracts text from PDF resumes.
- **AI-Powered Screening:** Uses TF-IDF vectorization to compare resumes with the job description.
- **Resume Ranking:** Scores resumes based on similarity to job requirements.
- **Keyword Extraction:** Identifies relevant keywords from the job description and resumes.
- **User-Friendly Interface:** Built with Streamlit for seamless interaction.

## Installation

### Prerequisites

- Python 3.x
- Required libraries: `streamlit`, `PyPDF2`, `scikit-learn`
- Install dependencies using:
  ```bash
  pip install -r requirements.txt
  ```

### Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/ai-resume-screening.git
   cd ai-resume-screening
   ```
2. Start the Streamlit application:
   ```bash
   streamlit run resume.py
   ```

## Usage

1. Enter the job description in the provided text area.
2. Upload multiple PDF resumes.
3. The AI model will analyze and rank resumes based on similarity.
4. View ranked resumes along with extracted keywords.

## Configuration

Modify `config.json` to adjust:

- Weightage of different evaluation criteria
- Additional filtering options

## Code Explanation

### Key Functions

- **`extract_text_from_pdf(file)`**: Extracts text from a given PDF resume.
- **`rank_resumes(job_description, resumes)`**: Uses TF-IDF and cosine similarity to rank resumes.
- **Keyword Extraction**: Retrieves key terms from both job descriptions and resumes for better transparency.

## Contributing

We welcome contributions! Feel free to submit issues, feature requests, or pull requests.

## License

This project is licensed under the MIT License.

## Contact

For support or inquiries, please reach out to [kruthib029@gmail.com](mailto\:kruthib029@gmail.com).

