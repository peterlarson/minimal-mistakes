---
title: "Recreating an arcade game in Java." 
exerpt: "Recreation of the classic arcade game Burgertime." 
header:
 image: /assets/images/level_1.JPG
 teaser: assets/images/level_1.JPG
gallery: 
 - url: /assets/images/level_1.JPG
   image_path: assets/images/level_1.JPG
   image_alt: burgertime level 1
 - url: /assets/images/level_4.JPG
   image_path: assets/images/level_4.JPG
   image_alt: burgertime level 4
 - url: /assets/images/reward_level.JPG
   image_path: assets/images/reward_level.JPG
   image_alt: burgertime reward_level
 - url: /assets/images/level_editor.JPG
   image_path: assets/images/level_editor.JPG
   image_alt: burgertime level_editor
 - url: /assets/images/hard_mode.JPG
   image_path: assets/images/hard_mode.JPG
   image_alt: burgertime hard mode
 - url: /assets/images/disappointed_message.JPG
   image_path: assets/images/disappointed_message.JPG
   image_alt: burgertime disappointed_message
last_modified_at: 2017-08-01
permalink: /burgertime/
---

During my first year at Rose-Hulman me and some of my friends did a project for our programming class that still give me pride today. Our assignment was to recreate the arcade game <a href="http://en.wikipedia.org/wiki/BurgerTime">burgertime</a>. 

The course was our introduction to Java, and so we completed the project using swing. Our game used minecraft images, dogs, and a cat with a chef's hat as the characters. 
Some features we liked of were a level editor, a hard mode including new music and graphics, and a critical failure scree.  

{% include gallery caption="Screenshots of gameplay" %}

The feature we were most proud of in our implementation was a method of using a grid-based level and collision system, while having fluid motion for the player character and enemies. When our team was discussing how to represent the game we disagreed about weather we should use tiles. I was against it, but later we found that if we animated the character and enemies based on a location within a tile we could have smooth movement and use tiles for representing the level. This satisfied my concerns about the apperance of the game, while making conflicts, enemy routing, and loading/storing the game significantly easier. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/x4M4ogS4xBE?rel=0" frameborder="0" allowfullscreen></iframe>

Gameplay of the first level of the game.

The thing we were the most proud of was the final boss level. We deviated from the classic game and added a cyborg dog that shoots lasers. There was also an animated background and dramatic music

<iframe width="560" height="315" src="https://www.youtube.com/embed/ntinA3krVjQ?rel=0" frameborder="0" allowfullscreen></iframe>

Final boss level.

<br/><br/><br/>