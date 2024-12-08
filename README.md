# PixOS - Pixel Art & Animation Editor

A retro-styled web-based pixel art editor with animation capabilities. Works completely offline!

## Features

### Drawing Tools
- Brush, Eraser, Fill tools
- Color picker
- Undo/Redo functionality
- Grid overlay
- Zoom controls

### Canvas Options
- Multiple sizes (16x16 to 128x128)
- Clear canvas function
- Grid overlay toggle

### Animation Features
- Multi-frame animation support
- Frame controls (add, duplicate, delete)
- Playback controls
- Adjustable FPS
- Loop toggle
- Onion skinning

### Export Options
- Export single frames as PNG
- Export animations as GIF

## Setup

1. Download the project files
2. Download gif.js library (https://github.com/jnordberg/gif.js)
3. Place in project structure:
PixOS/ ├── fonts/ │ └── PressStart2P-Regular.ttf ├── lib/ │ └── gif.js ├── PixOS.html ├── styles.css └── script.js
## Usage

### Basic Drawing
1. Select tool (Brush/Eraser/Fill)
2. Choose color
3. Draw on canvas

### Animation
1. Create frames using 'New Frame'
2. Set FPS (1-60)
3. Use Play/Pause to preview
4. Toggle Loop ON/OFF as needed
5. Use Onion Skin for reference

### Exporting
- Single frame: Click 'Export PNG'
- Animation: Click 'Export GIF'

## Requirements
- Modern web browser
- No internet needed
- Local gif.js library

