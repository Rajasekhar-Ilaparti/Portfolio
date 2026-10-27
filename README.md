# Ilaparti Rajasekhar — Portfolio

Personal portfolio of **Ilaparti Rajasekhar**, a B.Tech ECE student at Seshadri Rao Gudlavalleru Engineering College focused on embedded systems, IoT, and electronics.

## Highlights

- **Experience:** Embedded Systems Intern at Emertxe Information Technologies (PIC16F877A microwave oven controller)
- **Projects:** Microwave Oven Controller, Automated Water Gate Control System, ESP32 Web Control Dashboard, Smart Water Monitoring & Billing (concept)
- **Skills:** C, Embedded C, Python, Verilog · PIC16F877A, ESP32, ESP8266, Arduino · MPLAB IDE, Proteus, Vivado, GTKWave

## Structure

```
index.html   # the whole site: markup, styles, and scripts
photos/      # profile, about, and gallery images
```

The site is a single static page with no build step. It loads Google Fonts and, in the browser, pulls live repository data from the GitHub API and a contribution chart from ghchart.rshah.org.

## Resume

Put your resume in this folder as `resume.pdf`. The "Download Resume" button on the profile card appears automatically once the file exists.

## Running locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Updating content

The data lists live in the `<script>` at the bottom of `index.html`:

- `PROJECTS` — featured hardware builds; set `repo` to the GitHub repository name to link it. `cats` controls the filter buttons, and `overview`, `features`, `flow`, `hardware`, `future` fill the details pop-up.
- `WEB_PROJECTS` — web apps with a `live` URL and/or `repo`, plus a screenshot in `photos/web/`.
- `FILTERS` — order of the project filter buttons.
- `TYPED_WORDS` — phrases cycled by the hero typing animation.
- `GH_SKIP` / `GH_LIMIT` — repositories hidden from the live "GitHub Activity" section, and how many it shows. Repo descriptions come from each repository's "About" text on GitHub.
- `TOOLS` — the tools grid.
- `GALLERY` — photos in `photos/` with a `caption` (and optional `pos` to adjust cropping).

## Contact

- Email: rajasekharilaparthi@gmail.com
- LinkedIn: [rajasekhar-ilaparti](https://www.linkedin.com/in/rajasekhar-ilaparti)
- GitHub: [Rajasekhar-Ilaparti](https://github.com/Rajasekhar-Ilaparti)
