# TapTux — Official Project

> **[**TapTux**]() delivers multiple desktop operating systems in lightweight OS containers, built from scratch to run seamlessly on mobile devices.**
> Fully functional offline, it provides a complete desktop experience optimized for productivity and everyday use. 

## Contents

- [Executive Summary](#executive-summary) [Key Features](#key-features) [Installation & Usage](#installation--usage) [User Experience](#user-experience) [Security & Privacy](#security--privacy) [Developers & Contributors](#developers--contributors) [License & Contact](#license--contact)

---

# Executive Summary
> **TapTux** is a **modular platform** delivering multiple desktop operating systems through lightweight, custom-built OS containers.

- **Independent Application:** Runs fully standalone as a native package. ```BETA, NOT AVAILABLE```
- **[Termux](https://github.com/termux/termux-app)** Support: Fully integrated for seamless execution alongside Termux environments. ```AVAILABLE SOON```
- **Mobile & Embedded Ready:** Optimized for efficient, standalone operation across mobile and embedded devices.  
- **Performance & Configurability:** Fast, resource-efficient, and highly customizable desktop experience.  
- **Developer-Friendly:** Maintains clean, predictable code and a robust professional architecture.

---

## Project Editions & Installation

### 1. TapTux (CLI)
* **Features:** Lightweight command-line interface, low resource overhead, direct interaction with the `PGuard` isolation engine, and full scripting support for headless or embedded deployments.
```bash
TapTux CLI - Initial Release Scheduled
ETA: 29 Sept, 2026
```

### 2. TapTux (TUI)
* **Features:** Terminal-based user interface, interactive navigation, real-time container monitoring, and streamlined workspace management, It requires graphical display server like Termux:X11, Because this version was built on Qt. 
```bash
TapTux TUI - Initial Release Scheduled
ETA: The release has not been scheduled due to incomplete work  
```

### 3. TapTux (GUI)
* **Features:** Delivers a complete, immersive desktop user experience tailored specifically for Android users. Beyond standard container management, TapTux GUI bridges traditional well-known desktop operating systems (such as Windows and macOS environments) alongside entirely novel, custom-built OS environments engineered from the ground up for mobile form factors. It features a fluid C-based nested window architecture powered by optimized local sockets, seamless file bridging for safe data transfer between the host and isolated partitions, and an integrated Scaean security layer operating quietly in the background to ensure absolute runtime safety without sacrificing desktop fluidity or usability.
```bash
TapTux GUI - Initial Release Scheduled
ETA: The release has not been scheduled due to incomplete work  
```

# Security & Privacy

**Security Architecture & Threat Mitigation Framework:**
- TapTux establishes an uncompromising security paradigm across all isolated environments, engineered from the ground up to shield users against advanced cyber threats, malicious payloads, and untrusted runtime scripts, Rather than relying on superficial permission checks, the platform integrates a robust, low-level security subsystem designed to enforce absolute isolation without compromising performance.

- Deep-Layer Rootless Sandboxing (PGuard): Operating entirely within a secure user-space architecture without requiring root privileges, the platform intercepts low-level system calls to instantiate tightly bound, isolated runtime containers. This guarantees that any experimental, unverified, or potentially hostile software remains completely contained within its designated partition, leaving the primary operating environment entirely unaffected.

- Scaean Intelligent Perimeter Defense: Acting as the core security gateway, Scaean continuously inspects, filters, and regulates network packets and inter-process communications, It functions as an unyielding barrier that prevents malicious lateral movement, data leakage, or unauthorized interface scraping from nested containers.

- Nested Graphical Isolation: By deploying modular, lightweight containerized user interfaces managed directly through low-level C-based control structures, TapTux ensures that GUI-based applications execute within secure boundaries, This prevents rogue software from intercepting global keystrokes or accessing unauthorized display buffers.

- Autonomous Defender Subsystem: The architecture incorporates an active, real-time monitoring daemon that preemptively detects, flags, and neutralizes anomalous operations, unauthorized file system modifications, and suspicious network activities before they can impact system integrity.

> - **Important Security Advisory:** The integrated Defender framework is active by default to ensure continuous, bulletproof system protection, Users retain the administrative flexibility to disable the security subsystem; however, doing so completely lifts structural safeguards, Deactivating the defense mechanisms transfers absolute liability to the operator, any system instability, data compromise, or security breach arising from the execution of unverified software rests entirely upon the user.

# Requirements & operational structure
- Intelligent Resource Orchestration: TapTux dynamically reads and processes the real-time coordinates of your device's RAM, processor, and battery. It assumes complete, autonomous control over resource distribution across the entire operating architecture, eliminating system waste.

- ​Precision Hardware Throttling: By enforcing strict, intelligent consumption limits on RAM and CPU usage, TapTux actively mitigates the hardware strain that causes system degradation and lag.

- ​Unprecedented Battery Preservation: The core of the TapTux architecture is fundamentally designed around power mindfulness. By curtailing excessive processor and memory consumption, it guarantees a profound and positive impact on your battery's lifespan.

- ​Expanded Usability Horizons: Beyond core system optimization, TapTux introduces a dedicated, advanced power-saving framework. This ensures that your device remains highly functional and reliable, drastically expanding your operational window when you need it most.

**Requirements:**
> A device with at least Android 8, 16GB of storage, and 1GB of RAM.

# Developers & Contributors
> The project is officially managed and directed by a specialized group of developers operating under the organization name **DevOra**. The initiative is spearheaded by the primary owner and project team leader, **```Mikhail M. Abdelaziz```**, in strategic collaboration with **```(Bulgarian Vyasheslav, also known as JotarOS)```**, **```Avital Shalev```**, **```Tasuni Nagashita```** And **```Raed Abdullah```**.
 
