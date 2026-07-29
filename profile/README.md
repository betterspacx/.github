<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/betterspacx/.github/refs/heads/main/desi.jpg">
  <img alt="BetterFlow" src="https://raw.githubusercontent.com/betterspacx/.github/refs/heads/main/desi.jpg">
</picture>

# BetterFlow

**Browser-based screenshot editor & screen recorder.** Design beautiful screenshots with browser mockups, 3D transforms, animations, and export to PNG, JPG, MP4, WebM, or GIF — all in your browser.

[Try the Studio](https://app.betterflow.site) · [Landing Site](https://betterflow.site)

---

## Projects

| Directory | What | Stack |
|-----------|------|-------|
| [`app/`](app/) | Screenshot editor — the main product | Next.js 16, React 19, Tailwind CSS 4 |
| [`website/`](website/) | Marketing landing page | Astro 5, Tailwind CSS 4 |

**`app/`** — Single-page editor at `app.betterflow.site`. Full canvas editing, timeline animations, cloud export, and Chrome extension for screen recording. Open source under Apache 2.0.

**`website/`** — Landing site at `betterflow.site`. Static site with pricing, features, changelog, and mobile showcase.

---

## Getting Started

```sh
# App (editor)
cd app
pnpm install
pnpm dev

# Website (landing)
cd website
pnpm install
pnpm dev
```

See the [app guide](app/AGENTS.md) and [website guide](website/AGENTS.md) for full commands and conventions.

---

## License

Apache 2.0 — see [`app/LICENSE`](app/LICENSE).
