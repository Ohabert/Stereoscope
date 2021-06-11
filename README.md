# VR Stereoscope
This is HTML for a simple smartphone-based stereoscope built with [A-Frame](https://aframe.io/). It allows anyone with a smartphone and a cheap set of VR glasses to experience and interact with stereo images, in particular those created by vision scientists to understand how binocular stereo vision works. Any pair of left/right images can be viewed stereoscopically on a smartphone, just by passing the image URLs in a query string. 

Details about this project and a collection of popular stereo images are at [vision.seas.harvard.edu/stereoscope](https://vision.seas.harvard.edu/stereoscope/).

<img src="https://user-images.githubusercontent.com/46768895/121390844-c61cac80-c91b-11eb-8014-7943fe0dff0a.jpg" alt="header" width="600"/>

## Demos

The following examples require a pair of VR glasses and a smartphone. For glasses, we suggest something cheap and foldable that does not obstruct the phone's touchscreen, like the [Homido Mini](https://homido.com/en/mini/) or [Pocket 360](https://www.imcardboard.com/pocket-360.html). For the smartphone web browser, we recommend using Chrome in Android and Safari in iOS. 

#### Static scenes

Point your phone at one of the QR codes below (or click on the stereo image thumbnail if you are already viewing this page on your phone). Then, click the phone's VR button, rotate to landscape orientation, and attach some VR glasses. 

Troubleshooting:
* If the stimulus appears blurry or strange in VR mode, make sure your VR glasses are perfectly centered and aligned on your phone. It may take some fiddling.
* If Safari's title bar does not disappear in VR Mode, try this:
  * Close all browser tabs except for the current page
  * Rotate your phone to portrait orientation and then back to landscape
  * If all else fails, you can at least reduce its size by clicking `aA` -> `Hide Toolbar` in the address bar


<img width="100" alt="Julesz" src="https://user-images.githubusercontent.com/46768895/121567290-65a97000-c9ec-11eb-9162-28222345642e.png">

<img width="100" alt="pipes" src="https://user-images.githubusercontent.com/46768895/121568694-f59be980-c9ed-11eb-8837-a7545befb523.png">


#### Interactive scene
This scene is meant to change interactively as you rotate your head horizontally.

<img width="100" alt="pipes" src="https://user-images.githubusercontent.com/46768895/121568837-1f551080-c9ee-11eb-8e11-b2bbc4ef37d7.png">

#### Query string
To view any left/right images stereoscopically, use this query string syntax in your phone browser's address bar:
`<base URL> + ?lImg= + <left image URL> + &rImg= + <right image URL>`

Example:

[https://vision.seas.harvard.edu/stereoscope/StereoPages/static.html?lImg=/stereoscope/assets/StereoImages/1_11/2048eleven_l.png&rImg=/stereoscope/assets/StereoImages/1_11/2048eleven_r.png](https://vision.seas.harvard.edu/stereoscope/StereoPages/static.html?lImg=/stereoscope/assets/StereoImages/1_11/2048eleven_l.png&rImg=/stereoscope/assets/StereoImages/1_11/2048eleven_r.png)

## Getting Started

The easiest way to start making your own VR stereoscope is to [remix VR Stereoscope in glitch](https://glitch.com/edit/#!/remix/view-master). Simply follow that link, edit the HTML that's in `index.html` and `Stereopages/`, and see your changes live.

Alternatively, you can develop locally:
```
git clone https://github.com/Ohabert/Stereoscope.git  # Clone the repository
cd stereoscope && npm install  # Install dependencies
npm start  # Start the local development server
```
and point your browser to http://localhost:3000. The URL will be logged to the console when the development server starts. To see in VR Mode, load the logged URL in a browser on a smartphone that's on the same LAN. 

For A-Frame syntax check out the [A-Frame documentation](https://aframe.io/docs/1.2.0/introduction/).
