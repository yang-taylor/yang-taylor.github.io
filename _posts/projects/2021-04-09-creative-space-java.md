---
layout: post
title:  "CreativeSpace: A Drawing Program Made With JavaFX"
author: "Taylor Yang, Zoya Bawangaonwala"
date:   2021-04-09
tags:  	ctis210 guilford-college team-project java
category: coding-project
---

CreativeSpace was a collaboration between me and classmate Zoya Bawangaonwala.
(See her write-up [here](https://zoyab522.github.io/Personal-Website-Portfolio/CodingProjects.html#JavaAnchor)).
We spent about a month working on this project.
Since we worked as a team, we had to find a way to share our code, even when we aren’t working at the same time, from the same computer.
Our work flow involved a mix of using GitHub and emailing archives.

[View Code on GitHub](https://github.com/yang-taylor/Creative-Space)

## How to Use the Program
To start, the program does nothing by default.
Instead, the user should first select one of the options on the side panel of the screen.
Here, there are some shapes options, a brush option, options to change the color, and an eraser to selectively remove sections of work.
There are also buttons that allow the user to add a layer, remove the top layer, undo an action, and redo an action.
Currently, the program is a bit on the primitive side.
However, the code also allows a lot of flexibility for extending it– such as rearranging layers, adding different shapes, etc.

## Demo Images
![CreativeSpace Demo Image 1, Leaf Line Art](/assets/img/2021-04-09/Creative-Space-Demo-1.png)
![CreativeSpace Demo Image 2, Adding Shapes](/assets/img/2021-04-09/Creative-Space-Demo-2.png)
![CreativeSpace Demo Image 3, File Selector](/assets/img/2021-04-09/Creative-Space-Demo-3.png)

## Process
We wanted to create a drawing and digital art project, which would mimic some basic capabilities of Microsoft Paint or Procreate.
We planned on including features such as layers, using color pickers, and transforming images and shapes.
In the first iteration of our project, we created a drawing using Pane, for absolute positioning of shapes.
However, a bug we encountered was how the paint functionality looked sporadic and wasn’t as smooth as we liked.
Also, there were a lot of moving parts and global variables in this version, so we decided to scrap it.
In this current iteration of the project, we used Canvas and the GraphicsContext instead of Pane.
The good thing about recreating a project is that we could carry over some logic (such as for layering, undos/redos, changing colors), while improving by correcting some messes from before.