Andy Xie

This repo is a clone of https://github.com/nelaturuk/education_pathways.

#### Activity 1: Screenshot of cloned repo.
![Activity 1](/screenshots/act1_screenshot.PNG)

#### Activity 2-5: Screenshot of cloned repo.
![Activity 2](/screenshots/act2_home_screenshot.PNG)
![Activity 5](/screenshots/act2_results_screenshot.PNG)

#### Activity 6:

One thing we can say about the new UI is that the dropdown menus and search bar more aligned and organized with each other than the old UI. Before, the old UI has the dropdown menus for the division, department, and campus all clumped up beside each other. The new UI aligns all these tools with a defined border and is now much easier for the user to distinguish. 

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
