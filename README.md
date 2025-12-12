# [Thesis Title] Digital Human System based on Qwen LLM and Gaussian Splatting

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Paper](https://img.shields.io/badge/Paper-Master's_Thesis-blue)](link-to-your-pdf-if-available)

## 📖 Abstract
This repository contains the implementation and demo materials for the Master's dissertation: **"Digital human system based on Qwen large language model and Gaussian Splatting"**. 

We propose an end-to-end pipeline bridging the "Mind-Body Gap" in embodied AI. The system integrates **Qwen2.5-Omni** (Speech-to-Speech LLM) with **GaussianTalker** (3DGS Renderer) to achieve high-fidelity, low-latency conversational avatars.

## 🎥 Demo Results

### 1. End-to-End Conversation (RGB vs. Geometry)
We visualize the rendered RGB video alongside the grayscale geometry to demonstrate the structural stability of the 3D Gaussians.

![Comparison Demo](assets/comparison_demo.gif)
*(Left: Final Render, Right: 3D Gaussian Geometry)*

### 2. Fine-grained Dynamics (Eye Blinking)
The model successfully captures high-frequency motions such as eye blinking and subtle lip movements.
![Blinking Demo](assets/blinking_demo.gif)

## 🚀 System Architecture
![Architecture](assets/system_architecture.jpg)
* **Cognitive Core**: Qwen2.5-Omni (Thinker-Talker Architecture)
* **Visual Generator**: GaussianTalker (3D Gaussian Splatting)
* **Interface**: Gradio

## 🛠️ Installation & Usage
("Code coming soon")
