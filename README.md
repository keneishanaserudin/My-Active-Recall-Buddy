## The Problem
Many students rely on passive study methods, such as rereading, highlighting, underlining, watching, listening, or repeating, which may be less effective for long-term retention than active recall. Even when students practice active recall, they often struggle to produce optimal results without guidance or feedback. That said, **My Active Recall Buddy**, which is an inclusive, user-friendly learning assistant, may offer a solution to this problem.


## How It Works
**My Active Recall Buddy** is a web application where students can upload study materials, select topics, and practice active recall by writing explanations from memory within a timed session. After submitting their responses, an AI system will compare their explanations against the uploaded materials, highlight incorrect or missing information, and automatically generate a mistake log. Students can use this feedback to identify weak areas and improve their understanding through repeated recall sessions. The goal is to become the #1 study buddy for active learning, even for students unfamiliar with the active recall method.

Below is **My Active Recall Buddy** ‘s system diagram:
![System diagram](docs/diagram.png)


## Tech Stack
- **Language:** Python, JavaScript, HTML, CSS, SQL, Bash
- **Libraries:** React, Vite, FastAPI, PyMuPDF, OpenAI, SQLite 
- **External tools:** OpenAI API, Visual Studio Code, Git, GitHub, Vercel, hosting service

## Setup
How to run the project locally?
1. Clone the repository.
```git clone https://github.com/keneishanaserudin/My-Active-Recall-Buddy.git
cd My-Active-Recall-Buddy
```
2. Install frontend dependencies.
```cd frontend
npm install
```
3. Install backend dependencies.
For Mac:
```cd backend
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
```.venv\Scripts\activate
```
4. Configure the OpenAI API.


## Usage
1. Start the backend server.
```uvicorn main:app --reload
```
2. Install frontend dependencies.
```cd frontend
npm install
```
3. Use the application.
    1) Upload study materials in PDF or TXT format.
    2) Enter or select a topic to study.
    3) Start the stopwatch and write an explanation of the topic from memory.
    4) Submit your response for AI evaluation.
    5) Review the feedback identifying correct, incorrect, and missing concepts.
    6) Use the mistake log to identify topics that need further review.


## Roadmap
Planned features for **My Active Recall Buddy** in the future:
- [ ] Auto-generated flash cards.
- [ ] Mind map mode.
- [ ] Voice-to-text recalling.
- [ ] Spaced repetition notifications.
- [ ] Spaced repetition notifications.
- [ ] Spaced repetition notifications.
- [ ] Advanced document processing (analyzing multiple files or scanned notes).


## Author
Keneisha Naserudin, https://github.com/keneishanaserudin. 
