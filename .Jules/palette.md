## 2025-05-20 - Profile README Image Accessibility
**Learning:** GitHub profile READMEs frequently rely on embedded HTML `<img>` tags for badges, skill icons, header/footer graphics, and stats cards, which often omit `alt` attributes. Adding descriptive `alt` text provides screen readers with context for graphical elements that otherwise produce non-descriptive URL speech output.
**Action:** Always audit `<img>` tags in markdown files using automated checks for missing `alt` attributes and add meaningful descriptions.
