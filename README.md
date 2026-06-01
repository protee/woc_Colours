<div align="center">

<!-- Header with left text and right logo -->
<div style="display: flex; align-items: center; justify-content: space-between; width: 100%;">
  <div style="text-align: left;">
    <strong style="font-size: 1.2em;">Colour, reloaded.</strong><br>
    <strong style="font-size: 1em;">Mantra:</strong> Indexed purity. No RGB noise.<br>
    <strong style="font-size: 1em;">Tagline:</strong> Color, solved.
  </div>
  <div>
    <img src="https://www.protee.org/images/woc_Colours/woc_Colours.png" alt="woc_Colours Logo" width="60" style="border-radius: 12px;">
  </div>
</div>

<!-- Title and badges -->
# woc_Colours

[![4D Component](https://img.shields.io/badge/4D-Component-blue)](#)
[![License: Commercial](https://img.shields.io/badge/License-Commercial-red.svg)](#license)
[![Platform: macOS & Windows](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-lightgrey)](#)
[![4D v21+](https://img.shields.io/badge/4D-v21%2B-brightgreen)](#)

</div>

## Overview

woc_Colours is the advanced low‑level color management engine for the **ogTools suite**. It operates in both RGB and specialized indexed color spaces, providing unparalleled consistency and design flexibility for any 4D project. Localized in EN, FR, ES, DE.[reference:0]

---

## Key Features

### Supported Color Spaces
- **md** – Material Design (bright and efficient)
- **mdo** – Material Design OG (double the luminosity of md)
- **sw** – Senzā Wada original (new)
- **swo** – Senzā Wada OG reloaded (new)
- **rale** – RALe (smooth and soft)
- **pans** – Pantone Short (curated and efficient)
- **pant** – Pantone (comprehensive)
- **mn** – A custom space
- **4d** – Native 4D theme colors
- **svg** – Standard SVG colors
- **web** – Standard web colors[reference:1]

### Intelligent Color Editor
A single long integer can store both Stroke and Fill properties, each potentially from a different color space. The editor UI dynamically resizes when switching spaces to maintain perfectly squared color samples and seamlessly manages conversions between spaces.[reference:2]

### Comprehensive Tools
- **Ready‑to‑Use Widgets** – Includes color pickers, menus, and other UI elements for seamless integration.
- **Color Processing** – Provides common utilities for color manipulation and treatment.
- **Extended Libraries** – Features libraries for `rgb`, `colour`, `color`, and `svg` operations.
- **Pattern Library** – A collection of “delicious” patterns from Hero Patterns, complete with an embedded editor for customization.[reference:3]

### Advantages of Indexed Colors
- Stroke and Fill combined in one long integer.
- Limited choice that adds taste to your UI.
- With built‑in spaces, the effective limitation is low.
- Up to 16 spaces (4 bits) and 4096 indexes (12 bits).
- Lazy loading: spaces and conversion tables can be auto‑ or pre‑loaded.
- Display and copy colors in multiple formats: `[0x0…]`, `[sp:index] name`, numeric values, `rgb(r,g,b)`, `0xrrggbb`, etc.[reference:4]

---

## Installation & Dependencies

### Prerequisites
- **4D v21** or higher (Project mode recommended).
- [**wok_Krolific**](https://github.com/protee/wok_Krolific) – Licensing component (mandatory dependency).
- [**wox_Xlibrary**](https://github.com/protee/wox_Xlibrary) – Core utilities (mandatory dependency).
- The [**4D SVG component**](https://github.com/4d/4D-SVG) must be available in your project.

### Installation via Dependencies Manager (GitHub)

Starting with 4D v21, the recommended way to install woc_Colours (and any ogTools component) is through the **Dependencies Manager** using the **GitHub repository**:

1. In your 4D project, open the **Dependencies Manager** (`Project > Dependencies`).
2. Click the `+` button and select **Add a dependency from a Git URL**.
3. Enter the following Git URL:`protee/woc_Colours`
4. Choose the desired version (e.g., `main`, `latest`, or a specific release tag).
5. Confirm the installation – the component will be automatically fetched from GitHub, placed in the `Components` folder, and linked to your project.

> **Note**: For team development, commit the dependency configuration file (`dependencies.json`) to your source control so all team members automatically fetch the same version from GitHub.

---

## Part of the ogTools Suite

woc_Colours is the color management pillar of the comprehensive **ogTools suite**—an integrated development ecosystem for 4D. Other key components include:

| Component | Description |
|-----------|-------------|
| **wok_Krolific** | Centralized licensing system. |
| **wox_Xlibrary** | Core utilities for everyday development tasks. |
| **zen_Nucleus** | The complete ORDA framework binding your database to a sophisticated UI. |
| **waz_Wazar** | Intelligent UI widgets for modern interfaces. |
| **wor_Recursive** | Manage hierarchical data with ease. |
| **wob_Boxes** | Secure, Dropbox-like file repository. |
| **wod_DevTools** | Instant documentation generation. |
| **wom_Make** | Build and automation toolkit. |

> Together, these components form a powerful framework that allows developers to focus on unique business logic rather than reinventing the wheel.

---

## License

woc_Colours is a **commercial component** and is part of the paid ogTools suite. A valid license is required for use. For licensing options and trial requests, please contact the sales team directly.

---

## Localization

woc_Colours supports the following languages out‑of‑the‑box:

- 🇺🇸 English (EN)
- 🇫🇷 French (FR)
- 🇪🇸 Spanish (ES)
- 🇩🇪 German (DE)

Localization affects error messages, UI prompts, and built‑in pane texts.

---

## Support & Resources

- **Official Website**: [https://www.protee.org](https://www.protee.org)
- **Documentation**: Full documentation and HDI (Host Database Interface) demos are included with your purchase.

For direct inquiries:
- **Email**: [og@protee.org](mailto:og@protee.org)
- **Phone**: +33 6 3718 5941

---

## About the Creator

woc_Colours and the ogTools suite are developed by **Protée sarl**, a company with over 30 years of expertise in 4D development. Led by Olivier Grimbert, the team focuses on delivering high‑quality, production‑grade tools that enhance developer productivity and application reliability.

---

<div align="center">
  <sub>Built with ❤️ for the 4D community by Protée sarl. © 2016 - Present</sub>
</div>