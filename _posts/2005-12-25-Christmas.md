---
layout: default # Uses the structure from _layouts/default.html
title: "Christmas 2001" # This is the editable title above the video
author: "The Family"
date: 2001-12-25 10:00:00 -0500 # This date is used for sorting!
---

<div class="video-post">
    <h2 class="video-title">{{ page.title }}</h2>
    <span class="post-meta">Posted on: {{ page.date | date: "%B %-d, %Y" }}</span>
    
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/xoUCYCTkWU4?si=nkjbKjkpWw6mfnqN" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    
    <p></p>
</div>
