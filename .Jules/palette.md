## 2024-11-20 - Accessible Links and Focus Styles
**Learning:** Links that open in a new tab (`target="_blank"`) can be disorienting for screen reader users if not announced properly. Also, explicit `:focus-visible` styles are essential for keyboard users to know which element is currently focused.
**Action:** Always add an `aria-label` like `"[Link Name] (opens in a new tab)"` to `target="_blank"` links and ensure interactive elements have a clear `:focus-visible` state.
