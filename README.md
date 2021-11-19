# FASTAI_lesson2_bear_app
Following along with the FASTAI course version 4. This is from the Lesson 2 notebook and Lesson 3 video.
The code is derived from the lesson 2 notebook:
https://github.com/fastai/fastbook/blob/master/02_production.ipynb

This repo was setup for the express purpose of testing dashboard hosting on mybinder.org

Check out the results here:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Exocyst/FASTAI_lesson2_bear_app/production?labpath=voila%2Frender%2Fbear_app.ipynb)

Although not particularly complex, this simple classification model was easy to learn and seeing it hosted on mybinder.org is oddly satisfying.  The concepts were very well described by the FASTAI team.  I highly recommend the course to anyone who thinks deep learning is *too complex*. Actually, the concepts are dead simple, but it is critical to understand each component in isolation.  The videos and jupyter notebooks are a great introduction to how this complexity works.

### A little wrinkle to consider on binder:
When you create a new binder instance, a new docker container is created and hosted on google cloud (Thanks Google). However, if you then find out your code contains a bug, then you will need to update you Git repo. However, when you return to binder and once again try to create an instance for your main branch, it will pull the old docker container on google cloud, so your new code will never be considered. So, I created a new branch on git called **production**, and I targeted the mybinder instance linked above to that branch.
