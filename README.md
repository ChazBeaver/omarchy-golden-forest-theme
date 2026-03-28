# Golden-Forest for Omarchy

Golden-Forest is an Omarchy theme package built to coordinate the wider desktop theme with the Neovim theme **`golden-forest`**.

This repo is the Omarchy-side theme bundle. It provides the files Omarchy uses for desktop and application styling, while Neovim itself is styled by the separate Neovim colorscheme named `golden-forest`.

## Relationship to the Neovim theme

This Omarchy theme is designed to pair with the Neovim theme:

- **Neovim theme name:** `golden-forest`
- **Omarchy theme repo:** `omarchy-golden-forest-theme`

This setup keeps the system organized:

- Omarchy theme repo = desktop/app theming assets
- Neovim theme = editor colorscheme
- both share a common visual palette

## What this repo contains

Typical files include:

- `colors.toml`
- `colors.css`
- `btop.theme`
- `cava_theme`
- `chromium.theme`
- `mako.ini`
- `walker.css`
- `warp.yaml`
- `palette.json`

## How it works with Omarchy

Omarchy applies the theme files contained here to supported components and applications. Neovim should load the matching `golden-forest` colorscheme separately.

## Naming convention

- **Omarchy repo:** `omarchy-golden-forest-theme`
- **Neovim theme:** `golden-forest`

## Goal

Golden-Forest is intended to make the editor and the rest of the Omarchy environment feel visually unified.
