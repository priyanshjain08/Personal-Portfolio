# Priyansh Jain — Portfolio

A responsive personal portfolio website for **Priyansh Jain**, presented as a web designer and digital creative. The site highlights an introduction, design and development skills, selected frontend projects, and contact options.

## Features

- **Editorial-style landing page** with large typography, portrait artwork, signature text, and animated circular badge.
- **Responsive navigation** linking to Home, About Me, Skills, Projects, and Contact Me.
- **About section** describing the designer's approach to interface design, frontend development, and branding.
- **Skills and expertise** displayed as a grid of technology badges.
- **Project gallery** containing 11 frontend exercises and demos, including a background-image page, newspaper layout, Flexbox, dynamic gallery, profile card, navigation, iframe dashboard, table layout, box model, login page, and CSS animation.
- **Project detail views** opened through URL hash routes, with project metadata, descriptions, live embedded demos, and previous/next navigation.
- **Contact details** with email, location, LinkedIn, and GitHub links.
- **Contact form** that prepares an email in the visitor's default email app, with a Gmail compose fallback.
- Accessibility-minded touches such as semantic sections, visible focus styles, descriptive iframe titles, form labels, and reduced-motion support.

## Technologies

- HTML5
- CSS3, including Grid, Flexbox, custom properties, media queries, transitions, and keyframe animation
- Vanilla JavaScript
- Inline SVG icons and an embedded portrait image
- Google Fonts: Anton, Cormorant Garamond, Inter, and Mrs Saint Delafield

No build tool or package manager is required for the current single-file version.


## Preview

https://priyanshjain08.github.io/Personal-Portfolio/

## Customization

### Personal details and links

In the HTML file, update the visible introduction and About section, then change the email address and profile URLs in the Contact section. The current source includes:

- Email: `priyanshjain08.officail@gmail.com`
- LinkedIn: `https://www.linkedin.com/in/priyanshjain08`
- GitHub: `https://github.com/priyanshjain08`

Check the spelling of contact details before publishing.

### Location

The JavaScript variables `LOCATION` and `LOCATION_LINK` set the displayed location and map destination. Update both values if the location changes.

### Projects

The JavaScript array `P` contains project titles, categories, descriptions, roles, tools, and years. Edit these entries to update the project cards and detail pages. The `DEMOS` object contains the embedded demo HTML and related configuration.

### Visual styling

CSS custom properties near the top of the `<style>` block control the main palette:

- `--bg`: page background
- `--ink`: primary text
- `--acc`: accent color
- `--mut`: muted text
- `--line`: borders and separators
- `--card`: contact-card background

The same stylesheet includes responsive breakpoints for tablet and mobile layouts.

## External dependencies and notes

- Google Fonts are loaded from `fonts.googleapis.com`; the site uses fallback fonts if the service is unavailable.
- The contact form currently has `WEB3FORMS_KEY` set to an empty string. In this configuration, submitting the form opens a pre-filled email draft rather than sending a message directly from the website.
- A Web3Forms submission path exists in the JavaScript, but it requires a valid access key before it can be used. Do not publish a secret key in client-side code unless the provider explicitly supports that usage.
- The portrait is embedded as a Base64 data URL in the HTML, so it does not need a separate image file.
- The portfolio is currently a single HTML file; project demo markup is embedded in JavaScript and displayed using iframes.
- The source includes a location link pointing to Ajmer, Rajasthan, India. Update it if this is not the intended public location.


