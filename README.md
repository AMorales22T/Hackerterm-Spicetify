<div align="center">
  <h1>HackerTerm for Spicetify</h1>
  <p><i>A sleek, cyberpunk-inspired terminal aesthetic for your Spotify experience.</i></p>
  
  <img src="./assets/preview.png" alt="HackerTerm Preview" width="800"/>
</div>

---

## ⚡ Features

- **Cyberpunk Terminal Aesthetic:** Deep blacks and vivid neon accents (classic terminal green).
- **Immersive Visuals:** Subtle CRT flicker animations and retro monitor effects.
- **Dynamic Interactions:** Glitch hover states and typing animations for UI elements.
- **Command-Line Feel:** Reimagined UI components to look like a hacker's workspace.
- **High Performance:** Optimized CSS to keep Spotify running smoothly without freezing your system.

## 🛠️ Installation

### Prerequisites

Ensure you have [Spicetify CLI](https://spicetify.app/) installed and working properly.

### Setup

1. **Copy the Theme folder:**
   Place the `HackerTerm` folder into your Spicetify themes directory:
   - **Windows:** `%appdata%\spicetify\Themes\HackerTerm`
   - **Linux:** `~/.config/spicetify/Themes/HackerTerm`
   - **macOS:** `~/spicetify_data/Themes/HackerTerm`

2. **(Optional) Install the Extension:**
   Copy the `hackerTerminal.js` script to your Spicetify extensions directory:
   - **Windows:** `%appdata%\spicetify\Extensions\hackerTerminal.js`
   
3. **Apply the Theme:**
   Open your terminal and run the following commands:
   ```bash
   spicetify config current_theme HackerTerm
   spicetify config extensions hackerTerminal.js
   spicetify config inject_css 1 replace_colors 1 overwrite_assets 1
   spicetify apply
   ```

## 🎨 Customization

The colors can be easily modified by editing the `color.ini` file located inside the `HackerTerm` theme folder. Feel free to tweak the hex codes to create your own unique cyberpunk vibe!

## ⚠️ Notes

- If you experience system freezes or Spotify unresponsiveness, ensure that hardware acceleration is properly configured in your `config-xpui.ini`.
- This theme is designed for modern versions of the Spotify desktop client.

---
<div align="center">
  <i>Stay connected. Stay hacked.</i>
</div>
