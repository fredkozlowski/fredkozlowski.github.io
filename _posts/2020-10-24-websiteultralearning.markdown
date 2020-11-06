---
layout: post
title:  Learning How To Make A Website
date:   2020-10-24 15:01:35 +0300
image:  websiteultralearning/website2.JPG
tags:   Project
---

I read Scott H Young’s book Ultralearning a few weeks ago and I was inspired to run an ultralearning experiment on myself. Ultralearning is a technique for learning that is described as [aggressive, self directed learning](https://www.scotthyoung.com/blog/ultralearning/). I think that using the ultralearning techniques for achieving mastery is inefficient, but when learning from scratch they can be much more effective than regular book learning.

I chose to learn web development since I wanted to make a solid dent in what felt like an extensive field. I only knew HTML and CSS and wanted to know more about JavaScript and the various frameworks available for building websites, with a limited time frame of one week.

I wanted to build a site where you could input the movies you’d like to watch and then you would see what streaming service had the largest number of movies you chose. My first problem was getting a grasp of how the web development field is shaped. What did I need to use to create my website?

![]({{ site.baseurl }}/images/websiteultralearning/gandalf.JPG)

I spent a day just defining terms for myself, which I’ve posted here. This was helpful because I had an idea of what I needed to use to achieve my goals. Next, I did a quick mockup of what the website would look like and described the functionality I want.

![]({{ site.baseurl }}/images/websiteultralearning/mockup.jpg)

The first thing I wanted to learn was Bootstrap. It covered up my Achilles heel - making things look beautiful. After trawling through documentation and other websites I finally came up with a website looking like this.

![]({{ site.baseurl }}/images/websiteultralearning/website1.JPG)

After this, I built a backend. I chose Node.JS because it seemed popular. I set up the server to receive a POST request, search a JSON file, and return the JSON object. This would allow me to search for movies that are stored in the JSON. I avoided learning about databases since this would be a little too much to handle at the moment.

After that, I had a crash course introduction to Javascript and JQuery when I tried to handle the JSON object on the frontend. I would display some info about the movie and then give the option to add it to localStorage. This allowed me to find which streaming service is most popular among the movies stored on the list, which is displayed above the list.

I have a screenshot of the final result below. Unfortunately, while I could find a free API for movie data, I couldn’t find one that would give me what movies are on which streaming service. To show functionality, I made it so that streaming service is randomly generated. Also, one very big issue for me is making good looking websites. I faced this problem when creating my personal website and it came back to bite me here too. I experimented with a few layouts but settled on this simple look instead.
![]({{ site.baseurl }}/images/websiteultralearning/website2.JPG)

At some point, I’ll continue and create a CRUD app. Web development was interesting and the progress being easy to see was a welcome change from working on computer vision. I felt like the iteration speed was much faster.

With respect to ultralearning, I think I much prefer this method to trying to learn web dev by going through “prerequisites”,  or learning JavaScript, then Bootstrap, then Node JS. This was far more satisfying and much easier to stay motivated throughout.
