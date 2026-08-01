Secure AI Hackathon (Seattle Data AI & Security Community) — Data Analyst track. 

**Challenge statement**: Build an AI assistant or dashboard that lets users ask questions about a
dataset and get answers that are calculated or verified from the data,
rather than invented by the model. Teams may use a clean CSV, a notebook, a Streamlit or Gradio application, 
or a basic dashboard. The goal is not complex AI architecture; the goal is useful and trustworthy answers from data.

**Problems:** Students often get lost in tracking their financial performance by overspending or impulsive buying. This 
solution helps students to track and control a weekly budget across fixed and variable
spending categories, without a black-box chatbot that hallucinates
numbers, or a dashboard so rigid it can't handle a question outside its
exact intended scope.

**Solution:** Student budget analyser app. This app will do the following: 
Ask users to set their monthly budget based on: Their location, spending categories including: 
Fixed: Rent, insurance, subscription
Variables: Grocery, home necessity, entertainment, and impulsive buying. 

**Solution expectations:** The application must calculate, query, or verify results using the actual dataset. When the data cannot answer a question, the system should say so instead of generating an unsupported response. 

**Core workflow:** Dataset, user questions, verified answer and evidence. 

**Setup:** 
Python 3.9+ and pip.
bash
git clone: https://github.com/ngocanhne10/Student-budget-analyst
cd student-budget-analyst

**Installation**
bash
pip install -r requirements.txt
Installs: `streamlit`, `pandas`, `plotly` — all open source, no accounts or
API keys required.

**Execution**: bash
streamlit run app.py



