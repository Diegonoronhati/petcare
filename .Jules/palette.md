## 2024-05-14 - Provide Context for Links Opening in New Tabs
**Learning:** Screen reader users rely on context when links open in a new tab. Without warning, opening a new tab can be disorienting as the context changes abruptly and the back button might not work as expected.
**Action:** Always add an `aria-label` or visually hidden text indicating "(opens in a new tab)" to links with `target="_blank"`.
