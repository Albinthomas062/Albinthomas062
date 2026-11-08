# Palette's Journal

## 2026-09-08 - Accessible Alt Text in GitHub Profile READMEs
**Learning:** GitHub profile README widgets (capsule-render banners, skillicons, readme-stats, shields badges) often omit `alt` attributes or generate empty markup by default. Screen readers treat unlabelled `<img>` elements poorly, reading out raw CDN query URLs or skipping critical contextual information. Adding concise, informative `alt` text to each widget and badge makes the profile fully perceivable without altering visual appearance or introducing large diffs.
**Action:** When auditing profile README markup, inspect all `<img>` tags inside `<p align="center">` or skill groups and ensure each has a concise, descriptive `alt` attribute describing its section or destination.
