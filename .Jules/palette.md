# Palette's Journal - Critical UX & Accessibility Learnings

## 2026-03-24 - Profile README Image Accessibility
**Learning:** GitHub profile READMEs heavily rely on dynamic badge images and external SVG widgets (capsule-render, github-readme-stats, skillicons, shield badges) which often omit `alt` text or use generic alt text, making the profile inaccessible to screen reader users.
**Action:** Always inspect HTML `<img />` tags and Markdown `![alt](url)` images in profile READMEs to ensure meaningful `alt` descriptions are provided for stats, tech skills, and headers.
