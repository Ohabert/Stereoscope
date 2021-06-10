# VR Stereoscope
This repository contains a copy of the code on [this](https://vision.seas.harvard.edu/stereoscope/) website. It is a simple smartphone-based stereoscope built with A-Frame, for the purpose of experiencing and interacting with scientific binocular stereo stimuli.

<img src="https://user-images.githubusercontent.com/46768895/121390844-c61cac80-c91b-11eb-8014-7943fe0dff0a.jpg" alt="header" width="600"/>

## Demos

These examples require a pair of VR glasses and a smartphone with a web browser. We suggest the [Homido Mini](https://homido.com/en/mini/) or [Pocket 360](https://www.imcardboard.com/pocket-360.html). For browsers, if on android use Chrome; on IOS use Safari. For more examples and an explantation see [vision.seas.harvard.edu/stereoscope](https://vision.seas.harvard.edu/stereoscope/)

## Static Scenes

Point your phone at one of the QR codes below and then enter VR Mode to view the images stereoscopically.

<img width="100" alt="Julesz" src="https://user-images.githubusercontent.com/46768895/121567290-65a97000-c9ec-11eb-9162-28222345642e.png">


<img width="100" alt="pipes" src="https://user-images.githubusercontent.com/46768895/121568694-f59be980-c9ed-11eb-8837-a7545befb523.png">


## Interactive Scenes

This scene is meant to change interactively as you rotate your head horizontally.

<img width="100" alt="pipes" src="https://user-images.githubusercontent.com/46768895/121568837-1f551080-c9ee-11eb-8e11-b2bbc4ef37d7.png">

## Use Your Own Images

Insert a URL with a query string into your phone's brower's address bar with the following syntax:

`Base URL + ?lImg= + address of left image + &rImg= + address of right image`

Ex. 

[https://vision.seas.harvard.edu/stereoscope/StereoPages/static.html?lImg=/stereoscope/assets/StereoImages/1_11/2048eleven_l.png&rImg=/stereoscope/assets/StereoImages/1_11/2048eleven_r.png](https://vision.seas.harvard.edu/stereoscope/StereoPages/static.html?lImg=/stereoscope/assets/StereoImages/1_11/2048eleven_l.png&rImg=/stereoscope/assets/StereoImages/1_11/2048eleven_r.png)


Troubleshooting:
1. If the stimulus appears blurry or strange in VR mode, make sure your VR glasses are perfectly centered and aligned on your phone. It may take some fiddling
2. If Safari's title bar does not disappear in VR Mode, try this:

      1. Close all browser tabs except for the current page
      2. Rotate your phone to portrait orientation and then back to landscape

## Getting Started

The easiest way to start making your own VR stereoscope is to [remix the VR Stereoscope in glitch](https://glitch.com/edit/#!/remix/view-master). Simply follow that link, edit the HTML that's in index.html and /Stereopages, and see your changes live.
Alternatively, you can [fork this github repo](https://github.com/Ohabert/Stereoscope/fork), clone a copy of your fork locally by following these steps: 
1. 
[see image in next post for relevant information to copy from the a-frame github example]. For other ways to get started see the <a-frame boilerplate on github>.
