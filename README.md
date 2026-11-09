<div align="center">
  <img src="public/text.png" alt="EasyFrame Logo" height="150" />
  
  <h1>EasyFrame</h1>
  
  <p>
    <strong>Send Figma frames directly to Roblox Studio.</strong><br>
    A free, open-source workflow that converts your Figma designs into native, editable Roblox GUI using a simple 6-character code.
  </p>

  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows" alt="Platform" />
    <img src="https://img.shields.io/badge/License-Open_Source-green?style=for-the-badge" alt="License" />
    <img src="https://img.shields.io/badge/Privacy-100%25_Local-purple?style=for-the-badge" alt="Privacy" />
  </p>

  <!-- Quick Links -->
  <h3>
    <a href="https://www.easyframe.online/">🌐 Website</a> • 
    <a href="https://github.com/agent-nau/EasyFrame-Legal/releases">⬇️ Download</a> • 
    <a href="https://github.com/agent-nau/EasyFrame-Legal/issues">🐛 Report a Bug</a>
  </h3>
</div>

---

## 💡 Why EasyFrame?

Manually rebuilding complex UI in Roblox Studio takes hours. EasyFrame acts as a direct bridge between your design tool and your game engine. 

* ⚡ **Blazing Fast:** Skip the manual rebuilding process. Go from design to Studio in seconds.
* 🛡️ **100% Private:** No servers, no cloud, no tracking. Your designs are processed entirely on your local machine.
* 🧩 **Truly Native:** Generates real `Frames`, `TextLabels`, `UICorner`, and `UIListLayouts`—not just a static image.

---

## ✨ Features

*   **Roblox OAuth Integration:** Securely log in to upload your design images directly to your Roblox account.
*   **Smart Layer Tags:** Name your Figma layers with specific tags to automatically apply Roblox behaviors.
*   **Layout Support:** Automatically detects and applies `UIListLayout` and `UIGridLayout`.
*   **Effect Conversion:** Converts Figma shadows, strokes, and blurs into `UIStroke` and `UIGradient`.

### 🏷️ Supported Layer Tags
Name your Figma layers with these tags to tell EasyFrame exactly what to do:

| Tag | Roblox Conversion | Description |
| :--- | :--- | :--- |
| `_button` | `TextButton` | Turns the frame into a clickable button. |
| `_list` | `UIListLayout` | Stacks children vertically or horizontally. |
| `_grid` | `UIGridLayout` | Arranges children in a grid. |
| `_textbox` | `TextBox` | Allows user text input. |
| `_fit` | `AutomaticSize` | Automatically sizes the frame to fit its contents. |

---

## 🛠️ How It Works

1.  **Design in Figma:** Install the EasyFrame Figma plugin, select a frame, and click **"Generate Code"** (e.g., `3SYFM3`).
2.  **Paste in Studio:** Open the EasyFrame plugin inside Roblox Studio and paste your 6-character code.
3.  **Done:** Your UI spawns instantly in your workspace as fully editable Roblox instances.

---

## 📥 Getting Started

To use EasyFrame, download the latest files from the [**Releases Page**](https://github.com/agent-nau/EasyFrame-Legal/releases):

1. **EasyFrame for Windows (`.exe`)** 
   *   This is the core engine. Run this first and leave it running in the background.
2. **Figma Plugin (`.zip`)**
   *   Import this into your Figma desktop app to generate transfer codes.
3. **Roblox Studio Plugin (`.rbxm`)**
   *   Drop this file into your Roblox Studio plugins folder to receive your designs.

---

## 🤝 Contributing & Support

EasyFrame is a community-driven project. 
*   Found a bug? [Open an issue](https://github.com/agent-nau/EasyFrame-Legal/issues).
*   Want to request a feature? [Start a discussion](https://github.com/agent-nau/EasyFrame-Legal/issues).
*   Want to contribute code? Fork the repo and submit a Pull Request!

---

## ⚖️ License & Disclaimer

*   **License:** EasyFrame is free, open-source software. See the [LICENSE](LICENSE) file for details.
*   **Not Affiliated:** EasyFrame is an independent project. It is not affiliated with, endorsed by, or sponsored by Roblox Corporation or Figma, Inc. Roblox and Figma are trademarks of their respective owners.
