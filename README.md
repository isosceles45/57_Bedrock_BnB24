
<h1><strong>Resume Parser/Analyzer 📄</strong></h1>

<h2>Overview</h2>
This project aims to streamline the process of resume analysis and ranking by extracting relevant information from resumes provided by users and comparing them against a job description provided by the HR department. The primary technologies used in this project are Python, Spacy for natural language processing (NLP), and cosine similarity for ranking.

<h2>Project Description</h2>
The project involves the following steps:

Resume Collection: Resumes are collected from users, either through an upload feature or direct input.

Resume Parsing: The resumes are parsed using Spacy, a powerful NLP library in Python. Spacy is employed to extract key information such as name, email, skills, work experience, education, etc., from the resumes.

Job Description Input: The HR department provides a job description for the position they are hiring for. This job description serves as a reference point for evaluating the resumes.

Cosine Similarity: Cosine similarity is calculated between the job description and each parsed resume. This metric helps in determining the similarity between the candidate's qualifications and the job requirements.

Ranking Resumes: Resumes are ranked based on their cosine similarity score. Resumes with higher similarity scores are considered more relevant to the job and are ranked higher.

User Interface: The project may include a user interface where users can upload their resumes, view the extracted information, and see the ranking of their resumes compared to the job description.

Getting Started
To get started with this project, follow these steps:

<div>
    <h2>Install Dependencies:</h2>
    <pre>pip install spacy numpy</pre>
</div>

<div>
    <p>Download Spacy Model:</p>
    <pre>python -m spacy download en_core_web_sm</pre>
</div>

<div>
    <p>Clone the Repository:</p>
    <pre>git clone &lt;repository-url&gt;</pre>
</div>

<div>
    <p>Run the Application:</p>
    <pre>python main.py</pre>
</div>

Contributors
<ul>
  <li>Atharva Sardal - 2021.atharva.sardal@ves.ac.in</li>
  <li>Ashish Patil - 2021.ashish.patil@ves.ac.in</li>
  <li>Khalid Sayyed - 2021.khalid.sayyed@ves.ac.in</li>
</ul>

 Happy Recruiting! 🚀
