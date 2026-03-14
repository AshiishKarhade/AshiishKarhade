# CLAUDE.md — AI Assistant Guide for AshiishKarhade/AshiishKarhade

## What This Repository Is

This is a GitHub **special profile repository**. The `README.md` file automatically renders
on [https://github.com/AshiishKarhade](https://github.com/AshiishKarhade) as the public profile page.

**Repository owner**: Ashish Karhade
**Role**: Software Development Engineer at UBS
**Stack**: Java, Spring Boot (backend) · React.js (frontend) · DevOps/Cloud (Azure, Docker, Kubernetes)

There are **no source code files** — only `README.md` and this `CLAUDE.md`.

---

## Development Workflow

1. Edit `README.md` (the only content file)
2. Commit with a descriptive message
3. Push to `master` branch — profile updates are **live immediately** after push

```bash
git add README.md
git commit -m "your message"
git push origin master
```

> For AI-assisted development sessions, work on a feature branch and open a PR to master.

---

## File Structure

```
AshiishKarhade/
├── README.md     # GitHub profile page — rendered at github.com/AshiishKarhade
└── CLAUDE.md     # This file — AI assistant guide
```

---

## Key Conventions

- **Pure Markdown + inline HTML** — no JSX, no build step, no package.json
- **Centered sections** use `<div align="center">...</div>`
- **Vertical spacing** uses `<br/>` tags between sections
- **Reference-style links** are defined at the bottom of `README.md` for clean source reading
- **Icons** use `cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/...` (reliable CDN, not raw GitHub blob URLs)
- **Badges** use `shields.io` with `style=for-the-badge`

---

## External Services & APIs

| Service | Purpose | Base URL |
|---------|---------|----------|
| **komarev.com/ghpvc** | Profile view counter | `https://komarev.com/ghpvc/?username=AshiishKarhade&color=green` |
| **github-readme-stats** | GitHub stats card + top languages | `https://github-readme-stats-sigma-five.vercel.app/api` |
| **readme-typing-svg** | Animated typing headline | `https://readme-typing-svg.demolab.com` |
| **github-readme-streak-stats** | Commit streak display | `https://github-readme-streak-stats.herokuapp.com` |
| **github-profile-trophy** | Trophy showcase | `https://github-profile-trophy.vercel.app` |
| **github-readme-activity-graph** | Contribution activity graph | `https://github-readme-activity-graph.vercel.app/graph` |
| **shields.io** | Social + skill badges | `https://img.shields.io/badge/` |

All services are free and require no API keys — they work via public GitHub username.

---

## How to Add or Update Skills

Skills are rendered as `shields.io` badges grouped by category.

**Badge format:**
```
![Name](https://img.shields.io/badge/Name-HEX_COLOR?style=for-the-badge&logo=LOGO_SLUG&logoColor=white)
```

- Find logo slugs at [simpleicons.org](https://simpleicons.org)
- Use technology-native colors (e.g., Java → `#ED8B00`, Docker → `#2496ED`)
- Place under the appropriate category heading in the Skills section

**Example — adding TypeScript:**
```markdown
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
```

---

## How to Update Social Links

Reference-style links are defined at the **bottom** of `README.md`:

```markdown
[website]: https://ashiishkarhade.onrender.com
[twitter]: https://twitter.com/ashiishkarhade
[linkedin]: https://linkedin.com/in/ashiishkarhade
[instagram]: https://instagram.com/ashiishkarhade
[medium]: https://medium.com/@ashiishkarhade
```

Update the URL next to the label — all shields badges using `[label]` references auto-resolve.

---

## How to Update the Typing Animation

The animated header uses `readme-typing-svg`. Edit the `lines=` parameter (URL-encoded):

```
https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=2F80ED&center=true&vCenter=true&width=600&lines=LINE1;LINE2;LINE3
```

- Separate lines with `;`
- URL-encode special chars: space → `+`, `@` → `%40`, `|` → `%7C`, emoji → percent-encoded Unicode
- Use [URL Encoder](https://www.urlencoder.org/) if needed

---

## README Section Order

1. **Header** — animated typing SVG (centered)
2. **Badges** — profile views + Twitter follow (centered)
3. **About Me** — bullet-point summary
4. **GitHub Stats** — 3 cards side by side (Stats, Streak, Top Languages)
5. **Trophies** — GitHub profile trophies row
6. **Skills** — categorized shields.io badges
7. **Activity Graph** — contribution heatmap
8. **Connect** — social link badges

---

## Top Portfolio Inspirations

These repositories were studied to inform the design of this profile:

| GitHub | Key contribution |
|--------|----------------|
| `emmabostian/developer-portfolios` | Curated best-practice patterns |
| `DenverCoder1` | Streak stats + readme-typing-svg services |
| `ryo-ma/github-profile-trophy` | Trophy widget used in this profile |
| `TakshPatel02/TakshPatel-Portfolio` | GSAP animations, categorized skills |
| `adrianhajdin` | 3D portfolio concepts (future standalone site inspiration) |
| `said7388/developer-portfolio` | Next.js template (future standalone site upgrade) |

---

## Rules for AI Assistants

- **Never add** `package.json`, `node_modules`, or any source code files
- **Never push** profile README changes to any branch other than `master`
- **Always use** `cdn.jsdelivr.net` for devicons, not raw GitHub blob URLs
- **Always center** major sections with `<div align="center">`
- **Test** rendered output at [https://github.com/AshiishKarhade](https://github.com/AshiishKarhade) after pushing
- **Keep** the reference-style link block at the very bottom of `README.md`
