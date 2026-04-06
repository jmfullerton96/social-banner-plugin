# Social Banner Plugin

Generate professional, visually striking banner and header images for social media profiles.

## What it does

This plugin teaches Claude to create high-quality banner images using Python and Pillow. It handles the full workflow from design direction through platform-specific export, producing banners that look intentionally designed rather than AI-generated.

### Supported platforms

- **LinkedIn** — Personal profile banners (1584 x 396)
- **X / Twitter** — Header images (1500 x 500)
- **YouTube** — Channel art (2560 x 1440, with safe zone guidance)
- **Facebook** — Cover photos (820 x 312)

### Capabilities

- **Text banners** — Name + tagline with typography, glow effects, and atmospheric backgrounds
- **Text-free banners** — Abstract compositions, artistic backgrounds, brand visuals
- **Freeform specs** — Any design direction the user describes
- **Multi-platform export** — Design once, export to multiple platform dimensions with safe zone awareness

## How it works

1. Claude gathers your design requirements (platform, text, aesthetic direction)
2. Generates a draft banner using Pillow with layered rendering (background → atmosphere → elements → text glow → text)
3. Iterates based on your feedback
4. Exports final versions at the correct dimensions for your target platform(s)

## Installation

```bash
# From the official marketplace
/plugin install social-banner@claude-plugins-official

# Or from this repository directly
/plugin marketplace add jmfullerton96/social-banner-plugin
/plugin install social-banner
```

## Usage

Just ask Claude naturally:

- "Make me a LinkedIn banner"
- "Create a dark, celestial header image with my name and tagline"
- "I need banners for LinkedIn and Twitter — minimal, text-free, dark blue tones"
- "Design a YouTube channel banner for my AI engineering channel"

## Author

Joe Fullerton — [LinkedIn](https://linkedin.com/in/joe-fullerton-4a3a41142) · [GitHub](https://github.com/jmfullerton96)

MCP & Agent Architecture | AI Systems Engineering | DevOps
