---
title: "Computing Spatial Image Convolutions for Event Cameras"
collection: publications
permalink: /2018_event_convolutions
excerpt: 
date: 2018-12-02
venue: 
paperurl: 
citation: 
youtubeId: 
header:
   teaser: gradient_corners_thumbnail.png
---

<a href="https://cedric-scheerlinck.github.io/files/2018_event_convolutions.pdf" target="_blank"><b>PDF</b></a>&emsp;
<a href="https://drive.google.com/drive/folders/1Jv73p1-Hi56HXyal4SHQbzs2zywISOvc?usp=sharing" target="_blank"><b>Datasets</b></a>&emsp;
<a href="https://cedric-scheerlinck.github.io/files/2018_arxiv_convolutions.txt" target="_blank"><b>BibTex</b></a>

<b>Abstract.</b> Spatial convolution is arguably the most fundamental of 2D image processing operations.
Conventional spatial image convolution can only be applied to a conventional image, that is, an array of pixel values (or similar image representation) that are associated with a single instant in time.
Event cameras have serial, asynchronous output with no natural notion of an image frame, and each event arrives with a different timestamp.
In this paper, we propose a method to compute the convolution of a linear spatial kernel with the output of an event camera.
The approach operates on the event stream output of the camera directly without synthesising pseudo-image frames as is common in the literature.
The key idea is the introduction of an internal state that directly encodes the convolved image information, which is updated asynchronously as each event arrives from the camera.
The state can be read-off as-often-as and whenever required for use in higher level vision algorithms for real-time robotic systems.
We demonstrate the application of our method to corner detection, providing an implementation of a Harris corner-response `state' that can be used in real-time for feature detection and tracking on robotic systems.

<br />
<b>Reference:</b>
* Cedric Scheerlinck, Nick Barnes, Robert Mahony, "Computing Spatial Image Convolutions for Event Cameras", arXiv e-prints, 2018.