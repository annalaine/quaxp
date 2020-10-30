# Data Quality Explored

Welcome to the project QuaXP - Data Quality Explored.  
You find yourself on the tutorial page. Here you can learn everything about the course and how to use the book.  
Good luck!

__Tutorial: how to use the book?__

The course is supposed to be worked with in autonomy: there is no way of keeping track of someone's progress and results. If you wish to keep your scores, you should write them somewhere locally.

On this page, we present in different sections, the parts the book contains and how they should be used, the two different difficulty levels (beginner and advanced), and their content, and a note to use the book as a support for teaching.

## The different parts of the book

This book is divided in different parts. To fully understand how to work with it and which pages to visit, here is an overview on how each part is meant to be integrated in the learning experience.

### The introduction

The introduction contains some introductory content that can help to understand the course.  
If you never heard of machine learning before, and never tried to visualize some data on a graph, we highly recommend you to read the introduction.  
This section is meant for both beginner and advanced levels, the introduction to Python targetting only the advanced learners.

#### What is machine learning? 

{doc}`There<0-1-machine-learning>`, you can learn what "machine learning" means and how it is used in the course. This page is important to understand what the main steps in a machine learning experiment are. It is a good introduction to understanding the place of the data in the whole process.

#### Supervised learning used in this course 

On {doc}`this page<0-2-supervised-learning>`, we dig a little bit more in the details of the specific type of machine learning we use here. You learn how to measure the performance of a machine learning experiment, and how the data is specified depending on its type.

#### }Main types of graphs used in this course 

We present {doc}`here<0-3-graphs>` different ways we will use in the course to visualize the data or the results of our experiments. It follows the previous pages as you need to understand what the data and the results mean before being able to apprehend them on a graph.  
Specifically, we present histograms, boxplots, and classic 2-d plots of one variable against another.

#### .csv files - data format used in the course 

{doc}`This short page<0-4-data>` shows the format used for data files in the course. It is not necessary for the beginner level, but it can be useful to have an idea on how the data look like. For the advanced level, the knowledge of ``.csv`` files is necessary.

#### Get started with Python 

{doc}`This section<0-5-python>` offers 7 pages showing basic tutorials about Python. If you only want to follow the beginner level, you can skip this part. It is a good starting point for learners who want to follow the advanced level and have never worked with Python or with the Pandas library. Have a look at the different sections and identify what you already know and what you do not.

### The appendix

This part is only for curious minds, it contains additional content that is not necessary to understand the course. We present how the data have been collected and transformed before being used in the course, and how the machine learning algorithms that we choose work.

### The chapters

The course contains 3 chapters. Each chapter contains several sections that are entirely part of the course, with a quiz at the end of each page.  
At the end of the chapter, a practical task is proposed for the advanced level.

#### Chapter 1: numerical data

This chapter studies how to understand, gauge and deal with data quality for numerical data, meaning, datasets containing numbers. In our case, we took the specific case of AIS data, data sent by a ship along its journey at sea (speed, location, time). We propose several small experiments to understand how a change in the data affects the result of a machine learning experiment.

#### Chapter 2: image data

We dig into the world of images. How images are treated and understood by algorithms in a machine learning experiment, and how we can modify an image dataset to modify the results of our prediction. We chose a simple problem of object classification for this chapter: we want to build a model that can classify the object present on an image (for example: "is this animal a horse or a cat?").

#### Chapter 3: text data

__TODO when the chapter is implemented.__

## Beginner level

The beginner level aims to teach data quality to learners with no background in coding or computer science. The course follows the same path as for the advanced level, without the code cells and code instructions.

### Prerequisites and target audience

Some logic thinking is still needed to understand the beginner level, as we discuss about data, statistics and graphs. But everything is explained in time.

The beginner level targets every curious mind who would come accross this teaching offer and would like to learn more about machine learning and data. Curiosity is necessary, as it is not an easy topic, but we aim to make it as accessible as it can be.

### Summary videos

Summary videos at the beginning of each section aim to give a first glance of the addressed topics in the part. After watching those videos, you should be ready to start with the course itself.

### Quizzes

Inside the course, quizzes are proposed at the end of each page to test whether the page was well understood. Thoses quizzes are a way of self-learning: feedback is given for each question but nothing is mandatory.

### Visualizations

The visualizations (graphs, images, ...) for the beginner level are the same as for the advanced level. Most visualizations are static but sometimes, an interactive widget allows you to play around with parameters to see how the results are affected. Don't be shy with those widgets, even if they should display an error: there is no error that can make your computer crash.

### A jump to the next level?

For the most brave learners, there is always the possibility to shift from beginner to advanced. The only difference between the two levels is additional information about code and the possibility to run code cells.  

A tutorial to get started with Python is available in the introduction. Why not give it a try?

## Advanced level

The only difference between the beginner and the advanced level is the addition of code cells and code instructions.

### Code cells

The code cells integrated in the pages are the most important feature for the advanced level. They allow you to run and modify code directly in the book. Don't be shy to play around and modify them as much as you want: even if you should get an error, nothing is fatal for the book. Creating errors can also be part of the fun.

Tu run the cells __TODO when we are sure of the process.__

### Summary videos

Those videos at the beginning of each section give a summary of the addressed topics in the part.

For advanced learners, they can be used in several ways: either to test whether or not you already know what the chapter deals with, in that case, you can try to answer the quizzes directly and do the practical task to test yourself first. They can also help to remember the main points listed in each part, for example after having worked with the book, to refresh the knowledge, etc...

### Quizzes

At the end of each page, quizzes about the content of the page are proposed. Those quizzes do not contain any coding questions and are more thought of as a test and a refreshment about the concepts of the course.

### Practical tasks

At the end of each chapter, a practical task is proposed. There, you can apply on new data and examples the coding concepts you learned during the course.

Automatic grading is used to grade the practical task. __TODO: explain how it works once it works.__

## Use the book for teaching

__TODO__