# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Developers who use the Starship prompt (starship.rs) with zsh and want a custom, colored prompt or pinned status bar without hand-editing TOML. The author's own setup (Ghostty on macOS, Catppuccin Mocha, zsh, Nerd Font) is the reference case and the strong default, but the tool is shared with other developers, so defaults must work for any Starship user.

## Product Purpose

Prompt Bar Builder lets a developer visually compose a Starship prompt: pick modules, group them into colored segments, choose separator and cap styles, and place them either in a pinned bar (top or bottom of the terminal window) or on the line printed before every command. It previews the result in a simulated terminal and exports copy-ready `starship.toml`, a `.zshrc` block for the pinned bar, and an optional Ghostty keybind. Success: the user pastes the export and their real terminal matches the preview.

## Positioning

The preview and the export are generated from one shared token model, so what the simulated terminal shows is what Starship will render, including conditional modules (git, language, exit code, run time) that appear only in the right situation. It can import an existing `starship.toml` and rebuild it as editable segments, and it ships the zsh scroll-region technique that pins a Starship profile to the top or bottom row, which Starship cannot do on its own.

## Operating Context

Used on a laptop or desktop browser while the user's real terminal is open beside it. Flow: import existing config or start from the sample, arrange and color segments, check scenarios (git repo, code project, failed or slow command, narrow window), export, paste into `~/.config/starship.toml` and `~/.zshrc`, run `exec zsh`. Occasionally opened on a phone.

## Capabilities and Constraints

- Single self-contained HTML file published as a claude.ai artifact: no external requests beyond Google Fonts; no downloads; copy-to-clipboard only; localStorage for per-viewer drafts.
- Browser cannot render Nerd Font glyphs reliably, so the preview uses stand-in icons; the export writes glyphs as `\uXXXX` escapes.
- Module catalog (~50 Starship modules), two lanes (Pinned bar: bottom/top/off; Every prompt), separators arrow/round/slant/flat, start/end caps, scenarios, import, undo/redo, export tabs (starship.toml, .zshrc, ghostty).
- Top pinned bar loses scrollback for lines that scroll past it (terminal limitation).
- Multi-segment lines draw separators even when a middle segment is empty (Starship limitation); single-segment lines are wrapped in a conditional group.
- Terminology: "Pinned bar", "Every prompt", "segment", "module", "spacer".

## Brand Commitments

- Name: Prompt Bar Builder.
- Catppuccin Mocha is the default segment palette.
- Must not read as a generic SaaS dashboard.
- Must not be too dense for a 13–14" laptop; the preview must stay large.
- Dark-first, with a proper light theme for light-mode systems.

## Evidence on Hand

- The author's real `starship.toml` and `.zshrc` (used to test import); never shown in the UI — sample data uses a dummy user `dev@laptop` and path `~/projects/demo-app`.
- No testimonials, user counts, or claims exist; none may be invented.

## Product Principles

1. The preview is the promise: never show something Starship would not render.
2. Edit where you look: the terminal is the primary surface, not a picture of the settings.
3. Every destructive or replacing step (import, reset, export over an existing file) is reversible or clearly warned.
4. Defaults are opinionated and good; depth is available, not in the way.

## Accessibility & Inclusion

Keyboard-operable end to end (select, add, reorder, export) with screen-reader announcements for changes; WCAG AA contrast in the app chrome; text colors in segments are the user's choice but the app reports their contrast.
