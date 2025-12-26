# Yanix-Launcher by NextFerret
<img width="1000" height="1000" alt="Yanix Logo" src="https://github.com/user-attachments/assets/c1da0b2c-6719-4934-a6b1-e92697f08917" />


**Yanix-Launcher** is an independent, open‑source launcher for **Yandere Simulator**, built for **Linux**. This project is **not** affiliated with or endorsed by **YandereDev**.

Yanix runs the game through **WINE** (we recommend **WINE 8.0+**). Depending on your setup you might see a few graphical quirks, but most major issues were resolved in the Unity 6 build. If some characters look broken or don’t render, that’s a **game-side** problem for YandereDev to fix — not the launcher.

* **Primary platform:** Linux
* **macOS:** Not Supported.
* **Windows:** 50% - Pad mode don't runs natively.

System Requirements
-------------------

Linux:
- Intel i5 8th Gen / Ryzen 4000 Series (except 5 and 3)
- 12 GB RAM
- 3 GB Free Disk Space
- 4 GB VRAM/GTT

Windows:
Same as Linux.

Installation
------------

Ubuntu / Debian:
Install the Native Packages.

Arch Linux:
```
sudo pacman -S python-pyqt6 python-pyqt6-webengine python-requests wine winetricks
```
Fedora:
Install the Native Packages.

Optional Dependencies
---------------------

These are optional but recommended for enhanced functionality:
```
pip install pygame pypresence
```
- pygame — for "Pad Mode"
- pypresence — for Discord Rich Presence integration


## Notes

* WINE **8.0 or newer** is recommended.
* Graphics/text glitches are generally **game** issues, not Yanix-Launcher bugs.

---

## License & Credits

* Yanix-Launcher is open source and independent.
* Yandere Simulator © YandereDev. All trademarks belong to their respective owners.
