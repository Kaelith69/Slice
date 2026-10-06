# Slice

A focused, browser-based image slicer for turning one image into a row of numbered tiles.

**Live app:** [kaelith69.github.io/Slice](https://kaelith69.github.io/Slice/)

## What it does

- Runs entirely in the browser; images are not uploaded.
- Accepts PNG and other browser-readable image formats.
- Creates 2 to 10 square slices or free-form tiles.
- Supports drag-to-crop, move, resize, and keyboard adjustments.
- Names tiles with a custom prefix and optional zero-padding.
- Lets you preview and download individual PNG tiles.
- Exports all tiles as `squares.zip`.
- Includes light and dark themes.

## Use it

1. Open the [live app](https://kaelith69.github.io/Slice/).
2. Drop an image onto the workspace or choose one from your device.
3. Adjust the crop, slice count, tile mode, and file naming.
4. Select **Slice image**.
5. Download individual tiles or the complete ZIP folder.

## Run locally

This is a dependency-free static site. Open `index.html` directly in a browser, or serve the folder with any static web server:

```bash
python -m http.server
```

Then visit `http://localhost:8000`.

## Privacy

Processing happens locally in your browser. Slice does not send selected images to a server.

## Built with

HTML, CSS, and vanilla JavaScript using the Canvas and File APIs.

## License

No license has been specified for this repository yet.
