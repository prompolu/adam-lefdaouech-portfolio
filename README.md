# Adam Lefdaouech — Personal Portfolio

A personal portfolio with a WebGL helmet reveal, animated circuit, photo timeline, and responsive navigation.

Adam is a second-year student at EBS, Marketing Manager at Prompolu Aluminium, and Founder of Promark Marketing Agency.

## Run locally

Open `index.html` in a modern browser, or serve this directory:

```sh
python3 -m http.server 3000
```

Visit http://localhost:3000. No build step or package installation is required.

All HTML, CSS, JavaScript, and personal photos are embedded in `index.html`. Three.js, Lenis, Google Fonts, and the shared racing graphics and 3D model load from their configured online URLs. An internet connection is needed for the full experience; a portrait fallback handles unavailable WebGL.

## Edit

Edit `index.html` directly. The inline import map defines the external libraries; the `personal-assets` JSON block contains the embedded photos.

## Hosted version

https://kimi-grido1-racing.alefdaouech.chatgpt.site/

The hosted site is managed separately. A GitHub push alone does not publish it.
