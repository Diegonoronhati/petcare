## 2026-08-03 - External Link Accessibility
**Learning:** Links that open in a new tab (`target="_blank"`) can be disorienting for screen reader users if they aren't announced as such. Simply adding `rel="noopener noreferrer"` isn't enough for accessibility; an explicit notification is needed.
**Action:** Always add an `aria-label` (e.g., `aria-label="[Link Text] (opens in a new tab)"`) to external links to provide context for screen readers.
