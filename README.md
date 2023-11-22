# dvdjrnx.github.io

Hi, I'm David Journeaux, a frontend developer and growing UX/UI designer. I've created this simple GitHub Pages site to hold a collection of minor projects I've worked on.

To be frank, the past few years of my professional development have been focused on building features for Shopify as one of their software engineers. In light of that, I've not done much that reflects my current skill set within the public sphere. It's my hope this site will help to change that, presenting new projects that demonstrate my expertise in development and user experience over time.

I hope you’ll appreciate and enjoy the journey as much as I intend to myself.

## Small prototypes

### Assessing performance of Google Model Viewer for extracting 3D model dimension data

[View prototype](https://dvdjrnx.github.io/model-viewer-dimensions)
[Download a .glb file for testing](https://github.com/dvdjrnx/model-viewer-dimensions/blob/master/public/hamburger-draco.glb)

<img src="./public/download-glb.png" alt="Image showing where to download the mentioned .glb file in the linked GitHub repository page" />

This project was a prototyping test explored as part of my 3D and AR/VR work with Shopify. It tested `<model-viewer>`'s `getDimensions()` method for performance viability in a project that required quickly assessing a model's dimensions to facilitate further business logic down the line.

The prototype mounts a `<model-viewer>` instance when a file is dropped on the UI's drop zone, and the `<model-viewer>`'s `src` attribute is set to an object URL of the model. The moment the model loads, `getDimensions()` is called and x, y, and z dimensions are displayed.

Included in the code is a call to `console.time('getDimensions')` that runs on file drop, and a `console.endTime('getDimensions')` call that runs once dimensions are set in state. The results can be viewed in the console tab of Dev Tools and used to help guage the performance viability of using `<model-viewer>` to get dimensions from models of various file sizes.

UI was not a focus for this test.
