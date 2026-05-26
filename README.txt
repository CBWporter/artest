# Facing Duck HIRO Test

This is a replacement HIRO-marker test package.

Files:
- index.html
- facingduck.glb
- README.txt

Upload these two files to GitHub, replacing the current test files:
- index.html
- facingduck.glb

Important:
The HTML now references:

<a-asset-item id="facing-duck-model" src="./facingduck.glb"></a-asset-item>

So the model file MUST be called exactly:

facingduck.glb

Current orientation:
rotation="-90 180 0"

Current scale:
scale="3 3 3"

Current height:
position="0 0.8 0"

If the duck is upright but facing backwards, edit the inner model rotation to:
rotation="-90 0 0"

If the duck is still wrong, try:
rotation="90 180 0"
or
rotation="0 180 0"
