# LooM OS

**LooM OS** is a custom, blazingly fast, and ultra-lightweight Linux distribution built on a stable Debian 12 core. It is engineered from the ground up specifically for **DevOps Engineers, System Administrators, and Cloud Professionals** who demand performance over visual bloat.

By stripping away heavy Desktop Environments and replacing them with a pure, keyboard-centric Tiling Window Manager, LooM OS leaves maximum RAM and CPU resources available for your containers, compilations, and infrastructure deployments.

---

## 🔥 Enterprise Features

* **📦 DevOps-Ready Stack out of the box:** Skip the tedious initial environment setup. LooM OS comes pre-installed and pre-configured with industry-standard tools including **Docker Engine, Docker Compose, Terraform, and Ansible**.
* **⚡ Pure i3wm Experience:** Uses **i3wm** as the default window manager. No desktop icons, no heavy start menus—just pure efficiency through keyboard shortcuts.
* **💻 Developer-First Terminal:** Pre-configured with **Alacritty** (a GPU-accelerated terminal emulator) and **Zsh** paired with Oh-My-Zsh (syntax highlighting and autosuggestions enabled by default).
* **📊 Built-in Monitoring:** Ships with **Netdata** for real-time, high-resolution system and container performance monitoring.
* **🛡️ The LinUtil Toolkit:** Features our exclusive `linutil` CLI toolkit—an enterprise-grade utility for system maintenance and diagnostics.

---

## 🧰 The `linutil` Toolkit

LooM OS includes a proprietary, interactive command-line utility built to automate tedious SysAdmin tasks. Simply type `sudo linutil` in your terminal to access:

1. **System Deep Clean:** Safely purges apt cache, orphaned packages, and old logs to instantly free up disk space.
2. **Docker Janitor:** Safely removes dangling images, stopped containers, and unused volumes without breaking active deployments.
3. **Active Port Sniper:** Instantly identifies which services are listening on which ports, and allows you to kill rogue processes.
4. **SELinux Policy Doctor:** Diagnoses SELinux denials and provides actionable solutions (or audit logs) for troubleshooting.
5. **System Resource Monitor:** A quick CLI dashboard for checking CPU, RAM, and disk bottlenecks.

---

## 📘 LooM OS User Manual (Crash Course)

Because LooM OS is built on a Tiling Window Manager (i3wm), it relies heavily on keyboard shortcuts rather than a mouse. Here is everything you need to know to navigate the system.

### The Mod Key
The primary control key in LooM OS is the **`Alt` key** (configured as `Mod1`).

### Essential Navigation Shortcuts
* `Alt + Enter` : Open a new Terminal (Alacritty).
* `Alt + d` : Open the application launcher (dmenu). Type the name of any app and press Enter.
* `Alt + Shift + q` : Close/Kill the currently focused window.
* `Alt + Shift + e` : Exit i3 / Log out of the system.
* `Alt + [1-9]` : Switch to a different workspace (virtual desktop).
* `Alt + Shift + [1-9]` : Move the currently focused window to a different workspace.

### Window Layout Control
* `Alt + v` : Split the screen vertically for the next window.
* `Alt + h` : Split the screen horizontally for the next window.
* `Alt + f` : Toggle fullscreen mode for the current window.
* `Alt + Shift + Space` : Toggle a window between floating (drag with mouse) and tiling mode.

### Default Credentials (Live USB Mode)
If you are running LooM OS from a Live USB without installing it, the default login credentials are:
* **Username:** `user`
* **Password:** `live` (or leave blank and press Enter).

---

## 🛠️ Installation Guide

Ready to commit? Installing LooM OS is straightforward using the Debian Calamares graphical installer.

1. Download the latest `LooM_OS.iso` and its `SHA256` checksum from the releases page.
2. Verify the checksum to ensure data integrity:
   ```bash
   sha256sum -c LooM_OS_1.0.sha256
````

3.  Flash the ISO to a USB drive (8GB minimum) using tools like [Rufus](https://rufus.ie/) or [BalenaEtcher](https://etcher.balena.io/).
4.  Boot your machine from the USB. You will enter the Live Environment automatically.
5.  Press `Alt + Enter` to open the terminal.
6.  Launch the graphical installer by running:
    ```bash
    sudo debian-installer-launcher
    ```
7.  Follow the on-screen prompts to partition your disk, set your timezone, and create your permanent user account.
8.  Reboot and enjoy your new infrastructure powerhouse\!

-----

## 📜 License

LooM OS is open-source software. This project is licensed under the **GNU General Public License v3.0 (GPLv3)**. The CoreLoom scripts and specific configurations are provided under the same terms. See the `LICENSE` file for more details.

-----

**CoreLoom** — *Built by Engineers, for Engineers.*
<br>
© 2026-2027 CoreLoom & Abdullrahman Eissa. All Rights Reserved.

```
```