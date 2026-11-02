# SHOUT OUT — SIC PARVIS MAGNA

## Student Information
- **Full Name:** WEZILE MADONSELA
- **Student Number:** ST10516071
- **Subject:** Web Development / WEDE
- **Part:** Final PEO

> **Academic project note:** SHOUT OUT is a fictional cybersecurity organisation created for this academic website project. Product names, prices, branch information and contact details are project-created content.

## 1. Project Overview
SHOUT OUT is a fictional premium cybersecurity retail and services organisation aimed at families in Johannesburg, South Africa. The website presents cybersecurity products and services in a simple, professional and family-focused way.

The website contains:
1. `index.html` — Home
2. `about.html` — About
3. `products.html` — Products & Services
4. `enquiry.html` — Enquiry
5. `contact.html` — Contact

Proposed locations are Sandton, Zwartkop and Midstream.

The visual identity uses:
- White/off-white backgrounds
- Black typography
- Gold accents
- Silver accents
- Rose-gold accents
- Serif headings
- Sans-serif body text

The slogan is **SIC PARVIS MAGNA**.

## 2. Part 1 Feedback and Corrections
The feedback received after Part 1 was:

> “Good work, please use README to explain your work fully and the use of CSS shows copied work or not following the instructions.”

In response, Part 2 makes the CSS work more structured and explainable.

### Corrections and improvements
- Maintained one external stylesheet at `css/style.css`.
- Added a CSS reset to reduce browser inconsistencies.
- Added CSS custom properties for repeated colours, spacing and layout values.
- Added a clear typography system.
- Used Flexbox for one-dimensional layouts such as navigation and button groups.
- Used CSS Grid for multi-column cards and footer content.
- Added hover, focus-visible and active states.
- Added tablet and mobile media-query breakpoints.
- Used relative units including `rem`, `%`, `vw` and `clamp()`.
- Improved keyboard focus visibility.
- Added reduced-motion support.
- Expanded this README so sir can identify and understand the CSS decisions.

## part 2 feedback and corrections
>"Outstanding work,etc provide verified descriptive git commots for full marks,

in response, the final PEO is more descriptive hopefully

## corrections and improvements 
- updates made to home page

## 3. CSS Styling

### 3.1 External Stylesheet
All five pages use the same external stylesheet:

`css/style.css`

This avoids unnecessary duplication and allows common styling rules to cascade across the website.

### 3.2 CSS Reset
The stylesheet starts by resetting common browser defaults including margins, padding, box sizing, lists, links and image sizing. This creates a predictable base for the design.

### 3.3 Design Variables
The `:root` section stores repeated values such as:
- `--black`
- `--white`
- `--off-white`
- `--gold`
- `--silver`
- `--rose-gold`
- `--border`
- `--container`
- `--radius`

This makes the design easier to maintain because a shared value can be changed in one location.

### 3.4 Typography
Headings use a serif font stack to create the premium SHOUT OUT identity, while body text uses a sans-serif stack for readability.

Typography uses:
- `font-family`
- `font-size`
- `font-weight`
- `line-height`
- `letter-spacing`
- `clamp()`

`clamp()` allows headings to scale according to the viewport.

### 3.5 Layout
Flexbox is used for:
- Header alignment
- Navigation
- Button groups
- Action areas

CSS Grid is used for:
- Product cards
- Service cards
- Location cards
- Footer columns

The desktop card layout uses three columns, while media queries reduce this to two columns on tablets and one column on mobile.

### 3.6 Visual Styling
The design uses:
- Colours
- Borders
- Rounded corners
- Shadows
- Spacing
- Transitions

The design is intentionally restrained so that content remains the main focus.

### 3.7 Interactive States
The stylesheet includes:
- `:hover`
- `:focus-visible`
- `:active`

Hover effects provide visual feedback. `:focus-visible` gives keyboard users a clear indication of the selected interactive element. Active states provide feedback while controls are being pressed.

## 4. Responsive Design

### Breakpoints

| Viewport | Layout |
|---|---|
| Above 900px | Desktop |
| 651px–900px | Tablet |
| 650px and below | Mobile |

### Desktop
The navigation is horizontal and content cards can use three columns.

### Tablet
At 900px and below, multi-column cards reduce to two columns and footer content becomes more compact.

### Mobile
At 650px and below:
- Navigation becomes a mobile menu.
- Multi-column content becomes one column.
- Buttons become full width.
- Forms use available screen width.
- Footer content becomes one column.
- Tables can scroll horizontally.

## 5. Relative Units
Relative values were used to support different screen sizes:
- `rem` for typography and spacing
- `%` for responsive widths
- `vw` inside responsive heading calculations
- `clamp()` for fluid typography
- `min()` for responsive containers

## 6. Responsive Images
Images are restricted to the width of their containing elements with `max-width: 100%` and `height: auto`. This prevents images from causing horizontal overflow.

Where multiple image versions are available, HTML can also use `<picture>`, `srcset` and `sizes` to allow an appropriate image source to be selected.

## 7. Accessibility
Part 2 styling supports accessibility through:
- Visible keyboard focus states
- Readable typography
- Logical heading hierarchy
- Responsive layouts
- Form labels
- Descriptive image alternative text
- Reduced-motion support
- Adequate spacing around controls

WCAG 2.2 was used as an accessibility reference.

## 8. Testing and Iteration
Use browser developer tools to test the website at different viewport sizes.

### Screenshot evidence to add to the repository
1. Desktop — approximately 1366 × 768
2. Tablet — approximately 768 × 1024
3. Mobile — approximately 390 × 844
4. Mobile navigation open
5. Products/services section
6. Enquiry form
7. Contact page

### Testing checklist
- [ ] All five HTML pages open.
- [ ] Navigation works on every page.
- [ ] External CSS loads on every page.
- [ ] Desktop layout displays correctly.
- [ ] Tablet layout displays correctly.
- [ ] Mobile layout displays correctly.
- [ ] Mobile navigation works.
- [ ] Cards resize correctly.
- [ ] Forms fit within the viewport.
- [ ] Images do not overflow.
- [ ] No unnecessary horizontal overflow.
- [ ] Hover states work.
- [ ] Keyboard focus states are visible.
- [ ] Content remains readable at smaller widths.
- [ ] Website tested using browser developer tools.

## 9. File Structure
```text
SHOUT-OUT/
Evidence/
desktop-home
desktop-about
mobile-home
moblie-enquirey
tablet-products
tablet-services
├── index.html
├── about.html
├── products.html
├── enquiry.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
├── assets/
├── README.md
└── .gitignore
```

## 10. GitHub Version Control
Suggested descriptive commits:
```text
Part 2: add CSS reset and design variables
Part 2: add desktop typography and layout
Part 2: add responsive tablet styling
Part 2: add mobile responsive styling
Part 2: improve accessibility and focus states
Part 2: update README documentation
Part 2: add responsive testing evidence
```

## 11. Changelog

### Version 0.1.0 — Part 1 Foundation
- Created the SHOUT OUT fictional cybersecurity organisation concept.
- Defined the Johannesburg family-focused target audience.
- Defined Sandton, Zwartkop and Midstream as proposed locations.
- Created the five-page website structure.
- Established the luxury visual identity.
- Planned HTML5, CSS3 and vanilla JavaScript implementation.

### Version 0.2.0 — Part 1 Website Implementation
- Added the five website pages.
- Added navigation and website content.
- Added product and service information.
- Added enquiry and contact form structures.
- Added image and asset folders.
- Added initial JavaScript functionality.

### Version 0.3.0 — Part 2 Desktop CSS
- Reorganised the external stylesheet into clearly labelled sections.
- Added a CSS reset.
- Added CSS custom properties for colours, spacing and layout.
- Added a consistent typography system.
- Added responsive container sizing.
- Added Flexbox navigation and button layouts.
- Added CSS Grid card layouts.
- Added card borders, shadows and spacing.
- Added interactive button and navigation states.
- Added visible keyboard focus styling.

### Version 0.4.0 — Part 2 Responsive Design
- Added a tablet breakpoint at 900px.
- Added a mobile breakpoint at 650px.
- Changed multi-column content to two columns on tablet.
- Changed content grids to single-column layouts on mobile.
- Added mobile navigation styling.
- Adjusted typography and spacing for smaller screens.
- Made buttons and forms responsive.
- Added responsive table behaviour.
- Added reduced-motion support.

### Version 0.5.0 — Part 2 Documentation
- Expanded README documentation to explain the CSS implementation.
- Added explanations of selectors, Grid, Flexbox and responsive breakpoints.
- Added testing and screenshot requirements.
- Added Part 2 changelog entries.
- Added CSS and responsive-design references.

## 12. References
- World Wide Web Consortium (W3C). (2024). *Web Content Accessibility Guidelines (WCAG) 2.2*. https://www.w3.org/TR/WCAG22/
- Mozilla Developer Network (MDN). *CSS Reference*. https://developer.mozilla.org/en-US/docs/Web/CSS
- Mozilla Developer Network (MDN). *CSS Grid Layout*. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout
- Mozilla Developer Network (MDN). *Using media queries*. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries
- Mozilla Developer Network (MDN). *Responsive images*. https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Responsive_images
- South African Cybersecurity Hub. (2025). *Cyber Safety Awareness resources*. https://www.cybersecurityhub.gov.za/
- Google for Developers. (2026). *Maps Embed API overview*. https://developers.google.com/maps/documentation/embed/get-started
- Unsplash. (2026). *License*. https://unsplash.com/license

## 13. Academic Content Note
SHOUT OUT is a fictional academic project. Product names, service names, prices, branch information and contact details are project-created content and should not be presented as real commercial claims.
