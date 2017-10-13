---
layout: post
title: BlocJams
thumbnail-path: "img/blocjams.png"
short-description: Bloc Jams is a digital music player like Spotify.

---

{:.center}
![]({{ site.baseurl }}/img/blocjams.png)

## Explanation

I built the Bloc Jams digital music player as the foundation project while taking the Bloc Frontend Fundamentals Bootcamp. 

I started off using HTML to build the backbone of the application layout. Then I added styling and responsiveness with CSS. I used JavaScript to implement the interactivity in the application.


## Problem
1.Learn **HTML** and use it to create the backbone of the application. 

2.Learn **CSS** to add color, placement, icons, and other visual modifications
   to give the application a modern appearance. 

3.Learn **JavaScript** and **JQuery** to make Bloc Jams interactive. 



## Solution
1. With HTML <div> sections I created the backbone for the main areas of the landing page and I gave these elements class names to be used in the css and javascript content:
  * navigation bar - `<class = "navbar"></class>`
  * hero content - `<class = "hero-content" ></class>`
  * selling points - `<class = "selling-points"></class>`
    
2.Using the class names and CSS, I was able to easily add styling to the elements. I kept the to give the application a modern appearance. CSS styling separate from the HTML content. This *encapsulates* the  content and makes it easier to understand and build upon.
    
3.I added some cool animation to the selling points section using JavaScript. I *modularized* the animation of the selling points by putting it in a JavaScript function called animatePoints() in a JavaScript file called landing.js. This keeps everything organized and easy to enhance and debug.


## Results
##### Landing Page with Navigation Bar,  Hero Content,  and Animated Selling Points
   
<script src="https://fast.wistia.com/embed/medias/tneqeq1j63.jsonp" async></script><script src="https://fast.wistia.com/assets/external/E-v1.js" async></script><span class="wistia_embed wistia_async_tneqeq1j63 popover=true popoverAnimateThumbnail=true" style="display:inline-block;height:98px;width:150px">&nbsp;</span>

## Conclusion
It is always best to keep organization and structure of your project in mind from the beginning. Things can get large and unwieldy very quickly by having one file contain everything! Break things up in to manageable pieces. Baby steps...

