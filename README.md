# McMurtry College Redesign

A redesign of the McMurtry College website at Rice University.

McMurtry is Rice's 10th residential college, established in 2009, named for Burt and Deedee McMurtry (Class of 1956). The building was designed by Hopkins Architects, is LEED Gold certified, and features a horseshoe layout with a central courtyard, campfire pit, and rooftop terrace overlooking the Houston skyline.

The existing web presence didn't capture any of that. This redesign does.

## What's Here

A fully responsive single-page site featuring:

- **Hero section** with enormous Playfair Display serif typography (up to 9xl) over a gradient-overlaid campus photograph
- **Architecture section** highlighting the Hopkins Architects design and LEED Gold certification
- **Community section** with an asymmetric CSS grid layout showcasing college life
- **Innovation and resources sections** with hover-lift card interactions
- **Full-screen mobile navigation overlay** with smooth transitions
- **Scroll-triggered reveal animations** using Intersection Observer
- **Custom gold scrollbar** matching the college's color identity

## Design Choices

Navy and gold on cream. These are McMurtry's actual colors, not something I picked from a palette generator. Playfair Display for headlines gives the institutional gravitas a university college deserves. The enormous typography in the hero is a deliberate editorial choice, letting the college name itself become the visual centerpiece.

## Tech

Single HTML file, Tailwind CSS (CDN), Google Fonts (Playfair Display + Inter), Intersection Observer API, vanilla JavaScript.
