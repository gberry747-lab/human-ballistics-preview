# Human Ballistics Website

A fast, mobile-friendly, static website (plain HTML and CSS, no build step). It is ready to publish free on GitHub Pages.

## Pages
- `index.html` - home
- `performance-course.html` - the flagship course
- `membership.html` - online membership (Zoom, library, transcripts)
- `one-on-one.html` - private coaching
- `crm-humanfactors.html` - team and corporate training
- `fly-calm.html` - fear of flying program
- `testimonials.html` - all testimonials
- `about.html` - Ray's story
- `contact.html` - contact and booking form
- `css/styles.css` - all styling (brand colours are the `--brand` variables at the top)
- `js/main.js` - mobile menu and footer year

## To view it locally
Double-click `index.html`. It opens in your browser. That is the whole site, working.

## Before it goes live: two quick things to finish
1. **Contact form.** Open `contact.html` and find `YOUR_FORM_ID`. Create a free form at https://formspree.io, then paste your form endpoint so enquiries reach Ray's inbox. Claude can do this for you.
2. **Confirm the details.** Check the email address, the next course date, and the draft membership prices are correct. Update once the new name is chosen.

## To publish on GitHub Pages (free)
1. Create a repository on GitHub (for example `human-ballistics-site`).
2. Upload all the files in this `website/` folder to the repository (keep the folder structure: `css/`, `js/`, `assets/` alongside the HTML files).
3. In the repository, go to **Settings > Pages**, set the source to the `main` branch, root folder, and save.
4. After a minute the site is live at `https://YOURUSERNAME.github.io/human-ballistics-site/`.
5. To use a custom domain (like humanballistics.com or a new one), add it under Settings > Pages and follow GitHub's DNS steps. Claude can walk Ray through this.

## Rebranding when the new name is chosen
The brand appears in a small number of obvious places:
- The wordmark "Human Ballistics" and the "HB" monogram in the header and footer of every page.
- The `<title>` and description at the top of each HTML file.
- The colours (`--brand` variables) at the top of `css/styles.css`, only if a new palette is wanted.

Ask Claude to "find and replace the brand name across all pages" once the name is decided.

## Notes
- Fonts load from Google Fonts (Fraunces and Inter). This needs an internet connection, which any hosted site has.
- No tracking or analytics is included yet. Add Google Analytics or a privacy-friendly alternative later if wanted.
