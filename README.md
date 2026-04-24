# App Assets Repository 🖼️

This repository serves as a dedicated host for high-performance images and media assets used across my React applications and other web projects.

## 🚀 Purpose

I created this repository to solve performance issues caused by slow or unstable external image links. By hosting images directly on GitHub and using the correct raw URL format, I ensure faster loading times for the end-user, reliable uptime with fewer broken image links, better organization of my project-specific media, and reusable image links across different React apps and JSON data files.

## 🛠️ How to use an image in an App

To link an image from this repository to a project, use the raw GitHub URL format:

```txt
https://raw.githubusercontent.com/Hooman-Render/app-assets/main/image-name.avif
```

Example in HTML or JSX:

```html
<img src="https://raw.githubusercontent.com/Hooman-Render/app-assets/main/trampoline-party.avif" alt="Trampoline Party" />
```

Example in JSON:

```json
{
  "title": "Trampoline Party",
  "image": "https://raw.githubusercontent.com/Hooman-Render/app-assets/main/trampoline-party.avif"
}
```

## 🔗 Available Image Links

Trampoline Party: `https://raw.githubusercontent.com/Hooman-Render/app-assets/main/trampoline-party.avif`

Yoga: `https://raw.githubusercontent.com/Hooman-Render/app-assets/main/yoga.avif`

Badminton: `https://raw.githubusercontent.com/Hooman-Render/app-assets/main/badminton.avif`

Board Games: `https://raw.githubusercontent.com/Hooman-Render/app-assets/main/board-games.avif`

Bowling: `https://raw.githubusercontent.com/Hooman-Render/app-assets/main/bowling.avif`

Hiking: `https://raw.githubusercontent.com/Hooman-Render/app-assets/main/hiking.avif`

Lasertag: `https://raw.githubusercontent.com/Hooman-Render/app-assets/main/lasertag.avif`

Tea Tasting: `https://raw.githubusercontent.com/Hooman-Render/app-assets/main/tea-tasting.avif`

Tennis: `https://raw.githubusercontent.com/Hooman-Render/app-assets/main/tennis.avif`

## 📂 Structure

The root folder contains the main images and global assets. Image files are stored as optimized `.avif` files. File names must match the raw URL exactly.

Current structure:

```txt
/
├── trampoline-party.avif
├── yoga.avif
├── badminton.avif
├── board-games.avif
├── bowling.avif
├── hiking.avif
├── lasertag.avif
├── tea-tasting.avif
└── tennis.avif
```

## ✅ Notes

Use the correct raw GitHub base URL:

```txt
https://raw.githubusercontent.com/Hooman-Render/app-assets/main/
```

Do not use the incomplete format:

```txt
https://githubusercontent.com
```

Always use clear `alt` text when adding images to a React app for better accessibility.

Good example:

```html
<img src="https://raw.githubusercontent.com/Hooman-Render/app-assets/main/bowling.avif" alt="People playing bowling in a neon bowling alley" />
```

Bad example:

```html
<img src="https://raw.githubusercontent.com/Hooman-Render/app-assets/main/bowling.avif" alt="image" />
```

---

Maintained by [Hooman-Render](https://github.com/Hooman-Render)
