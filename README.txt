# Simple WebAR Marker Test

This folder contains a minimal AR.js marker-based AR test.

## Files

- `index.html` - the WebAR test page
- `model.glb` - your uploaded GLB model, renamed for simplicity

## Upload

Upload the whole `ar-test` folder to your website, for example:

https://yourwebsite.org/ar-test/

The page must be served over HTTPS for mobile camera access.

## Print the marker

This test uses the standard AR.js HIRO marker.

Search online for:

AR.js HIRO marker print

or use the marker image from the AR.js examples/docs.

Print it on A4 paper with strong black-and-white contrast.

## Test

1. Open the page on your phone.
2. Allow camera access.
3. Point the camera at the printed HIRO marker.
4. The model should appear above the marker and spin.

## Quick tweaks inside index.html

If the model is too large or small, edit:

scale="0.35 0.35 0.35"

If the model sits too low or high, edit:

position="0 0.45 0"

If the model is sideways, edit:

rotation="0 0 0"
