# Social Preview Image Generation Prompt

Use this prompt with an image generation tool (e.g. Nano Banana) to create the GitHub social preview image.

## Specifications

- **Resolution**: 1280 x 640 pixels
- **Format**: PNG
- **Purpose**: GitHub repository social preview (shown in link previews on Twitter, Slack, Discord, etc.)

## Prompt

```
A modern, clean developer tool banner at 1280x640 resolution.

Dark background with a subtle gradient from deep navy (#0d1117) to dark blue-gray (#161b22).

Centered large white typography: "kwin-mcp" in a bold monospace font (like JetBrains Mono or Fira Code).

Below the title, a tagline in lighter gray (#8b949e): "MCP Server for Linux Desktop GUI Automation"

Visual composition: On the left side, a stylized terminal window with faintly visible code lines (suggesting CLI/MCP interaction). On the right side, an overlapping semi-transparent GUI application window (suggesting a desktop app being automated). The two windows overlap slightly in the center, representing the bridge between AI agents and desktop applications.

Small technology icons or text labels arranged in a subtle row near the bottom: KDE Plasma logo, Wayland logo, Python logo — all in muted monochrome or single-accent-color style.

Accent color: KDE Plasma blue (#1d99f3) used sparingly for highlights, window borders, and subtle glow effects.

Style: minimal, developer-focused, GitHub-aesthetic. No gradients on text. No busy backgrounds. Clean and professional like a modern dev tool landing page.
```

## Upload Instructions

After generating the image:

1. Go to the repository Settings > General > Social preview
2. Upload the generated 1280x640 PNG image
3. Or use: `gh api repos/isac322/kwin-mcp --method PATCH --input -` (requires base64-encoded image)
