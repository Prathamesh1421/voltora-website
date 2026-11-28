# VOLTORA Website

A responsive, multi-page static website recreated from the four supplied mobile screenshots:
- `index.html` — Home
- `about.html` — About VOLTORA
- `projects.html` — Practical Work / portfolio
- `contact.html` — Contact page and enquiry form
- `assets/` — logo, CSS and JavaScript

## Preview on your phone or computer
Open `index.html` in a browser. For a more reliable local preview, use VS Code with the Live Server extension.

## Publish for free with GitHub Pages
1. Sign in or create a free account at https://github.com.
2. Create a new **public** repository, for example `voltora-website`.
3. Upload all four HTML files and the complete `assets` folder (keep the folder structure).
4. Open the repository **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then Save.
7. Wait a few minutes. GitHub will show your free website address, normally `https://YOUR-USERNAME.github.io/voltora-website/`.

## Use your own domain at no monthly hosting cost
You already own `voltora.co.in`. GitHub Pages hosting is free; the domain registration itself is a separate renewal cost.
1. In repository **Settings → Pages → Custom domain**, enter `voltora.co.in` and Save.
2. At your domain DNS provider, configure the records GitHub Pages currently specifies for the repository. GitHub's official guide: https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site
3. Also configure `www` if you want `www.voltora.co.in` to work.
4. Wait for DNS propagation, then enable **Enforce HTTPS** in Pages settings when available.

Do not delete existing DNS records until you have checked which records are needed for email or other services.

## Contact form setup (important)
The contact form uses FormSubmit, a third-party form-to-email service, and submits to `voltoraofficial11@gmail.com`. On the first real submission, FormSubmit may send an activation email to that inbox. Open that email and activate the form. Then test the form again. Check spam if the activation email is not visible. The website itself is free to host; FormSubmit has its own service terms and availability.

## Editing content
- Change text directly in the relevant HTML file.
- Replace the logo by replacing `assets/logo.svg` (keep the same filename).
- Add real project photos later by replacing each “Photo coming soon” block with an `<img>` element and an image file inside `assets`.
- The hero currently uses a remote Unsplash background image, so that one background requires an internet connection. The rest of the site is local.

## Notes
This is a close responsive recreation from screenshots, not the original website source code. The supplied screenshots do not contain the original vector logo file or actual project photographs, so the logo is recreated as an editable SVG approximation and the portfolio uses the same “Photo coming soon” placeholders shown in the screenshots.
