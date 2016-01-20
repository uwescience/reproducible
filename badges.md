---
title: badges
layout: default
---

[[Overview and index]](index.html)


# Badges for Reproducbility and Open Science

<a
href="http://htmlpreview.github.io/?https://github.com/sr320/tmp-badge/blob/master/rros-badge-web.html">
<img src="https://img.shields.io/badge/RROS%20Badge-75-yellow.svg" alt="ROS
Badge"></a>



This page gives a brief summary of *work in progress* on a project to develop
a badge that can be earned by following some of the current best practices
in the field, such as the [Guidelines](guidelines.html) we are developing.

## Inspiration

 - The [Center for Open
   Science](http://cos.io/) project on
   [Badges to Acknowledge Open Practices](https://osf.io/tvyxz/).
   These badges are designed for journals to award to individual papers.

 - [UW Green Laboratories](http://green.uw.edu/green-laboratory).
   This program encourages staff, faculty, and students to make their
   laboratories and workplaces more sustainable.

 - Mozilla Science Lab [Contributorship
   Badges](https://mozillascience.org/contributorship-badges-a-new-project)
   to acknowledge diverse contributions to a publication.

## Goals

 - Have a low-stakes program to raise the visibility on campus of people doing
   reproducible research and open science,
 - Provide some simple incentives to working reproducibly and in the open,
 - Get researchers who are new to these ideas onto a trajectory of
   improvement,
 - Communicate to people the key principles and tools for reproducible
   research and open science,
 - Bronze, Silver, Gold levels based on cumulative history of following
   best practices for code and data.

## Status

Some description of the initial conception can be found on 
[this GitHub wiki page](https://github.com/uwescience/reproducible/wiki/%5BDRAFT%5D-Open-Science-and-Reproducible-Badges)
with discussion on this 
[issue](https://github.com/uwescience/reproducible/issues/3).

A first pass at a 
[badge submission form](https://docs.google.com/forms/d/1WqeQRmPi42pD-OqHxTqfA7aWqgPrkNjV8PTixA-m2sI/viewform?c=0&w=1)
was created using Google forms
during a Mozilla Code Sprint in June, 2015, along with a 
[description and point system](http://htmlpreview.github.io/?https://github.com/sr320/tmp-badge/blob/master/rros-badge-web.html).
A [shinyapp](https://benmarwick.shinyapps.io/ros_badge/) was also created to
present the information submitted in a form others can browse, but the data
submitted is no longer in the system.

This submission form was tested out both among eScience researchers and with
some volunteers from NYU and Berkeley at the 2015 Moore/Sloan Data Science
Environments Summit.  The consensus was that the form was cumbersome and 
required too much pasting of data from elsewhere.  

Subsequent discussions led to various ideas that have not yet been implemented:

 - Organize data collection for some sets of data by publication rather than
   splitting up links to the paper, to the data, to the code in different
   sections.  One possible outline was posted in 
   [this issue](https://github.com/uwescience/reproducible/issues/6).
   An inviting and easy to use form needs to be designed.

 - Make it possible for users to update their information if they want to
   earn more points, rather than having to start from scratch in the form.
   This can be done with Google forms (by saving a URL), 
   but long term it would be better to
   have some sort of authentication.  Can this be done using existing login
   credentials such as [GitHub](https://github.com/) or 
   [ORCID](http://orcid.org/)?

 - Scrape metadata automatically from users' ORCID account rather than
   having to cut and paste data about publications or data repositories.

 - Design a good way of presenting the data collected so that people can
   browse and learn about how others share their data and code.

 - Use the Mozilla [Open Badges](http://openbadges.org/) infrastructure?

