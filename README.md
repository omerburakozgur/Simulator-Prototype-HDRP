<div align="center">

<h1>🌅 Simulator Prototype (HDRP)</h1>
<h3>High-Fidelity Environment & Technical Art Showcase</h3>

<p>
  <a href="https://omerburakozgur.itch.io/simhdrp" target="_blank">
    <img src="https://img.shields.io/badge/View_Gallery-Itch.io-FA5C5C?style=for-the-badge&logo=itch.io&logoColor=white" alt="Itch.io" />
  </a>
  <a href="#" target="_blank">
    <img src="https://img.shields.io/badge/Watch-Tech_Showcase-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube" />
  </a>
</p>

| **Render Pipeline** | **Language** | **3D Tool** | **Focus** |
| :---: | :---: | :---: | :---: |
| <img src="https://img.shields.io/badge/Unity_HDRP-000000?style=flat-square&logo=unity&logoColor=white" /> | <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white" /> | <img src="https://img.shields.io/badge/Blender_3D-E87D0D?style=flat-square&logo=blender&logoColor=white" /> | <img src="https://img.shields.io/badge/Tech_Art_%26_Lighting-purple?style=flat-square" /> |

</div>

<div align="center">
 <td colspan="2" align="center">
      <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/90705984/518828062-680936e7-1bbe-429c-b6b1-51ff496eb90f.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20251125%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20251125T193930Z&X-Amz-Expires=300&X-Amz-Signature=5896c842948e1fe7b82ecaa2fd6c36ad9f8abf7aee20f1a849cdbc0fe434937b&X-Amz-SignedHeaders=host" alt="Main Showcase" width="50%" />
    </td> 
    <tr </tr>
   <td align="center">
      <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/90705984/518825856-22c5e705-1492-444d-9878-5d4549a8b1cc.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20251125%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20251125T194014Z&X-Amz-Expires=300&X-Amz-Signature=fdc641c008581d29c3e80130f881bc380c539188a64ee18c421d290d0c48c8fc&X-Amz-SignedHeaders=host" alt="Volumetrics" width="50%" />
    </td>
    <td align="center">
      <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/90705984/518825889-7822900d-6ce9-410c-8d81-901313f690f5.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20251125%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20251125T194020Z&X-Amz-Expires=300&X-Amz-Signature=2cd5f52d3e8db10a18e90d89a43dd20061bb8d258d44c81cc711665b0247fa97&X-Amz-SignedHeaders=host" alt="Volumetrics" width="50%" />
    </td>
    <td align="center">
      <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/90705984/518825906-ed31b62f-214e-4eba-9344-6ef87bcd460a.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20251125%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20251125T194025Z&X-Amz-Expires=300&X-Amz-Signature=d988d64e2d8b1612ac3b80f71b3e7e5ebb4abcb6560c37f7600dce4d69285d37&X-Amz-SignedHeaders=host" alt="Volumetrics" width="50%" />
    </td>
    <td align="center">
      <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/90705984/518825919-0e49f991-021b-401e-b121-54c5af09345f.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20251125%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20251125T194031Z&X-Amz-Expires=300&X-Amz-Signature=a5c7a6a43d5b8c5b27043ad9aea4eb795a32b2f67a0b252522ec77d81c683a58&X-Amz-SignedHeaders=host" alt="Volumetrics" width="50%" />
    </td>
</div>

<br>

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
