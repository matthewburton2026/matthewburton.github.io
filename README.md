# Student Portfolio

A plain HTML, CSS, and SVG portfolio site for a network administration and
cybersecurity student. There are no build steps, package dependencies,
analytics, or tracking scripts.

## Editing the site

Edit the HTML files directly:

- `index.html` is the home page and short introduction.
- `about.html` contains the bio, education, goals, and skills.
- `projects.html` contains three example project cards. Replace each TODO with
  your own Problem, What I did, Tools, and Outcome details. Keep project
  descriptions general and do not publish sensitive network information.
- `updates.html` is the learning journal. It includes a commented article
  template at the top of the file and three example entries.
- `contact.html` contains the email, LinkedIn, and GitHub placeholders. Update
  both the visible text and each link destination.
- `css/styles.css` contains all site styling. Update the CSS variables near the
  top to change the site colors or fonts.
- `assets/project-screenshot-placeholder.svg` is the local placeholder shown
  on each project card. Replace its references in `projects.html` with your
  own screenshot paths and update each image's alt text and TODO comment.
- Add your resume PDF at `assets/resume.pdf`; the home page already links to it.

The HTML page links are relative, so the site can be hosted at the default
GitHub Pages URL or on a custom domain.

## Adding an update

1. Open `updates.html` and copy the commented `<article>` template at the very
   top of the file.
2. Paste it inside the `update-list` section, before the older entries.
3. Replace the date, title, tags, and short body. Use the date in
   `YYYY-MM-DD` format for the `datetime` value and a readable date for the
   text shown on the page.
4. Keep entries newest-first. Describe challenges and lessons in general terms
   and leave out sensitive technical details.

## Publishing with GitHub Pages

1. Add these site files to the root of your GitHub repository and push them to
   the `main` branch.
2. In the repository, open **Settings**, then **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/(root)` folder, then save.
5. After GitHub Pages finishes publishing, the live site link will appear on
   the **Settings → Pages** screen.
