# CONSERVATION - CONSERVE THE ROTY BROI

## About This Repo

`conservation` is the official frozen/static web page for **CONSERVATION — Conserve the ROTY BROI**, an art-and-culture initiative that extends the ROTY BROI NFT project into the physical world. This repository exists to document the project story, showcase the collaborators and artworks, and provide a stable public landing page that can be deployed reliably for years.

### Purpose & Scope

- Preserve and communicate the CONSERVATION project narrative and public references.
- Showcase collaboration between Web3-native creators and traditional/physical artists.
- Keep the website intentionally **static** to reduce operational risk and long-term maintenance overhead.

### Blockchain

- Primary chain: **Ethereum**
- Compatibility: **EVM-compatible**, with a migration-friendly posture for other EVM chains.

### Technology

- **Static HTML / CSS / Vanilla JavaScript**
- **Content-hashed** assets for immutable caching
- Deployed as **static hosting on Vercel**
- External scripts (if any) are intended to be pinned and documented

### How We Maintain Quality

- We keep this repo “frozen output”: no package manager and no build system by design.
- We prioritize stability (no breaking changes, no dependency drift) and document maintenance actions under `EVERGREENING/completion-log-*.md`.
- We periodically verify deployment health, cache headers, and the validity of external links.

### Project Story (Context)

In early 2022, the ROTY BROI project gained significant exposure and was invited to Bali for an exhibition. About a month before the exhibition, the core team split and the project continued with only two remaining roles: development and project management.

During the Bali residency, we met many local, traditional physical artists—painters, sculptors, and other creators—who were curious about Web3 culture and how NFTs can be used for arts and cultural preservation.

After the exhibition, we continued the residency and built **CONSERVATION** together with several Balinese physical artists (credited on the website), led by our project manager. The purpose was to conserve and extend ROTY BROI through real-world artistic collaboration.

This became a key milestone for Prof. NOTA’s work across both the “0101 Universe” and the physical reality universe—opening a long-running bridge between the two.

---

---

## Maintenance by Prof. NOTA Evergreen Standard

This repository is intentionally **frozen** and designed to remain evergreen
while staying production-safe.

No build system, package manager, or runtime dependency is used by design.

### Runtime

- Runtime: **None (static HTML / CSS / Vanilla JS)**
- Build step: **None**
- Package manager: **None**
- Dependency model:
  - External scripts via CDN only (documented and pinned)
- Deploy target:
  - **Vercel (static hosting)**
  - ~~Netlify~~
  - ~~Self-hosted / Docker~~
  - ~~Other platform~~

### Asset & Cache Policy (Frozen)

- All JS and CSS files are **content-hashed**
- Static assets are served with:
  - `Cache-Control: public, max-age=31536000, immutable`
- HTML files are served with revalidation enabled
- No further JS/CSS changes are expected

### Maintenance Policy

There are **no routine dependency updates**.

Recommended periodic checks (manual, optional):

1. Verify deployment health:
   - No 404 errors
   - No mixed-content warnings
2. Verify headers:
   - Cache-Control
   - Security headers (nosniff, referrer-policy, etc.)
3. Verify external services:
   - Analytics IDs still active
   - CDN links still valid

### Change Policy

- JS/CSS changes: **Not allowed**
- Asset updates: **Not allowed**
- Content updates:
  - HTML-only
  - Must not introduce new runtime dependencies

Any future functional change must be done in a **new repository or versioned successor**.

---

---

> Shush, I'm playing, learning, and working. 🤫 🤫 🤫 🤫

- 😄 &nbsp; I'm [Prof. NOTA](https://nota.endhonesa.com/), per/pers.
- 🤙 &nbsp; I’m currently playing.
- 🌱 &nbsp; I’m currently learning.
- 🔭 &nbsp; I’m currently working.
- 👯 &nbsp; I’m not looking to collaborate.
- 🤔 &nbsp; I’m not looking for help.
- 💬 &nbsp; Don't ask me about that.
- 📫 &nbsp; Don't try to reach me.
- ⚡ &nbsp; Fun fact: [The King's NFTs project](https://docs.endhonesa.com/)

> Here are some ideas to get you started:

A derivative project which give birth to an NFT collection, named "Conserve ROTY BROI" that contains physical artworks by various traditional artists in BALI island to Conserve some of The ROTY BROI NFTs' artwork assets.

> Regards
>
> [Prof. NOTA](https://nota.endhonesa.com/)
>
> [init.endhonesa.com](https://init.endhonesa.com/)
