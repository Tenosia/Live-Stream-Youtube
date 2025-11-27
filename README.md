# Live Stream

A collection of GLSL shaders created during live coding streams. This repository contains various shader projects ranging from simple 2D effects to complex 3D terrain rendering with advanced lighting and atmospheric effects.

## Overview

This project includes shader code in multiple formats:
- **Kodelife project files** (`.klproj`) - Located in `/kodelife` directory, for use with the Kodelife IDE
- **ShaderToy GLSL files** (`.glsl`) - Located in `/shadertoy-glsl` directory, ready to use on ShaderToy.com
- **Web examples** - HTML files demonstrating how to embed shaders in web pages
- **Shared library** - Common WebGL driver code in `/lib` directory

## Project Structure

```
shaders/
├── kodelife/              # Kodelife project files (.klproj)
├── shadertoy-glsl/        # ShaderToy GLSL files (.glsl)
├── lib/                   # Shared WebGL driver (webgl-driver.js)
├── shadertoy/             # Web example: Basic shader embedding
├── shadertoy-2/           # Web example: Alternative shader embedding
├── CodebaseLightning/     # Web example: Lightning effect
└── Lightspeed/            # Web example: Volumetric rendering
```

## Getting Started

### Kodelife Projects

The `.klproj` files in the `/kodelife` directory are Kodelife project files. To use them, download the Kodelife IDE from [hexler.net](https://hexler.net). Kodelife is a fantastic IDE for developing and experimenting with shaders in real-time.

### ShaderToy

The `.glsl` files in the `/shadertoy-glsl` directory are ready to use on [ShaderToy.com](https://shadertoy.com). Simply copy the code into a new shader on the ShaderToy website.

### Web Integration

Example HTML files demonstrating how to embed shaders in web pages can be found in:
- `/shadertoy` directory
- `/shadertoy-2` directory
- `/CodebaseLightning` directory
- `/Lightspeed` directory

All web examples use the shared WebGL driver located in `/lib/webgl-driver.js`. This driver handles WebGL initialization, shader compilation, and rendering loop.

## Shader Projects

### 2D Shaders

**Kodelife Projects** (in `/kodelife` directory):
- **codebasealpha1.klproj**: Basic 2D shader demonstrating distance field visualization (Episode 61)
- **codebasealpha2.klproj**: 2D kaleidoscopic shader with hypnotic effects (Episode 61)
- **codebasealpha12.klproj**: Electrifying 2D lightning shader (Episode 80)

**ShaderToy GLSL** (in `/shadertoy-glsl` directory):
- **codebasealpha.glsl**: Kaleidoscopic pattern shader with polar coordinate transformations

### 3D Shaders

**Kodelife Projects** (in `/kodelife` directory):
- **codebasealpha3.klproj**: Soft-colliding spheres - basic 3D shader (Episode 63)
- **codebasealpha4.klproj**: Highly reflective 3D shader (Episode 64)
- **codebasealpha5.klproj**: 3D shader featuring a shiny cube-like object

### Terrain Shaders

**Kodelife Projects** (in `/kodelife` directory):
- **codebasealpha6.klproj**: Mountain terrain shader v1 - features mountains, snow, forests, and fog (Episodes 65 and 67)
- **codebasealpha9.klproj**: Mountain terrain shader v2 - enhanced with lakes and clouds (Episode 69)

**ShaderToy GLSL** (in `/shadertoy-glsl` directory):
- **TerrainShaderToy.glsl**: Terrain shader v1 for ShaderToy.com
- **TerrainCloudsWaterShaderToy.glsl**: Terrain shader v2 for ShaderToy.com with lakes and clouds

### Atmospheric and Effects Shaders

**Kodelife Projects** (in `/kodelife` directory):
- **codebasealpha7.klproj**: Sun, sea, and sky - experimental shader working on waves and clouds
- **codebasealpha8.klproj**: Cloud rendering shader
- **codebasealpha10.klproj**: Rocket-powered animated shader with fire and smoke effects (Episode 73)
- **codebasealpha11.klproj**: Text-based shader project (Episode 75)

## Web Examples

The repository includes several web-based examples:

- **shadertoy/**: Basic shader embedding example
- **shadertoy-2/**: Alternative shader embedding example (3D merging spheres)
- **CodebaseLightning/**: Lightning effect shader demonstration (uses texture from df.png)
- **Lightspeed/**: Volumetric rendering shader with space tunnel effects

All examples use the shared WebGL driver from `/lib/webgl-driver.js` for consistent behavior and easier maintenance.

