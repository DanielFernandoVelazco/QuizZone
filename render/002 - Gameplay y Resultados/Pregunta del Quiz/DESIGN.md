---
name: Electric Arcade
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#c3c0ff'
  on-secondary: '#1d00a5'
  secondary-container: '#3626ce'
  on-secondary-container: '#b3b1ff'
  tertiary: '#ffb95f'
  on-tertiary: '#472a00'
  tertiary-container: '#ca8100'
  on-tertiary-container: '#3e2400'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#e2dfff'
  secondary-fixed-dim: '#c3c0ff'
  on-secondary-fixed: '#0f0069'
  on-secondary-fixed-variant: '#3323cc'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '800'
    lineHeight: 4rem
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.5rem
    fontWeight: '800'
    lineHeight: 3rem
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '700'
    lineHeight: 2rem
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '600'
    lineHeight: 1.5rem
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '700'
    lineHeight: 1rem
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system delivers an electric, high-stakes gamified experience balanced by modern SaaS precision. It targets competitive trivia enthusiasts, remote teams, and classroom learners who crave momentum, agency, and instant visual validation. 

The emotional arc is built around anticipation, swift decision-making, and triumphant feedback loops:
- **Kinetic Energy:** Pulsing countdowns, dynamic progress states, and vibrant feedback bursts sustain user engagement.
- **Legible Competition:** Clear visual hierarchies ensure leaderboard rankings, streaks, and score updates read instantly on any device.
- **Elevated Polish:** Clean structural geometry keeps the interface professional and focused, avoiding toy-like clutter while retaining playful arcade urgency.

## Colors

The palette employs deep slate canvases to make vibrant indigo bases, bright amber streaks, and contextual status colors pop with luminous intensity.

- **Primary (`#6366F1` / Electric Indigo):** Primary buttons, interactive answer bases, active selection strokes, and focal UI highlights.
- **Secondary (`#4F46E5` / Deep Violet):** Container fills, pressed interaction states, and structural gradient overlays.
- **Tertiary (`#F59E0B` / Radiant Amber):** Streaks, XP multipliers, score counters, star badges, and dynamic time-warning states.
- **Neutral (`#0F172A` / Obsidian Slate):** Background canvas foundation paired with `#1E293B` (Surface Layer 1) and `#334155` (Surface Layer 2) to build rich optical depth.
- **Success (`#10B981` / Emerald Green):** Correct answer reveals, positive delta indicators, and achievement triggers.
- **Destructive / Error (`#EF4444` / Crimson Coral):** Incorrect choices, streak losses, expired timers, and form validation errors.

Use high-contrast borders and low-opacity color washes (`primary/15`, `success/15`, `tertiary/15`) to indicate active, hover, or pressed states without creating visual noise.

## Typography

The type system relies on **Plus Jakarta Sans** across all levels to balance geometric punch with crisp, open counterforms.

- **Numerics & Scores:** Timer countdowns, point tallies, and rank badges utilize tabular figures (`font-variant-numeric: tabular-nums`) with `800` (ExtraBold) weight to prevent layout jitter during live counter animations.
- **Headlines:** Question prompts and leaderboard headers use `700` or `800` weights with tightened letter tracking (`-0.02em`) to maximize punch and readability.
- **Labels & Badges:** Gamified badges, metadata, and status tags use `label-sm` with full uppercase styling and expanded tracking (`0.05em`) for legibility against saturated accents.

## Layout & Spacing

The layout is built around a responsive 12-column fluid grid for dashboard and administrative views, condensing into a focused, single-column vertical track (max-width `768px`) during live gameplay modes.

- **Desktop (1024px+):** 12-column grid, `2rem` outer margin, `1.5rem` gutter. Admin dashboards and multi-column leaderboard grids leverage full screen widths.
- **Tablet (768px - 1023px):** 8-column grid, `1.5rem` outer margin, `1rem` gutter. Dynamic sidebars collapse into persistent bottom bars or slide-over drawer sheets.
- **Mobile (< 768px):** 4-column layout, `1rem` outer margin, `1rem` gutter. Gameplay mechanics shift to full-width card stacks with sticky bottom triggers.

Vertical rhythm is governed by a strict 8pt scale: micro-spacers (`space-xs`, `space-sm`) define pill badges and button insets, while macro-spacers (`space-lg`, `space-xl`) separate question prompts from answer matrices.

## Elevation & Depth

Visual hierarchy is communicated through luminous surface tiers combined with soft, colored glows rather than traditional murky dropshadows:

- **Level 0 (Canvas):** Pure `#0F172A` void.
- **Level 1 (Card/Container Surfaces):** Solid `#1E293B` accented with a `1px` translucent border (`rgba(255, 255, 255, 0.08)`).
- **Level 2 (Interactive Floating Modules):** `#334155` with `0 8px 24px -4px rgba(0, 0, 0, 0.4)` and a `1px` high-contrast edge highlight (`rgba(255, 255, 255, 0.12)`).
- **Gamified Glow (Pulsing States):** Dynamic interactive elements use soft ambient outer halos matching the state's hue:
  - Default Indigo Glow: `0 0 20px -3px rgba(99, 102, 241, 0.45)`
  - Streak Amber Glow: `0 0 20px -3px rgba(245, 158, 11, 0.45)`
  - Success Green Glow: `0 0 24px -2px rgba(16, 185, 129, 0.5)`
  - Danger Coral Glow: `0 0 24px -2px rgba(239, 68, 68, 0.5)`

## Shapes

The interface embraces a balanced curvature:
- **Base Components (Cards, Panels, Modals):** Medium curvature (`0.5rem` / `8px`) provides solid structural framing without feeling boxy.
- **Answer Selection Buttons & Content Cards:** Use `rounded-lg` (`1rem` / `16px`) to invite touch interactions.
- **Interactive Badges, Pills, and Progress Tracks:** Completely rounded (`9999px` capsule style) to reinforce game token aesthetics.

## Components

### Answer Choice Buttons
- Large, tactile horizontal cards featuring a prominent left-aligned keycap indicator (A, B, C, D) wrapped in a solid container (`#0F172A`).
- **Resting:** `#1E293B` background, `2px` border in `rgba(255, 255, 255, 0.08)`, subtle scale-up on hover (`scale: 1.015`).
- **Selected:** Border transforms to `#6366F1` with an indigo ambient glow.
- **Correct State:** `#10B981` border with emerald wash (`#10B981` at 15% opacity), accompanied by an animated checkmark icon.
- **Incorrect State:** `#EF4444` border with crimson wash (`#EF4444` at 15% opacity) accompanied by an animated shake trigger.

### Timer Bars & Countdowns
- Full-width linear capsule bars (`roundedness: 3`, height: `8px` or `12px`) with smooth CSS ease transforms.
- Dynamic color transitions: fills transition from `#6366F1` (normal) down to `#F59E0B` (last 50%), switching to `#EF4444` with a synchronized pulse animation in the final 20% countdown.

### Streak & Gamification Badges
- Compact pill-shaped containers with high-contrast borders and saturated gradient backgrounds.
- Streak counters feature fire/multiplier icons alongside tabular numbers, highlighted by an outer tertiary amber glow.

### Leaderboards
- High-density ranked list items with contrasting top-3 podium treatments:
  - 1st Place: `#F59E0B` metallic gold edge highlight and star crest.
  - 2nd Place: `#94A3B8` silver edge highlight.
  - 3rd Place: `#B45309` bronze edge highlight.
- Current user pinned row sticks to the bottom viewport with a distinct Indigo halo when outside visible ranking bounds.

### Admin Data Tables
- Clean tabular layouts framed in `#1E293B` with muted column borders (`#334155`).
- Sticky table headers with `label-sm` uppercase text.
- Inline status tags (Draft, Active, Archived) rendered as soft rounded pills (`roundedness: 3`) with contextual text and subtle background washes.