# Roland Jacob — Portfolio (scaffold)

This is a simple static portfolio scaffold based on the documentation you provided.

What I created:
- `index.html` — Home (hero, profile, featured projects)
- `projects.html` — Projects listing
- `about.html` — About / Education / Skills
- `contact.html` — Contact form + contact info
- `css/style.css` — Global styles (mobile-first, responsive)
- `images/` — folder for your images (placeholders created as filenames only)

How to use:
1. Add your real images to `site/images/` with these filenames or update the HTML image paths:
   - `profile.jpg`
   - `canva-project.jpg`
   - `wireframe-project.jpg`
   - `python-project.jpg`
2. Open `site/index.html` in a browser to view the site.

Deployment suggestions:
- Upload to GitHub and enable GitHub Pages.
- Or deploy the `site/` folder to Netlify, Vercel, or any static-hosting provider.

Notes & assumptions:
- I assumed a static HTML/CSS site is desired (no build tools). If you'd like React/Vue/Next/Svelte or a CSS framework, tell me and I can re-scaffold.
- I used Google Fonts (Open Sans) and basic responsive CSS (Flexbox/Grid) per your doc.
- Images are not included as binaries. Add your profile and project images into `site/images/`.

Next steps I can take (pick any):
- Replace placeholder images with actual images and optimize them.
- Add a small JavaScript file for the BMI calculator interactivity.
- Improve accessibility (aria labels, form submission handling) and add meta tags for SEO.
- Wire the contact form to Formspree or similar service for live messages.
