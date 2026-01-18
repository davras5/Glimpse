# Glimpse

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![No Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen)](https://github.com/davras5/Glimpse)
[![Offline Ready](https://img.shields.io/badge/Offline-Ready-blue)](https://github.com/davras5/Glimpse)

A single-file HTML photo gallery for browsing construction site photos organized in folders.

<img src="assets/preview.JPG" alt="Frontend Preview">

## Features

- **Single HTML file** - No server required, works offline
- **Folder navigation** - Resizable sidebar with folder tree
- **YouTube-style controls** - Play/pause slideshow, progress bar, fullscreen
- **Thumbnail strip** - Quick navigation with horizontal scroll
- **Keyboard shortcuts** - Arrow keys, Space (play/pause), F (fullscreen)
- **Image preloading** - Smooth slideshow with 2 images preloaded ahead
- **Sorting options** - By folder or filename (ascending/descending)
- **Responsive** - Works on desktop and mobile

## Usage

1. Place `Fotogalerie.html` in the parent folder containing your image subfolders
2. Update the `allImages` array in the script with your image paths
3. Open the HTML file in any modern browser

## Structure

```
project-folder/
├── Fotogalerie.html
├── 2024-01_Folder-Name/
│   ├── image1.jpg
│   └── image2.jpg
└── 2024-02_Another-Folder/
    └── image3.jpg
```

## Controls

| Key | Action |
|-----|--------|
| `←` `→` | Previous / Next image |
| `Space` | Play / Pause slideshow |
| `F` | Toggle fullscreen |
| `Esc` | Exit fullscreen |

## License

MIT
