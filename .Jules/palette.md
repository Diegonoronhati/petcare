## 2024-05-18 - External Link Accessibility
**Learning:** Screen reader users need to be informed when links open in a new tab (i.e. have `target="_blank"`), otherwise the sudden change of context can be disorienting.
**Action:** Always add an `aria-label` (e.g. `aria-label="Link text (opens in a new tab)"`) or visually hidden text when creating external links with `target="_blank"`.