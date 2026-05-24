# 📐 Architecture

> Full reference → [ARCHITECTURE.md](https://github.com/KhusniddinIskandarov/plants-website/blob/main/docs/ARCHITECTURE.md)

**v1.1.0** — Production ready. Live on Vercel, Netlify and GitHub Pages.

---

## 🗂️ Structure

```text
src/
  assets/images/   — optimized WebP assets
  components/      — footer, navigation, UI components
  layouts/         — MainLayout, Header, Footer
  modules/         — scroll, navbar, swiper behavior
  pages/           — sections: Hero, Services, About, Popular, Reviews
  styles/          — Tailwind entry + custom styles
  main.js          — app entry point
```

---

## 🔖 Version History

| Version | Phase                       | Highlights                                       |
| ------- | --------------------------- | ------------------------------------------------ |
| v1.1.0  | Performance & Accessibility | Lighthouse 100, local fonts, srcset, aria-labels |
| v1.0.0  | Production                  | Deployment, WebP images, SEO finalization        |
| v0.4.0  | UX                          | Scroll animations, swiper, navbar behavior       |
| v0.3.0  | UI                          | All sections, footer components, styles          |
| v0.2.0  | Architecture                | Layout system, components, entry point           |
| v0.1.0  | Foundation                  | Vite, TailwindCSS, ESLint, Husky                 |

---

> _"Build simple first, structure later based on real needs."_
