## 2024-07-24 - Add accessibility label to external link
**Learning:** External links with `target="_blank"` don't announce to screen readers that they open in a new tab by default, which can be disorienting. Adding an `aria-label` provides this context.
**Action:** When adding links with `target="_blank"`, include `aria-label="Opens in a new tab"` or similar context.