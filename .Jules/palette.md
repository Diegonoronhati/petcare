## 2024-08-08 - Explicit ARIA Labels for New Tabs and Focus Visibility
**Learning:** React generic `App-link` classes and standard text lack screen reader context for `target="_blank"` behavior. Default browser focus outlines can sometimes be obscured by site styles.
**Action:** When adding standard links that open in new tabs, ensure an `aria-label` is provided noting this behavior. Always add `:focus-visible` pseudo-class for custom focus rings to ensure keyboard accessibility.
