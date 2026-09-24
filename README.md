# PS4 GoldHEN Host [7.00 - 13.52] by OGH

A custom, high-performance, and **100% offline-ready** GoldHEN exploit host for PlayStation 4 consoles running firmwares from **7.00 to 13.52**. This host features a premium Retro-Gaming Pixel Art design with animated orange neon glows, a custom full-screen background, and automated success/failure visual screens.

---

## 🌟 Features

* **Firmware Support:** Multi-firmware targeting (7.00 up to 13.52) with automatic firmware detection and redirection.
* **100% Offline Cache:** Fully autonomous application cache manifests allowing you to run the exploit anytime without an internet connection.
* **Retro-Gaming Aesthetics:** Integrated local arcade-style pixel font (`Press Start 2P`) requiring zero internet access to load.
* **Dynamic Neon Visuals:** CSS-animated pulsing headers, custom glow separation lines, and blinking text elements.
* **Live Progress Bar:** High-visibility neon orange progress bar showcasing the real-time installation percentage of your offline cache.
* **Smart Event Screens:** Automated system using a JavaScript observer to display full-screen `success.jpg` or `failed.jpg` graphics depending on the jailbreak outcome.

---

## 📁 Project Structure

Ensure your root directory matches the layout below:

```text
├── index.html                   # Main entry landing page
├── style.css                    # Centralized styling, animations, and local font config
├── background.jpg               # Your custom menu background graphic
├── success.jpg                  # Full-screen graphic displayed on exploit success
├── failed.jpg                   # Full-screen graphic displayed on exploit failure
├── PressStart2P-Regular.ttf     # Local arcade font file (required for offline styling)
├── goldhen_2.4b18.12.bin        # GoldHEN payload binary
├── 505.manifest                 # AppCache manifest files per firmware range
├── 700.manifest
├── 900.manifest
├── css.manifest
├── slopkit.manifest
├── cache505.html                # Firmware specific cache installer pages
├── cache700.html
├── cache900.html
├── cachecss.html
└── cacheslopkit.html            # Main installer page for newer firmwares
```

---

## 🎨 Theme Description

This host layout is built on a high-fidelity **Retro-Gaming & Synthwave** aesthetic crafted specifically for TV displays:

* **Typography:** Powered by the pixelated `Press Start 2P` font, scaled globally at a strict `22px` height to align perfectly with vintage arcade standards and television safe-zones.
* **Color Palette:** Dominated by a deep electric orange (`#ff7700`) paired with an immersive dark backdrop (`background.jpg`) depicting futuristic neon geometric contours.
* **Animated Glow Effects:** Integrated CSS keyframe animations provide a slow, rhythmic pulsation (`neonPulse`) on texts and horizontal bars, mimicking authentic glowing gas-discharge neon tubes.
* **Interactive Elements:** Features structured, translucent navigation buttons utilizing high-intensity neon borders that brightly invert into full solid block color styles upon joystick selection.

---

## 🚀 Installation & Deployment

### 1. PS4 Browser Setup
1. Turn on your PS4 and connect to your network.
2. Open the **Internet Browser**, press **Options**, go to **Settings**.
3. Select **Delete Cookies** and **Clear Website Data**.
4. Type your host URL into the address bar and press **Go**.
5. The host will automatically identify your firmware and start installing the offline cache with the custom progress bar.
6. Once the message says `CACHE INSTALLED SUCCESSFULLY ✔`, close the browser, disconnect your PS4 from the internet, and re-open the browser to trigger the exploit completely offline.

---

## 🛠️ Manifest Updates
If you add or alter any file name, make sure to document it at the bottom of your corresponding `.manifest` files so the PS4 system stores the updated assets inside its local partition.
```text
background.jpg
style.css
success.jpg
failed.jpg
```

---

## 🤝 Special Thanks
* **SiSTRo** (For the incredible GoldHEN payload)
