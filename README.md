# Resume Ranking Based on Job Description Using NLP NER Model

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Implementation](#Implementation)

## Project Overview
The project aims to revolutionize the recruitment process by introducing an intelligent resume parsing and ranking system. Leveraging cutting-edge Natural Language Processing (NLP) techniques and machine learning algorithms, the system automates the extraction of essential information from resumes, compares it against job descriptions, and generates a suitability score. This helps recruiters swiftly identify top candidates, saving time, reducing bias, and improving decision-making accuracy.

## Features
- Automated resume parsing and extraction of key information
- Matching resumes with job descriptions using a suitability score
- Reduction of manual effort in resume screening
- Improvement in candidate matching accuracy
- Promotion of fairness and objectivity in candidate evaluation
- User-friendly interface for easy interaction

## System Architecture
The system is composed of several components:
1. **User Interface (UI)**: Developed using HTML, CSS, and JavaScript.
2. **Authentication**: Google OAuth for secure user authentication.
3. **API Interaction**: Handles operations such as uploading resumes, fetching job descriptions, and processing data.
4. **Backend**: Developed using Flask, a lightweight web framework for Python.
5. **Database**: MongoDB for efficient data management and retrieval.
6. **NLP Module**: Utilizes SpaCy for Named Entity Recognition (NER) to parse resumes and job descriptions.
   
![Final System Archi drawio](https://github.com/panjyar/Resume_Ranking_System/assets/121200924/f12a9fe0-816c-4d47-901d-bbc97e356a50)

## Technologies Used
- **Programming Languages**: Python, JavaScript
- **Frameworks**: Flask (backend), SpaCy (NLP)
- **Database**: MongoDB
- **Authentication**: Google OAuth
- **Other Tools**: HTML, CSS, VS Code, Google Cloud Platform, Google Colab

## Installation
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/resume-ranking-nlp.git
   cd resume-ranking-nlp

2. **Set Up Virtual Environment**
   python -m venv env
   source env/bin/activate   # On Windows use `env\Scripts\activate`
3. **Install Dependencies**
   pip install -r requirements.txt
4. **Set Up Environment Variables**
    Create a .env file in the project root directory and add your Google OAuth credentials and MongoDB URI:
    GOOGLE_CLIENT_ID=your_google_client_id
    GOOGLE_CLIENT_SECRET=your_google_client_secret
    MONGO_URI=your_mongodb_uri
5.  **Run the Application**
     flask run
    
## Implementation

  ![Prokect Home Page](https://github.com/panjyar/Resume_Ranking_System/assets/121200924/eecf1766-6c22-4ad1-9163-ca3c46560e3c)
  ![Rank List](https://github.com/panjyar/Resume_Ranking_System/assets/121200924/bbca9606-b70f-4556-bc58-e5061e5a7c63)
