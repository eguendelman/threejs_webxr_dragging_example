# A basic three.js / WebXR example (for VR)

## Live on GitHub Pages

See it live [here](https://webxr.eg42.net)

## Description

This is an extracted version of the [three.js - VR / Dragging](https://threejs.org/examples/?q=webxr#webxr_vr_dragging) example.

This isn't really minimalist because it hosts a copy of the three.js library and utilities instead of using a CDN.

Basically I downloaded a recent version of three.js, and put the contents of:

- `build` into `./js/three.js-r123/build`
  - specifically only `three.module.js` is needed
- `examples/jsm` -> `./js/three.js-r123/lib/jsm`
  - I copied everything

This is so the relative paths work out (code in `jsm` refers to `../../build/three.module.js`)
