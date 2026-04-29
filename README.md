# AI Recruiting System

An AI-powered recruitment system that automates resume screening, extracts candidate skills, and ranks applicants based on job requirements using Machine Learning and NLP techniques.

---

## Features

-  Resume parsing and text extraction  
-  AI-based candidate ranking system  
-  Skill extraction using NLP techniques  
- Job description vs candidate matching score  
-  Automated screening process  

---

## Objective

To reduce manual effort in recruitment by automatically analyzing resumes and ranking candidates based on their relevance to job descriptions using AI techniques.

---

## Tech Stack

- Python 
- Machine Learning (Scikit-learn / NLP)  
- Pandas, NumPy  
- Flask / Django (if applicable)  
- HTML, CSS, JavaScript  
- Visual Studio Code  
- Git & GitHub  

---


## Project Directory Structure

```bash
AI-recruiting-system/
│
├── Frontend/                    # Frontend user interface
│   ├── index.html
│   ├── styles.css
│   ├── script.js
│   ├── components/
│   └── assets/
│
├── backend/                     # Backend logic and APIs
│   ├── app.py                   # Main Flask/Django file
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   ├── config.py
│   └── utils/
│
├── resume_rank/                 # Resume ranking module
│   ├── static/
│   │   ├── uploaded_resumes/    # Uploaded resume storage
│   │   └── processed_resumes/
│   ├── main.py
│   ├── ranker.py
│   └── utils.py
│
├── package-lock.json            # Node.js dependencies lock file
├── requirements.txt             # Python dependencies
├── .env                         # Environment variables
├── .gitignore
├── README.md                    # Project documentation
└── run.py                       # Entry point to run the application
```


---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/nisma01paudel/AI-recruiting-system.git
cd AI-recruiting-system
```
2. Backend Setup
```
cd backend
npm install
```
Run backend server:
```
npm start
```
or (if using nodemon):
```
npm run dev
```
3. Frontend Setup
```
cd Frontend
npm install
```
Run frontend:
```
npm start
```
or:
```
npm run dev
```
4. Python Dependencies (if applicable)
```
pip install -r requirements.txt
```
Run Python backend:
```
python app.py
```

## How It Works

- Resume uploaded by user  
- NLP extracts text and skills  
- Job description is analyzed  
- Matching score is calculated  
- Candidates are ranked automatically  

---

## Future Improvements

- Improve NLP accuracy  
- Add deep learning model  
- Deploy as web application  
- Add authentication system  
- Integrate job portals  

---

## Contributors

This project was developed as part of the 6th Semester B.E. Computer Engineering curriculum at Nepal Engineering College.

- Nisma Paudel  
- Prakash Bhatta  
- Sabina Dhahal  

---

## License

Academic project – Nepal Engineering College  

---

## Acknowledgement

We would like to express our gratitude to our supervisor and Nepal Engineering College for their support and guidance.
