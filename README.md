# Nature, Unfiltered — HTML Final Project

A responsive, single-page HTML5 site about mountains and lakes, forest waterfalls, oceans, and simple ways to care for nature.

## Files

- `index.html` — complete page structure and embedded CSS.
- `assets/mountain-lake.svg` — original local illustration used as an image.
- `assets/forest-waterfall.svg` — original local illustration used as an image.
- `assets/ocean-waves.svg` — original local illustration used as an image.

All three `<img>` elements use descriptive `alt` text and local asset paths so they do not depend on third-party image URLs. The page includes a document type, `head`, `title`, `body`, semantic landmarks, a heading hierarchy, a list with three items, and an external link.

## Validate the page

1. Open `index.html` locally in your browser and confirm that all three illustrations appear.
2. Open the [W3C Markup Validation Service](https://validator.w3.org/). Choose **Validate by File Upload** and upload `index.html`.
3. Fix any reported errors before submitting. Warnings are not usually graded as errors in the assignment instructions.
4. After publishing the page, enter its public URL into the [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/).

## Publish with GitHub Pages

1. Create a new public GitHub repository, for example `nature-unfiltered`.
2. Upload `index.html`, `README.md`, and the entire `assets` folder. Keep the folder structure unchanged.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose the `main` branch and `/(root)`, then save.
5. Wait for GitHub Pages to publish the site. Open the URL shown in **Settings → Pages** and test the navigation and images.
6. Submit that public URL for peer review. A typical URL looks like `https://YOUR-USERNAME.github.io/nature-unfiltered/`.

The GitHub Pages URL above is only a format example. It will not work until you publish the files in your own GitHub account.

## Peer-review checklist for the three classmates' sites

For each classmate, open the submitted URL and record whether:

- The page loads instead of showing a 404 error.
- The source includes `<!doctype html>`, `head`, `title`, `body`, `h1`, and `main`.
- There are at least three list items and three images.
- Every image loads and has meaningful, descriptive `alt` text.
- There is an external link and at least three semantic elements.
- Heading levels follow a logical order without skipping (for example, `h1` → `h2`, not `h1` → `h3`).
- The W3C validator and WAVE do not report errors.

Follow your course's grading instructions: do not deduct points for warnings alone if the rubric says warnings are allowed.
