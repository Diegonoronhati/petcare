## 2024-03-24 - Accessibility improvements for external links
**Learning:** Screen readers and keyboard navigation users benefit from clear indicators when a link opens in a new tab. Often, external links lack contextual information and visible focus states, making them less accessible.
**Action:** Always add an `aria-label` explaining if a link opens in a new tab (e.g., "Link Name (opens in a new tab)") and ensure that interactive elements have a clear `:focus-visible` outline for keyboard navigation.
