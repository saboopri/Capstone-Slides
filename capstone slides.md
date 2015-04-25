---
title: capstone slides
author: Priyanka
mode : selfcontained
framework: revealjs
hitheme : zenburn
revealjs:
  theme: night
  transition: none
  center: "true"
bootstrap:
  theme: amelia
knit        : slidify::knit2slides
---

# Predict Next Word!
### DATA SCIENCE CAPSTONE 
#### JHU - COURSERA

<small> Created by Priyanka Saboo</small>

<small><small> Slide Template taken from [Slidify Examples](http://ramnathv.github.io/slidifyExamples/) </small></small>

---

## Why Predict?

> Isn't is awesome when someone can read your mind? Okay, maybe we can't do that right now BUT what we can do is **predict what you will type next...**

.fragment so when you type: <strong>i love...</strong>

.fragment our first prediction would be <strong>YOU</strong>

---

## BUT How Does It Work?

<small>...hit next arrow...</small>

.fragment You enter a word or a phrase

.fragment Our application runs the magic algorithm (pre-modeled by huge datasets from news, blogs and twitter taken from [HC Corpora](www.corpora.heliohost.org))

.fragment Our application returns up-to five possible predictions

.fragment It even lets you select the word and continue searching until your sentence is complete

---

## Algorithm?

.fragment The application is pre-modeled and trained by N-grams made from huge datasets

.fragment The datasets had to be cleaned before they could be trained

.fragment We then built a function <strong>search</strong>, for prediction, using Basic NLP and utilizing N-grams in Markov Model and Back-off Model

> The <strong>TM Package</strong> was used extensively in creating the Application

---

## Why Dont You Try It Yourself?

> The application is deployed at [ShinyApps.io](https://saboopri.shinyapps.io/predictword-capstone/)*

.fragment Wait for the application to load

.fragment Begin typing word(s) in the provided text box

.fragment The word(s) will be searched for the next best prediction

.fragment The predictions will be shown with your typed phrase. You can select one of the predictions to copy it in the text field and the next prediction will be automaticaly searched

.fragment Check out the cool <strong>WordCloud</strong>, the <strong>Probability Graph</strong>, and <strong>About</strong> for more details

> THANK YOU

<small>* Click on the link to access the app</small>
