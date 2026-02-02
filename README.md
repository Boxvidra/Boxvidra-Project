# TapTux — Official Project

> **[**TapTux**]() delivers multiple desktop operating systems in lightweight OS containers, built from scratch to run seamlessly on mobile devices.**
> Fully functional offline, it provides a complete desktop experience optimized for productivity and everyday use. 

## Contents

- [Executive Summary](#executive-summary) [Key Features](#key-features) [Installation & Usage](#installation--usage) [User Experience](#user-experience) [Security & Privacy](#security--privacy) [Contribution Guide](#contribution-guide) [License & Contact](#license--contact)

---

# Executive Summary
> **TapTux** is a **modular platform** delivering multiple desktop operating systems through lightweight, custom-built OS containers.

- **Independent Application:** Runs fully standalone. ```BETA, NOT AVAILABLE```
- **[Termux](https://github.com/termux/termux-app)** Support: Operates as a separate environment, isolated from Termux’s internal programs and tools (similar to Proot). ```AVAILABLE SOON```
- **Mobile & Embedded Ready:** Optimized for offline use on mobile and embedded devices.  
- **Performance & Configurability:** Fast, efficient, and highly customizable desktop experience.  
- **Developer-Friendly:** Maintains clean, predictable code and professional user experience.

# Security & Privacy

TapTux is designed with security and privacy as a top priority across all its OS containers. Its architecture ensures complete isolation from the host system, relying on the fact that Termux does not expose any sensitive information in `/data/data/com.termux/`. This isolation prevents any interference with the host system files or applications.

**Restricted Countries:** TapTux is not supported in the following regions due to regulatory restrictions:  
- United Arab Emirates  
- Qatar
- Israel  

**Security Mechanisms:**  
- TapTux applies a system-wide security framework to all containers, aiming to protect users from suspicious programs, malicious codes, and untrusted scripts.  
- The platform includes a built-in Defender system that monitors and blocks potentially harmful operations.  
- Users can choose to disable the Defender, but doing so transfers all responsibility to the user, any damage or risk resulting from running unverified software becomes the user's responsibility.  

These measures ensure that TapTux provides a safe, predictable, and user-controlled environment, without compromising the independence or functionality of the contained desktop operating systems.
