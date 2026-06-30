<div align="center">
  <img src="https://raw.githubusercontent.com/raysan5/raylib/master/logo/raylib_logo_animation.gif" alt="Raylib Logo" width="150"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="terrablocklogo.png" alt="TerraBlock Logo" width="150"/>

  <br><br>

  <a href="https://github.com/vitobatbino/terrablock/releases">
    <img src="https://img.shields.io/github/downloads/vitobatbino/terrablock/total?style=flat&color=brightgreen" alt="Downloads">
  </a>
  <a href="https://github.com/vitobatbino/terrablock/stargazers">
    <img src="https://img.shields.io/github/stars/vitobatbino/terrablock?style=flat&color=007ec6" alt="Stars">
  </a>
  <a href="https://github.com/vitobatbino/terrablock/releases">
    <img src="https://img.shields.io/github/v/release/vitobatbino/terrablock?include_prereleases&label=Latest%20Release&style=flat&color=brightgreen" alt="Latest Release">
  </a>
  <a href="https://github.com/vitobatbino/terrablock/tags">
    <img src="https://img.shields.io/github/v/tag/vitobatbino/terrablock?label=Latest%20Tag&style=flat&color=007ec6" alt="Latest Tag">
  </a>

  <h1>TerraBlock</h1>
  <p><b>A lightweight, high-performance, cross-platform voxel engine written in C++.</b></p>
</div>

---

## 📖 About The Project

**TerraBlock** is a custom-built voxel game engine heavily inspired by the early prototypes of Minecraft. 

The goal of this project is to build a hyper-optimized, standalone engine from scratch without relying on massive frameworks like Unity or Unreal. By writing memory-efficient C++ and leveraging multithreading, TerraBlock is designed to run incredibly fast on modern machines while maintaining strict compatibility with retro hardware.

### 🚀 Engine Capabilities

The TerraBlock engine is built on a highly modular and optimized architecture:
*   **Voxel Interaction:** Fast 3D raycasting allowing for real-time block breaking, placing, and targeting highlights.
*   **Infinite-Style Meshing:** Asynchronous, double-buffered chunk generation running on background threads ensures zero flickering and no main-thread lag spikes.
*   **Engine Persistence:** Native C++ binary level saving and loading utilizing DEFLATE compression for minimal file footprints on disk.
*   **Voxel Physics:** Custom AABB grid collision allowing for smooth wall-sliding and snappy, frictionless classic movement.
*   **Pure Retro Graphics:** Powered by legacy OpenGL 1.1 with Flat-Shaded lighting, cross-chunk face culling, and dynamic 1D texture atlases.

---

## 🛠️ Built With

This engine was built from the ground up utilizing the following technologies:
*   **[C++11/17]** - Core engine logic, memory management, file systems, and multithreading.
*   **[CMake]** - Cross-platform build system for Linux and Windows.
*   **[Raylib]** - Window management, inputs, and hardware abstraction.
*   **[FastNoiseLite]** - Lightweight 2D/3D fractal noise generation.

---

## 🎮 How to Play

Head over to the [Releases](../../releases) tab and download the version for your operating system:
1.  **Extract the ZIP/TAR file** to a folder on your computer. *(Do not run the game directly from inside the archive!)*
2.  Ensure the `assets/` folder is located right next to the executable.
3.  Run `TerraBlock` (Linux) or `TerraBlock.exe` (Windows). 

**Controls:**
*   `W A S D` or `Left Stick` - Move
*   `Mouse` or `Right Stick` - Look
*   `Spacebar` or `A Button` - Jump (Hold to bunny-hop)
*   `Left Click` or `Right Trigger` - Break Block
*   `Right Click` or `Left Trigger` - Place Block
*   `ENTER` - Save World
*   `BACKSPACE` - Load World
*   `R` - Hold to respawn dynamically
*   `ESC` - Quit Game

---

## 🗺️ Roadmap

- [x] TerraBlock Prototype v0.0.0.1 (Cave game tech test)
- [x] TerraBlock Prototype v0.0.0.2 (rd-132211)
- [ ] **Next Up:** TerraBlock Prototype v0.0.0.3 (rd-132328)
- [ ] TerraBlock Prototype v0.0.0.4 (rd-20090515)
- [ ] TerraBlock Prototype v0.0.0.5 (rd-160052)
- [ ] TerraBlock Prototype v0.0.0.6 (rd-161348)
- [ ] TerraBlock v0.0.1 (Minecraft Classic [mc-161607])

---

## 🙏 Special Thanks

A massive thank you to **[Ray](https://github.com/raysan5)** and all the contributors behind **[Raylib](https://github.com/raysan5/raylib)**. 

Raylib's philosophy of providing a clean, C-based hardware abstraction layer without forcing a bloated IDE on the developer is what made this project possible. It is truly the ultimate library for learning how game engines actually work under the hood. 

*Also thanks to the `rres` packing system for keeping the assets clean and secure!*
