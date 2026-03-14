Markdown# KISS – The Ultimate Fan Page

![Responsive mockup of the website](https://via.placeholder.com/800x400?text=Responsive+Mockup+KISS+Fan+Page)  
*(Replace the placeholder above with a real screenshot from https://ami.responsivedesign.is/ once the site is deployed)*

A static fan site dedicated to the legendary rock band KISS. The page presents the band's history, members, selected songs, interviews, booking information, images, and sources—all wrapped in a theatrical and thematic design inspired by KISS's iconic makeup and stage aesthetic.

**Live Site:** [https://night0509star.github.io/kiss-fan-page/](https://night0509star.github.io/kiss-fan-page/)  
*(Update the link once your site is deployed on GitHub Pages)*

## Table of Contents

- [UX](#ux)
  - [Strategy](#strategy)
  - [User Stories](#user-stories)
  - [Wireframes](#wireframes)
- [Features](#features)
  - [Existing Features](#existing-features)
  - [Future Features](#future-features)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits)

## UX

### Strategy
The target audience is KISS fans of all ages as well as new listeners who want to discover the band in an engaging and visual way. The site should convey the feeling of a real KISS concert—dramatic, energetic, and full of nostalgia—through dark tones, glow effects, and iconic design elements.

### User Stories
- As a KISS fan, I want a quick overview of the band's history and members.
- As a new visitor, I want to explore their most classic songs and learn more about them.
- As a visitor, I want to experience a stylish, thematic design that reflects KISS aesthetics (makeup, fire, black/red/gold).
- As a mobile user, I want the site to be fully responsive and work perfectly on phone and tablet.

### Wireframes
*(Add simple sketches here—either hand-drawn photos or created in Figma/Balsamiq)*

![Desktop Wireframe](assets/wireframes/desktop-wireframe.jpg)  
![Mobile Wireframe](assets/wireframes/mobile-wireframe.jpg)

## Features

### Existing Features
- **Fixed navigation header** with smooth scrolling to all sections (`scroll-behavior: smooth`).
- **Thematic design** featuring a gradient background, glow effects on text and links, and four fixed corner circles recreating Starchild, Demon, Spaceman, and Catman—entirely built with pure CSS (clip-path and pseudo-elements).
- **Collapsible `<details>` elements** for expanded information about each band member and song.
- **Responsive layout** and image gallery that adapts to screen size.
- **External button** to the official KISS website that opens in a new tab.
- **Semantic HTML** with proper section elements and accessibility improvements (descriptive alt text on images).

### Future Features
- Embedded YouTube videos for interviews and live performances.
- Audio player to listen to songs directly on the site.
- Dark/light mode toggle.
- Fan contact form.

## Technologies Used
- HTML5
- CSS3 (including advanced clip-path, pseudo-elements, and gradients)
- Google Fonts – "Metal Mania" for headings
- GitHub Pages – for hosting and deployment
- W3C HTML & CSS Validator
- ami.responsivedesign.is – for responsive mockups

## Testing

The site's functionality and responsiveness have been manually tested on the following devices and browsers:

| Device                 | Browser                 | Result     |
|------------------------|-------------------------|------------|
| iPhone 13              | Safari                  | Passed     |
| Samsung Galaxy S21     | Chrome                  | Passed     |
| iPad Pro               | Safari                  | Passed     |
| Desktop (1920×1080)    | Chrome, Firefox, Edge   | Passed     |

### Validation
- HTML: [W3C Validator – no errors](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnight0509star.github.io%2Fkiss-fan-page%2F)
- CSS: [W3C CSS Validator – no errors](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fnight0509star.github.io%2Fkiss-fan-page%2F)

### Known Bugs
- No known bugs after the latest updates.

## Deployment

The site is published via GitHub Pages:

1. Go to the repository → Settings → Pages
2. Select branch `main` and folder `/ (root)`
3. Save – the site becomes available at the specified GitHub Pages URL

For local development:
1. Clone the repository: `git clone https://github.com/Night0509Star/kiss-fan-page.git`
2. Open `index.html` in any browser.

## Credits

### Content
- All text about the band, members, and songs is compiled and rewritten from Wikipedia (2025) and official sources.
- Song descriptions based on Wikipedia and music reviews.

### Media
- Images sourced from Wikimedia Commons, kissonline.com, and other public sources (all permitted for non-commercial use or fair use for a fan site).
- All images include descriptive alt text and are credited in the sources section on the site.

### Code
- Corner CSS makeup circles: Custom implementation using clip-path, pseudo-elements, and polygons.
- Smooth scrolling: Native CSS property `scroll-behavior: smooth`.

Thanks to the KISS Army worldwide – **You Wanted the Best, You Got the Best!** 🤘