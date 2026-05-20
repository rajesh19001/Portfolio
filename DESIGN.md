---
name: Woven Precision
colors:
  surface: '#051424'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#c6c6cd'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#909097'
  outline-variant: '#45464d'
  surface-tint: '#bec6e0'
  primary: '#bec6e0'
  on-primary: '#283044'
  primary-container: '#0f172a'
  on-primary-container: '#798098'
  inverse-primary: '#565e74'
  secondary: '#ffb68e'
  on-secondary: '#532200'
  secondary-container: '#ab4c00'
  on-secondary-container: '#ffe2d5'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#001b21'
  on-tertiary-container: '#008da5'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#ffdbca'
  secondary-fixed-dim: '#ffb68e'
  on-secondary-fixed: '#331200'
  on-secondary-fixed-variant: '#763300'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
typography:
  headline-xl:
    fontFamily: Hanken Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin: 32px
  container-max: 1280px
---

## Brand & Style
The design system embodies the intersection of material science and high-end software engineering. It treats the UI as a digital loom, where "interlaced" structures and "microscopic" precision define the aesthetic. The target audience includes research institutions, tech recruiters, and industrial partners who value the rigor of engineering alongside the tactile nature of textiles.

The style is **Technical Minimalism** with a **Tactile** twist. It avoids unnecessary decoration, instead using structural elements—like borders that mimic fiber threads and grid lines that resemble a loom's warp and weft—to create visual interest. The emotional response is one of calculated innovation: calm, structured, and highly capable.

## Colors
This design system utilizes a deep, nocturnal palette to establish a "developer-hacker" atmosphere, punctuated by high-visibility technical accents.

*   **Primary (Deep Slate):** Used for the foundation of the interface, providing a sense of depth and stability.
*   **Secondary (Warm Copper):** Inspired by conductive fibers and raw industrial materials. Used for primary actions and highlights of craftsmanship.
*   **Tertiary (Technical Cyan):** Represents the "tech" layer—data points, code snippets, and active states.
*   **Neutral (Cool Gray):** Facilitates technical legibility and defines the structural grid without competing with the content.

## Typography
The typographic hierarchy creates a contrast between "Humanist Modernism" and "Machine Logic." 

Headlines use **Hanken Grotesk** for a sharp, contemporary feel that remains approachable. Body copy utilizes **Inter** for maximum readability across dense technical descriptions. All metadata, technical specs, and UI labels are set in **JetBrains Mono**, reinforcing the "textile engineering" and "developer" crossover. Tight letter-spacing on headlines gives a dense, "woven" feel, while labels are slightly tracked out for a blueprint-like clarity.

## Layout & Spacing
The layout is governed by a **Strict 12-Column Fixed Grid** that mirrors the structured nature of woven fabric. 

*   **Warp and Weft Logic:** Elements should align to a baseline grid of 4px. Vertical "thread" lines (1px width) are used to separate major layout sections, creating a literal grid on the screen.
*   **Micro-spacing:** Consistent 16px and 24px gaps ensure technical data doesn't feel cluttered.
*   **Mobile Reflow:** On mobile devices, the 12-column grid collapses to a 4-column structure. The "thread" lines transition from vertical to horizontal to maintain the sense of interlaced sections.

## Elevation & Depth
Depth is achieved through **Tonal Layering and Technical Outlines** rather than traditional shadows. This maintains the "precision" aesthetic.

*   **Base Layer:** Deepest slate (#0F172A).
*   **Surface Layer:** A slightly lighter slate (#1E293B) used for cards and containers.
*   **Outlines:** Instead of shadows, use 1px borders in a low-opacity Cool Gray or Copper to define boundaries. 
*   **Interlaced Depth:** Use semi-transparent overlays with a "micro-mesh" SVG pattern to suggest a physical layer of fabric resting over the UI.

## Shapes
The shape language is primarily **Geometric and Technical**. 

Corners use a "Soft" (0.25rem) radius to prevent the UI from feeling hostile, but the overall impression should be one of "machined edges." In specific technical components (like code blocks or fiber diagrams), use "Sharp" (0px) corners to emphasize the engineering aspect. Hexagonal and diamond shapes can be used sparingly as icons or background motifs to reference molecular structures in textile chemistry.

## Components
Consistent component styling reinforces the engineering narrative:

*   **Buttons:** Rectangular with minimal rounding. Primary buttons use a solid Copper background with dark Slate text. Secondary buttons are "ghost" style with a Cyan outline and JetBrains Mono labels.
*   **Technical Chips:** Use a monospaced font and a "tag" aesthetic. They should look like physical labels found on industrial fabric rolls.
*   **Input Fields:** Bottom-border only, or very thin 1px outlines. Focus states should trigger a subtle Cyan glow that mimics a "scanned" or "active" laser state.
*   **Cards:** Use the Surface Layer color with a 1px border. In the top-right corner of cards, include a small "coordinate" or "serial number" in JetBrains Mono to enhance the technical feel.
*   **Fiber Visualizer:** A custom component representing project categories using interlaced SVG lines that change density based on the "complexity" of the project.