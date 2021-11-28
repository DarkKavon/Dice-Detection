# Dice-Detection

## Table of content
* [Authors](#aut)
* [General information](#info)
* [Technology](#tech)
* [Idea description](#desc)


<a id='aut'></a>
## Authors
* Kacper Wandel
* Bartosz Pietrowiak

<a id='info'></a>
## General information
Dice detection is image processing project which purpose is to detect dices and theirs dots on image.
Program also prints statistic information about dices and dots. <br>
Example pictures are in 'dices' directory. <br>
Use of artificial intelligence is not allowed.

<a id='tech'></a>
## Technology
* Python: openCV, matplotlib, pylab

<a id='desc'></a>
## Idea description
1. Image is read by openCV in BGR format
2. Image is proccesing in followinf order:
* Contrast and brightness adjustments
* Convert to gray scale
* Thresholding
* Canny edge detection
* Dilation
3. Transformed image is searched for contours
4. Found contours are classified to be a dice or not
5. For every dice program search for contours inside 
6. Found contours are classified to be a dot or not
7. Program prints following statistics: number of dice walls, number of dices and sum of dots
8. Program prints orginal image with dices and dots marked and with labels informing about dots on every dice






