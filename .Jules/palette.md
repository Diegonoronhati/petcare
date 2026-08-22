## 2024-06-25 - Informing Users About External Links Opening in New Tabs
**Learning:** Screen reader users can be disoriented if a link opens in a new tab (`target="_blank"`) without any warning. The default Create React App template includes a link to "Learn React" that opens in a new tab without an `aria-label` to warn users.
**Action:** When adding links that open in new tabs, ensure they have an `aria-label` explaining this behavior (e.g., `aria-label="Learn React (opens in a new tab)"`). Additionally, ensure images have descriptive `alt` text rather than generic terms like "logo".
