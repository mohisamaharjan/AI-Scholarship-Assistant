## Project Title
AI Scholarship Assistant (Automated Scholarship Matching & SOP Generation using AI Agents
)

## Project Description / Problem Statement
Finding scholarships and writing strong Statements of Purpose (SOPs) can be time-consuming for students. 
This project automates scholarship matching based on a student's profile and generates personalized SOPs using AI agents.

## Features
- Intake Agent: Collects student profile including GPA, skills, and interests.
- Match Agent: Matches student with relevant scholarships based on keywords and GPA.
- SOP Writer Agent: Generates personalized SOPs using a local LLM (distilgpt2).
- Evaluator Agent: Scores SOPs based on keyword relevance.
- Session & Memory: Stores student profiles in temporary and long-term memory.
- Parallel Execution: Generates multiple SOPs simultaneously for efficiency.
- Visualizations: Shows scholarship counts per degree and top keywords.


## Architecture

Sequential and parallel agents workflow:

1. **Intake Agent** → Collects student data
2. **Match Agent** → Finds eligible scholarships
3. **SOP Writer Agent** → Generates SOP for each scholarship
4. **Evaluator Agent** → Scores SOP
5. **Output** → DataFrame with matched scholarships & SOP files





## Tools & Technologies
- Python 3.x
- Pandas, Matplotlib, Seaborn
- Transformers (distilgpt2)
- ThreadPoolExecutor for parallel processing
- Logging for observability


## Future Improvements
- Deploy as a web app for students to use online.
- Integrate more powerful LLMs for better SOP quality.
- Add more sophisticated matching using NLP similarity.


