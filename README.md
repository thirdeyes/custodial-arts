# Custodial Arts

*We do the dirty work.*

Custodial Arts is a consultancy for operations, tools, and technology at digital businesses. It's also a source of honest advice about which AI promises are ready to deliver business results and which aren't.

The name comes from the joke about calling a janitor "an expert in the custodial arts." The joke works because it's true: the essential work is the unglamorous work, and the person doing it usually sees the building more clearly than anyone. We give that work the fancy name it deserves, and we give the results no embellishment at all.

---

## What's in this repo

| Path | What it is |
|---|---|
| [`brand/manifesto.md`](brand/manifesto.md) | Why we exist and what we believe. Start here. |
| [`brand/voice.md`](brand/voice.md) | How we write: tone, words we use and avoid, where the joke stops |
| [`services/services.md`](services/services.md) | The five services, what each delivers, and how each is measured |
| [`content/linkedin.md`](content/linkedin.md) | Content playbook, recurring series, and ready-to-adapt starter posts |
| [`business/word-of-mouth.md`](business/word-of-mouth.md) | How to make referrals deliberate, including the forwardable paragraph |
| [`business/launch-checklist.md`](business/launch-checklist.md) | Name, legal, paperwork, and presence setup |
| [`site/index.html`](site/index.html) | One-page website. A single file with no build step. |

## The short version

**What we do:** Clean up operations, tools, and technology. We untangle processes and handoffs, rationalize the tool stack, and give honest AI readiness assessments.

**How we're different:**
- **Measure before we mop.** Baseline first, results reported against it, misses included.
- **Say what it is.** No overstating, no overselling.
- **Your building, your rules.** We adapt to how you work, not the other way around.
- **Leave it cleaner, and leave.** No dependency. We hand over the keys.

**How we grow:** Word of mouth, plus useful and slightly tongue-in-cheek content on LinkedIn and other professional channels. No ad campaigns.

## Deploying the site

`site/index.html` is self-contained. The only external request is Google Fonts, and system fonts take over if it fails. Any static host works:

- **GitHub Pages:** Settings → Pages → deploy from branch, folder `/site` (or move the file to `/docs`)
- **Vercel:** works with the project's Root Directory left blank. `vercel.json` serves `site/index.html` at `/`, and `.vercelignore` keeps the business docs out of the deployment.
- **Netlify:** point the project at the `site` directory with no build command

Before going live, replace the two `TODO` placeholders in the contact section with the real email address and LinkedIn page URL.

## Brand quick reference

| Token | Light | Dark | Use |
|---|---|---|---|
| Paper | `#F6F2EA` | `#151412` | Background |
| Ink | `#1B1A17` | `#EDE7DB` | Text |
| Caution | `#F2C230` | `#F2C230` | Sparingly: the "wet floor sign" accent |
| Steel | `#5B6770` | `#95A1AA` | Labels, metadata |

**Type:** Cormorant Garamond (the "fancy") · IBM Plex Sans (the work) · IBM Plex Mono (the work-order labels)

The visual idea mirrors the name: gallery and museum elegance applied to janitorial subject matter, with one caution-sign yellow to remind everyone that real work is happening.
