# Ilaparti Rajasekhar — Portfolio

[![Live site](https://img.shields.io/badge/Live%20site-rajasekharilaparti--portfolio.netlify.app-2563EB?style=for-the-badge&logo=netlify&logoColor=white)](https://rajasekharilaparti-portfolio.netlify.app/)

**🌐 Visit the portfolio: [rajasekharilaparti-portfolio.netlify.app](https://rajasekharilaparti-portfolio.netlify.app/)**

Personal portfolio of **Ilaparti Rajasekhar**, a B.Tech ECE student at Seshadri Rao Gudlavalleru Engineering College focused on embedded systems, IoT, and electronics.

## Highlights

- **Experience:** Embedded Systems Intern at Emertxe Information Technologies (PIC16F877A microwave oven controller)
- **Hardware projects:** [Electrical Pole Safety Alert System](https://github.com/Rajasekhar-Ilaparti/Electrical-Pole-Safety-Alert-system), [AgriGate](https://github.com/Rajasekhar-Ilaparti/-AgriGate-Automated-Water-Gateway), [Plant Care Rover](https://github.com/Rajasekhar-Ilaparti/Plant-care-rover-with-RP-pico-and-Esp32c3), [FireGuard UNO](https://github.com/Rajasekhar-Ilaparti/FireGuard-Uno), [Turbidity Monitor](https://github.com/Rajasekhar-Ilaparti/Water-Treatment-Plant-Turbidity-Monitoring-System), [Smart Nursery Watering](https://github.com/Rajasekhar-Ilaparti/-Smart-Nursery-Watering-System), [Distance Alert System](https://github.com/Rajasekhar-Ilaparti/Distance-alert-system-with-Esp32-c3-mini)
- **Web & software:** [LAN File Share](https://github.com/Rajasekhar-Ilaparti/LAN-File-Share), [OLED Video Maker](https://rajasekhar-ilaparti.github.io/oled-video-maker/), [Hush](https://hushchatt.netlify.app/)
- **Skills:** C, Embedded C, C++, Python, JavaScript, Verilog · ESP32, Arduino, PIC16F877A, Raspberry Pi Pico · MPLAB IDE, Proteus, Vivado, GTKWave · AI tools: Claude / Claude Code, ChatGPT, GitHub Copilot, Google Gemini

## Hosting

The site is deployed on Netlify at **https://rajasekharilaparti-portfolio.netlify.app/**.

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
- `WEB_PROJECTS` — web and software projects with a `live` URL, `download` link and/or `repo`, plus a screenshot in `photos/web/`.
- `FILTERS` — order of the project filter buttons.
- `TYPED_WORDS` — phrases cycled by the hero typing animation.
- `GH_SKIP` / `GH_LIMIT` — repositories hidden from the live "GitHub Activity" section, and how many it shows. Repo descriptions come from each repository's "About" text on GitHub.
- `TOOLS` — the tools grid.
- `GALLERY` — photos in `photos/` with a `caption` (and optional `pos` to adjust cropping).

## Contact

- Email: rajasekharilaparthi@gmail.com
- LinkedIn: [rajasekhar-ilaparti](https://www.linkedin.com/in/rajasekhar-ilaparti)
- GitHub: [Rajasekhar-Ilaparti](https://github.com/Rajasekhar-Ilaparti)
