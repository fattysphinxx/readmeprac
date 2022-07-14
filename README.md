---
title: Home
hide_title: true
slug: /
---

<p align="center">
  <img src="https://i.imgur.com/sJzfZsL.jpg" width="154" />
  <h1 align="center">InstaPy</h1>
  <p align="center">Tooling that <b>automates</b> your social media interactions to "farm" Likes, Comments, and Followers on Instagram implemented in Python using the Selenium module.</p>
  <p align="center">
    <a href="https://github.com/timgrossmann/InstaPy/blob/master/LICENSE">
      <img src="https://img.shields.io/badge/license-GPLv3-blue.svg" />
    </a>
    <a href="https://github.com/SeleniumHQ/selenium">
      <img src="https://img.shields.io/badge/built%20with-Selenium-yellow.svg" />
    </a>
    <a href="https://www.python.org/">
    	<img src="https://img.shields.io/badge/built%20with-Python3-red.svg" />
    </a>
    <a href="https://travis-ci.org/timgrossmann/InstaPy">
      <img src="https://travis-ci.org/timgrossmann/InstaPy.svg?branch=master" />
    </a>
    <a href="https://www.github.com/timgrossmann/InstaPy#backer">
      <img src="https://opencollective.com/instapy/backers/badge.svg" />
    </a>
    <a href="https://www.github.com/timgrossmann/InstaPy#sponsors">
      <img src="https://opencollective.com/instapy/sponsors/badge.svg" />
    </a>  
    <a href="https://discord.gg/FDETsht">
      <img src="https://img.shields.io/discord/510385886869979136.svg" />
    </a>
  </p>
</p>





<br />

# Install Guide



## ** Download **

### * Download frontend repository **
https://github.com/SCC-AI-3/Spartagora_Front

### * Download backend repository **
https://github.com/SCC-AI-3/Spartagora_Back

### ** unzip both files **
<img width="213" alt="Screen Shot 2022-07-13 at 11 30 29 PM" src="https://user-images.githubusercontent.com/104494448/178758959-6a4dfb0f-371c-410f-ab59-95218858fbfd.png">

### ** setting venv **
#### * for mac *
```elm
python -m venv venv
```

```elm
source venv/bin/activate
```

```elm
pip install -r requirements.txt
```

####
* for window * 


## ** create admin, set up DB **

in spartagora_front project
```elm
python manage.py makemigrations > python manage.py migrate > python manage.py createsuperuser
```

## ** open localhost **

in spartagora_front project (port number 8000)
```elm
use live server or else 
```

in spartagora_back project (port number 5000)
```elm
python manage.py runserver
```

## ** And Joy it! **






