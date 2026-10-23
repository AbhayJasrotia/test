# Profile redesign guide

## Design direction

- **Layout:** like your reference, a bold framed banner (thick black frame, large name, a character on each side), then skill scrolls, then quiet text sections.
- **Palette:** paper `#ebe7dd`, ink `#121212`, charcoal, ash and mist greys. The only colour is one small red 道 seal.
- **Type:** Shippori Mincho, converted to outlines so it renders identically everywhere.
- **Artwork:** your three Musashi images, processed into black ink on transparent. Their white backgrounds were removed so the paper shows through, and they were upscaled 2x with light sharpening. The source is 360 px, so they are slightly soft at banner size. Processed copies are in `assets/art/`.
  - Seated Musashi: left of the banner.
  - Katana in the earth with crows: right of the banner, with its ground faded out at the left edge.
  - Leaping Musashi: across the sun in the footer.
- **Credit:** the README ends with a line crediting Takehiko Inoue. The art is his. A personal fan tribute is fine, but do not sell or monetise anything that uses it.

## Skills

Three scrolls with slowly scrolling names (Systems, Network, Web). The text is converted to outlines, and the README's alt text lists every skill for screen readers.

You asked for: Linux, shell scripting, Python, Docker, Git, AWS, networking, security, Wireshark, Postman, Nmap, Windows Server, MERN. I kept JavaScript, FastAPI, C and C++ from your old list.

**I added these for your field. Delete any you do not use:** Active Directory, Nginx, Ansible, TCP/IP. Tell me and I will regenerate the scrolls.

## Animation

- On load, once: the name fades in, the brush stroke draws itself, then the role line, Japanese text and seal fade in.
- Always on, slowly: skill names scroll (rows 1 and 3 left, row 2 right), mist drifts, the sun breathes, grass sways, crows fly and flap.
- People with "reduce motion" turned on see the still image.

## Add the files to GitHub

Your profile repo is `SuperAdmin777/SuperAdmin777`.

1. Delete the old root files: `banner.svg`, `card-01..04.svg`, `dashboard.svg`, `terminal.svg`, `divider.svg`, and the `snake.yml` workflow. Delete the `output` branch too.
2. Upload the `assets/` folder as it is (banner, scrolls, divider, footer, and the `art/` folder).
3. Replace `README.md`.
4. Commit to `main`, then hard-refresh your profile (Ctrl+Shift+R).

## Maintain it

- Edit text directly in `README.md`. Keep the `<p align="center">` wrappers.
- Add a project by uncommenting the template under Work. Pin your best repos too.
- Add other social links under Contact, only with real URLs.
- To change skills, name, sizes or speed, ask me and I will regenerate the SVGs.

## Notes

- The banner is about 740 KB because the two artworks are embedded. That is still fine for GitHub.
- I checked the images in a standards-based renderer (still frame only). I have not seen the motion or the final result on github.com, so check your profile once after committing.
- There are no external image services, so nothing third-party can break.
