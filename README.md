
<p align="center"><a href="https://akhiarya.netlify.app/"><img src="favicon.png" width="150px" height="150px"/></a></p>
<h1 align="center"><a href="https://akhiarya.netlify.app/">Wedding Invitation</a> :ring: <br> <br> SAVE THE DATE: APR 24, 2021 <br> <a href="https://akhiarya.netlify.app/">akhiarya.netlify.app</a></h1>

[![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/arungop/akhiarya?style=plastic)](https://akhi.netlify.app/) [![Netlify Status](https://img.shields.io/netlify/1377b58e-6196-4b6d-9e9b-b7b1e9e0cf57?style=plastic)](https://app.netlify.com/sites/akhiarya/deploys) [![GitHub license](https://img.shields.io/github/license/vinitshahdeo/Wedding-Invitation?logo=github)](https://github.com/vinitshahdeo/Wedding-Invitation)   [![Release date](https://img.shields.io/github/release-date/arungop/akhiarya?style=plastic)](https://github.com/arungop/akhiarya/releases/tag/v0.1)

## Wedding Invitation :ring:

<details>
  <summary><strong>View Invitation</strong></summary>
  <a href="https://github.com/arungop/akhiarya/blob/v0.1/assets/pdf/akhiwedsarya.pdf"> Inivitation letter</a>
</details>

A kerala style wedding inivitaion website designed for my friend's marriage. This invitation website is inspired from clean and amazing work of [Vinitshahdeo](https://github.com/vinitshahdeo/Wedding-Invitation). Take a look and feel free to give him a star. 

## Additional features

- A responsive photo gallery
- Embedded pre wedding video (muted)
	- Because the main attraction of the original content is in the background score. 




## Feel free to use this template to build your wedding website!

To reuse this, follow the steps:

- *Replace the date in [script.js](https://github.com/arungop/akhiarya/blob/main/js/script.js#L15) to have a timer running for your big day!*

```js
// Set the date we're counting down to
var countDownDate = new Date("Nov 29, 2020 00:00:00").getTime();
```

- *If you wish to change the track which plays on click, edit the `src` in [index.html](https://github.com/arungop/akhiarya/blob/main/index.html#L165)*

```html
<div class="music">
   <audio src="./assets/mp3/song.mp3" id="my_audio" loop="loop"></audio> 
</div>
```

> Song: Inkem Inkem by Gopi Sundar. [Cover: flutesiva](https://www.youtube.com/watch?v=x84OUIVai3Y&ab_channel=flutesiva)


- *Responsive image gallery can be modified by adding the images in /assets/img folder . Also change the paths in the html [index.html](https://github.com/arungop/akhiarya/blob/main/index.html#L111). 

```css
body {
  margin: 0;
  padding: 0;
}

.containerw3 {

	display: flex;
	overflow: hidden;
	flex-wrap: wrap;
	margin: -2.5px;
}
.containerw3:after {
	content: '';
	flex-grow: 999999999;
	min-width: 200px;
	height: 0;
}
.containerw3 > * {
	position: relative;
	display: block;
	height: 250px;
	margin: 2.5px;
	flex-grow: 1;
}
.containerw3 > * > img {
	height: 250px;
	object-fit: cover;
	max-width: 100%;
	min-width: 100%;
	vertical-align: bottom;
}
.containerw3.containerw3-margin {
	margin: 2.5px;
}

```
Html part:

```html
<div class="containerw3 containerw3-margin">
            <a href="#">
                <img src="assets/img/d11.webp" />
            </a>
</div>

```
- *Pre-wedding video
	- Save the video in the /assests/video folder and replace the file name [index.html](https://github.com/arungop/akhiarya/blob/main/index.html#L97).

```html
<div>
<video width="100%" height="100%" autoplay loop muted>
  <source src="assets/video/save_s.mp4" type="video/mp4">
  <source src="assets/video/save_s.mp4" type="video/ogg">
Your browser does not support the video tag.
</video>
</div>

```
- *Bonus tip. You can replace the beautiful flowers on the top of the website with Cassia fistula and yellow flower shower. 

### Do not forget to leave a star! :hugs:


<br><sup><i>With warm regards,<br>
**[Arun Gopinath](https:arungopi.gitlab.io)**<i></sup><br>



