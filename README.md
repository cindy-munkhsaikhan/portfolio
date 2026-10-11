# Technical Portfolio

Welcome to my technical portfolio! I am a Master of
Information Technology (Applied AI) student at
Macquarie University, with academic experience in machine
learning, computer vision, natural language
processing and front-end development.

This portfolio showcases selected academic and
professional projects, including the technologies
I used, my contributions and what I learned.

## Projects

1. [Computer Vision — Object Detection & Image Segmentation](#project-1-computer-vision--object-detection--image-segmentation)
2. [Natural Language Processing — Text Classification](#project-2-natural-language-processing--text-classification)
3. [Front-End Web Development — Catalyst Fund](#project-3-front-end-web-development--catalyst-fund)
4. [Python Programming — UC Berkeley CS61A](#project-4-uc-berkeley--structure-and-interpretation-of-computer-programs)

---

## Projects

### 1. Computer Vision — Object Detection & Image Segmentation
**Technologies:** Python, PyTorch, YOLOv8, U-Net, ResNet18

- Fine-tuned YOLOv8 for object detection.
- Implemented U-Net with ResNet18 for image segmentation.
- Evaluated model performance using mAP, Dice and IoU.

**Course:** Deep Learning

**Technologies:** Python, PyTorch, YOLOv8n, U-Net, ResNet18, OpenCV

### Project Overview

This project explores object detection and image segmentation using deep learning. I trained and fine-tuned YOLOv8n for object detection and implemented U-Net with a ResNet18 encoder for image segmentation.

For the final task, I used the TACO (Trash Annotations in Context) dataset to detect and segment litter in real-world images.

### 1. Object Detection — YOLOv8n

I trained YOLOv8n on the TACO dataset to identify different types of litter, including plastic bottles, drink cans, and cardboard.

The model predicts bounding boxes, object categories, and confidence scores.

![Object Detection Results](cv_detection.png)

### 2. Image Segmentation — U-Net

I implemented U-Net with a pretrained ResNet18 encoder to segment litter objects from the background.

Unlike object detection, which identifies objects using bounding boxes, segmentation predicts the pixels belonging to each object.

![Image Segmentation Results](cv_segmentation.png)

### Challenges and Lessons Learned

The models were able to identify some litter objects, but performance was limited, particularly for small objects and complex backgrounds.

This project helped me understand transfer learning, model evaluation, and the challenges of applying computer vision to real-world images.


## Project 2: Natural Language Processing — Text Classification

**Technologies:** Python, Scikit-learn, TF-IDF,
Logistic Regression, Linear SVM

### Model Performance Comparison

I compared Naive Bayes, Logistic Regression and
Linear SVM using training and test accuracy and
F1-score. Linear SVM achieved the highest test
accuracy, although its larger training–test gap
suggested possible overfitting.

![Model Performance Comparison](nlp_comparison.png)

### Exploring Model Predictions

I also used Logistic Regression to classify text
into 15 categories. The confusion matrix shows
that the model correctly identified many Safe
examples but struggled with some unsafe categories.

![Text Classification Results](text_prediction_analysis.png)

---

## Project 3: Front-End Web Development — Catalyst Fund

**Type:** Professional Project | Front-End Development Internship

**Technologies:** Next.js, React, Tailwind CSS, JavaScript

### Project Overview

I collaborated with another front-end developer to complete the project and deliver the website on time.

### My Contributions

- Developed responsive web pages and interactive features using Next.js.
- Worked on front-end components and website layouts.
- Collaborated with another developer to integrate our work.
- Helped resolve integration issues before the project deadline.

### Challenges and Lessons Learned

One challenge was integrating our work near the project deadline, which caused unexpected issues. We worked together to resolve the problems and complete the website on time.

This experience taught me the importance of communication, teamwork and coordinating code changes during software development.

### Live Website

[Catalyst Fund — View Website](https://www.otcatalystfund.mn/)
![Catalyst Fund Website](live_website.png)

---

## Project 4: Python Programming — UC Berkeley CS61A

**Type:** Independent Coursework Practice | UC Berkeley CS61A

**Technologies:** Python, Object-Oriented Programming,
Recursion, Algorithms

### Project Overview

I worked on three programming projects from UC
Berkeley's CS61A course using provided starter code.
These projects helped me practise Python programming,
problem-solving and implementing different algorithms.

### 1. Ants vs. SomeBees — Tower Defense Game

A strategy-based game where players place ants to
defend their colony against bees.

I worked on the Python backend, implementing different
ant behaviours, attack mechanisms and game rules.
This included creating ant classes with different
abilities, managing interactions between ants and
bees, and implementing the Queen Ant's special abilities.

This project helped me understand object-oriented
programming and class inheritance.

![Ants Game](ants_game.png)

### 2. Hog — Dice Game

A turn-based dice game where two players compete
to reach a target score.

I implemented dice-rolling rules, scoring calculations
and turn-based game logic. I also developed strategies
for choosing how many dice to roll and used repeated
simulations to compare outcomes.

This project helped me practise functions, control
flow and higher-order functions.

![Hog Game](hog_game.png)

### 3. Cats — Typing Test

A typing test that measures typing speed and accuracy.

I implemented paragraph selection, typing accuracy
and words-per-minute calculations, and autocorrect
functionality. I also worked on recursive algorithms
to compare words and calculate edit distances.

This project helped me practise string manipulation,
recursion and algorithmic problem-solving.

![Cats Typing Test](cats_game.png)

### Challenges and Lessons Learned

These projects strengthened my Python programming
skills and helped me understand how to work with
existing code, break down problems into smaller
functions and debug different implementations.
