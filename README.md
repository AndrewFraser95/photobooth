# Photobooth

Single-file photobooth for iPhone Safari. Guests get a strip of 3 or 4 photos with the host's own text at the bottom.

## Set up an event
Open the app, type the text for the strip (e.g. "Sam's 30th Birthday"), choose 3 or 4 photos, the delay (3/5/10s) and the camera. Settings are remembered on that device.

To share a pre-set link: `https://andrewfraser.com/photobooth/?text=Sam%27s%2030th&shots=3&delay=5`

## Host it (HTTPS required for the camera)
`npm install` then `npm run deploy` publishes to the `gh-pages` branch.
In the GitHub repo: Settings > Pages > deploy from branch `gh-pages` (root).

## On the iPhone
1. Open the https link in Safari, allow the camera.
2. Optional: Share > Add to Home Screen for fullscreen.
3. Set up the event, tap Start. After the photos, guests tap **Save to my phone** > Save Image.
