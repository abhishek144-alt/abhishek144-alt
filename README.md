# Abhishek Yadav — Animated GitHub Profile

A self-contained, GitHub-safe animated profile built around the supplied transparent portraits. The visual system uses **#070b16** deep navy, **#247bff** electric blue, **#ff354f** crimson and off-white typography.

## Assets

![Hero](assets/hero.svg?v=1)
<img width="1200" height="560" alt="stack" src="https://github.com/user-attachments/assets/863508f7-29de-4b27-9f4d-70058b93e40d" /><img width="1200" height="520" alt="hero" src="https://github.com/user-attachments/assets/51ed7c06-e384-4684-b9ad-02639e7545d0" />
<img width="1200" height="560" alt="connect" src="https://github.com/user-attachments/assets/e35e7ea7-434d-427a-a1ca-54c79038ca3b" />
<img width="1200" height="620" alt="about-life" src="https://github.com/user-attachments/assets/6e421c6a-67d8-4446-8db4-d1415abab738" />

![About / Life](assets/about-life.svg?v=1)

![Stack](assets/stack.svg?v=1)

![ID dashboard](assets/id-dashboard.svg?v=1)

![Connect](assets/connect.svg?v=1)

## About

ECE undergraduate at Raj Kumar Goel Institute of Technology, Class of 2027, with a focus on RTL design, functional verification, Verilog HDL, digital circuits, and Xilinx Vivado. The resume reports an **8.03 CGPA through 6th semester** and lists Verilog, TCL, Python, RTL Design, Functional Verification, Pipelining, STA, UART/SPI/I2C, Vivado, WSL and GitHub. fileciteturn0file0L5-L14

## Projects

| Project | Year | Focus | Repository |
|---|---:|---|---|
| 4-Bit Processor | 2026 | RTL design, processor datapath, functional verification | https://github.com/abhishek144-alt/4-bit-Processor-Verilog |
| UART Transceiver | 2026 | FSM TX/RX, 16× oversampling, baud generation, loopback | https://github.com/abhishek144-alt/UART-Transmitter-Reciever |
| 8-Bit ALU | 2026 | Synthesizable Verilog, 9 operations, status flags, testbench | https://github.com/abhishek144-alt/verilog-alu-8bit |

Project details are grounded in the supplied resume and the public repositories. The 8-bit ALU repository is public and documents its Verilog/Vivado/verification flow. fileciteturn0file0L15-L37

## Verified profile data

- **Name:** Abhishek Yadav
- **Location:** Ghaziabad, India
- **Degree:** B.Tech, Electronics & Communication Engineering
- **Class:** 2027
- **CGPA:** 8.03 through 6th semester
- **Debugging:** 12+ RTL/testbench defects documented in the resume
- **GitHub:** 5 public repositories shown on the profile at build time
- **GitHub stars:** 0 at build time; no inflated counters are used in the artwork

The education record and 12+ debugging figure come from the resume. fileciteturn0file0L26-L40 The GitHub repository count is from the public profile checked during packaging.

## Connect

![Connect](assets/connect.svg?v=1)

- **GitHub:** https://github.com/abhishek144-alt
- **LinkedIn:** https://www.linkedin.com/in/abhishek-yadav-1088ba296/
- **Portfolio:** https://abhishek144-alt.github.io/my-portfolio/
- **Email:** mailto:abhishekyaduvanshi144@gmail.com

The social links are intentionally outside the SVG because links embedded inside an SVG rendered as a GitHub README image are not reliably clickable.

## Animation / implementation

- SVG-only animation: CSS + SMIL; no JavaScript, `foreignObject`, network-loaded images or fonts.
- Each SVG embeds the supplied PNG artwork and WOFF2 fonts as data URIs.
- CSS entrances use `animation-fill-mode: both`.
- SMIL begins at `0s`; keyTimes provide readable fallback timing/base states.
- Reduced-motion mode hides the animated layer and exposes a static final composition.
- The interests carousel changes every 4 seconds with segment progress indicators.
- The ID card uses a damped drop/settle followed by a subtle swing and a restrained foil sweep.

## Fonts / licenses

The display font is **Inter Display ExtraBold** and the mono font is **DejaVu Sans Mono**. Both are embedded as WOFF2 data URIs. License notices are included in `LICENSE-Inter-OFL.txt` and `LICENSE-DejaVu-OFL.txt`.

The GitHub mark in `connect.svg` is based on the Simple Icons GitHub SVG source (embedded as path data; no network request). The LinkedIn card uses the standard `in` monogram; portfolio/email use neutral utility glyphs. Simple Icons documents its SVG library and usage in its public repository.

## Preview / verification

Open `preview.html` locally to inspect all five SVGs, including reduced-motion/static variants. The package was checked for:

- valid XML/SVG parsing
- RGBA source portraits and transparent alpha extrema
- no `http://`, `https://`, `url(` external resources or `<script>` tags inside SVG assets
- relative README image paths ending in `?v=1`
- no contribution-city section
- no invented social/repository counts
- complete-head/hand framing in the supplied PNG assets

## Upload exactly these files

Upload the **five files under `assets/`**, plus `README.md` to the root of your profile repository. `preview.html` and the two license files are included for local review/documentation; they are not required for the GitHub profile rendering itself.
<img width="720" height="720" alt="id-dashboard" src="https://github.com/user-attachments/assets/9d9819ab-8a77-47be-adca-23844e6240c0" />
