---
layout: default
---
<h1>Welcome to my blog</h1>
Hey, here you can follow my progress in data science. Bellow I have mapped `the learning path` I am following. I will update that path as I discover more content. Of course, it is not an exhaustive list.

In the sidebar, you can also find a section where I gather all [the projects I am working on]({{site.url}}/my_blog/project) - and [a teaching section]({{site.url}}/my_blog/teaching) where I explain the knowledge I have learned. 

> Value of knowledge shouldn't depend upon where that knowledge was acquired <cite>&mdash; Giles McMullen-Klein</cite>

<hr>

## 1.  First step in data science
First of all, to have a better insight into what I will learn, I tried to resume [the job of a data scientist]({{site.url}}/my_blog/what_does_a_datascientist). Then I read Vishal Maini & Samer Sabri's book. This is a good resource to start, with a good overview of this broad subject.

<figure>
  <a href="https://medium.com/machine-learning-for-humans/why-machine-learning-matters-6164faf1df12"><img src="./assets/ml_human.jpg">
  </a>
</figure>


It is easy to understand for a first step in Machine learning - a good mixte between analogies, exemples and technical explanation. You will find a lot of different resources to go deeper in the different fields - projects, videos, books and so much more. The authors give as well some interesting personal advice at the end of the book.

`What I have learned?`
  - good insight and first intuition about the different fields of Machine Learning 

<hr>

## 2. Math
If I want to go deeper, I need to understand all the math around Machine learning.  
  * Linear Algebra  
  * Calculus  
  * probability and statistics


## 3.Futur work
- Python basics: already do with my background. I will do some exercise to refresh and improve my learning skills
- dive into all the link of the book to go a bit deeper in all the learning method

- Dive into Python
  * Python project 
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




