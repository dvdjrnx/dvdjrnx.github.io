<a id="top"></a>

<img src="/public/dvdjrnx.jpg" alt="Headshot of front-end developer and growing UX/UI designer, David Journeaux" width="240" height="240" style="border-radius: 100%;">

# dvdjrnx.github.io

<br>

Hi, I'm David Journeaux, a **front-end developer** and growing **UX/UI designer**. I've created this simple GitHub Pages site to hold a collection of minor projects I've worked on over the years.

To be frank, my most recent professional development and growth has occurred within two private endeavours:

- Building features for **Shopify** as one of their software engineers
- Creating prototypes for my own passion project, **The Altered**.

In light of this, I've not done much that reflects my current skillset within the public sphere. It's my hope this site will help to change that, presenting new, public projects that accurately demonstrate my expertise and learnings in development and user experience with time.

I hope you’ll appreciate and enjoy the journey as much as I intend to myself.

<br>

## Table of Contents

<details>

<summary>Three.js learnings</summary>

<ul>
  <li>
    <a href="#marble-race">Marble Race</a>
  </li>
  <li>
    <a href="#animated-galaxy">Animated Galaxy</a>
  </li>
  <li>
    <a href="#scroll-based-animation">Scroll-based Animation</a>
  </li>
</ul>

</details>

<details>

<summary>Small prototypes</summary>

<ul>
  <li>
    <a href="#model-dimension-extraction-test">Model Dimension Extraction Test</a>
  </li>
</ul>

</details>

<br>

## Three.js learnings

<br>

### [Marble Race](https://dvdjrnx.github.io/marble-race)

**[View GitHub repo](https://github.com/dvdjrnx/marble-race)** • **[View live prototype](https://dvdjrnx.github.io/marble-race)** • <span style="color: #7d8590">Requires keyboard to play</span>

<br>

<img src="/public/marble-race-banner.jpg" alt="Banner showing the Marble Race starting line.">

<br>

#### Project description

> **TLDR**: A 3D marble race game made with Three.js and React Three Fiber.<br>**Tech used**: React, Three.js, React Three Fiber, Drei, JavaScript, HTML, CSS

This project brings together many concepts of working with Three.js and React Three Fiber to create an in-browser game controlled by a keyboard.

It features a marble that can be directed via arrow and WASD keys. It can also jump with the space bar. The goal is to move as quickly as possible down a track with multiple, randomized obstacles.

When you first move, a timer begins. Upon reaching the end of the track, the timer stops and shows you your time. You can then restart to beat your previous record.

The work was undertaken as one of many steps in acquiring [my Three.js certification](https://threejs-journey.com/certificate/view/24741) through [Three.js Journey](https://threejs-journey.com/).

<details>

<summary>Project image</summary>

<br>

<img src="/public/marble-race.jpg" alt="A purple marble sits at the beginning of a race track filled with moving red obstacles. The words Marble Race appear beside the marble. There's an unstarted timer that appears above the marble and a simplistic display of arrow or WASD keys and a space bar below.">

</details>

<br>

[Back to Table of Contents](#table-of-contents) • [Back to top](#top)

<hr>

<br>

### [Animated Galaxy](https://dvdjrnx.github.io/animated-galaxy)

**[View GitHub repo](https://github.com/dvdjrnx/animated-galaxy)** • **[View live prototype](https://dvdjrnx.github.io/animated-galaxy)**

<br>

<img src="/public/animated-galaxy-banner.jpg" alt="Banner showing an orange and red spiral galaxy.">

<br>

#### Project description

> **TLDR**: A controllable, animated galaxy presented in 3D with hundreds of thousands of particles. Created with Three.js.<br>**Tech used**: Three.js, lil-gui, JavaScript, HTML, CSS

This project explores particle systems and animation in 3D and handling hundreds of thousands of particle instances in the browser. It was created with Three.js and React Three Fiber.

It features a whirling galaxy with distinct branches. The branches become more homogenous as the animation plays out. In the upper-right corner is a GUI that allows users to dynamically adjust multiple parameters for the scene, including colors, size, branches, and particle count.

The work was undertaken as one of many steps in acquiring [my Three.js certification](https://threejs-journey.com/certificate/view/24741) through [Three.js Journey](https://threejs-journey.com/).

<details>

<summary>Project image</summary>

<br>

<img src="/public/animated-galaxy.jpg" alt="A whirling orange and yellow galaxy appears against the black backdrop of space.">

</details>

<br>

[Back to Table of Contents](#table-of-contents) • [Back to top](#top)

<hr>

<br>

### [Scroll-based animation](https://dvdjrnx.github.io/scroll-based-animation)

**[View GitHub repo](https://github.com/dvdjrnx/scroll-based-animation)** • **[View live prototype](https://dvdjrnx.github.io/scroll-based-animation)** • <span style="color: #7d8590">Best viewed in landscape orientation</span>

<br>

<img src="/public/scroll-based-animation-banner.jpg" alt="Banner showing a torus floating beside the words Contact Me.">

<br>

#### Project description

> **TLDR**: A simple mock-portfolio front page with 3D animation triggered by scrolling. Made with Three.js.<br>**Tech used**: Three.js, lil-gui, JavaScript, HTML, CSS

This project explores scroll-based animation with 3D elements. It was created with Three.js.

It features a mock portfolio front page with floating 3D elements. The 3D elements will spin quickly in response to entering the viewport, and their position will adjust based on your mouse movement. In the upper-right corner is a GUI that allows users to dynamically adjust the color of the 3D elements.

The work was undertaken as one of many steps in acquiring [my Three.js certification](https://threejs-journey.com/certificate/view/24741) through [Three.js Journey](https://threejs-journey.com/).

<details>

<summary>Project image</summary>

<br>

<img src="/public/scroll-based-animation.jpg" alt="The words My Portfolio sit against a starscape with a green donut shape floating off to the side.">

</details>

<br>

[Back to Table of Contents](#table-of-contents) • [Back to top](#top)

<hr>

<br>

<br>

## Small prototypes

<br>

### [Model Dimension Extraction Test](https://dvdjrnx.github.io/model-viewer-dimensions)

**[View GitHub repo](https://github.com/dvdjrnx/model-viewer-dimensions)** • **[View live prototype](https://dvdjrnx.github.io/model-viewer-dimensions)** • <span style="color: #7d8590">Best viewed on desktop</span>

<br>

<img src="/public/model-viewer-dimensions-banner.jpg" alt="Banner showing the model dimension extraction test UI.">

<br>

#### Project description

> **TLDR**: A quick and dirty prototype of a Google Model Viewer-based 3D model dimension extractor.<br>**Tech used**: Google Model Viewer, React, JavaScript, HTML, CSS

This project was a prototyping test explored as part of my 3D and AR/VR work with Shopify. It tested `<model-viewer>`'s `getDimensions()` method for performance viability in a project that required quickly assessing a model's dimensions to facilitate further business logic down the line.

The prototype mounts a `<model-viewer>` instance when a file is dropped on the UI's drop zone, and the `<model-viewer>`'s `src` attribute is set to an object URL of the model. The moment the model loads, `getDimensions()` is called and x, y, and z dimensions are displayed.

Included in the code is a call to `console.time('getDimensions')` that runs on file drop, and a `console.endTime('getDimensions')` call that runs once dimensions are set in state. The results can be viewed in the console tab of Dev Tools and used to help gauge the performance viability of using `<model-viewer>` to get dimensions from models of various file sizes.

UI was not a focus for this test.

<details>

<summary>Project image</summary>

<br>

<img src="/public/model-viewer-dimensions.jpg" alt="Screenshot of prototype showing a Marshall amp model loaded in the UI with dimensions displayed and the timing results shown in Dev Tools.">

</details>

<br>

[Download a .glb file for testing](https://github.com/dvdjrnx/model-viewer-dimensions/blob/master/public/hamburger-draco.glb)

<details>

<summary>How to download</summary>

<br>

The link above will take you to a GitHub repository page where you can download a .glb file if you don't have your own for testing. The image below shows where you can find the download button on the linked repository page.

<img src="/public/download-glb.png" alt="Image showing where to download the mentioned .glb file in the linked GitHub repository page.">

</details>

<br>

[Back to Table of Contents](#table-of-contents) • [Back to top](#top)

<hr>
