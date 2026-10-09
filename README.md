# Karthik Uppari — Portfolio

![Portfolio preview](og.png)

Personal portfolio of **Karthik Uppari**, a B.Tech CS (AI/ML) student at NIAT, Hyderabad, building backend systems and AI products. Open to software engineering internships.

## What's inside

- **Hero:** a real-time liquid-metal 3D shape (WebGL raymarching shader) that follows the cursor, with a static gradient fallback when WebGL is unavailable.
- **Selected work:** a pinned horizontal gallery with real screenshots and case-study overlays for CogniSpace, RecoverFlow, Nimbus and Balaji Family Dhaba.
- **Toolkit, Path, How I build, Contact:** skills, education and experience, working style, and ways to reach me.
- **⌘K / Ctrl+K command palette** for jumping around the site.
- **Accessibility and motion:** keyboard navigation, focus-trapped dialogs, a skip link, and full `prefers-reduced-motion` support.
- **Mobile layout:** the gallery stacks vertically and the header gets a frosted bar.

## Projects featured

| Project | What it is | Links |
| --- | --- | --- |
| CogniSpace | Notes, docs and a sprint board with an AI Copilot | [Code](https://github.com/karthik1122-code/cognispace) · [Live](https://cognispace-sigma.vercel.app) |
| RecoverFlow | Policy-first AI revenue recovery for failed Razorpay payments | [Code](https://github.com/karthik1122-code/recoverflow) · [Live](https://recoverflow-ten.vercel.app) |
| Nimbus | AI analytics product site (front end only, simulated data) | [Code](https://github.com/karthik1122-code/nimbus) |
| Balaji Family Dhaba | Responsive digital menu site | [Code](https://github.com/karthik1122-code/balaji-chilukur-family-dhaba) · [Live](https://balaji-chilukur-family-dhaba-fawn.vercel.app) |

## Tech

Plain HTML, CSS and JavaScript in a single file. No framework, no build step and no dependencies. Fonts load from Google Fonts.

## Project structure

```
index.html   the whole site (markup, styles, scripts)
og.png       social share image (1200×630)
assets/      project screenshots used in the Work section
```

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

It is a static site, so any static host works. On Vercel, import the repo, choose the **Other** framework preset, leave build settings empty and deploy.

After deploying, update the site URL in `index.html` (`og:url`, canonical link, `og:image`, `twitter:image` and the JSON-LD `url`) to your real domain so link previews work.

## Contact

[upparikarthik505@gmail.com](mailto:upparikarthik505@gmail.com) · [GitHub](https://github.com/karthik1122-code) · [LinkedIn](https://linkedin.com/in/karthik-uppari-4005a7373)
