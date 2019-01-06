---
layout: single
title: "Microbes in Unity" 
excerpt: "An Unity conversion of a game that was created at Motek Forcelink"

header:
  teaser: /assets/img/portfolio/microbes/microbes_1-th.png

gallery:
  - url: /assets/img/portfolio/microbes/microbes_2.png
    image_path: /assets/img/portfolio/microbes/microbes_2-th.png
    alt: "Microbes image 2"
  - url: /assets/img/portfolio/microbes/microbes_3.png
    image_path: /assets/img/portfolio/microbes/microbes_3-th.png
    alt: "Microbes image 3"
  - url: /assets/img/portfolio/microbes/microbes_4.png
    image_path: /assets/img/portfolio/microbes/microbes_4-th.png
    alt: "Microbes image 4" 
  - url: /assets/img/portfolio/microbes/microbes_5.png
    image_path: /assets/img/portfolio/microbes/microbes_5-th.png
    alt: "Microbes image 5" 
---

![Microbes header image](/assets/img/portfolio/microbes/microbes_1.png)

For my graduation project at Motekforce Link I had to transfer one of their games to Unity. The original game was created in their own engine named D-Flow. I needed to rebuild the game with the help of the original Lua source code.

The game is played on a treadmill and features various tasks that can help with the walking disorders of patients. The character in the game can be controlled by the players positioning on the treadmill. The positioning of the player can be determined by the force plates in the treadmill or with the help of a Kinect if connected. The borders in the game indicate the dimensions of the treadmill so that the player knows where it is safe to walk.

During the development I was responsible for implementing a communication protocol to another program that would communicate the available controls for the game. This makes it possible to use a seperate interface with more features that therapists can use with their patients. This implementation has also been used for other projects. The communication protocol was also utilized to control the hardware, instead of directly integrating the treadmill controls into Unity.

{% include gallery %}