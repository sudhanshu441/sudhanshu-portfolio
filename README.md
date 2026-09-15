# Sudhanshu — Portfolio Prototype

Visual prototypes (not an implementation) of a personal portfolio site for a
PHP / Laravel backend engineer. Two directions live on one canvas, each on its
own page.

## Page 1 — SnapFolio style (current direction)

A rebuild of the [SnapFolio](https://bootstrapmade.com/snapfolio-bootstrap-portfolio-template/)
template by BootstrapMade, using values lifted from its own `assets/css/main.css`
rather than from screenshots.

| Token | Value |
| --- | --- |
| Background | `#1f1f1f` (`.light-background` sections `#2c2c2c`) |
| Surface | `#232323` (`#323232` on light sections) |
| Text / headings | `#ffffff` |
| Accent | `#ececec` |
| Contrast (text on accent) | `#310606` |
| Sidebar | `#1b1b1b`, 300px fixed, 20px radius card |

Fonts: Roboto (body), Ubuntu (headings), Nunito (nav) — the template's own
stacks. Section padding 60px; section titles carry 50×2px accent rules.

Bootstrap Icons can't load in the preview, so the icons are matching inline SVGs.

| File | Screen | Frame |
| --- | --- | --- |
| `Main.dc.html` | Home — hero, about, stats, skills, resume, portfolio, services, testimonials, contact | 1440 × 8800 |
| `Detail.dc.html` | Portfolio details page | 1440 × 2600 |
| `Phone.dc.html` | Home, mobile | 390 × 7600 |

### Licence

SnapFolio is a BootstrapMade template. The free licence requires the
"Designed by BootstrapMade" footer credit, which the mockups keep. The pro
licence allows removing it. See https://bootstrapmade.com/license/

## Page 2 — Editorial (earlier direction)

Light editorial: warm off-white paper, deep warm ink, one clay accent,
Instrument Serif + Schibsted Grotesk + JetBrains Mono. Kept for comparison.

| File | Screen | Frame |
| --- | --- | --- |
| `EditorialHome.dc.html` | Home | 1440 × 5600 |
| `EditorialCase.dc.html` | Case study | 1440 × 3800 |
| `EditorialPhone.dc.html` | Home, mobile | 390 × 5400 |

## Placeholders

Anything in `[square brackets]` carries a dotted underline and is waiting on
real details: surname, companies, dates, city, email, phone, photos,
screenshots and every number. Project write-ups and the skills list are
drafted examples for a backend role, not real work. Skill-bar percentages are
deliberately left as `[00%]`.

## Layout

`canvas.json` holds artboard positions, the two pages and the sticky notes.
