<p align="center">
  <a href="https://photos.davishiggins.com"><img src="assets/hero.svg" width="100%" alt="photos &amp; frames: creation and expression through motion. Animated cover with the p&amp;f mark and title beside a viewfinder where each landscape reveals its color as crop corners tighten, next to a black-and-white film strip." /></a>
</p>

<h1 align="center">photos &amp; frames</h1>

<p align="center"><strong>My photography portfolio: galleries shown in black and white until you reach for them, plus editing, curation, and gallery services.</strong></p>

<p align="center">
  <a href="https://photos.davishiggins.com"><img src="assets/btn-open.svg" height="44" alt="View the gallery" /></a>&nbsp;
  <a href="https://www.higginsd.com/work/photos-and-frames"><img src="assets/btn-case.svg" height="44" alt="Case study" /></a>&nbsp;
  <a href="https://davishiggins.com"><img src="assets/btn-dh.svg" height="44" alt="Davis Higgins" /></a>
</p>

<p align="center"><sub>Live · Photography, design, and build by Davis Higgins</sub></p>

---

## See it in motion

<p align="center">
  <img src="assets/demo.gif" width="880" alt="Screen recording of photos.davishiggins.com: switching the gallery to the nature collection, hovering a black-and-white photo so it reveals color, opening it in the lightbox, and stepping to the next frame." />
</p>

<p align="center"><sub>Real capture of the live gallery's nature collection. <a href="assets/demo.png">Static frame</a></sub></p>

## What it does

- **Color is earned.** Every photo appears in black and white and reveals its real color on hover, focus, or touch, so the eye reads composition first and color second.
- **One collection at a time.** The gallery is split into portraits, nature, and couples. Each collection shows its frame count and opens into a full-screen lightbox with keyboard navigation.
- **More than a portfolio.** A services page covers photo editing, portfolio websites, custom galleries, and visual curation, with a contact route for inquiries.

## Why I built it

I wanted a home for my photography that feels like an exhibition, not a feed. The site follows one visual rule, monochrome first and color on intent, with lowercase type and quiet chrome that stay out of the pictures' way.

## What I built

I took the photographs and designed and built the site:

- The black-and-white-to-color interaction, working with a mouse, the keyboard, and touch
- Collection-based gallery browsing with a lightbox
- An animated homepage composition, smooth scrolling, and page motion
- The workflow that prepares every original photo for the web
- The services and contact pages

<details>
<summary><strong>How it's put together</strong></summary>

<br />

```mermaid
flowchart TB
    R[Original photos] --> S[Web-ready images]
    S --> G[Gallery: one collection at a time]
    G --> C[Monochrome card<br/>color on hover, focus, or touch]
    C --> L[Full-screen lightbox]
```

| Decision | Why |
|---|---|
| **The reveal works for everyone** | Color responds to keyboard focus and a tap, not just a mouse, so the core interaction works on every device. |
| **Fast on a phone** | Images load as they're needed, so an image-heavy page stays responsive. |
| **One photo, many collections** | A photograph can live in more than one collection without being duplicated. |

</details>

## Screens

<table>
  <tr>
    <td width="62%"><img src="assets/screenshot-home.png" alt="photos & frames homepage: the title and 'creation and expression through motion' beside a collage of black-and-white photos." /></td>
    <td rowspan="2" width="38%" align="center"><img src="assets/screenshot-mobile.png" width="300" alt="Services page on a phone, starting with photo editing." /></td>
  </tr>
  <tr>
    <td><img src="assets/screenshot-gallery.png" alt="The nature collection: a marina, a canal at dusk, and a dog on leaves, shown in black and white." /></td>
  </tr>
</table>

<sub>Homepage · Nature collection · Services on mobile</sub>

## Technology

| Layer | Technology |
|---|---|
| App | React, TypeScript, Vite |
| Styling | Tailwind CSS |
| Motion | GSAP, Framer Motion, Lenis |
| Hosting | Vercel |

---

<p align="center">
  <a href="https://photos.davishiggins.com"><img src="assets/btn-open.svg" height="44" alt="View the gallery" /></a>&nbsp;
  <a href="https://github.com/DavisHiggins"><img src="assets/btn-more.svg" height="44" alt="More of my work" /></a>
</p>

<p align="center"><sub>© 2026 Davis Higgins. All rights reserved. Photographs may not be reused.</sub></p>
