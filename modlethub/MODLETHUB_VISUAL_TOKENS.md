# ModletHub visual direction used in CampaignPulse AI

Reference: the user-provided ModletHub creator early-access page screenshot.

## Palette sampled from the screenshot

| Role | Value | Use |
|---|---|---|
| Primary ink | `#1D1D1F` | Main heading, hero surface, active navigation |
| Action orange | `#C93E05` | Primary buttons, links, diagnostic accent |
| Action hover | `#A93205` | Hover state for primary actions |
| Canvas | `#FFFFFF` | Main application background |
| Soft surface | `#F7F7F7` | Sidebar, cards and secondary surfaces |
| Border | `#E5E5E5` | Dividers, inputs and card outlines |
| Muted text | `#686868` | Supporting text and labels |
| Warm accent | `#F2B49A` | Small eyebrow/accent text on dark surfaces |

## Typography

The screenshot shows a modern, tightly tracked sans-serif display face and clean sans-serif body copy. The screenshot alone does not identify the exact font file or family. CampaignPulse therefore uses an Inter-first system sans-serif stack, with bold, tight-tracked headings and readable body text. This is a visual approximation, not a claim to use ModletHub's licensed or proprietary typeface.

## UI principles

- White, spacious page canvas.
- Near-black editorial headings and restrained dark hero.
- ModletHub orange reserved for primary calls to action, links and small diagnostic accents.
- Light neutral cards with fine borders; avoid heavy gradients and excessive decoration.
- Clear hierarchy, compact labels, generous spacing and responsive layouts.
- Keep CampaignPulse's own product identity and creator attribution; do not copy ModletHub logos or imply endorsement.

## Implementation

- Streamlit theme: `.streamlit/config.toml`
- App styling: `app.py`
