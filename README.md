# Portfolio

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

## Description

This project was a challenge of design as well as functionality and coding. I wrote this app to illustrate the importance of flexbox as well as to provide an opportunity to add interesting portfolios in the future. I included screenshots of my design process at the bottom of this README.

I designed the images individually in PowerPoint and eventually built an animation in PowerPoint and made a mockup gif. I then explored ways in which I could code the gif, and realised the limitations of CSS of on-scroll events. I hope that in 3 months time (May 2022) I will be able to use Javascript and DOM Manipulation to make it even more interactive.

### Timeframe

I spent about 80 hours on this project from creating the images to designing the code and testing for compatibility issues with iOS.

## Table of Contents

-  [Usage](#usage)
-  [Screenshots](#screenshots)
-  [Early designs](#designs)
-  [Known bugs](#bugs)
-  [Credits](#credits)
-  [License](#license)

## Usage

To access the app, please open [Portfolio](https://leoelicos.github.io/bcs-02-portfolio/) in Chrome on a PC or Mac.

To move down the page, scroll down with your scroll button, or swipe up on your phone.

## Screenshots

### Deployed

![Animation](./assets/screenshots/screenshot-of-deployed.jpg)

## Designs

Some of my design process in its early stages:

### Initial idea 1

![Initial Idea 1](./assets/mockups/idea1.png)

### Initial idea 2

![Initial Idea 2](./assets/mockups/idea2.png)

### First Mockup

![First Mockup](./assets/mockups/mockup1.gif)

### Initial idea 3

![Initial Idea 3](./assets/mockups/idea3.jpg)

### Second Mockup

![Second Mockup](./assets/mockups/mockup2.gif)

## Bugs

The app currently does not work fully in iOS Safari and iOS Chrome — see [Bugs](#bugs)

Tested this app on iPhone 11 Pro Max in Safari and Chrome and also iPhone 13 in Safari and the text flowed behind the mountains.

### Bug: iOS Safari and Chrome (fixed)

Text was appearing behind the mountains as Safari was not interpreting z-index.

I fixed this by adding `-webkit-transform: translate3d(0, 0, 0);` before `z-index`, triggering hardware acceleration in Safari to read positive z-index values. This allowed the text to properly layer over the background images.

## Credits

-  CSS Normalize https://necolas.github.io/normalize.css/

## License

&copy; Leo Wong <leoelicos@gmail.com>

Licensed under the [MIT License](./LICENSE.txt).

---
