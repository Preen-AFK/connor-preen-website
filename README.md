connorpreen.com
Personal site of Connor Preen, 2nd generation mainframer.
As you scroll, each step of my career installs a component on a 3D mainframe. Brain Health Central, my side project, joins as a second frame linked to the first. A greenbar job log at the end gives the short version.
Live site: connorpreen.com
Built with
Plain HTML, CSS and JavaScript in a single file, with no build step
Three.js r128 for the 3D mainframe
GSAP 3.12.5 and ScrollTrigger for the scroll animation
Archivo and IBM Plex fonts from Google Fonts
Netlify for hosting
Three.js and GSAP load from cdnjs, so there's nothing to install.
Run it locally
Open `index.html` in a browser, or serve the folder:
```bash
python3 -m http.server 8000
```
Then go to `http://localhost:8000`.
Deploy
Netlify deploys every commit to `main`. There is no build command, and the publish directory is the repo root.
`connorpreen.info` forwards to `connorpreen.com`.
Accessibility and fallbacks
With reduced motion turned on, the page shows the finished machine with no scroll animation.
If WebGL or Three.js is unavailable, a static mainframe illustration replaces the 3D scene.
All career content is regular HTML, so it stays readable without the 3D.
Contact
LinkedIn
preenconnor@gmail.com
