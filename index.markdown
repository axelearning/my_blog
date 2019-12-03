---
layout: default
---
<h1>Welcome to my blog</h1>
Hey, here you can follow my progress in data science. Bellow I have mapped `the learning path` I am following. I will update that path as I discover more content. Of course, it is not an exhaustive list.

In the sidebar, you can also find a section where I gather all [the projects I am working on]({{site.url}}/my_blog/project) - and [a teaching section]({{site.url}}/my_blog/teaching) where I explain the knowledge I have learned. 

> Value of knowledge shouldn't depend upon where that knowledge was acquired <cite>&mdash; Giles McMullen-Klein</cite>

<hr>

## 1.  First step in data science
First of all, it is important to have a good overview of this broad subject. In that purpose, understanding [the job of a data scientist]({{site.url}}/my_blog/what_does_a_datascientist) is primordial. Then I recommend Vishal Maini & Samer Sabri's book, this is a good resource to start, with The big picture of artificial intelligence and machine learning.

<figure>
  <a href="https://medium.com/machine-learning-for-humans/why-machine-learning-matters-6164faf1df12"><img src="./assets/ml_human.jpg">
  </a>
</figure>


This series is a guide for getting up-to-speed on high-level machine learning concepts. It is easy to understand with a good mixte between analogies, exemples and technical explanation. You will find a lot of different resources to go deeper in the different fields - projects, videos, books and so much more. The authors give as well some interesting personal advice at the end of the book.

## `What I have learned?`
  - good insight and first intuition about the different fields of Machine Learning 

<hr>

## 2. Math
To have a deeper understanding of machine learning, I review some mathematical knowledge. My goal is about creating mathematical intuition rather than learn the formulas and computation methods. 
### ✔︎ Introduction to Linear Algebra and Calculus
  [Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) & [Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr): I highly recommend to see the videos of Grant Sanderson. His visual approach with superb animations will give you solid conceptualisation of those subjects. 

### ✔︎ Multivariable calculus 
  [MVC Khan Academy](https://www.khanacademy.org/math/multivariable-calculus): Khan Academy and Grant Sanderson worked together in the purpose to create a course with a visual meaning of important tools useful in the field of Multivariable Maxima and Minima and Constrained Optimization. You will learn about Gradient, Laplacian, lagrangian multiplier and so on. 

### ✔︎ Probability and statistics
  [Statistics and probability Khan Academy](https://www.khanacademy.org/math/statistics-probability): This interactif and well design course provide an introduction to important tools as Regression, Confidence Intervals, Significance Test and so much more. 

## `What I have learned?`
  - review the important tools of multivariables calculus and statistics
  - obtain a visual understanding of those concepts
<hr>

## 3.Futur work
- First python project to review the basic of Python
- dive into all the link of the book to go a bit deeper in all the learning method
- take the standford class about machine learning
- read the book

- Subject we need to cover:
  * Data exploration and data visualization 
  * Python and data science  
  * Data structure and algorithms in python  

- Machine learning   
  * statistical learning  
  * TensorFlow

- Other useful language  
  * SQL 
  * R  
  * Git and version control

> Special thanks to the YouTuber [*Giles McMullen-Klein*](https://www.youtube.com/channel/UC68KSmHePPePCjW4v57VPQg). This guy gather a lot of different resources about data science. Those videos are superb and motivational. I highly recommend you follow his channel! Most of the content below come from his video ["Can you LEARN DATA SCIENCE for FREE?"](https://www.youtube.com/watch?v=eTxyviU0Ddo&feature=share&fbclid=IwAR1Ldib0ETlVNsHHEt_TU99SMggVk_AKFvCfd0Zm-THIN7K33spV6-ayTxY)

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




