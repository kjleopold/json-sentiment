# Requests, JSON, and basic NLP with spaCy

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

* (Question 1) Lyrics printed: 1 pt
* (Question 1) File created and submitted with notebook: 1 pt
* (Question 2) Correct polarity reported: 1 pt
* (Question 2) Question answered thoughtfully: 1 pt
* (Question 3) Function defined as specified: 1 pt
* (Question 3) Song lyrics retrieved and stored in separate files (0.5 pts/song): 2 pts
* (Question 4) Polarity scores printed (with appropriate label containing song title, .25 pts/song): 1 pt
* (Question 4) Questions answered thoughtfully: 2 pts

## Objective
This exercise illustrates how to access web-hosted APIs, get back a response in JSON to an external site. format, and extract the information we need from the JSON. Accessing APIs is a key skill for data analysts. APIs are used to get stock data, weather data, and much more. This project used an API to access song lyrics or poems. The specific API used isn't important, there are many and they often change. The goal is to be able to (a) make an API request and (b) find the information needed in the returned response.

### Step 1: Copy the base repository to local machine
* `git clone` [requests-json-nlp.ipynb](https://github.com/wmnlp-materials/json-sentiment)

### Step 2: Set Up and Activate Virtual Environment
* `python -m venv .venv`
* `.venv/Scripts/activate`
* Select appropriate interpreter
    - Ctrl + Shift + P
    - Python: Select Inerpreter
    - Choose .venv\Scripts\python.exe

### Create .gitignore and Install Packages
* Create .gitignore.
* Create requirements.txt to install packages.
* `pip install -r requirements.txt`

### Open Notebook and Complete Tasks
* Make sure kernel is selected.
* Add a viewable, clickable link to GitHub repo after name in the Markdown Introduction.
* Use Markdown headings to show content by each question number.
* Complete the questions.

### Execute the notebook

### Commit and push to GitHub
* `git add .`
* `git commit -m "Meaningful comment"`
* `git push`
* Verify the notebook appears correctly in GitHub.

### Export to HTML and Finalize Repo
* `!jupyter nbconvert --to html pyplot.ipynb`
