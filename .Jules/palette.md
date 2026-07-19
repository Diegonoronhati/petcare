## 2024-05-14 - Improve standard CRA template accessibility
**Learning:** The default Create React App template has minor accessibility issues: the logo alt text is simply "logo" (not descriptive) and the "Learn React" link opens in a new tab without warning screen reader users.
**Action:** When working with default templates or similar UI elements, always ensure images have descriptive alt text and external links opening in new tabs have an `aria-label` or similar warning.
