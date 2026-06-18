# Changelog

## v1.0 — 2026-06-18

Initial public/freeware release candidate.

### Added

- Empty first-run startup.
- Start Here tutorial window.
- Optional tutorial rows via **More > Reload Tutorial Rows**.
- Delete tutorial rows via bucket filtering and **More > Delete Visible**.
- Explicit target locking with **Set Target** and **Clear Target**.
- Normal row insert through clipboard paste path.
- NoCopy row insert through direct typing.
- Protected rows with password prompt.
- Protected edit warning.
- Copy/cut blocking for protected body editor.
- List, List2, List3, and 1B1 row modes.
- Current panel line/cell preview.
- Ephemeral line marks for list/1B1 workflows.
- Compact/expanded Current panel.
- Export All and Export Visible with timestamped suggested filenames.
- Import File.
- Open Data Folder.
- About window with license, local data, protected row, and branding information.
- Splash and app branding assets.
- EXE icon branding.

### Changed

- Tutorial rows are no longer auto-loaded on first run.
- App starts clean and empty when no snippets exist.
- Start Here explains how to load tutorial rows manually.
- Main UI kept utility-first and uncluttered.

### Notes

- DumbInsert v1.0 is freeware, not open source.
- Data is stored locally under `%APPDATA%\DumbInsert`.
- Protected rows are not a replacement for a password manager or enterprise secrets vault.
- Multi-instance use is not coordinated; if multiple instances save at the same time, last save wins.
