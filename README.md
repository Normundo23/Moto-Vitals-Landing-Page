Moto Vitals — Landing Page

The official marketing site for Moto Vitals, a mobile app that tracks motorcycle maintenance — oil changes, brake pads, chain drive, and more — in one live dashboard.



What's in this repo

.
├── index.html      # Landing page (hero, features, how it works, about, contact)
├── privacy.html    # Privacy Policy
├── terms.html      # Terms of Use
└── README.md       # You are here

This is a fully static site — no build step, no dependencies, no framework. Open index.html in a browser and it works.

Previewing locally

Just double-click index.html, or serve it properly with:

bashpython3 -m http.server 8000

then visit http://localhost:8000.

Deploying (free, no card required)

Netlify (fastest)


Go to app.netlify.com/drop
Drag this folder onto the page
Live in seconds at https://your-site-name.netlify.app


GitHub Pages


Push this repo to GitHub
Settings → Pages → Source: main branch, root folder
Live at https://yourusername.github.io/repo-name


Cloudflare Pages


pages.cloudflare.com → Create project → Direct Upload
Upload this folder
Live at https://your-site-name.pages.dev


Before going live, update


 Contact email set to motovitals@gmail.com across index.html and both legal pages
 Replace the placeholder Facebook link in the Contact section
 Add your real live URL to the top of this README
 Point any affiliate program application (Involve Asia, Lazada, AliExpress, etc.) at this deployed URL instead of a raw CDN link


Tech

Plain HTML/CSS/JS. Fonts via Google Fonts (Space Grotesk, Inter, JetBrains Mono). No frameworks, no tracking scripts, no cookies beyond what your hosting provider adds by default.

About Moto Vitals

Moto Vitals is currently in early access testing, starting with riders in the Philippines on popular commuter bikes like the Honda Winner X, with more makes and models planned.


© 2026 Moto Vitals. All rights reserved.
