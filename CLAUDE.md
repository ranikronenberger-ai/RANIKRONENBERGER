# Rani Kronenberger — Personal Site

## Project overview
Personal website for Rani Kronenberger. A landing page with a couple of additional pages.

## Structure
- `index.html` — landing page
- `about.html` — who am i
- `projects.html` — projects & passions
- `publications.html` — publications
- `values.html` — values
- `contact.html` — contact
- `unhinged.html` — un/hinged project page

## Style
- Background: #fff (white) on all interior pages. Landing page (index.html) uses a full-viewport photo. NO dark bg.png wrapper, NO floating page-card on a dark background.
- Fonts: Cormorant Garant (headings), DM Sans (body)
- No animations — zero. No keyframes, no transitions beyond simple hover opacity.
- No CSS/SVG drawings or fake illustrated objects. Only real photos/screenshots provided by the user.
- When the user provides a screenshot of a real object, use that exact image file — never substitute with CSS art or SVG.

## Layout & Responsiveness
- CRITICAL: Every page must look correct at all screen sizes — mobile, tablet, large desktop. Never let content overlap, overflow, or scramble when resizing.
- Use flexible units (%, vw, clamp, flex, min/max) — avoid fixed pixel widths that break on small screens.
- All pages must share the same layout structure and dimensions so the site feels consistent.
- No page-card floating on a dark background. Content sits directly on the #fde8f0 body.

## Guidelines
- Keep it personal and minimal
- All pages feel cohesive: same nav, same pink background, same font pairing
- Folder patterns on projects.html are LOCKED — do not change them
