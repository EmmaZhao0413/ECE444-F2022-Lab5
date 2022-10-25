Emma Zhao, Wendy Wang, Mandy Hsu
# CARTE Education Pathways

This repo is a clone of https://github.com/nelaturuk/education_pathways.git

<img width="1431" alt="Screen Shot 2022-10-24 at 12 57 05 PM" src="https://user-images.githubusercontent.com/103273559/197582669-c7017e10-8b0b-4fce-9d3b-f2e026ceff53.png">

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

## Activity 2-5
![](images/activity2345-2.png)
![](images/activity2345-1.png)

## User Stories

### Review System Interface
<img width="630" alt="Screen Shot 2022-10-24 at 10 21 50 PM" src="https://user-images.githubusercontent.com/103273559/197667015-d0fc946d-93bc-4472-bf34-c7dc1e7fc74a.png">

<img width="1440" alt="Screen Shot 2022-10-24 at 10 19 47 PM" src="https://user-images.githubusercontent.com/103273559/197666754-f0ba75b9-2228-44df-b2fe-4a76658c41ea.png">

### Minor Fliter
<img width="627" alt="Screen Shot 2022-10-24 at 10 25 12 PM" src="https://user-images.githubusercontent.com/103273559/197667442-06e43885-b2d0-4cd9-a0a4-0c40627afc5d.png">

<img width="1440" alt="Screen Shot 2022-10-24 at 10 27 09 PM" src="https://user-images.githubusercontent.com/103273559/197667631-47c5693b-9ebb-4b21-8de1-8a53ed38604e.png">

### Flag inaccurate course page
![](images/activity6-1.png)
![](images/activity6-2.png)
![](images/activity6-3.png)



