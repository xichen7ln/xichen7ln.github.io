# Xi Chen — Academic Website

A static academic website for Xi Chen, Department of Sociology and Social Policy, Lingnan University.

## GitHub Pages publishing

1. Create a new GitHub repository under the intended site owner’s account (ideally the professor’s).
2. Upload all files **inside** this directory to the repository root (including the `assets/` folder). Do not upload the ZIP itself as a lone file.
3. In repository **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
4. Once deployment succeeds, GitHub provides the Pages URL in that Settings page.

To update the site later, edit the HTML/asset files and commit them to `main`. GitHub Pages will redeploy without changing the URL.

## Local portrait

The official portrait supplied for the project is bundled at `assets/xi-chen-portrait.jpg`. The homepage loads this **local file**, not an external photo URL, so future changes to the university's photo URL will not affect it.

To replace the photo later, replace `assets/xi-chen-portrait.jpg` with the professor’s approved new photograph using the same filename and commit the change. Confirm permission for public use before deployment.

## Website structure

`index.html` (Home), `publications.html`, `projects.html`, `teaching.html`, `talks.html`, and `assets/` (styles, JavaScript, favicon).

This package does not itself publish a live site; publishing requires the repository owner to create/configure a GitHub Pages repository.
