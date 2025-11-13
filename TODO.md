# Task: Remove Theme Toggle, Fix Headings, Standardize Fonts

## Information Gathered
- Theme toggle button present in index.html and about.html (HTML, CSS, JS).
- Services.html and manufacturing.html have headings with text-black, but fonts may not be loading properly, causing visibility issues.
- Font inconsistency: index.html and about.html use Lato (body) and Playfair Display (headings); others use Montserrat (body) and Roboto/Inter (headings).
- Dark mode support in index.html and about.html needs removal.

## Plan
- Remove theme toggle button from index.html and about.html: HTML button, CSS (.theme-toggle), JS (toggle logic, localStorage).
- Remove darkMode from Tailwind config in index.html and about.html.
- Remove dark mode CSS classes from index.html and about.html.
- Update fonts in services.html, manufacturing.html, contact.html, projects.html: Change Google Fonts link to Playfair Display and Lato, update Tailwind config to include playfair and lato, change body font-family to Lato, update headings to font-playfair.
- Ensure headings in services.html and manufacturing.html remain text-black (already present).

## Dependent Files
- index.html
- about.html
- services.html
- manufacturing.html
- contact.html
- projects.html

## Followup Steps
- Test all pages to ensure headings are visible and fonts load correctly.
- Verify theme toggle is removed and no dark mode functionality remains.
- No installations needed.
