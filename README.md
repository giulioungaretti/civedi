# Astigmatism Friendly Theme for VS Code

A Visual Studio Code color theme specifically designed for people with moderate to strong astigmatism. This theme reduces eye strain, prevents halation, and minimizes blur by following evidence-based accessibility guidelines.

## Features

- **Soft off-white background (#F7F7F2)** - Reduces glare while maintaining high readability
- **Dark grey text (#1A1A1A)** - High contrast without the harshness of pure black
- **Minimal syntax highlighting** - Only strings and errors/warnings are colored
- **Monochrome code** - Reduces visual complexity and halation effects
- **Clear error visibility** - Errors (red) and warnings (orange) remain clearly visible

## Why This Theme?

People with astigmatism often struggle with:

1. **Pure white backgrounds** - Cause glare and scatter light unevenly
2. **Pure black text on pure white** - Maximum contrast can increase halation
3. **Dark mode (white on black)** - Forces pupil dilation, causing blur and "glowing" text
4. **Heavy syntax highlighting** - Multiple colors create visual noise and increase focusing difficulty

This theme addresses all these issues by:

- Using a soft off-white background that keeps pupils stable
- Using very dark grey instead of pure black for reduced edge fuzziness
- Keeping code mostly monochrome to reduce visual complexity
- Only highlighting what matters: **strings** (for string/data visibility) and **errors/warnings** (for immediate attention)

## Color Palette

| Element | Color | Hex Code |
|---------|-------|----------|
| Background | Soft Off-White | #F7F7F2 |
| Text | Very Dark Grey | #1A1A1A |
| Comments | Medium Grey | #606060 |
| Strings | Green | #2E7D32 |
| Errors | Red | #D32F2F |
| Warnings | Orange | #E65100 |
| Info | Blue | #1976D2 |

## Recommended Additional Settings

For optimal readability with astigmatism, consider these VS Code settings:

```json
{
  "editor.fontSize": 14,
  "editor.lineHeight": 1.6,
  "editor.fontFamily": "'Segoe UI', 'Inter', 'Calibri', sans-serif",
  "editor.fontWeight": "400",
  "window.zoomLevel": 0.5
}
```

### System Settings

- **Screen brightness**: Match your room's ambient light
- **Color temperature**: Enable Windows Night Light at 30-40%
- **Display scaling**: Consider 110-125% scaling if text feels small

## Installation

### From VSIX (Local)

1. Run `vsce package` in the extension directory
2. In VS Code: Extensions → `...` menu → "Install from VSIX..."
3. Select the generated `.vsix` file

### Manual Installation

1. Copy this folder to your VS Code extensions directory:
   - Windows: `%USERPROFILE%\.vscode\extensions\`
   - macOS/Linux: `~/.vscode/extensions/`
2. Restart VS Code
3. Select the theme: File → Preferences → Color Theme → "Astigmatism Friendly"

## Research Background

This theme is based on accessibility research from:

- **Level Access** - Digital accessibility guidelines
- **RNIB** (Royal National Institute of Blind People) - Vision accessibility recommendations  
- **WCAG** - Web Content Accessibility Guidelines (minimum 4.5:1 contrast ratio)
- **UX accessibility research** - Studies on astigmatism and screen readability

## Contributing

Feedback and contributions are welcome! If you have astigmatism and have suggestions for improving the theme, please open an issue or pull request.

## License

MIT License
