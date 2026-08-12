# Changelog

All notable changes to the "Astigmatism Friendly Theme" extension will be documented in this file.

## [1.0.2] - 2026-08-12

### Added
- Theme colors for modern chat, inline chat, sticky scroll, merge editor, Command Center, and sidebar surfaces
- Marketplace gallery banner

### Changed
- Updated the publishing workflow to Node.js 24 and pinned `@vscode/vsce`
- Added release validation so Git tags must match the extension version
- Reduced the packaged extension by excluding GitHub workflow files

## [1.0.0] - 2026-01-12

### Added
- Initial release of Astigmatism Friendly Theme
- Soft off-white background (#F7F7F2) to reduce glare
- Very dark grey text (#1A1A1A) for optimal readability
- Minimal syntax highlighting - only strings and errors/warnings
- Monochrome code for reduced visual complexity
- Full editor theming including:
  - Activity bar
  - Side bar
  - Editor
  - Tabs
  - Terminal
  - Status bar
  - Panels
  - Notifications
  - Git decorations
  - Diff editor
- Semantic token support
- Error/warning visibility preserved with distinct colors
