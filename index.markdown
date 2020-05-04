---
layout: default
---
# How I learned Data Science?
Hey, welcome on bord, here you can follow my progress in data science. Below I have mapped `the learning path` I am following. I will update that path as I discover more content. Of course, it is not an exhaustive list.

# Progress and futur work

![Coggle_data_science](assets/mind_map2.png)
<hr>

- Go deeper in the math
	* Introduction to statistical learning
	* Reading again some chapter of Hand-on ML
- Business insight with the book Data Science for Business
- Practice, practice and practice again 
	* Achieve all the project on Hand-on ML
- Introduction to Database
	* Introduction to algorithm with python
	* SQL
- Introduction to Hadoop
- Introduction to web dev (1 week challenge) - create the version 2 of the blog
- Introduction to cyber security

# My Curiculum
In the next following sections, we will go through all this different fields.
## 1.  The big picture of Data Science
First, it is important to have a good overview of this broad subject. In that purpose, understanding [the job of a data scientist]({{site.url}}/my_blog/what_does_a_datascientist) is primordial. As a resume, I gather in the list and the mind map bellow all the *"tools"* you and I will need to master in Data Science:

  - **Learn to code** - Python is an excellent first option with a large community and strong libraries for Data Science
  - **Data Analysis** to gain insight from data
  - **Machine Learning** to make prediction and draw conclusion from this insight
  - A good understanding of **Math** and **Algorithms** is mandatory 


<hr>

## 2.  A spark of motivation
As a spark of motivation I start by understanding the basic of Machine Learning. The goal here is to gain sens and motivation for the futur work in math and code. I recommend Vishal Maini & Samer Sabri's book, this is a good resource to start with the big picture of artificial intelligence and machine learning.

<figure>
  <a href="https://medium.com/machine-learning-for-humans/why-machine-learning-matters-6164faf1df12"><img src="./assets/ml_human.jpg">
  </a>
</figure>

This series is a guide for getting up-to-speed on high-level machine learning concepts. It is easy to understand with a good mixte between analogies, examples and technical explanation. You will find a lot of different resources to go deeper in the different fields - projects, videos, books and so much more. The authors give as well some interesting personal advice at the end of the book.

## `What I have learned?`
  - good insight and first intuition about the different fields of Machine Learning 

<hr>

## 3. Math
To have a deeper understanding of machine learning, I review some mathematical knowledge. My goal is about creating mathematical intuition rather than learn the formulas and computation methods. 
### ✔︎ Introduction to Linear Algebra and Calculus
  [Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) & [Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr): I highly recommend to see the videos of Grant Sanderson. His visual approach with superb animations will give you a solid conceptualization of those subjects. 

### ✔︎ Multivariable calculus 
  [MVC Khan Academy](https://www.khanacademy.org/math/multivariable-calculus): Khan Academy and Grant Sanderson worked together in the purpose to create a course with a visual meaning of important tools useful in the field of Multivariable Calculus. I realy enjoy the part on Maxima and Minima and Constrained Optimization. You will learn about Gradient, Laplacian, Lagrangian multiplier and so on. 

### ✔︎ Probability and Statistics
  [Statistics and probability Khan Academy](https://www.khanacademy.org/math/statistics-probability): This interactive and well-designed course provides an introduction to important tools as Regression, Confidence Intervals, Significance Test and so much more. 

## `What I have learned?`
  - review the important tools of Multivariable Calculus and Statistics
  - obtain a deep visual understanding of those concepts
<hr>

## 4.Data Analysis 
If you want to get into Data Science, you have to know how to manipulate data. Most of your time, as a data scientist engineer, will be spend on manipulating, analysing and getting data ready for modeling. **I recommend to perform data analysis with pandas**, the popular open source library for data analysis in Python. 


One of the creator of pandas, Wes McKinney, wrote a book called *“Python Data Analysis”* and it is a really good choice for learning data analysis in Python. **This book show you how to solve a broad set of data analysis problems effectively**. You will get complete instructions for manipulating, processing, cleaning, and crunching dataset. It is well written and the real-world examples are really usefull to understand the workflow of data analysis in Python.


<figure>
  <a href="https://www.oreilly.com/library/view/python-for-data/9781491957653/"><img src="./assets/book_data_analysis.jpg">
  </a>
</figure>

As a complement, in [the Harvard course on Data science](https://matterhorn.dce.harvard.edu/engage/ui/index.html#/2016/01/14328), you will find great lectures on data analysis. I really recommend to at least take a look to [Exploratory Data Analysis and effective Visualizations](https://matterhorn.dce.harvard.edu/engage/player/watch.html?id=4dc7719e-1ef4-4ee5-a9d9-fc48c3e13185), you will discover some usefull principles for effective visualization. Take also a look at plotly and Tableau to complete your skills in data visualization.


## `What I have learned?`
- use flexible tools to load, clean, transform, merge, and reshape data
- create informative visualization with matplotlib
- apply the pandas groupby facility to slice, dice and summurize datasets
- manipulate time series data
- learn how to solve real world data analysis problems with detailed examples

--- 

## 5. Machine learning
Through the book Hands‑On Machine Learning with Scikit‑Learn, Keras, and TensorFlow by Aurélien Géron I discovered the machine learning landscape. Each chapter ends by a quizz and few coding project. A really enjoy this mix between learning new knowledge, testing your understanding with the quizz and practising on project.

<figure>
  <a href="https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/"><img src="./assets/Hands_on_ml.jpg">
  </a>
</figure>

## `What I have learned?`
- Explore the machine learning landscape, particularly neural nets
- Use Scikit-Learn to track an example machine-learning project end-to-end
- Explore several training models, including support vector machines, decision trees, random forests, and ensemble methods
- Use the TensorFlow library to build and train neural nets
- Dive into neural net architectures, including convolutional nets, recurrent nets, and deep reinforcement learning
- Learn techniques for training and scaling deep neural nets

---
> "Value of knowledge shouldn't depend upon where that knowledge was acquired" <cite>&mdash; [*Giles McMullen-Klein*](https://www.youtube.com/channel/UC68KSmHePPePCjW4v57VPQg)</cite>. Special thanks to this guy who gathers a lot of different resources about data science. Those videos are superb and motivational.




<hr>
<br>
 <h1>Posts</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="/my_blog{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>




