
# Resume Screening App

## Overview
The **Resume Screening App** is a tool designed to automate the process of screening resumes and matching them with job descriptions. The application uses Natural Language Processing (NLP) techniques to analyze and evaluate resumes, making it easier for HR professionals and recruiters to identify the most relevant candidates.

## Features
- Upload and parse resumes in various formats such as PDF, DOCX, and TXT.
- Extract key information like name, skills, education, and work experience.
- Match resumes with job descriptions based on relevant skills and experience.
- Generate a relevance score for each resume based on its compatibility with the job description.
- Simple and user-friendly interface for uploading and analyzing resumes.

## Technologies Used
- **Python**: Main programming language for backend logic.
- **Flask**: Web framework used to build the backend of the application.
- **scikit-learn**: Used for machine learning algorithms and text classification.
- **NLTK / spaCy**: For text processing and natural language analysis.
- **PDFMiner / python-docx**: For extracting text from PDF and DOCX files.
- **HTML, CSS, JavaScript**: Frontend technologies for building the user interface.

## Installation

### Clone the Repository
To get started, clone the repository to your local machine:

```bash
git clone https://github.com/veenasahu/Resume-Screening-App.git
````

### Install Dependencies

Navigate to the project directory and install the required dependencies:

```bash
cd Resume-Screening-App
pip install -r requirements.txt
```

### Run the Application

After installing the dependencies, run the app locally:

```bash
python app.py
```

The app will run on `http://localhost:5000`.

## Usage

1. Open the app in your web browser.
2. Upload a resume file (PDF, DOCX, or TXT format).
3. Upload the job description.
4. Click on **Analyze** to get a resume matching score.
5. Review the results, which include suggestions and relevance scores based on the analysis.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request to merge your changes into the main branch.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

* NLP libraries like `spaCy` and `NLTK` for text processing and analysis.
* Open-source contributors who made these tools available for free.
* The project uses `scikit-learn` for implementing machine learning models.


