# 🎮 Block Shooter - AR Object Placement & Interaction Tool

An immersive **Unity AR (Augmented Reality)** application that enables users to detect planes, place various assets dynamically, manipulate them in real-time with custom 3D transform gizmos, and interact with the environment by shooting magic spells or projectiles.

Built using **Unity 2022.3.49f1 LTS** and **Unity XR / AR Foundation**, this tool offers a robust framework for spawning, selecting, and transforming objects in a physical space.

---

## 🌟 Key Features

*   **🔍 AR Plane Detection & Placement**: Scan real-world surfaces and place virtual objects dynamically using a paginated, scriptable-object-based placement bar.
*   **📐 3D Interactive Transform Gizmos**: 
    *   **Translation (Move)**: Position objects precisely along custom or global axes.
    *   **Rotation**: Rotate objects around axes using interactive handles.
    *   **Scale**: Resize placed objects dynamically.
*   **✨ Object Selection & Highlighting**: Tap to select placed objects, activating visual selection cues and manipulation UI controls.
*   **💥 Projectile & Magic Spell Mechanics**: Shoot magic spells or projectiles at placed blocks/objects to interact with them in the AR scene.
*   **📦 Modular Scriptable Object Database**: Easily add new placement prefabs, icons, and settings via Unity Scriptable Objects (`PlacementObjectSO`).

---

## 🛠️ Tech Stack & Dependencies

*   **Game Engine**: Unity `2022.3.49f1`
*   **XR Framework**: Unity XR Plugin Management & AR Foundation (ARCore/ARKit)
*   **UI Tooling**: Unity UI & TextMesh Pro (TMP)
*   **Level Design**: Unity ProBuilder (for meshes and prototyping objects)
*   **Input**: Unity Input System

---

## 📁 Project Structure

*   📂 **`Assets/`**:
    *   📂 **`XR/`**: XR configuration assets, simulation environments, and preference profiles.
    *   📂 **`other/`**: Assets, 3D meshes (ProBuilder), materials, shaders, and scenes.
        *   📂 **`Scripts/`**: Core C# logic for placement, gizmo transforms, UI interactions, and spelling/shooting mechanics.
*   📂 **`Packages/`**: Manifest and lock files managing package dependencies.
*   📂 **`ProjectSettings/`**: Unity project settings (Player settings, input axes, graphics configurations, etc.).

---

## 🚀 Getting Started

### Prerequisites
*   **Unity Editor**: Version **`2022.3.49f1`** or later.
*   **Mobile Device**: An AR-compatible iOS device (ARKit support) or Android device (ARCore support).

### Installation & Run Steps
1.  **Clone the Repository**:
    ```bash
    git clone https://github.com/Arohi-Shah/Block-Shooter.git
    cd Block-Shooter
    ```
2.  **Open in Unity**:
    *   Open **Unity Hub**.
    *   Click **Add** -> **Add project from disk**.
    *   Select the `Block-Shooter` root directory.
    *   Ensure the Editor version is set to `2022.3.49f1`.
3.  **Build and Deploy**:
    *   Go to **File** -> **Build Settings**.
    *   Switch platform to **Android** or **iOS**.
    *   Ensure the main AR scene is added to the "Scenes In Build".
    *   Click **Build And Run** with your mobile device connected via USB.
