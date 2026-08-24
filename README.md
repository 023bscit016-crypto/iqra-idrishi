# Iqra Idrishi — portfolio

Live: **https://abhishekbarali.github.io/iqra-idrishi/**

Portfolio for Iqra Idrishi, a UI/UX designer in Kathmandu. Four projects: Nepdine (restaurant
management system), a movie reservation app, WishKart (greeting cards) and a DualSense product
card study.

Plain HTML, CSS and JavaScript. No build step, no dependencies — open `index.html` and it
works, including offline.

```
index.html          the whole page
assets/site.css     all styling
assets/fonts/       10 self-hosted subsetted woff2 files (~240 KB)
assets/work/        project screenshots
assets/ink/         hand-authored SVG ornament
```

## Editing

Everything you are likely to change is in `index.html`, in reading order:

| To change | Look for |
|---|---|
| The intro line | `class="jo-lede"` |
| A project title or description | `class="piece-title"` / `class="piece-one"` |
| Role, dates, tools | `class="plate"` |
| A case study | `class="fusuma-body"` |
| The About text | `class="hito-prose"` |
| Education and certificates | `class="dl-ledger"` |
| Contact details | `class="contacts"` |

Case-study text is draft copy and carries a visible "Draft copy — edit freely" badge. Delete
the `<p class="draft">` line once it reads the way you want.

## Notes

Project screenshots are Iqra's own design work. All ornament — the ink landscape, the seal,
the wave tile, the tool icons — is authored SVG in this repository. Typefaces are Shippori
Mincho B1, Zen Kaku Gothic New and Yuji Syuku, all under the SIL Open Font License.

The Japanese text is decorative. Every kanji is hidden from screen readers and no information
depends on reading it; the page's meaning is carried entirely by the English.
