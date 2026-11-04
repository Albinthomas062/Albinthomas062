# Palette's Journal

## 2026-09-08 - Profile README Image Accessibility & Link Context

**Learning:** Profile README repositories frequently rely on external SVG widgets (shields badges, capsule renders, skill icons, stats cards) embedded as raw `<img>` tags without `alt` attributes or with icon-only links lacking `aria-label`s. Screen readers perceive these either as cryptic URLs or announce no context at all.
**Action:** Always provide explicit descriptive `alt` attributes indicating what stats or technologies are shown, and add `aria-label` to badge anchor tags so assistive tech users know where the link leads.
