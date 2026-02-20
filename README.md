# 3D Scanning & Digital Character Animation

[![View on GitHub Pages](https://img.shields.io/badge/View_on-GitHub_Pages-blue?style=for-the-badge&logo=github)](https://liamyehudai.github.io/dance/)

## Project Overview
This project explores the intersection of 3D scanning technology and digital character animation. By scanning a real-world subject and converting them into a rigged, animated digital avatar, we are investigating the workflows required to bridge the gap between physical reality and virtual environments.

---

## The Process

1. **3D Scanning (Capture):**
   We used **Luma 3D** to perform a high-fidelity 3D scan of the student, Abisheka Pitumpe. This stage captures the geometry and textures of the subject to create a digital double.

2. **Initial Export:**
   The scan was exported from Luma 3D as a `.glb` file (GL Transmission Format), which is a standard format for efficient transmission and loading of 3D scenes and models.

3. **Format Conversion (Blender):**
   The `.glb` file was imported into **Blender** and converted to `.fbx` (Filmbox). This conversion is necessary for compatibility with various rigging and animation pipelines.

4. **Auto-Rigging and Animation (Mixamo):**
   The `.fbx` model was uploaded to **Mixamo**. We used Mixamo’s auto-rigging algorithms to generate a skeletal structure (rig) for the model and applied pre-built animations to bring the avatar to life.

5. **Final Rendering (Blender):**
   The animated `.fbx` file was imported back into **Blender**. In this final stage, we refined the materials, lighting, and camera settings to render out the completed animation.

---

## Why We Are Doing This

* **Workflow Exploration:** To understand the technical hurdles and best practices for converting raw 3D scans into functional digital assets.
* **Avatar Creation:** To develop a repeatable pipeline for creating realistic digital avatars for use in games, VR/AR, or digital art.
* **Educational Research:** Exploring how accessible tools like Luma 3D and Mixamo can be combined with professional software like Blender to democratize high-end digital character creation.