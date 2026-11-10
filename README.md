# Savanna Brew Café

A responsive, five-page HTML and CSS website developed for the **Introduction to Web Development** assignment.

## Run locally

Open `index.html` in a modern web browser. The site does not require a build step, dependencies, or a web server.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Home, introduction and featured products |
| `about.html` | Café story, owner and values |
| `menu.html` | Menu with KES prices |
| `gallery.html` | Responsive eight-image gallery |
| `contact.html` | Café details, hours and enquiry/reservation form |

All pages share `css/style.css`. All imagery is bundled in `images/` for offline use.

## Requirements and testing

- Semantic HTML5 with one external CSS file; no JavaScript or frameworks.
- Flexbox navigation, CSS Grid gallery, responsive layout and native form validation.
- Local automated checks: 409 assertions passed, zero failures.
- Rendered at widths of 320, 375, 560, 768, 1024 and 1440 pixels.
- **Official W3C HTML and CSS validation has not been run.** See `README.txt` for the detailed testing record.

## Important limitation

The contact form uses `mailto:`; it does not save or confirm reservations. The café and its contact details are fictional as specified by the assignment brief. Images are generated illustrative assets.