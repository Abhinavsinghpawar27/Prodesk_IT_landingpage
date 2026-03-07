# Prompts Used (AI Assistance Log)

## 1) Project Scoping
Create a complete single-page landing website for a fictional agency named "Prodesk IT" using HTML, Tailwind CSS (CDN), and vanilla JavaScript in one `index.html` file.  
Requirements:
- Responsive desktop/mobile layout
- Sticky glassmorphism navbar
- Hero section with strong brand-first headline
- Services section (3 items)
- Footer with social links
- Dark/light mode toggle
- Micro-interactions (button hover + card lift)
- Clean semantic HTML and accessible structure

## 2) UX and Visual Quality Pass
Improve visual hierarchy and spacing so the first viewport reads as one composition:
- Brand name should be a hero-level signal
- Keep one dominant message in hero
- Reduce clutter and avoid competing blocks
- Ensure CTA buttons are clear and high contrast
- Preserve mobile-first responsive behavior

## 3) Dark Mode Engineering
Implement robust dark mode for the full page (not only navbar):
- Toggle a `dark` class on root element
- Persist preference in `localStorage`
- Respect system preference on first load
- Ensure all sections have matching `dark:*` styles
- Verify text/background contrast in both themes

## 4) Navbar and Mobile Menu
Implement a sticky navbar with:
- Desktop links (Home, About, Services, Contact)
- Mobile hamburger menu
- Smooth open/close interaction
- Keyboard and aria attributes for accessibility
- Backdrop blur/frosted glass effect

## 5) Micro-interactions
Add lightweight motion with performance in mind:
- CTA buttons: hover color shift + subtle scale
- Service items: lift effect on hover
- Avoid excessive animation noise
- Keep transitions under ~300ms for responsiveness

## 6) Bug Fix Prompt
Debug hero heading rendering issue where gradient text appears as blocks:
- Replace unreliable utility combination with stable CSS gradient text class
- Keep readability in both light and dark themes
- Retest on mobile and desktop breakpoints

## 7) Submission Support
Generate internship submission docs:
- `README.md` with features, setup, screenshot, and live link sections
- `Prompts.md` listing AI prompts used
- Keep content concise, professional, and reviewer-friendly