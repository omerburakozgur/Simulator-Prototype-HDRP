<div align="center">

<h1>🌅 Simulator Prototype (HDRP)</h1>
<h3>High-Fidelity Environment & Technical Art Showcase</h3>

<p>
  <a href="https://omerburakozgur.itch.io/simhdrp" target="_blank">
    <img src="https://img.shields.io/badge/View_Gallery-Itch.io-FA5C5C?style=for-the-badge&logo=itch.io&logoColor=white" alt="Itch.io" />
  </a>
  <a href="https://www.youtube.com/watch?v=XMrsSZeXPhw" target="_blank">
    <img src="https://img.shields.io/badge/Watch-Tech_Showcase-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube" />
  </a>
</p>
</div>

<p align="center">
  <a href="https://www.youtube.com/watch?v=XMrsSZeXPhw" target="_blank">
  <img src="https://github.com/user-attachments/assets/9780a2e0-f58d-4e54-9dc3-fab31e86f132" alt="Main Showcase" width="60%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f0f74917-ef86-4e2b-a732-c76629568a3a" alt="Detail 1" width="49%" />
  <img src="https://github.com/user-attachments/assets/05b3e2d3-734e-4d0c-b782-3a8d7c36d53e" alt="Detail 2" width="49%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/91b85438-0925-4cfb-ab5e-582cee7de084" alt="Detail 3" width="49%" />
  <img src="https://github.com/user-attachments/assets/e1cd3e3e-0ab2-429e-b6ef-3af3b1f4a7ae" alt="Detail 4" width="49%" />
</p>

<br>
<div align="center">

| **Render Pipeline** | **Language** | **3D Tool** | **Focus** |
| :---: | :---: | :---: | :---: |
| <img src="https://img.shields.io/badge/Unity_HDRP-000000?style=flat-square&logo=unity&logoColor=white" /> | <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white" /> | <img src="https://img.shields.io/badge/Blender_3D-E87D0D?style=flat-square&logo=blender&logoColor=white" /> | <img src="https://img.shields.io/badge/Tech_Art_%26_Lighting-purple?style=flat-square" /> |
</div>

## 📖 Project Overview

**Simulator Prototype (HDRP)** is a non-playable technical exploration project focused on achieving **photo-realism** and **high-fidelity simulation** using Unity's High Definition Render Pipeline (HDRP).

Unlike my gameplay-focused projects, this prototype serves as a showcase of my skills in **Technical Art**, **Level Design**, and **Environmental Storytelling**. It demonstrates the ability to build immersive worlds using advanced lighting, procedural generation, and C# scripting for environmental dynamics.

---

## ⚙️ Technical Deep Dive (Technical Art)

This project pushed the boundaries of Unity's graphical capabilities, requiring a deep understanding of the rendering pipeline and optimization techniques.

### 🌤️ Global Illumination & Lighting
Instead of standard baked lighting, I configured a hybrid approach suitable for dynamic times of day.
* **Physical Sky System:** Implemented a procedurally generated sky that reacts to the sun's position (controlled by C# scripts), creating realistic atmospheric scattering.
* **Volume Framework:** Architected a hierarchy of **Global and Local Volumes** to control Exposure, White Balance, and Tonemapping dynamically as the camera moves through different biomes.

### 🏔️ Terrain & Procedural Generation
* **Terrain Architecture:** Sculpted the landscape using a combination of manual brushes and **Terrain Stamps** to create realistic geological formations.
* **Procedural Texturing:** Utilized layer-based procedural texturing tools to blend grass, rock, and sand textures naturally based on slope and height maps.
* **Foliage System:** Managed density and placement of 3D trees and 2D grass billboards, utilizing **Billboarding** techniques to maintain performance.

### 🌊 Visual Effects & Volumetrics
* **Interactive Water:** Configured realistic water shaders with refraction, reflection, and wave simulation dependent on wind variables.
* **Volumetric Fog:** Designed local fog volumes to create depth and mood in valley areas, optimizing the **Volumetric Quality** settings to balance visual fidelity with GPU cost.

---

## 🎨 Asset Pipeline & Optimization

The visual fidelity was achieved through a mix of custom modeling and efficient asset integration.

* **Blender Workflow:** Modeled specific hard-surface props and architectural elements in Blender, handling UV mapping and texture baking before importing to Unity.
* **LOD (Level of Detail):** Configured aggressive LOD transitions for foliage and complex props to keep the vertex count manageable.
* **Occlusion Culling:** Set up static occlusion areas to prevent rendering objects blocked by large terrain features.

---

<div align="center">
  <a href="mailto:omerburakozgur1@gmail.com">
    <img src="https://img.shields.io/badge/Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://www.linkedin.com/in/omerburakozgur/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
</div>
