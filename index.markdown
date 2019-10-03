---
layout: default
---
 <h1>Welcome to my blog</h1>
Hey, here you can follow my progress in data science. Just bellow you will find **the learning path** I am following. I will update that path as I discover more content. Of course it is not an exhaustive list.

You can also find in the sidebar a section where I gather all [the projects I am working on]({{site.url}}/my_blog/project), and [a teaching section]({{site.url}}/my_blog/teaching) where I explain the knnowledges I have learnt. 

> Value of knowledge shouldn't depend upon where that knowledge was aquired <cite>&mdash; Giles McMullen-Klein</cite>

<hr>

## 1.  First step in data science
First of all to have a better insight of what I will learn, I tried to resume [the job of a data scientist](first_article). Then I started to read the free book of *Vishal Maini & Samer Sabri* : [Machine learning for human](https://everythingcomputerscience.com/books/Machine%20Learning%20for%20Humans.pdf) - this book give a good overview  of this broad subject. 
<hr>

## 2.Futur work
- Python basics  : already do with my background 

- Math
  * Linear Algebra
  * Calculus
  * probability and statistics

- Dive into Python
  * Python project
  * Data exploration and data vizualisation
  * Python and data science 
  * Data structure and algorithms in python
  
- Machine learning 
  * statistical learning
  * tensorflow

- Other usefull language
  * SQL
  * R
  * Git and version control


> Special thanks to the youtubeur [*Giles McMullen-Klein*](https://www.youtube.com/channel/UC68KSmHePPePCjW4v57VPQg). This guy gather a lot of different ressources about data science. Thoses video are superb and motivational. I highly recomand you to follow his chanel! Most of the content bellow come from his video ["Can you LEARN DATA SCIENCE for FREE?"](https://www.youtube.com/watch?v=eTxyviU0Ddo&feature=share&fbclid=IwAR1Ldib0ETlVNsHHEt_TU99SMggVk_AKFvCfd0Zm-THIN7K33spV6-ayTxY)

<hr>
<br>
 <h1>Posts</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
