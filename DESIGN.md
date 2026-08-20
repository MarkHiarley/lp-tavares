---
name: Tavares Odontologia

description: Editorial clinical atlas for human, precise dental care.
colors:
  ink: "#122b27"
  ink-soft: "#1c3933"
  paper: "#f3f0e8"
  paper-deep: "#e5e0d4"
  white: "#fbfaf5"
  gold: "#c7a45e"
  gold-soft: "#dcc78e"
  coral: "#e86f54"
  coral-dark: "#b94b38"
typography:
  display:
    fontFamily: "Bricolage Grotesque, sans-serif"
    fontSize: "clamp(3.5rem, 8vw, 7.5rem)"
    fontWeight: 500
    lineHeight: 0.95
    letterSpacing: "-0.045em"
  body:
    fontFamily: "DM Sans, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
rounded:
  none: "0"
  circle: "50%"
spacing:
  section: "clamp(5.5rem, 11vw, 11rem)"
  page: "clamp(1.25rem, 4vw, 4.5rem)"
components:
  button-primary:
    backgroundColor: "{colors.coral}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "1rem 1.2rem"
  button-secondary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.none}"
    padding: "1rem 1.2rem"
---

# Design System: Tavares Odontologia

## Overview

**Creative North Star: "O Atlas do Sorriso"**

A Tavares Odontologia is presented as a calm clinical atlas: precise enough to communicate expertise, warm enough to make a first conversation feel easy. The page uses a midnight-green field, paper-like surfaces, registration lines, gold annotations and coral actions. Real clinic photography is treated as documentary evidence, not decoration.

The visual language is editorial and flat by default. Large typographic statements, ruled lists and cropped portraits create a sense of considered care without relying on generic healthcare gradients, icon tiles or testimonial claims. The first screen makes the clinic, location, promise and booking action immediately legible.

**Key Characteristics:**
- Midnight-green atlas field with paper-white reading surfaces.
- Gold registration marks and coral action moments.
- Full-bleed, documentary clinic photography with annotation labels.
- Zero-radius geometry, thin rules and generous editorial spacing.

## Colors

The palette balances a grounded clinical green with paper neutrals and two expressive accents: gold for trust and coral for action.

### Primary
- **Midnight Ink** (#122b27): Hero, footer and high-contrast action surfaces.
- **Deep Clinic Green** (#1c3933): Secondary dark sections and specialty list.

### Secondary
- **Archive Gold** (#c7a45e): Registration marks, small labels and quiet emphasis.
- **Soft Gold** (#dcc78e): Dark-surface secondary text and fine detail.
- **Coral Action** (#e86f54): Primary calls to action and directional markers.
- **Deep Coral** (#b94b38): Labels and links on paper surfaces.

### Neutral
- **Paper** (#f3f0e8): Main reading surface.
- **Paper Deep** (#e5e0d4): Image fallback and tonal separation.
- **Clinic White** (#fbfaf5): Elevated paper surface and photographic captions.

### Named Rules
**The Coral Coordinates Rule.** Coral marks the next human action; it does not decorate every surface.

## Typography

**Display Font:** Bricolage Grotesque (with sans-serif fallback)
**Body Font:** DM Sans (with sans-serif fallback)
**Label/Mono Font:** DM Sans in tracked uppercase

**Character:** Bricolage Grotesque gives the clinic a distinctive, slightly irregular editorial voice while DM Sans keeps clinical information clear and approachable.

### Hierarchy
- **Display** (500, `clamp(3.5rem, 8vw, 7.5rem)`, `.95): Hero mission and major statements.
- **Headline** (500, `clamp(2.75rem, 5.6vw, 6rem)`, `.95): Section statements with short, assertive measure.
- **Title** (500, `clamp(1.45rem, 2.5vw, 2.1rem)`, `.95): Specialist names and specialty rows.
- **Body** (400, `16px`, `1.55`, max 70ch): Institutional copy and service descriptions.
- **Label** (400, `.68rem`, `.14em` tracking, uppercase): Location, section index, image annotations and contact metadata.

### Named Rules
**The Short Sentence Rule.** Display type carries one clear thought; detail stays in DM Sans below it.

## Layout

The page uses a 12-column editorial grid with a fluid maximum width of 1240px and page padding from 1.25rem to 4.5rem. Sections alternate between dark ink, paper, white and coral fields to pace the scroll. The hero pairs an oversized statement with a layered two-image study. Specialty rows remain linear and scannable; the team uses a portrait-led asymmetric grid.

At 900px, navigation collapses into a menu and multi-column areas simplify. At 640px, all content becomes one or two columns, display type scales with viewport width, and secondary specialty descriptions hide in favor of fast scanning.

## Elevation & Depth

The system is flat by default. Depth comes from tonal surface changes, image cropping, overlapping image frames and thin registration lines rather than generic shadows. Hover states use small transforms and color changes; they do not lift entire cards into floating panels.

### Named Rules
**The Flat Evidence Rule.** Photography and ruled structure create depth; no decorative shadow should compete with a patient's story.

## Shapes

The interface is mostly square and editorial: buttons, image frames and containers use zero-radius corners. Circular geometry is reserved for atlas orbits and location marks. Borders are thin and low-contrast except for purposeful gold or coral emphasis.

## Components

### Buttons
- **Shape:** Square, direct and compact (`0` radius).
- **Primary:** Coral background, ink text, `1rem 1.2rem` padding.
- **Hover / Focus:** White background on dark surfaces, visible coral focus outline, and a small upward translate.
- **Secondary:** Ink background with paper text for the coral contact section.

### Cards / Containers
- **Corner Style:** Square containers; no nested rounded cards.
- **Background:** Paper, white or dark tonal fields.
- **Shadow Strategy:** No resting shadow; image overlap and borders provide separation.
- **Border:** One-pixel rules in ink, gold or low-opacity paper.
- **Internal Padding:** Section rhythm is generous; rows use compact vertical padding.

### Navigation
- **Style:** Fixed midnight-green bar with a small reversed logo and quiet tracked links.
- **Default / Hover:** Muted paper links brighten on hover; the gold-outlined booking action is always visible on desktop.
- **Mobile:** A native button reveals a full-width stacked menu and keeps booking prominent.

### Atlas Image Study
- **Style:** Real clinic photography sits inside thin framed rectangles with small archival captions.
- **Behavior:** Images crop with `object-fit: cover`; hover uses a restrained scale for tactility.

## Do's and Don'ts

### Do:
- **Do** let coral identify the next action.
- **Do** pair real photography with short, factual captions.
- **Do** preserve the square, ruled editorial grammar across new sections.
- **Do** keep every claim grounded in the clinic's supplied content.
- **Do** maintain keyboard focus, readable contrast and comfortable touch targets.

### Don't:
- **Don't** introduce generic blue healthcare gradients or glossy glass panels.
- **Don't** turn every section into equal-sized icon cards.
- **Don't** fabricate testimonials, clinical outcomes, prices or schedules.
- **Don't** use rounded pills as the default control shape.
