# Personal site: fahimcp495.github.io

A plain HTML and CSS site (no build step, no JavaScript). Light and dark themes follow the visitor's system setting.

## Publish it on GitHub Pages

1. On GitHub, create a **public** repository named exactly `fahimcp495.github.io` (the name must match your username).
2. Upload everything in this folder to the repository root: `index.html`, the other `.html` pages, `style.css`, `404.html`, the `images` folder and the `.nojekyll` file. Make sure `.nojekyll` is included (it is a hidden file).
3. In the repository, open **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. Wait a minute or two, then open https://fahimcp495.github.io.

## Things to personalize

- **Photo.** Save a square photo as `images/profile.jpg`, then in each page replace
  `<div class="avatar" aria-hidden="true">IK</div>` with
  `<div class="avatar"><img src="images/profile.jpg" alt="Md Ibrahim Khandakar"></div>`.
- **CV.** Compile your latest `CV.tex`, save the PDF as `cv.pdf` in the repository root, and add
  `<li><span class="label">CV</span> <a href="cv.pdf">PDF</a></li>` to the `links` list in each page. Check first that the PDF contains only what you want public (your CV lists a phone number).
- **Pages.** To add a page, copy `research.html`, change the title, the `aria-current="page"` link and the content, and add a link to it in the `topnav` of every page.
- **Colors and fonts.** Everything is controlled by the variables at the top of `style.css`.

## Keep it accurate

Every statement on the site comes from your CV or your public repository. When something changes, such as a new role, an end date, or a publication, update the page in the same commit as the CV.
