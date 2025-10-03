<img alt="WebGPU logo" src="https://raw.githubusercontent.com/gpuweb/gpuweb/cd07d570226c8e4c82a1b616f967fe76f98920a3/logo/webgpu-responsive.svg" width="400">

<!-- TODO: add a live webgpu test like on https://get.webgl.org -->

`webgpu.org` is a work in progress. Please visit one of the links below.

- [WebGPU Implementation Status](https://github.com/gpuweb/gpuweb/wiki/Implementation-Status)
- [WebGPU Report](https://webgpureport.org/)

# Community

- The `public-gpu@w3.org` [mailing list](https://lists.w3.org/Archives/Public/public-gpu/) is a good place to ask questions or provide feedback on the API.
- You can also join the chat on Matrix in the "Web Graphics" Matrix Community: [#webgraphics:matrix.org](https://matrix.to/#/#webgraphics:matrix.org).
    - The general WebGPU channel is [#WebGPU:matrix.org](https://matrix.to/#/#WebGPU:matrix.org).

# Samples &amp; Demos

- [WebGPU Samples](https://webgpu.github.io/webgpu-samples/)

# Learning Resources

- [WebGPU Fundamentals](https://webgpufundamentals.org/)
- [WebGPU on MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API)
- [Tour of WGSL](https://google.github.io/tour-of-wgsl/)

# Specifications &amp; Documents

- [WebGPU API Specification Draft](https://gpuweb.github.io/gpuweb/)
- [WGSL Specification Draft](https://gpuweb.github.io/gpuweb/wgsl/)
- [WebGPU Correspondence Reference](https://gpuweb.github.io/gpuweb/correspondence/) - contributions wanted

# Libraries implementing WebGPU

- [wgpu](https://github.com/gfx-rs/wgpu) - Rust, used in Firefox, Servo, and Deno
  - Available for: Rust, C ([wgpu-native](https://github.com/gfx-rs/wgpu-native) - contributions wanted)
  - Native + WebAssembly
- [Dawn](https://github.com/google/dawn) - C++, used in Chrome, Edge, and other Chromium browsers
  - Available for: C, C++, [Node](https://github.com/google/dawn/tree/main/src/dawn/node)
  - Native only
- [Emdawnwebgpu](https://github.com/google/dawn/blob/main/src/emdawnwebgpu/pkg/README.md) - bindings for Emscripten
  - WebAssembly only, via Emscripten
