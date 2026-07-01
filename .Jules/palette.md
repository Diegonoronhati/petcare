## 2024-05-24 - Warning screen readers about links opening in new tabs
**Learning:** Links that open in a new tab (`target="_blank"`) can be disorienting for screen reader users if they aren't expecting the context switch.
**Action:** Always add an `aria-label` to external links that open in a new tab, clarifying that it opens in a new tab (e.g., `aria-label="Link text (opens in a new tab)"`).
