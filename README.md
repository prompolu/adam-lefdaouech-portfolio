# Adam Lefdaouech — Personal Portfolio

A personal portfolio with a WebGL helmet reveal, eight selected marketing, web, motion-design and software projects, native project-film playback, an animated circuit, a photo timeline, and responsive navigation.

Adam is a second-year student at EBS, Marketing Manager at Prompolu Aluminium, Founder of Promark Marketing Agency, and Graphic Motion Designer at Euromed.

## Run locally

Open `index.html` in a modern browser, or serve this directory:

```sh
python3 -m http.server 3000
```

Visit http://localhost:3000. No build step or package installation is required.

All HTML, CSS, JavaScript, and personal photos are embedded in `index.html`. Three.js, Lenis, Google Fonts, and the shared racing graphics and 3D model load from their configured online URLs. An internet connection is needed for the full experience; a portrait fallback handles unavailable WebGL.

## Selected work

The work section presents Promark, Prompolu Aluminium, DEBROMP, STRUGAL Maroc, UEMF / Euromed, Saraproc Maroc, La Locandiera, and L’Artisan du Bois, in that order. Prompolu’s website and product films are grouped in one entry, with the website link before the films. Visitors can filter projects and watch films on request, including Adam’s uploaded 36-second UEMF tutorial. The Euromed video is included in `media/GMD19-UEMF-phone.mp4`; keep that directory alongside `index.html` when serving the site.

See [WORK-SOURCES.md](WORK-SOURCES.md) for the evidence and scope of the project descriptions.

## Edit

Edit `index.html` directly. The inline import map defines the external libraries; the `personal-assets` JSON block contains the embedded photos.

## Hosted version

https://kimi-grido1-racing.alefdaouech.chatgpt.site/

The hosted site is managed separately. A GitHub push alone does not publish it.
