# HIRO Marker AR Sanity Test

This is a clean marker-based AR test. It does not use GPS.

Files:
- index.html
- model.glb
- README.txt

Upload index.html and model.glb to your GitHub Pages repository root, replacing the current geolocated test files.

Test:
1. Open https://cbwporter.github.io/artest/ on your phone.
2. Allow camera access.
3. Point at a printed HIRO marker.
4. The duck should appear and spin.

Current model settings:
- position="0 0.5 0"
- scale="3 3 3"
- rotation animation: one full spin every 7 seconds

If the duck is too big/small, edit scale in index.html:
- Smaller: scale="1 1 1"
- Bigger: scale="5 5 5"
