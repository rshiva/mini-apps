---
name: Prompt Bar Builder
description: A Nerd Font specimen sheet for your own Starship prompt, set in Catppuccin ink.
colors:
  crust-ground: "#11111b"
  mantle-sheet: "#181825"
  base-raise: "#1e1e2e"
  surface-rule: "#313244"
  surface-rule-strong: "#45475a"
  mocha-ink: "#cdd6f4"
  mocha-ink-soft: "#bac2de"
  mocha-ink-muted: "#a6adc8"
  peach-mark: "#fab387"
  mark-ink: "#11111b"
  green-ok: "#a6e3a1"
  yellow-warn: "#f9e2af"
  red-bad: "#f38ba8"
  terminal-base: "#1e1e2e"
  latte-ground: "#dce0e8"
  latte-sheet: "#eff1f5"
  latte-raise: "#e6e9ef"
  latte-rule: "#ccd0da"
  latte-rule-strong: "#acb0be"
  latte-ink: "#4c4f69"
  latte-ink-soft: "#5c5f77"
  latte-ink-muted: "#626579"
  latte-peach-mark: "#fe640b"
  latte-mark-text: "#b54708"
  latte-ok: "#2b7a1e"
  latte-warn: "#8a5a00"
  latte-bad: "#b8254a"
  segment-yellow: "#f9e2af"
  segment-teal: "#94e2d5"
  segment-sky: "#89dceb"
  segment-blue: "#89b4fa"
  segment-mauve: "#cba6f7"
  segment-pink: "#f5c2e7"
typography:
  headline:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "19px"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "-0.01em"
  group-title:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 600
    lineHeight: 1.2
  body:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
  body-small:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "13.5px"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "13.5px"
    fontWeight: 600
    lineHeight: 1.2
  control:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1
  terminal:
    fontFamily: "PBB Symbols, JetBrains Mono, ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "13.5px"
    fontWeight: 400
    lineHeight: 1.7
  code:
    fontFamily: "JetBrains Mono, ui-monospace, monospace"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.55
  codepoint:
    fontFamily: "PBB Symbols, JetBrains Mono, ui-monospace, monospace"
    fontSize: "11.5px"
    fontWeight: 500
    lineHeight: 1.35
  wordmark:
    fontFamily: "PBB Symbols, JetBrains Mono, ui-monospace, monospace"
    fontSize: "13px"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "0.01em"
  specimen:
    fontFamily: "PBB Symbols"
    fontSize: "34px"
    fontWeight: 400
    lineHeight: 1
  index-glyph:
    fontFamily: "PBB Symbols"
    fontSize: "30px"
    fontWeight: 400
    lineHeight: 1.15
rounded:
  nested: "5px"
  field: "6px"
  control: "7px"
  inset: "8px"
  plate: "9px"
  popover: "10px"
  sheet: "12px"
  bottom-sheet: "14px"
spacing:
  hair: "2px"
  xs: "4px"
  sm: "6px"
  md: "8px"
  lg: "12px"
  xl: "14px"
  sheet: "18px"
  gutter: "24px"
  section: "28px"
  page-inline: "20px"
components:
  button:
    backgroundColor: "transparent"
    textColor: "{colors.mocha-ink}"
    typography: "{typography.control}"
    rounded: "{rounded.control}"
    padding: "0 14px"
    height: "36px"
  button-hover:
    backgroundColor: "{colors.base-raise}"
  button-primary:
    backgroundColor: "{colors.peach-mark}"
    textColor: "{colors.mark-ink}"
    typography: "{typography.control}"
    rounded: "{rounded.control}"
    padding: "0 14px"
    height: "36px"
  button-icon:
    backgroundColor: "transparent"
    textColor: "{colors.mocha-ink}"
    rounded: "{rounded.control}"
    size: "36px"
  scenario-toggle:
    backgroundColor: "transparent"
    textColor: "{colors.mocha-ink-soft}"
    rounded: "{rounded.field}"
    padding: "0 9px"
    height: "28px"
  segmented-control-active:
    backgroundColor: "{colors.peach-mark}"
    textColor: "{colors.mark-ink}"
    padding: "0 11px"
    height: "32px"
  glyph-plate:
    backgroundColor: "{colors.mantle-sheet}"
    textColor: "{colors.mocha-ink}"
    rounded: "{rounded.plate}"
    padding: "12px 8px 9px"
  glyph-plate-selected:
    backgroundColor: "{colors.base-raise}"
    textColor: "{colors.mocha-ink}"
  index-cell:
    backgroundColor: "transparent"
    textColor: "{colors.mocha-ink}"
    rounded: "0"
    padding: "14px 12px 11px"
    height: "108px"
  input-field:
    backgroundColor: "{colors.mantle-sheet}"
    textColor: "{colors.mocha-ink}"
    typography: "{typography.control}"
    rounded: "{rounded.control}"
    padding: "0 12px"
    height: "36px"
  proof-sheet:
    backgroundColor: "{colors.mantle-sheet}"
    rounded: "{rounded.sheet}"
  inspector:
    backgroundColor: "{colors.mantle-sheet}"
    rounded: "{rounded.sheet}"
    padding: "18px"
    width: "340px"
  terminal-hud:
    backgroundColor: "{colors.crust-ground}"
    textColor: "{colors.mocha-ink}"
    rounded: "{rounded.inset}"
    padding: "3px"
  lane-chip:
    rounded: "{rounded.control}"
    padding: "3px 6px 3px 3px"
    height: "36px"
  badge-ok:
    backgroundColor: "rgba(166,227,161,.12)"
    textColor: "{colors.green-ok}"
    rounded: "{rounded.field}"
    padding: "5px 10px"
---

# Design System: Prompt Bar Builder

## Overview

**Creative North Star: "The Glyph Specimen Sheet"**

The page is a type specimen for the user's own prompt. At the top sits the proof: a live terminal, rendered in real Nerd Font glyphs, that is also the place you edit. Everything beneath it is plates and an index, the way a foundry sheet lays out a font. Each separator and cap is a glyph plate labeled with its codepoint. Each module is an index cell showing its glyph, its codepoint and its `$variable`. The chrome is Catppuccin ink: a crust ground, mantle sheets, hairline surface rules. Peach is the proofing mark, the single color that says "this one" (selection, primary action, focus, caret, text selection).

Density is that of a working tool, not a dashboard. The terminal stays big (up to about 46vh), the inspector is one sticky sheet on the right, and the plates and index read as print rather than as cards in a form. The UI is dark-first. It follows the system into a real Catppuccin Latte light theme, but the terminal proof and the export code well stay dark because they show what a real terminal will render.

The world rejects the settings dashboard: sidebar lists, rows of form fields, white cards with drop shadows, and a second layout panel that duplicates the preview.

**Key Characteristics:**
- Catppuccin Mocha ink UI, with Catppuccin Latte ink as the light theme; the terminal proof is always a dark terminal.
- Peach is the only accent for app state. Green, yellow and red appear only as status (contrast verdicts, notices, destructive actions).
- Real Symbols Nerd Font glyphs are both the specimen material and the UI icon set (codicons).
- Schibsted Grotesk sets the UI words. JetBrains Mono appears only where the content is code: terminal text, codepoints, `$variables`, hex values, export files, the wordmark.
- Surfaces are flat and separated by hairline rules. Only floating layers get lift.

## Colors

The ink is Catppuccin's neutral ladder (crust, mantle, base, surface0/1, text/subtext). One warm proofing mark sits on top of it. The segment palette is Catppuccin Mocha, which belongs to the user, not to the app.

### Primary
- **Peach Proofing Mark** (peach-mark; Latte: latte-peach-mark): fills the primary action (Export, Copy), active segmented options, the active export step number and text selection. It draws selected plates and tabs as a border with a 12–14% tint (`--mark-soft`), draws the focus ring as a 2px outline, and draws the selection underline under a terminal segment. It is also the caret color and the corner flag on index cells that are in use. Text on a peach fill is always mark-ink (crust).
- **Latte Mark Text** (latte-mark-text): the burnt-peach used on the light theme where peach sits as text (link buttons, "in use", selected-plate checkmarks). The fill orange is not legible as text on Latte paper. In the dark theme, text-peach equals peach-mark.

### Neutral
- **Crust Ground** (crust-ground; Latte: latte-ground): the page itself, the sticky rail, the sticky module-index header, the terminal HUD.
- **Mantle Sheet** (mantle-sheet; Latte: latte-sheet): the proof sheet, the inspector, glyph plates, inputs, the picker, dialogs, hover fill of index cells.
- **Base Raise** (base-raise; Latte: latte-raise): hover fill for buttons and plates, module rows inside the inspector, inline code chips.
- **Surface Rule** (surface-rule; Latte: latte-rule): hairlines. These are the index grid lines, sheet borders, the rule under the terminal, and the dividers in the inspector and dialog.
- **Surface Rule Strong** (surface-rule-strong; Latte: latte-rule-strong): control borders (buttons, inputs, segmented controls), dashed add/drop affordances, the scrollbar thumb.
- **Mocha Ink / Soft / Muted** (mocha-ink, mocha-ink-soft, mocha-ink-muted; Latte: latte-ink family): primary text, secondary labels, then captions, codepoints and `$variables`. Muted on Latte is darkened to #626579 so it meets AA.
- **Terminal Base** (terminal-base): the default proof background (`--tbg`). The user can change it. Terminal chrome text is fixed Mocha ink.

### Status
- **Green OK / Yellow Warn / Red Bad** (green-ok, yellow-warn, red-bad; Latte: latte-ok, latte-warn, latte-bad): status only. Text or icon in the full color, sitting on the same hue at 10–15% alpha. They are used by contrast badges, notices, the export warning line, the armed-reset button, Delete, and the drag-to-remove zone.

### Segment Palette (user content)
- **Catppuccin Mocha swatches** (peach-mark, segment-yellow, green-ok, segment-teal, segment-sky, segment-blue, segment-mauve, segment-pink, red-bad, plus lavender #b4befe, rosewater #f5e0dc and the dusty purple #b48ead): the default segment backgrounds, offered as 30px swatches. They color prompt segments and the powerline wordmark. They never color app chrome.

### Named Rules
**The One Mark Rule.** Peach is the only app accent, and it always means "chosen, primary, or focused". Do not use it for decoration, headings, or a second meaning.

**The User's Colors Rule.** Segment colors belong to the user's prompt. App chrome never borrows teal, blue or mauve, so a user's palette can never be confused with UI state.

**The Proof Stays Dark Rule.** In the light theme the chrome turns Latte, but the terminal proof and the export code well keep Mocha ink (#11111b / #cdd6f4). They stand in for a real terminal.

## Typography

**UI Font:** Schibsted Grotesk (with ui-sans-serif, system-ui, -apple-system, Segoe UI)
**Mono Font:** JetBrains Mono (with ui-monospace, SF Mono, Menlo, Consolas), always stacked behind PBB Symbols so glyphs render inline
**Symbol Font:** PBB Symbols, a subset of Symbols Nerd Font, inlined

**Character:** A sturdy, slightly condensed grotesk for the words a person reads, and a coding mono for the strings a terminal reads. The split between them carries meaning.

### Hierarchy
- **Headline** (600, 20px, 1.2, -0.01em): section heads such as "Separators and caps" and "Modules". A 14px muted sentence sits on the same baseline.
- **Title** (600, 19px, 1.25): the inspector heading (segment name). The dialog head uses 18px and the empty-state head 17px.
- **Group Title** (600, 15px, 1.2): plate-group heads ("Between segments"). Index group heads are 14px in ink-soft, with a 12px mono count after them.
- **Body** (400, 15px, 1.5): base text. Notes and descriptions run 14px. Export instructions are capped at 78ch.
- **Label** (600, 13.5px): field labels in the inspector and plate names.
- **Control** (500, 14px): button text. Primary buttons use weight 600.
- **Terminal** (400, 13.5px, 1.7): the proof. It drops to 11.5px under 640px.
- **Codepoint / Variable** (500, 11–11.5px mono, ink-muted): `U+E0B0`, `$version`, hex readouts (12px).
- **Specimen** (PBB Symbols, 34px, 1): the glyphs on the plates. Index glyphs are 30px.
- **Wordmark** (700, 13px mono): "prompt bar builder" set as a three-segment powerline in crust on Mocha segment colors.

### Named Rules
**The Mono Means Machine Rule.** JetBrains Mono appears only on strings a terminal or config file would contain: commands, codepoints, `$variables`, hex values, TOML/zsh output, step numbers, the wordmark. Labels, headings and buttons are always Schibsted Grotesk.

**The Real Glyph Rule.** Icons and specimens come from the inlined Symbols Nerd Font (codicons for UI, the powerline and devicon ranges for specimens), set in their own font at weight 400 and line-height 1. Do not substitute Unicode dingbats, emoji or a second icon library.

**No Uppercase Labels Rule.** Every label and heading is sentence case with no tracking. No eyebrows or overlines.

## Layout

The page has a sticky top rail (wordmark on the left; undo, redo, Reset, Import, Export on the right) above a two-column shell. The main column is `minmax(0,1fr)` next to a 340px inspector, with a 24px gutter, a 1480px maximum width and 20px inline page padding. The main column stacks three bands 28px apart: the proof (terminal plus fused lane outline), the separator/cap plates, and the module index.

- **Proof:** the terminal is `clamp(300px, 46vh, 440px)` tall in bar mode. Scenario toggles sit in its title bar. The two-lane outline hangs off its lower edge, inside the same sheet, divided by a hairline.
- **Plates:** three plate groups per row with 22px/28px gaps. Each group holds 4 equal tiles with 6px gaps.
- **Index:** a ruled grid, `auto-fill minmax(176px, 1fr)`, with 108px-tall cells. The header row (heading, search, "Click adds to" target) sticks below the rail at 60px.
- **Inspector:** sticky at 64px and scrolls internally (max `100vh - 80px`). It stacks fields 18px apart with 9px between a label and its control.
- **Rhythm:** a 2/4/6/8/12/14/18/24/28 ladder. Tight 4–8px inside controls and chips, 12–18px inside sheets, 22–28px between bands.
- **Breakpoints:** at 1180px the inspector narrows to 300px and plates go 2-up. At 900px the shell is one column and the inspector becomes a bottom sheet (58vh, 14px top corners, a mini proof at the top), and the module picker becomes a bottom sheet too. At 640px page padding drops to 16px, lane tracks wrap, plates go 1-up, and the index goes 2-up and stops sticking.
- **Touch targets:** 36px default control height; compact controls are 28–32px.

## Elevation & Depth

The UI is flat. Depth comes from tonal layers: crust ground, then mantle sheet, then base raise, with hairlines in surface0/surface1 between them. Nothing at rest has a shadow. Only layers that float above the page get lift.

### Shadow Vocabulary
- **Lift** (`box-shadow: 0 6px 14px -6px rgba(0,0,0,.55)`; Latte `rgba(76,79,105,.35)`): the module picker, the export dialog, the inspector when it becomes a bottom sheet.
- **HUD drop** (`box-shadow: 0 10px 24px -10px rgba(0,0,0,.8)`): the floating edit strip inside the terminal, which always sits on dark.
- **Swatch ring** (`box-shadow: 0 0 0 2px <sheet>, 0 0 0 4px <ink>`): the pressed color swatch. This is a ring, not elevation.
- **Scrim** (rgba(8,8,14,.66); Latte rgba(76,79,105,.45)): behind modal dialogs.

### Named Rules
**The Flat Sheet Rule.** Plates, cells, the proof sheet and the inspector are separated by rules and tone, never by shadow. A shadow means "this is floating over the page right now".

## Shapes

Corners are small and get softer as the container gets bigger. Nested buttons use 5px, fields 6px, controls and chips 7px, inset panels and the HUD 8px, glyph plates 9px, popovers 10px, sheets and dialogs 12px, bottom sheets 14px (top corners only). Index cells are square and share 1px ruled borders, so the index reads as a ruled specimen table. Dashed borders mean "a place something can go": add-segment, add-module, drop gaps and the remove zone. Index cells in use carry a 16px peach corner triangle in the top-left, a printer's mark. The selected terminal segment gets a 2px peach underline that wipes in from the left.

## Components

### Buttons
- **Shape:** 7px corners, 36px tall, 14px inline padding, 8px icon gap, 15px codicon.
- **Default:** transparent with a surface-rule-strong border and ink text. Hover lightens the border to ink-muted and fills with base raise.
- **Primary:** peach fill and border, crust text, weight 600. Hover is `brightness(1.07)`. There is one per view (Export in the rail, Copy in the dialog).
- **Bare / Icon:** borderless; hover fills with base raise. Icon buttons are 36px square.
- **Armed (destructive confirm):** red border and text on red-soft.
- **Link buttons:** borderless peach text (latte-mark-text on light) at 600 weight, underlined on hover with a 3px offset. Delete uses the same pattern in red.
- **Focus:** a 2px peach outline at 2px offset, everywhere.

### Chips
- **Scenario toggles:** these sit in the terminal title bar. They have a 6px radius, 28px height, a surface1 border and a small 7px square checkbox before the label. When pressed: peach border, peach 12% tint, filled peach square.
- **Lane chips:** a segment's own background and text color, 7px radius, 36px tall, a grip handle, and modules as 28px inner hit areas. Selected chips get a 2px peach outline at 2px offset. The spacer chip is transparent with a dashed outline.

### Cards / Containers
- **Corner Style:** 12px for the proof sheet, the inspector and dialogs; 9px for plates.
- **Background:** mantle sheet on crust ground.
- **Shadow Strategy:** none at rest (see Elevation).
- **Border:** 1px surface rule.
- **Internal Padding:** 18px in the inspector, 10–12px in the outline, 12–16px in dialogs.

### Inputs / Fields
- **Style:** mantle fill, 1px surface-rule-strong border, 7px radius (6px when nested in the inspector), 32–36px tall. Numeric and text option fields are set in 13px mono because they hold config values.
- **Segmented control:** a joined group with 1px dividers. The active option is a peach fill with crust text.
- **Checkboxes:** 18px native, with `accent-color` set to peach.
- **Focus:** the global 2px peach outline.

### Navigation
- **Rail:** sticky and ground-colored, with no border, sitting over content. Actions are grouped left to right: history (bare icons), a 1px rule, Reset (bare), Import (default), Export (primary). Under 640px the text labels on bare buttons are hidden and the rail wraps.
- **Export steps:** numbered step tabs with a 20px mono number tile. The selected step gets a peach border and tint and a peach-filled number.

### Glyph Plate (signature)
A 9px tile on mantle. From top to bottom: the specimen glyph at 34px, centered on a painted block; the name at 13.5px/600; the codepoint at 11.5px mono in ink-muted. Hover gives a strong rule and a raise fill, and re-sets the live terminal in that glyph. Selected gives a peach border, a peach-soft fill and a peach codicon check next to the name.

### Index Cell (signature)
A square cell in the ruled grid. The glyph (30px) sits top-left with its codepoint (11px mono) top-right, then the module name (14.5px/600) and its `$variable` (11.5px mono). Hover fills with mantle. Cells in use get the peach corner flag and a "· in use" suffix in mark text. Cells are draggable into lanes.

### Terminal Proof and HUD (signature)
The terminal title bar has a translucent black overlay (22%), traffic-light dots, the session title in mono and the scenario toggles. The body uses the terminal type. Hovering a segment draws a 2px inset white underline; the selected segment draws the peach proof underline. The HUD is a floating crust strip inside the terminal (8px radius, surface1 border) holding 30px bare buttons, with Delete in red.

### Status Badge
6px radius with 5px/10px padding: status-colored text and icon on the same hue at low alpha. It is used for the contrast verdict ("9.9:1 · easy to read").

## Do's and Don'ts

### Do:
- **Do** keep peach as the only app-state accent: primary fill, selected border plus 12–14% tint, 2px focus outline, selection underline.
- **Do** set every icon in the inlined Symbols Nerd Font (codicons) at weight 400, line-height 1, 13–16px in UI.
- **Do** label every glyph specimen with its codepoint in 11–11.5px JetBrains Mono, ink-muted.
- **Do** separate flat surfaces with 1px surface-rule hairlines and tonal steps (crust, mantle, base).
- **Do** use dashed surface-rule-strong borders only for places where something can be added or dropped.
- **Do** switch peach-as-text to latte-mark-text (#b54708) in the light theme. Keep the terminal and code well in Mocha ink.
- **Do** keep controls at 36px, with 28–32px only for compact controls nested in the terminal and inspector.

### Don't:
- **Don't** put shadows on plates, cells, the proof sheet or the inspector at rest. Lift belongs to the picker, dialogs and bottom sheets only.
- **Don't** set labels, headings or buttons in JetBrains Mono, or config strings in Schibsted Grotesk.
- **Don't** color app chrome with the segment palette (teal, blue, mauve, pink). Those colors belong to the user's prompt.
- **Don't** use Unicode dingbats, emoji or a second icon set in place of Nerd Font glyphs.
- **Don't** add uppercase tracked eyebrows or kickers above headings. Section heads are sentence case, with a same-line muted description.
- **Don't** add a layout panel or form rows that duplicate the terminal proof. Editing happens in the proof, in the lanes fused to it, and in the inspector.
