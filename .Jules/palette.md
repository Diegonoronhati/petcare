## 2024-05-15 - Default Create React App Accessibility Issues
**Learning:** Default Create React App templates often include boilerplate with sub-optimal accessibility. For example, generic image alt text ("logo") doesn't describe the image properly, and external links opening in new tabs don't inform screen readers of this behavior.
**Action:** Always review and refine accessibility for default generated boilerplate. Ensure image alt text is descriptive (e.g., "React logo") and external links have clear `aria-label` attributes indicating they open in a new tab.
