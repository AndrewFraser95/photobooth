# Photobooth

Single-file 4-photo booth for iPhone Safari. Caption and settings are constants at the top of the script in `index.html`.

## Host it (HTTPS required for the camera)
`npm install` then `npm run deploy` publishes `index.html` to the `gh-pages` branch.
In the GitHub repo: Settings > Pages > deploy from branch `gh-pages` (root).
Live at https://andrewfraser95.github.io/photobooth/

## On the iPhone
1. Open the https link in Safari, allow the camera.
2. Optional: Share > Add to Home Screen for fullscreen.
3. Pick 3s / 5s / 10s, tap Start. After 4 photos the strip downloads.

iOS shows a one-tap "Download" prompt and saves to Files. Tap **Save to Photos** > Save Image to put it in the camera roll.
