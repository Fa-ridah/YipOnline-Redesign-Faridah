# YipOnline-Redesign-Faridah
YipOnline website redesign – Figma to HTML/CSS conversion

Live Demo: [https://yourusername.github.io/yiponline-redesign/](https://yourusername.github.io/yiponline-redesign/)  
https://yiponlineredesign.netlify.app/

## Project Overview
Redesign of the YipOnline website (Figma design → clean, semantic HTML & CSS).  
Goal: Convert pixel-perfect Figma layout into a functional, modern single-page site while preserving brand colors, typography, and structure.

## Tech Stack
- HTML5
- CSS3 (Flexbox + absolute positioning from Figma export)
- Google Fonts: Inter & Plus Jakarta Sans
- No frameworks (vanilla code)

## Key Features Implemented
- Responsive-ready header with shadow & centered navigation
- Hero section with gradient headline & call-to-action buttons
- Services cards with icons & hover states
- How It Works section with numbered steps
- Testimonials carousel-style layout
- Footer with social links & copyright
- Blue accent line above section subtitles (custom pseudo-element)

## Challenges & Solutions
- **Absolute positioning from Figma export** → Converted root to `relative` + `height: auto` to prevent clipping/blank page
- **Colors missing in PDF export** → Enabled "Background graphics" in Chrome print dialog
- **Layout shift/scrollbar issues** → Added `overflow-y: scroll` on body + `margin: 0 auto` centering
- **Image paths** → Kept relative paths (`assets/images/`) for GitHub compatibility

## How to Run Locally
1. Clone repo: `git clone https://github.com/yourusername/yiponline-redesign.git`
2. Open `index.html` in browser (or use Live Server)

## Live GitHub Pages Demo
(Enable in Step 6 below)

## Portfolio & Contact
- Behance: https://www.behance.net/AFaridah
- LinkedIn: https://www.linkedin.com/in/faridah-ayelabegan
- https://faridahportfolio.netlify.app/
- Email: faridahayelabegan@gmail.com

Thank you for viewing!
