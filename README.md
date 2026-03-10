<img alt="WebGPU logo" src="https://raw.githubusercontent.com/gpuweb/gpuweb/cd07d570226c8e4c82a1b616f967fe76f98920a3/logo/webgpu-responsive.svg" width="400">

<!-- TODO: add a live webgpu test like on https://get.webgl.org -->

WebGPU and WGSL (WebGPU Shading Language) are W3C standards for GPU acceleration on the Web.
There are also implementations of WebGPU in other languages, for both WebAssembly and native applications.

`webgpu.org` is a work in progress - contribute [here](https://github.com/webgpu/webgpu.org)!

# Implementation Status

- [WebGPU Implementation Status](https://github.com/gpuweb/gpuweb/wiki/Implementation-Status) - status of different browsers/OSes, and how to report bugs
  - For status of individual features, check on your device using [WebGPU Report](https://webgpureport.org/)

# Community Spaces

- Chat - "Web Graphics" Matrix Community: [#webgraphics:matrix.org](https://matrix.to/#/#webgraphics:matrix.org)
    - The general WebGPU channel is [#WebGPU:matrix.org](https://matrix.to/#/#WebGPU:matrix.org)
- Q&A and feature proposals - [GitHub Discussions](https://github.com/gpuweb/gpuweb/discussions)
- Mailing list - `public-gpu@w3.org` [at the W3C](https://lists.w3.org/Archives/Public/public-gpu/)

# Samples &amp; Demos

- [WebGPU Samples](https://webgpu.github.io/webgpu-samples/) - sample code and demos of various features and graphics/compute techniques
- [compute.toys](https://compute.toys/)
- [wgpu Examples](https://wgpu.rs/examples/) (Rust on Wasm)
- ... and many more [here](https://github.com/mikbry/awesome-webgpu?tab=readme-ov-file#demos)

# Learning Resources

- [WebGPU Fundamentals](https://webgpufundamentals.org/) - tutorials and articles on many WebGPU and graphics topics
- [WebGPU on MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API) - API documentation
- [Tour of WGSL](https://google.github.io/tour-of-wgsl/) - tutorials on WGSL (WebGPU Shading Language)
- [Get started with GPU Compute on the Web](https://developer.chrome.com/docs/capabilities/web-apis/gpu-compute)
- [WebGPU Best Practices](https://toji.dev/webgpu-best-practices/)

# Developer Tools

- [WebGPU Report](https://webgpureport.org/) - status on your device
- From the community:
  - [WGSL Inspector](https://github.com/brendan-duncan/webgpu_inspector)
  - [WebGPU-Dev-Extension](https://github.com/greggman/webgpu-dev-extension)
  - [WebGPUReconstruct](https://github.com/Chainsawkitten/WebGPUReconstruct)

# Specifications &amp; References

- [WebGPU API Specification](https://gpuweb.github.io/gpuweb/)
- [WGSL Specification](https://gpuweb.github.io/gpuweb/wgsl/)
- [WebGPU Correspondence Reference](https://gpuweb.github.io/gpuweb/correspondence/) - contributions wanted
- [WebGPU on MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API)
- From the community:
  - [webgpu.rocks WebGPU/WGSL Reference](https://webgpu.rocks/)

# Browser News &amp; Articles

- [WebGPU on *Chrome for Developers*](https://developer.chrome.com/docs/web-platform/webgpu)

# Videos &amp; Presentations

- Meetups - click through for lists of presentations
  - [2026-03 GDC](https://www.khronos.org/events/3d-on-the-web-2026)
  - 2025-07 SIGGRAPH ([video](https://www.youtube.com/watch?v=gdMtgJTe1qY), [slides](https://www.khronos.org/assets/uploads/developers/presentations/WebGL%2BWebGPU_SIGGRAPH_2025.pdf)
  - [2025-03 GDC](https://www.khronos.org/events/3d-on-the-web-2025)
  - 2024-07 SIGGRAPH ([video](https://www.youtube.com/watch?v=mTYmr1b0ZnQ), [slides](https://www.khronos.org/assets/uploads/developers/presentations/WebGL__WebGPU_BOF_2024-07-31.pdf)
  - [2024-03 GDC](https://www.khronos.org/events/webgl-webgpu-meetup-GDC-2024)
  - (just search online if you're looking for a specific past meetup)

# Community libraries for use with WebGPU

- Shaders
  - [WESL](https://github.com/wgsl-tooling-wg/wesl-spec/blob/main/README.md) - extensions for WGSL
  - [Slang](https://github.com/shader-slang/slang) (experimental)
  - [wgsl_reflect](https://github.com/brendan-duncan/wgsl_reflect)
- Engines
  - [Three.js](https://threejs.org/docs/#WebGPU)
  - [Babylon.js](https://doc.babylonjs.com/setup/support/webGPU)
  - [Unity](https://docs.unity3d.com/6000.3/Documentation/Manual/WebGPU.html)
  - [PlayCanvas](https://blog.playcanvas.com/build-webgpu-apps-today-with-playcanvas/)
  - [Toucan](https://github.com/google/toucan)
  - [React Native WebGPU](https://github.com/wcandillon/react-native-webgpu)
- Machine Learning
  - [TensorFlow.js](https://github.com/tensorflow/tfjs)
  - [ONNX Runtime](https://onnxruntime.ai/docs/tutorials/web/ep-webgpu.html)
  - [Apache TVM](https://github.com/apache/tvm)
- ... and many more [here](https://github.com/mikbry/awesome-webgpu?tab=readme-ov-file#libraries)

# Libraries implementing WebGPU

- [wgpu](https://github.com/gfx-rs/wgpu) - Rust, used in Firefox, Servo, and Deno
  - Available for: Rust, C ([wgpu-native](https://github.com/gfx-rs/wgpu-native) - contributions wanted)
  - Native + WebAssembly
- [Dawn](https://github.com/google/dawn) - C++, used in Chrome, Edge, and other Chromium browsers
  - Available for: C, C++, [Node](https://github.com/google/dawn/tree/main/src/dawn/node)
  - Native only
- [Emdawnwebgpu](https://github.com/google/dawn/blob/main/src/emdawnwebgpu/pkg/README.md) - bindings for Emscripten
  - WebAssembly only, via Emscripten

# More resources from the community

- [Awesome WebGPU](https://github.com/mikbry/awesome-webgpu)
