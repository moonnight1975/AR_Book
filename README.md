# 📘 AR Book – Unity AR Foundation Project

![Unity](https://img.shields.io/badge/Unity-2021%2F2022%20LTS-black?style=flat&logo=unity)
![Platform](https://img.shields.io/badge/Platform-Android-green?style=flat&logo=android)
![AR](https://img.shields.io/badge/Tech-AR%20Foundation-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

> **Bring printed pages to life with augmented reality.**

**AR Book** is an interactive Augmented Reality experience built using **Unity**, **AR Foundation**, and **ARCore/Vuforia**. By scanning specific book pages or images, users trigger 3D models and animations that overlay the real world.

---

## 🖼️ Screenshots & Demo

<p align="center">
  <img src="https://github.com/user-attachments/assets/21536006-875c-4b3e-842d-082820c16190" width="45%" alt="AR Demo 1">
  <img src="https://github.com/user-attachments/assets/0d0c4b54-25d2-42af-80fa-ec7a3cd70e82" width="45%" alt="AR Demo 2">
</p>


---

## ✨ Features

* **🖼️ Image Tracking:** High-precision detection of book pages or custom markers.
* **🧱 Instant 3D Spawning:** Automatically instantiates linked 3D objects upon recognition.
* **🎞️ Interactive Animations:** Triggers specific animations (e.g., character movement, page unfurling) when a target is found.
* **🚀 Optimized Performance:** Lightweight assets ensuring smooth 60fps performance on mobile.
* **📱 Cross-Device Support:** Builds directly for Android (ARCore) with scalable architecture.

---

## 🛠️ Technologies Used

| Category | Tech Stack |
| :--- | :--- |
| **Engine** | Unity 2021 / 2022 LTS |
| **AR Framework** | AR Foundation, ARCore XR Plugin |
| **Tracking** | Vuforia Engine (Optional) |
| **Language** | C# |
| **Platform** | Android (ARM64) |

---

## 📂 Project Structure

```text
AR_Book/
│
├── Assets/
│   ├── Scripts/          # Core C# logic (Trackers, Spawners)
│   ├── Models/           # 3D Assets (.fbx, .obj) & Materials
│   ├── Prefabs/          # AR-ready prefabs with colliders
│   ├── Scenes/           # Main AR Scene
│   └── StreamingAssets/  # (If using Vuforia databases)
│
├── Packages/             # Unity manifest & dependencies
└── ProjectSettings/      # Player & Graphics settings
