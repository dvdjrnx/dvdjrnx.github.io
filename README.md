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
  <li>
    <a href="#3d-physics">3D Physics</a>
  </li>
  <li>
    <a href="#portal-scene">Portal Scene</a>
  </li>
  <li>
    <a href="#post-processing">Post-processing</a>
  </li>
  <li>
    <a href="#raging-sea">Raging Sea</a>
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

**[View GitHub repo](https://github.com/dvdjrnx/marble-race)** • **[View live demo](https://dvdjrnx.github.io/marble-race)** • <span style="color: #7d8590">Requires keyboard to play</span>

<br>

<img src="/public/marble-race-banner.jpg" alt="Banner showing the Marble Race starting line.">

<br>

#### Project description

> **TLDR**: A 3D marble race game made with Three.js and React Three Fiber.<br>**Tech used**: `React` • `Three.js` • `React Three Fiber` • `React Three Rapier` • `react-postprocessing` • `Drei` • `Zustand` • `R3F-Perf` • `JavaScript` • `HTML` • `CSS`

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

**[View GitHub repo](https://github.com/dvdjrnx/animated-galaxy)** • **[View live demo](https://dvdjrnx.github.io/animated-galaxy)**

<br>

<img src="/public/animated-galaxy-banner.jpg" alt="Banner showing an orange and red spiral galaxy.">

<br>

#### Project description

> **TLDR**: A controllable, animated galaxy presented in 3D with hundreds of thousands of particles. Created with Three.js.<br>**Tech used**: `Three.js` • `lil-gui` • `JavaScript` • `HTML` • `CSS`

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

**[View GitHub repo](https://github.com/dvdjrnx/scroll-based-animation)** • **[View live demo](https://dvdjrnx.github.io/scroll-based-animation)** • <span style="color: #7d8590">Best viewed in landscape orientation</span>

<br>

<img src="/public/scroll-based-animation-banner.jpg" alt="Banner showing a torus floating beside the words Contact Me.">

<br>

#### Project description

> **TLDR**: A simple mock-portfolio front page with 3D animation triggered by scrolling. Made with Three.js.<br>**Tech used**: `Three.js` • `lil-gui` • `JavaScript` • `HTML` • `CSS`

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

### [3D Physics](https://dvdjrnx.github.io/3d-physics)

**[View GitHub repo](https://github.com/dvdjrnx/3d-physics)** • **[View live demo](https://dvdjrnx.github.io/3d-physics)**

<br>

<img src="/public/3d-physics-banner.jpg" alt="Banner showing numerous 3D shapes falling onto a green plane under the effects of gravity.">

<br>

#### Project description

> **TLDR**: A chaotic 3D scene implementing physics using Three.js and React Three Fiber.<br>**Tech used**: `React` • `Three.js` • `React Three Fiber` • `React Three Rapier` • `R3F-Perf` • `Drei` • `JavaScript` • `HTML` • `CSS`

This project explores applying physics to a 3D scene created with Three.js and React Three Fiber. At its core, it features a spinning, rectangular block. Numerous models fall into the scene under the effects of gravity and are bounced around by the block, reacting as would be reasonably expected in the real world for their individual shapes.

The project also displays a performance monitor for profiling different performance indicators, such as FPS, memory usage, and GPU load.

The work was undertaken as one of many steps in acquiring [my Three.js certification](https://threejs-journey.com/certificate/view/24741) through [Three.js Journey](https://threejs-journey.com/).

<details>

<summary>Project image</summary>

<br>

<img src="/public/3d-physics.jpg" alt="Multiple peach cubes, a hamburger, and a yellow ball fall to a green floor with a spinning red rectangular block.">

</details>

<br>

[Back to Table of Contents](#table-of-contents) • [Back to top](#top)

<hr>

<br>

### [Portal Scene](https://dvdjrnx.github.io/portal-scene)

**[View GitHub repo](https://github.com/dvdjrnx/portal-scene)** • **[View live demo](https://dvdjrnx.github.io/portal-scene)**

<br>

<img src="/public/portal-scene-banner.jpg" alt="A wide digital banner depicting a stylized portal with swirling black and white patterns in the center, flanked by wooden structures with lanterns, against a starry night sky backdrop, suggesting a mystical or fantasy setting.">

<br>

#### Project description

> **TLDR**: A low-poly 3D portal scene featuring custom animated shaders. Modeled in Blender, shaded and coded in Three.js and React Three Fiber.<br>**Tech used**: `React` • `Three.js` • `React Three Fiber` • `WebGL` • `WebGL Shaders` • `Drei` • `JavaScript` • `HTML` • `CSS`

This project explores writing custom animated shaders, building a scene in blender, baking lighting, and loading the scene in Three.js. The project also makes use of React Three Fiber.

The shader work is highlighted in the glowing and shifting patterns within the portal's stone circle. The scene features a low-poly 3D scene of a lantern-lit, fenced pathway leading through rocks and tree stumps to a mysterious stone portal. An axe rests in one of the stumps, and fireflies float against a black sky.

The work was undertaken as one of many steps in acquiring [my Three.js certification](https://threejs-journey.com/certificate/view/24741) through [Three.js Journey](https://threejs-journey.com/).

<details>

<summary>Project image</summary>

<br>

<img src="/public/portal-scene.jpg" alt="A 3D image depicting a stylized portal with swirling black and white patterns in the center, flanked by wooden structures with lanterns, against a starry night sky backdrop, suggesting a mystical or fantasy setting.">

</details>

<br>

[Back to Table of Contents](#table-of-contents) • [Back to top](#top)

<hr>

<br>

### [Post-processing](https://dvdjrnx.github.io/post-processing)

**[View GitHub repo](https://github.com/dvdjrnx/post-processing)** • **[View live demo](https://dvdjrnx.github.io/post-processing)** • <span style="color: #7d8590">Best viewed in landscape orientation</span>

<br>

<img src="/public/post-processing-banner.jpg" alt="A digital banner showcasing post-processing effects with a spherical ball and a cube distorted and set against a two-tone green backdrop that creates a surreal, abstract landscape.">

<br>

#### Project description

> **TLDR**: A simple 3D scene with a user-adjustable post-processing "drunk" effect. Created with Three.js and React Three Fiber.<br>**Tech used**: `React` • `Three.js` • `React Three Fiber` • `react-postprocessing` • `Drei` • `Leva` • `R3F-Perf` • `JavaScript` • `HTML` • `CSS`

This project explores post-processing in a 3D scene, allowing users to dynamically adjust the intensity of an animated, drunken wave effect applied over top of a simple scene. It was created with Three.js and React Three Fiber.

It features a ball and cube on a green plane. In the upper-right corner is a GUI that allows users to adjust two parameters that affect the "drunk" view distortion: frequency and amplitude.

The project also displays a performance monitor for profiling different performance indicators, such as FPS, memory usage, and GPU load.

The work was undertaken as one of many steps in acquiring [my Three.js certification](https://threejs-journey.com/certificate/view/24741) through [Three.js Journey](https://threejs-journey.com/).

<details>

<summary>Project image</summary>

<br>

<img src="/public/post-processing.jpg" alt="A 3D rendering of a ball and a cube under the influence of a 'Drunk Effect' post-processing filter, evidenced by on-screen sliders for frequency and amplitude adjustments. The ball and cube are resting on a flat surface with a light green background. The ball appears distorted into an egg shape, and the cube has a slightly skewed form, demonstrating the effects of the filter on simple geometric shapes.">

</details>

<br>

[Back to Table of Contents](#table-of-contents) • [Back to top](#top)

<hr>

<br>

### [Raging Sea](https://dvdjrnx.github.io/raging-sea)

**[View GitHub repo](https://github.com/dvdjrnx/raging-sea)** • **[View live demo](https://dvdjrnx.github.io/raging-sea)**

<br>

<img src="/public/raging-sea-banner.jpg" alt="A wide banner image depicting an abstract representation of a tumultuous sea with dynamic shades of blue, creating the illusion of waves in motion under a stormy sky.">

<br>

#### Project description

> **TLDR**: A low poly sea with rolling waves and dynamic user controls. Made with Three.js.<br>**Tech used**: `Three.js` • `WebGL` • `WebGL Shaders` • `lil-gui` • `JavaScript` • `HTML` • `CSS`

This project explores animating WebGL shaders and patterns. It was created with Three.js.

It features a features a low-poly sea with rolling waves. In the upper-right corner is a GUI that allows users to dynamically adjust multiple parameters for the scene, including wave elevation, frequency, and speed, small wave iterations, and sea colors.

The work was undertaken as one of many steps in acquiring [my Three.js certification](https://threejs-journey.com/certificate/view/24741) through [Three.js Journey](https://threejs-journey.com/).

<details>

<summary>Project image</summary>

<br>

<img src="/public/raging-sea.jpg" alt="A 3D image that simulates a raging sea at night with varying shades of blue, alongside a control panel with sliders for 'bigWavesElevation', 'bigWavesFrequency', and other parameters, indicating this is a computer-generated visualization with adjustable settings for wave dynamics.">

</details>

<br>

[Back to Table of Contents](#table-of-contents) • [Back to top](#top)

<hr>

<br>

<br>

## Small prototypes

<br>

### [Model Dimension Extraction Test](https://dvdjrnx.github.io/model-viewer-dimensions)

**[View GitHub repo](https://github.com/dvdjrnx/model-viewer-dimensions)** • **[View live demo](https://dvdjrnx.github.io/model-viewer-dimensions)** • <span style="color: #7d8590">Best viewed on desktop</span>

<br>

<img src="/public/model-viewer-dimensions-banner.jpg" alt="Banner showing the model dimension extraction test UI.">

<br>

#### Project description

> **TLDR**: A quick and dirty prototype of a Google Model Viewer-based 3D model dimension extractor.<br>**Tech used**: `Google Model Viewer` • `React` • `JavaScript` • `HTML` • `CSS`

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
