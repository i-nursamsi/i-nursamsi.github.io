# Ilyas Nursamsi: research website

This is a single-page static site, so GitHub Pages can host it as it is with no build step.

## Put it online (about 10 minutes)

1. Sign in to GitHub as **i-nursamsi**.
2. Create a new **public** repository named exactly `i-nursamsi.github.io`.
3. On the new repo page, click **uploading an existing file**. Drag in `index.html`, `README.md` and the `images` folder, then click **Commit changes**.
4. Open **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main**, and folder to **/ (root)**, then click Save.
5. After a minute or two the site is live at **https://i-nursamsi.github.io**.

## After it is live

- **Photo:** add a portrait named `images/profile.jpg`, ideally 800 × 1000 px or larger (4:5 ratio). Until you do, the page shows your initials.
- **Contact form:** send yourself one test message from the live site. FormSubmit will email you a one-time **Activate** link. Click it, and from then on every message arrives in your Gmail.
- **LinkedIn:** search `index.html` for `LinkedIn`, remove the `<!--` and `-->` around that line, and put in your profile URL.

## Editing later

Click `index.html` on GitHub, then the pencil icon. Edit the text and click **Commit changes**. The site updates within a minute.

- **New paper:** copy an existing `<li>…</li>` under Publications and change the text. For a new year, copy a whole `<div class="pubs-year">` block.
- **Real project images:** replace a project's `<canvas …></canvas>` with `<img src="images/your-figure.jpg" alt="Short description">`, and upload the image to the `images` folder.
- **Oulu email:** in the Contact section, change both `ilyasnursyamsi05@gmail.com` addresses (link text and `href`) and the address in the form's `action`.

## Custom domain (optional)

To use a domain such as `ilyasnursamsi.com`, buy it from any registrar, then add it under **Settings → Pages → Custom domain** and follow GitHub's DNS instructions.
