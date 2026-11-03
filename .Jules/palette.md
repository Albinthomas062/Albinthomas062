## 2026-11-03 - Accessible Profile README Widgets and Badges
**Learning:** Profile READMEs often rely on external SVG widgets (like capsule-render, skillicons, github-readme-stats, and shields.io) embedded via HTML `<img>` tags. Without explicit `alt` attributes, screen readers announce raw URLs or unhelpful filenames, severely diminishing accessibility for visually impaired users.
**Action:** Audit all embedded `<img>` tags in markdown profile repositories and provide concise, descriptive `alt` text identifying the widget content or linked badge destination.
