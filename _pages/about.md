---
permalink: /
title: "👋 Hi, welcome to my cozy coding home 🏡"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<img src="/images/cat_code+meme.jpg" alt="cat_meme" width="300"/>

👩‍💻 I'm a first year graduate student at CMU MIIS (Master of Science in Intelligent Information Systems). 

📑 I'm still exploring my research interests, but I'm mainly focus on Natural Language Processing and computational linguistics.

✍️ My previous researches involve AMR (Abstract Meaning Representation) and UMR (Universal Meaning Representation) annotation, and C-STS (Conditional Semantic Textual Similarity). 

# Experience

## 👩‍🏫 Undergraduate Teaching Assistant

- Assisting Professor in Problem Solving in Python with over 70 students to enhance student understanding by holding
regular office hours and providing mentorship. 

- Help professor grade and give feedbacks to students’ homework and programming assignments. 

- Holding weekly recitations to answer students’ questions about lectures materials. 

## 🥼 Undergraduate Research Assistant  

- Assist Professor Pustejovsky’s Lab to complete domain specific AMR (Abstract Meaning Representation) annotation. 

- Manually annotate and validate machine generated AMR graphs using AMR-dict and UMR writer. 

- Design and propose domain specific rules to adopt AMR graphs to suit for recipe data set 

- Using Python, spaCy and Flask to process jsonlines file and visualize event trigger and entity spans across sentences. 

- Generating GLAMR that incorporates subevent structure for predicates and designating opposition structure for the object undergoing change.

# Projects

## 🤔 SWiT: Emoji Annotation

Emojis have surged in popularity every since their invention. People use them to add more emotions to the plain text. 

However, emojis also have their unique connotation: the same emoji can have completely different meanings depending on the context in which it appears. 

[Our emoji annotation project](https://github.com/KeerXu721/SWiT) aims to understand the nuanced connotations of three popular emojis: 

  1.😭 (loudly crying face)  
  2.🥲 (smiling face with tear)  
  3.🥺 (face holding back tears)

We designed the annotation guidelines to annotate the emoji emotions and we ran sklearn’s Logistic Regression model and sklearn’s Naive Bayes model on it to get a baseline. 

## 💭 Emoji Generator for Texts 

[Emoji project](https://github.com/yueliulu/COSI217Final) again 🥳

There are tons of emojis, but when we are messaging, it takes forever to find the perfect emoji suited for our text 😫. 

Our goal is to augment sentences with suitable emojis to imbue it with liveliness and emotion. And we designed a webpage using Streamlit to deploy this functionality 

For example:  
Input:  “I like noodles”  
Output: ❤️🍜 (suggested emoji by the model)

