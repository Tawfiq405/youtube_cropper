# YouTube Video Cropper

A local web application that allows you to watch YouTube videos with custom cropping and aspect ratio controls.

## Features

- 🎥 Load any YouTube video by URL
- ✂️ **Visual Crop Tool**: Draw custom crop regions directly on the video with drag-and-resize handles
- 🖼️ **Fullscreen Mode**: View your cropped video in fullscreen (YouTube controls remain accessible)
- 🔍 Zoom controls for precise cropping (1x to 3x)
- 📐 Multiple aspect ratio presets (16:9, 21:9, 4:3, 1:1, 9:16, Cinema)
- 🎯 Precise position controls (horizontal and vertical)
- 📏 Adjustable width and height
- 🔄 Reset button to restore defaults
- 🎨 Beautiful, modern UI with overlay controls

## How to Run

1. Make sure you have Python 3 installed
2. Navigate to the project directory
3. Run the server:
   ```bash
   python3 server.py
   ```
4. Open your browser and go to: `http://localhost:8000`
5. Paste a YouTube URL and start cropping!

## Controls

- **Zoom Level**: Zoom in to crop the video (1x to 3x)
- **Horizontal Position**: Move the video left/right when zoomed
- **Vertical Position**: Move the video up/down when zoomed
- **Width/Height**: Adjust the container dimensions
- **Aspect Ratio Presets**: Quick buttons for common formats
- **Reset**: Return all settings to default values

## Example URLs to Try

- Standard video: `https://www.youtube.com/watch?v=dQw4w9WgXcQ`
- Any YouTube video URL will work!

## Technical Details

- **Backend**: Python HTTP server
- **Frontend**: HTML, CSS, JavaScript
- **API**: YouTube IFrame Player API
- **No dependencies required** (uses Python standard library)

## Notes

- The server runs on port 8000 by default
- All processing happens in the browser
- No video data is downloaded or stored
- Videos are streamed directly from YouTube
