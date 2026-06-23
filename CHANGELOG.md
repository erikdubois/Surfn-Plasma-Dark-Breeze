# Changelog

## 2026.06.23 — README install commands

### What Changed

**Install docs:** the README install section now lists the meta packages (top-level `*-icons-meta`, plus the group meta where applicable) alongside the per-variant `*-icons-git` package — replacing the outdated single `pacman -S` line.

### Files Modified

- README.md

## 2026.06.21 — repo standardisation

### What Changed

Added the standard project docs and corrected the README's dependency note, which
wrongly said the theme inherits the base Surfn set and pulls in `surfn-icons-git`.

### Technical Details

- Ships only `Surfn-Plasma-Dark-Breeze`, which `Inherits=breeze-dark,breeze,hicolor`.
  The package `surfn-plasma-dark-breeze-icons-git` has no hard dependencies (`depends=()`).
- Added CLAUDE.md.

### Files Modified

- README.md, CHANGELOG.md, CLAUDE.md
