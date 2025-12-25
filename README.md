# Image Stacker

A simple web application to layer images on top of each other using Fabric.js.

## Features

- **Upload Overlay Image**: Upload a PNG (preferably with transparency) that acts as a frame/template
- **Add Your Photo**: Upload your photo to place behind the overlay
- **Manipulate Your Photo**: 
  - Drag to reposition
  - Resize using corner handles
  - Rotate your image
  - Adjust scale with slider
- **Adjust Overlay Opacity**: See through the overlay while positioning your photo
- **Download**: Export the final stacked image at 2x resolution

## How to Use

1. Open `index.html` in your browser
2. Click "Upload Overlay" and select your frame/template image
3. Click "Add Your Photo" and select your background photo
4. Drag and resize your photo to position it perfectly behind the overlay
5. Click "Download Image" to save your creation

## Sample Files

- `sample-overlay.svg` - A sample frame overlay to test with

## Tech Stack

- Vanilla JavaScript
- Fabric.js for canvas manipulation
- No build tools required - just open in browser!

## Tips

- Use PNG images with transparency for best results as overlays
- The overlay image determines the final canvas size
- Your photo will automatically scale to cover the canvas area
- Adjust the overlay opacity to see your photo better while positioning
- The downloaded image will have the overlay at full opacity

## License

MIT








