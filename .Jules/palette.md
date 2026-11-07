# Palette's Journal - Critical Learnings Only

## 2026-03-04 - Accessible Alt Text in GitHub Profile Markdown
**Learning:** Profile READMEs commonly use remote SVG services (`capsule-render`, `skillicons.dev`, `shields.io`, and stats APIs) rendered via raw `<img>` tags. When `alt` attributes are omitted, screen reader users miss crucial content such as tech proficiencies and social links, and fall back to pronouncing raw service URLs or silence.
**Action:** Always inspect raw `<img>` tags in markdown/profile pages and provide succinct, context-aware `alt` text summarizing the technologies or linked destinations.
