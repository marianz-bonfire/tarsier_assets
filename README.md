# Package Assets Repository

This repository serves as a **centralized, public collection of assets** used across multiple projects and published packages, including those hosted on **pub.dev**.

It is designed to store and serve static media files such as logos, screenshots, diagrams, and banners that need to be publicly accessible (e.g., for README files, documentation, and package listings).

---

## 📦 What This Repository Contains

- 📌 Package logos
- 🖼 Screenshots and UI previews
- 🎨 Banners and badges
- 📊 Diagrams and illustrations
- 📘 Documentation-related images

All assets are hosted publicly to ensure compatibility with:
- **pub.dev**
- GitHub README rendering
- External documentation sites



## 📁 Repository Structure

```text
package-assets/
├── package_name_1/
│   ├── logo.png
│   ├── banner.png
│   └── screenshots/
│       ├── screen_1.png
│       └── screen_2.png
│
├── package_name_2/
│   ├── logo.svg
│   └── preview.png
│
└── shared/
    ├── icons/
    └── badges/

```

---
```html
<img
  src="https://raw.githubusercontent.com/username/package-assets/main/package_name_1/logo.png"
  height="260"
/>
```