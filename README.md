# 🍎 Death Note Network Judgment (KIRA GUI)

> *"The human whose name is written in this note shall be scanned..."*

**KIRA Nmap GUI** is a stylized, anime-inspired graphical wrapper for the Nmap network scanner. Built with Python and Tkinter, it allows you to perform network reconnaissance using an interface modeled after the "Death Note" aesthetic.

<img width="879" height="858" alt="Screenshot 2025-12-14 at 2 16 03 PM" src="https://github.com/user-attachments/assets/2586a6ee-bab2-44a4-8630-65f87f074c18" />

![Status](https://img.shields.io/badge/Status-Active-red?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge)
![Nmap](https://img.shields.io/badge/Dependency-Nmap-green?style=for-the-badge)

## 💀 Features

* **Immersive UI:** Custom "Gothic/Death Note" color palette (Black, Bone White, Blood Red, Misa Lavender).
* **Shinigami Eyes:** Quick toggle checkboxes for common Nmap flags:
    * Version Detection (`-sV`)
    * Default Scripts (`-sC`)
    * OS Detection (`-O`)
* **The Notebook:** A scrollable judgment log that displays scan results in real-time.
* **Interactive Judgment:**
    * **Clickable Ports:** Click on open ports (e.g., `80/tcp`) to attempt to open them in your browser.
    * **Clickable URLs:** Automatically detects and links HTTP addresses.
* **Threaded Execution:** The UI remains responsive while the "writing" (scanning) occurs.
* **Custom Background:** Supports loading external textures (`deathnote_bg.jpg`) for maximum immersion.

## 📋 Prerequisites

Before running the script, you must have the following installed on your system:

1.  **Python 3.x**
2.  **Nmap:** The script relies on the Nmap binary.
    * **Windows:** [Download Nmap](https://nmap.org/download.html) and **ensure it is added to your system PATH**.
    * **Linux:** `sudo apt install nmap`
    * **macOS:** `brew install nmap`
3.  **Fonts (Optional but Recommended):**
    * For the best visual experience, install the **"Old English Text MT"** font. The script will fallback to Times New Roman if not found.

## 🛠️ Installation

1.  **Clone the Repository** (or download the script):
    ```bash
    git clone https://github.com/king-gh1dra/Death-Map
    ```

2.  **Install Python Dependencies:**
    This project requires `Pillow` for image handling.
    ```bash
    pip install pillow
    ```
    *(Note: Tkinter is usually included with Python, but on Linux, you may need `sudo apt install python3-tk`)*

3.  **Add a Background (Optional):**
    Place an image named `deathnote_bg.jpg`, `paper.jpg`, or `texture.png` in the same directory to enable the background texture.

## 📓 Usage

1.  Run the script:
    ```bash
    python deathmap.py
    ```
2.  **Victim Identifier:** Enter the Target IP address (e.g., `192.168.1.1`).
3.  **Shinigami Eyes:** Select the checkboxes for the type of scan info you want.
4.  **Execute:** Click the **DELETE** button.
5.  **Judgment:** Watch the "Judgment Log" for results. Click on highlighted links to investigate.

> **Note on Permissions:** Some Nmap features (like OS detection `-O`) require root/administrator privileges. You may need to run your terminal as Administrator (Windows) or use `sudo python deathnote_scanner.py` (Linux/Mac).

## 📸 Screenshots

*(Add a screenshot of your running application here so users can see the UI)*

## ⚠️ Disclaimer

**This tool is for educational and authorized testing purposes only.**

Scanning networks you do not own or do not have explicit permission to audit is illegal in many jurisdictions. The creator of this tool is not responsible for any misuse or damage caused by this program. Use your "Death Note" responsibly.

## ⚖️ License

This project is open-source. Feel free to modify it... *if you dare.*
