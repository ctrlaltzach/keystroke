# keystroke

A keyboard-first note capture tool designed to keep you in flow state.

## Why keystroke?

Switching between keyboard and mouse breaks focus. keystroke eliminates that friction — capture thoughts in under 2 seconds, without ever leaving your keyboard.

## Core idea

**Hypothesis:** Removing hand-to-mouse context switches reduces capture friction, keeps users in flow state, and changes what and how much people capture.

## Features

- **Global hotkey** (`Ctrl+Shift+K`) opens capture window from anywhere
- **Keyboard-only navigation** — no mouse required
- **Minimal, distraction-free UI** — just text
- **Fast search** — find notes instantly
- **Local storage** — your notes stay on your machine

## Quick start

1. Download latest release
2. Run the app, set your hotkey
3. `Ctrl+Shift+K` to capture
4. `Ctrl+Shift+L` to search

## Keyboard shortcuts

- `Ctrl+Shift+K` — Open capture
- `Ctrl+Shift+L` — Open search/list
- `Ctrl+Shift+D` — Delete last note
- `Esc` — Close window
- Arrow keys — Navigate in search
- `Enter` — Open/confirm
- `Ctrl+T` — Toggle dark mode

## Status

Early development. This is an experiment in whether keyboard-centric capture actually improves flow and productivity.

## Research

I'm studying how interaction modality affects information capture behavior and subjective flow state. If you're interested in participating in a 3-4 week user study, reach out.

## Building locally

```bash
git clone https://github.com/ctrlaltzach/keystroke.git
cd keystroke
npm install
npm run dev
```