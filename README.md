# Hand Particle Experience

A browser-based particle playground controlled with hand gestures. Move your hand to change the particle shape, color, and rotation; pinch to adjust the size.

## Run locally

Open the project through a local web server rather than directly as a `file://` URL. Camera access generally requires `localhost` or HTTPS.

For example, with Python installed:

```powershell
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000), select **Start Experience**, and allow camera access.

The page loads Three.js and MediaPipe from public CDNs, so an internet connection is required.
