---
title: Goblin Mode workshop - OpenCV
---

![Joecasso image - portrait of Joe with face overlaid by Picasso-style face](joecasso.webp)

## Introduction to Computer Vision

Today's workshop covers an introduction to working with computer vision, using the OpenCV library through a web browser. 

> The scientific discipline of computer vision is concerned with the theory behind artificial systems that extract information from images. Image data can take many forms, such as video sequences, views from multiple cameras, multi-dimensional data from a 3D scanner, 3D point clouds from LiDaR sensors, or medical scanning devices. The technological discipline of computer vision seeks to apply its theories and models to the construction of computer vision systems.

OpenCV is a computer vision library that handles facial recognition, gesture recognition, human-computer interaction, object detection, motion, tracking, emotion tracking, and additonal functionality. 

It is the underlying technology of everything from 'face filters' on social media apps to surveillance technology. This is a workshop for us to get a handle on the basics of OpenCV, to understand its capabilities, how we can use it, and where it is limited or fails.

This is a purposely exploratory, experimental workshop, with some starter code that can be tested, modified and even embedded in a website.

## Basic OpenCV test with p5.js

Tested and verified working on Chrome-based browsers. Does not work within Firefox.

[Link to starter code](https://editor.p5js.org/kylemcdonald/sketches/F8rmuVkgP)

This intoduction to working with OpenCV with p5.js shows facial detection and recognition. Can you get an intuitive understanding of how it works? Test out the variables. What results can you get?

**Activity: look at the example variables that are given to you. Using these variables, what overlays can you make? Add your knowledge of JavaScript and/or p5.js to add new items that modify the image output.**

## Facial recognition with overlay example: Picasso filter

[Link to Picasso face replacement](https://editor.p5js.org/Joemckay/sketches/CKHLreMYU)

Joe's code sketch builds on the basic OpenCV example test, adding custom shapes with vectors. It is an example of a more complex facial filter one can build with face detection. 

## Embedding on a web page

A p5.js code sketch can be saved (must log in with a free account.) You can then select File > Share and select 'embed'. This will give you custom HTML with an `<iframe>` tag that can be integrated into your site with custom CSS. Resize, make it transparent (check out the opacity CSS attribute), or integrate the frame with other elements on your webpage.
