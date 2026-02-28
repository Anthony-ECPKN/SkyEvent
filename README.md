# 🚁 SkyEvents: A Large-Scale Event-enhanced UAV Dataset for Robust 3D Scene Reconstruction

[![ICLR 2026](https://img.shields.io/badge/ICLR-2026-blue.svg)](https://iclr.cc/)
[![Project Page](https://img.shields.io/badge/Project-Page-green.svg)](https://anthony-ecpkn.github.io/nerfies.github.io/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

> **[ICLR 2026 Accepted]** This is the official repository for the paper:  
> **"SkyEvents: A Large-Scale Event-enhanced UAV Dataset for Robust 3D Scene Reconstruction"** 

[🌍 Project Page](https://anthony-ecpkn.github.io/nerfies.github.io/) | [📝 Paper (Coming Soon)]() | [📊 Dataset (Coming Soon)]()

## 📖 Introduction

Recent advances in large-scale 3D scene reconstruction using unmanned aerial vehicles (UAVs) have spurred increasing interest in neural rendering techniques (e.g., 3DGS). However, existing approaches with conventional cameras struggle to capture consistent multi-view images in extremely blurred and low-light environments due to inherent dynamic range limitations.

To bridge this gap, we introduce **SkyEvents**, a pioneering large-scale event-enhanced UAV dataset designed specifically for 3D scene reconstruction. 

### Key Features:
* **Multi-modal Data:** Incorporates synchronized RGB video, Event streams, and LiDAR point clouds.
* **Large Scale & Diversity:** Spans over 8 hours of video (45 sequences) covering 1.41 km², captured across diverse illumination conditions (daytime, dusk), scenarios, and flight altitudes (70-100m).
* **Supporting Modules:** We provide the **GTA** (Geometry-constrained Timestamp Alignment) module for precise RGB-Event synchronization, and the **RER** (Region-wise Event Rendering) loss to guide and enhance 3D Gaussian Splatting rendering optimization.

## 🚀 TODO List / Roadmap

We are actively preparing the codebase and dataset for public release. Please stay tuned!

- [x] Release the Project Page.
- [ ] Release the Camera-ready Paper on arXiv.
- [ ] **Code Release:**
- [ ] **Dataset Release:**
- [ ] **Hardware Open Source:** Provide CAD designs of the sensor bracket and hardware synchronization scripts.


