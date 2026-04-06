# Social Media Banner Dimensions Reference

Last updated: April 2026

## Platform Specs

### LinkedIn
- **Personal profile banner**: 1584 x 396 px (4:1)
- **Company page banner**: 1128 x 191 px
- **Safe zone**: Profile photo (circular, ~140px diameter) overlaps bottom-left corner. Keep critical content at least 200px from the left edge and 80px from the bottom.
- **Mobile crop**: LinkedIn crops top and bottom on mobile. Keep key content vertically centered.

### X / Twitter
- **Header image**: 1500 x 500 px (3:1)
- **Safe zone**: Profile photo overlaps bottom-left. Keep critical content at least 200px from left edge and 100px from bottom.
- **Mobile crop**: Minimal cropping on mobile, but profile photo overlay area shifts.

### YouTube
- **Channel banner**: 2560 x 1440 px (16:9)
- **Safe area for text/logos**: 1546 x 423 px centered within the banner
- **Mobile visible area**: ~1546 x 423 px (center portion)
- **Desktop visible area**: ~2560 x 423 px
- **TV visible area**: Full 2560 x 1440 px
- **Max file size**: 6 MB

### Facebook
- **Personal cover photo**: 820 x 312 px (~2.63:1)
- **Page cover photo**: 820 x 312 px
- **Mobile display**: 640 x 360 px (crops sides on mobile, top/bottom on desktop)
- **Safe zone**: Keep key content centered. Profile photo overlaps bottom-left.

## Master Canvas Strategy

The skill uses a master canvas approach:
1. Design at the largest needed resolution: **2560 x 1440 px** (YouTube's full size)
2. Define a "safe zone" in the center that works across all platforms
3. On export, crop/resize from the master to each platform's dimensions
4. The safe zone for text across ALL platforms is approximately **1400 x 350 px**, centered

## Export Mapping

From a master canvas of 2560 x 1440:
- **LinkedIn**: Crop to center strip 2560 x 640, then resize to 1584 x 396
- **X/Twitter**: Crop to center strip 2560 x 853, then resize to 1500 x 500
- **YouTube**: Use full canvas, text stays in 1546 x 423 safe area
- **Facebook**: Crop to center strip 2560 x 975, then resize to 820 x 312

Note: Background elements (stars, gradients, patterns) extend to full canvas so crops still look complete. Text and focal elements stay within the universal safe zone.
