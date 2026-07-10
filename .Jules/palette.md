## 2024-07-10 - App.js Accessibility Review
**Learning:** Found missing context for screen readers when opening a link in a new tab (`target="_blank"`) and poor `alt` text for the logo. These are common accessibility pitfalls in starter templates.
**Action:** Always add context to `target="_blank"` links using `aria-label` (e.g., "(opens in a new tab)") and use descriptive `alt` text for images.
