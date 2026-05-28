---
name: "A IA Tem Classe Social? - Foucault"
colors:
  primary: "#78d2ff"
  secondary: "#9b78ff"
  tertiary: "#ef71c5"
  neutral: "#a7a0c9"
  surface: "#11101d"
  text: "#f7f4ff"
  text-muted: "#a7a0c9"
  border: "rgba(120, 210, 255, .22)"
  error: "#ef71c5"
  success: "#89f3c1"
  background: "#080711"
  panel: "#11101d"
  soft: "#d8d2ff"
typography:
  display-hero:
    fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: "clamp(3.5rem, 7.8vw, 7.35rem)"
    fontWeight: 900
    lineHeight: ".94"
    letterSpacing: "0"
  section-heading:
    fontFamily: "Inter, ui-sans-serif, system-ui"
    fontSize: "clamp(2rem, 4vw, 4.2rem)"
    fontWeight: 900
    lineHeight: "1.02"
    letterSpacing: "0"
  subheading-large:
    fontFamily: "Inter, ui-sans-serif, system-ui"
    fontSize: "clamp(1.25rem, 2vw, 1.72rem)"
    fontWeight: 800
    lineHeight: "1.2"
    letterSpacing: "0"
  body-large:
    fontFamily: "Inter, ui-sans-serif, system-ui"
    fontSize: "clamp(1.16rem, 2vw, 1.38rem)"
    fontWeight: 400
    lineHeight: "1.72"
    letterSpacing: "0"
  body:
    fontFamily: "Inter, ui-sans-serif, system-ui"
    fontSize: "1.04rem"
    fontWeight: 400
    lineHeight: "1.65"
    letterSpacing: "0"
  body-small:
    fontFamily: "Inter, ui-sans-serif, system-ui"
    fontSize: ".98rem"
    fontWeight: 400
    lineHeight: "1.65"
    letterSpacing: "0"
  label:
    fontFamily: "Inter, ui-sans-serif, system-ui"
    fontSize: "1rem"
    fontWeight: 700
    lineHeight: "1.2"
    letterSpacing: "0"
  code-label:
    fontFamily: "Cascadia Mono, SFMono-Regular, Consolas, monospace"
    fontSize: ".78rem"
    fontWeight: 900
    lineHeight: "1.2"
    letterSpacing: ".16em"
  mono:
    fontFamily: "Cascadia Mono, SFMono-Regular, Consolas, monospace"
    fontSize: "1.15rem"
    fontWeight: 900
    lineHeight: "1.2"
    letterSpacing: "0"
rounded:
  none: "0"
  sm: "6px"
  md: "8px"
  lg: "8px"
  full: "9999px"
spacing:
  xs: ".45rem"
  sm: ".9rem"
  md: "1.2rem"
  lg: "2rem"
  xl: "3.8rem"
  xxl: "6rem"
preview_tokens:
  button_primary_bg: "#78d2ff"
  button_primary_text: "#080711"
  button_primary_border: "#78d2ff"
  button_secondary_bg: "transparent"
  button_secondary_text: "#f7f4ff"
  button_secondary_border: "#78d2ff"
  button_tertiary_text: "#9b78ff"
  surface_bg: "#080711"
  card_bg: "#11101d"
  text: "#f7f4ff"
  text_muted: "#a7a0c9"
  border: "rgba(120, 210, 255, .22)"
  accent: "#78d2ff"
  button_radius: "8px"
  card_radius: "8px"
  input_radius: "8px"
components:
  button-primary:
    bg: "#78d2ff"
    text: "#080711"
    border: "#78d2ff"
    radius: "8px"
    padding: ".7rem 1.15rem"
    font: "1rem Inter weight 800"
  button-secondary:
    bg: "transparent"
    text: "#a8e7ff"
    border: "rgba(120, 210, 255, .52)"
    radius: "8px"
    padding: ".72rem 1.35rem"
    font: "1rem Cascadia Mono weight 800 uppercase"
  card:
    bg: "linear-gradient(180deg, rgba(255, 255, 255, .048), rgba(255, 255, 255, .026))"
    border: "rgba(165, 155, 215, .16)"
    radius: "8px"
    shadow: "0 16px 50px rgba(0, 0, 0, .18)"
    padding: "1.25rem"
  badge-default:
    bg: "rgba(120, 210, 255, .12)"
    text: "#a8e7ff"
    border: "transparent"
    radius: "6px"
    padding: ".28rem .55rem"
    font: ".78rem Cascadia Mono weight 900 uppercase"
  nav-header:
    bg: "rgba(8, 7, 17, .78)"
    text: "#918bad"
    border_bottom: "rgba(255, 255, 255, .1)"
    backdrop_filter: "blur(18px)"
    height: "auto"
---

## 1. Visual Theme & Atmosphere

This page uses a dark, speculative classroom aesthetic: part sociology lecture, part interface for mapping invisible systems of power. The background is nearly black with violet-blue depth, while cyan, violet, pink, and green accents behave like signals moving across a network.

The typography is heavy and declarative. Headlines are large, compressed by tight line-height, and set at high weight to make concepts feel urgent. Monospace labels introduce an analytic, technical voice that connects Foucault's vocabulary to algorithmic systems.

Surfaces are layered but restrained: translucent panels, thin luminous borders, subtle radial fields, and a fixed animated canvas suggest surveillance, relation, and data circulation without turning the page into a dashboard.

**Key Characteristics:**

- Dark immersive academic interface.
- Cyan is the primary signal color.
- Violet and pink create conceptual tension and contrast.
- Cards are low-radius, glass-tinted, and lightly elevated.
- Monospace tags mark concepts, cases, and section numbers.
- Large hero type frames the central question as a provocation.
- Navigation is sticky, blurred, horizontal, and section-driven.
- Content is organized as a lecture path, not as marketing.
- The animated field should feel like a network, not decoration.

## 2. Color Palette & Roles

### Primary

Use `#78d2ff` as the main intellectual signal: section numbers, borders, focus accents, links, tags, and the first stop in the hero gradient. It should read as observation, tracing, and analytic light.

### Brand & Dark

The core background is `#080711`, with `#11101d` as the panel color. Keep the page dark enough for the neon accents to matter. Avoid light sections.

### Accent Colors

Use `#9b78ff` for philosophical abstraction, `#ef71c5` for conflict or critique, and `#89f3c1` for case labels or constructive paths. These colors work best as highlights, not broad fills.

### Interactive

Navigation hover states use translucent cyan fills. Links and pills should not become loud buttons unless the page needs a clear call to action.

### Neutral Scale

Body text sits near `#d7d2ea`. Muted labels use `#a7a0c9` or `#918bad`. The main title and major statements use `#f7f4ff`.

### Surface & Borders

Use thin borders: `rgba(255, 255, 255, .08)` for quiet dividers, `rgba(120, 210, 255, .22)` for conceptual emphasis, and `rgba(120, 210, 255, .52)` for strong frames.

### Shadow Colors

Shadows are black and soft, usually `rgba(0, 0, 0, .18)` to `.38`. Do not use colorful glows broadly; reserve luminous effects for hero emphasis and selected accent cards.

### Color Philosophy

The palette turns Foucault's concepts into a visual system: dark institutional space, cyan surveillance traces, violet abstraction, pink critique, and green openings for debate or activity.

## 3. Typography

Use Inter or the system sans stack for the main text. Favor weight and scale over decorative fonts. The page should feel clear enough for teaching, but intense enough for philosophical provocation.

Use Cascadia Mono or a system monospace for section numbers, eyebrow text, tags, case labels, and small analytic markers. Monospace text should be uppercase when it functions as metadata.

Hero headings should be extremely large, with line-height below `1`. Section headings should remain large but readable, and body copy should keep generous line-height around `1.65` to `1.72`.

## 4. Components

### Hero

The hero is centered, tall, and question-driven. Use an uppercase monospace eyebrow, a large headline with a gradient phrase, a muted explanatory subtitle, and a row of compact pills for metadata.

### Navigation

The nav is sticky with blur, dark translucency, and horizontal scrolling on smaller screens. Links are compact, bold, and section-numbered.

### Cards

Cards use 8px radius, subtle borders, translucent gradients, and restrained shadows. They should hold concepts, comparisons, cases, and activities.

### Quotes

Quotes are framed panels with a cyan left border, glass background, strong type, and generous spacing. Use them for conceptual turning points.

### Concept Rows

Concept rows pair a cyan concept name with explanatory paragraphs. The layout is two-column on desktop and single-column on mobile.

### Activity Cards

Activities use automatic numbering, pink numeric markers, and dense instructional lists. They should feel practical and classroom-ready.

## 5. Layout & Spacing

Constrain main content to `1180px`. Use full-width dark bands only through the natural page background; individual sections should be separated by thin borders, not floating wrappers.

Hero spacing is generous: roughly `8rem` top padding on desktop and `5.5rem` on mobile. Sections use about `3.8rem` vertical padding.

Desktop grids use two columns for cases and comparison cards, three columns for short conceptual prompts, and a split layout for major questions. Mobile collapses everything to one column.

## 6. Content Voice

The tone is critical, clear, and pedagogical. It should sound like a sociology class that takes technology seriously without becoming technical manual prose.

Prefer questions that expose power relations:

- Que tipo de sujeito a IA produz?
- Quem se torna visivel ao poder?
- Que norma passa a operar como verdade?
- Quando a IA diz quem voce e, quem tem o poder de discordar?

Avoid generic technology optimism. The page should examine how systems classify, normalize, govern, and produce subjects.

## 7. Motion & Interaction

The background canvas creates slow-moving points and connecting lines. Keep the motion ambient, subtle, and non-interactive. It should suggest networks of surveillance and relation.

Hover states should be simple: color shift, translucent cyan fill, or border emphasis. Avoid bouncy motion, large transforms, or playful transitions.

Respect reduced-motion preferences if expanding the implementation.

## 8. Accessibility & Responsiveness

Maintain high contrast between text and dark surfaces. Keep body text above 16px equivalent and preserve line-height for long reading.

On mobile, collapse section heads, splits, concept rows, and grids into a single column. Pills may wrap; nav should scroll horizontally.

Do not place explanatory body text over the animated canvas without the dark page background and adequate contrast.

## 9. Agent Prompt Guide

When creating a new page in this design system, build a dark academic single-page lecture experience. Start with a provocative hero question, then guide the reader through numbered sections, concept cards, concrete cases, debate frames, activities, and a strong closing quote.

Use the existing visual vocabulary: cyan as analytic signal, violet/pink as critique, green as case/action marker, Inter for prose, Cascadia Mono for metadata, 8px radii, sticky blurred nav, translucent cards, and a subtle network canvas.

Do not make a marketing landing page. Do not replace the lecture structure with generic cards. Do not use beige academic styling, white document layouts, or decorative illustrations. The subject is power, knowledge, surveillance, and algorithmic classification; the page should make those relations visible.
