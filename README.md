# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Create virtual environment
'''bash
python3 -m venv .venv
source .venv/bin/activate
'''

## Git add and commit 
'''bash
git add .
git commit -m "comment"
git push -u origin main
'''

## Install Dependencies
'''bash
python3 -m pip install beautifulsoup4 html5lib ipykernel jupyterlab matplotlib requests spacy spacytextblob
python3 -m pip freeze > requirements.txt
'''

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt
