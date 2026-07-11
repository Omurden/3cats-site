# 3Cats Studio — Website Design Brief

**For:** Claude Designer
**Deliverable:** five distinct home-page design directions for the 3Cats Studio marketing site.

---

## 1. Your role
You are a senior brand & web designer. Design the marketing website for **3Cats Studio** from scratch. I want **five genuinely different directions** to choose from — not one design in five colourways. Each should be a complete, buildable home page I can preview and compare side by side.

## 2. The one rule that matters most
**The site is the STUDIO's identity — deliberately independent from the mood of any single game.**

Our first title, *All Time High*, happens to be a dark, moral-descent finance thriller. **The site must NOT inherit that darkness.** The 3Cats brand is **warm, modern, optimistic, and pastel** — a confident contemporary design studio / gallery: colourful, clean, human. The game is featured as *content*, but it does not set the tone.

Palette mood: **pastel + modern.** Soft contemporary colour, generous light, crisp type. "Pastel" must read as *sophisticated and premium* — never babyish or cutesy.

## 3. About 3Cats Studio (all true — use as real copy, no lorem)
- Independent game studio based in **Amsterdam**.
- Makes **premium, story-first, choice-driven fiction** — games with real consequences and an ending you earn. Line in use: *"Premium, story-first games you can actually finish."*
- **A studio, not a single game.** A growing shelf of titles on one shared narrative engine, so each new game ships sooner without losing craft. Each game brings "its own colour to the shelf."
- Small team: **a human producer + an AI production crew under editorial control.** Every part — story, design, music, code — is human-authored under editorial control, created with AI assistance.
- Brand motif: **"the three cats" = three colours** (currently three softened primaries — periwinkle, raspberry, butter — shown as three dots). The *idea of three* is brand equity: keep a three-part colour signature, but you may reinterpret the exact hues and the mark freely.
- Domain **3cats.studio** · contact **info@3cats.studio**.

## 4. What exists today (you are replacing it — start fresh)
The current site is a single self-contained `index.html` on GitHub Pages: an "Amsterdam pastel / De Stijl" look (Mondrian-ish softened primaries, Delft-blue accent, Source Sans 3 + JetBrains Mono). It's fine but I want fresh thinking — **do not copy it.** Treat it only as proof the constraints below are achievable.

## 5. First title to feature (as content, styled to fit YOUR pastel system)
**All Time High** — coming Q4 2026.
- Logline: *"How far would you go in a mania? Every choice has a ledger. Every gain has a price."*
- Hook: A moral-descent thriller told through your phone, your feeds, and a trading terminal. Chase a California fortune one "just one more trade" at a time — through a crypto mania where every gain costs something. Your choices write the ledger. **Six endings.**
- Platforms: Windows, macOS, SteamOS / Deck · 10 languages.
- Primary CTA: **Wishlist on Steam** → `https://store.steampowered.com/app/4944370/`
- The game's own key art may be dark — frame it inside your pastel system (e.g. a contained card) so the *page* stays light and modern. Don't theme the site around it.

## 6. What each home page must contain
- **Header / nav** (sticky): Games · Studio · Press · Contact · light/dark toggle · brand mark (three-colour signature).
- **Hero:** studio positioning — one strong headline + lede. Establishes the brand, not a single game.
- **Games:** a featured *All Time High* card (logline, hook, platforms, wishlist CTA, one or two screenshots) **plus** a "more titles in the works" tile that sells the growing-shelf idea (many colours).
- **Studio / About:** the human-producer + AI-crew-under-editorial-control story; the "endings you earn" craft ethos.
- **Contact:** press & hello → `info@3cats.studio`.
- **Footer:** brand · © 3Cats Studio · 3cats.studio · a short "works of fiction / not financial advice" disclosure.
- (The separate press page only needs to follow the *chosen* direction later — you don't need five press pages.)

## 7. The five directions
Make them **conceptually distinct** — different layout logic, type systems, grid, motion, and use of the three-colour motif — all inside "pastel + modern." Give each a **name and a one-paragraph rationale** (concept, mood, colour logic, type pairing, who it's for).

To force real divergence, spread them across a spectrum like the following — **these are starting lenses, not a checklist. Substitute anything stronger; surprise me:**
1. **Editorial / gallery** — magazine-like, big type, lots of white space, art-directed.
2. **Playful / toy-system** — the three cats as a living, kinetic motif; rounded, friendly.
3. **Swiss / systematic** — strict grid, typographic, precise, restrained pastel accents.
4. **Soft-dimensional** — gentle gradients, soft shadows, glassy depth, tactile pastel surfaces.
5. **Zine / expressive** — bolder, characterful, print-inspired, confident colour blocking.

Each must still feel unmistakably like **one studio**: premium, modern, pastel.

## 8. Design-system requirements (all five)
- **Light and dark** themes, both first-class, with a working toggle.
- **WCAG AA** text contrast — pastels included. Never trade legibility for prettiness.
- **Responsive**, mobile-first; no horizontal page scroll (wide elements scroll inside their own container).
- Tasteful **motion**, with `prefers-reduced-motion` respected.
- A coherent **type scale** and a named **colour-token** system.
- Accessible semantics: real landmarks, `:focus-visible` states, meaningful alt text.

## 9. Technical constraints (match the live deploy model)
- Each direction = **one self-contained `.html` file**, **zero external requests**. Inline all CSS; prefer **pure CSS / SVG** for art and the brand mark; if you use fonts or raster images, embed them as `data:` URIs. It must render offline on **GitHub Pages** with no network.
- No build step, no framework. Vanilla HTML/CSS + minimal vanilla JS (theme toggle / light motion only).
- Name the files `design-1.html` … `design-5.html`; keep each independently openable.

## 10. Deliverables
1. Five self-contained home pages (`design-1.html` … `design-5.html`), each in both light & dark.
2. For each: a short rationale (name, concept, palette logic, type, best-fit use).
3. A brief **comparison summary** — trade-offs, and your top recommendation with why.

## 11. Acceptance checklist
- [ ] Pastel + modern; premium, never cutesy.
- [ ] **Not** themed after the game's darkness; studio-first identity.
- [ ] Five genuinely distinct concepts (not recolours).
- [ ] Real 3Cats copy/facts used (no lorem).
- [ ] Three-colour brand signature present (freely reinterpreted).
- [ ] Light + dark · WCAG AA · responsive · reduced-motion.
- [ ] Each is one self-contained HTML file with zero external requests.
