# Hong-Liang Lin — Academic Portfolio

This repository is ready for GitHub Pages.

## Recommended repository name

`Hong-Liang-de.github.io`

## Publish

1. Extract this ZIP.
2. Upload the **contents** of the extracted folder to the root of your GitHub repository.
3. In GitHub open **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save and wait for deployment.

Your website should then be available at:

`https://Hong-Liang-de.github.io`

## Before publishing

Edit `index.html` and replace:

- `your.email@example.com`
- `https://www.linkedin.com/in/your-linkedin/`

Replace:

`assets/Hong-Liang_Lin_CV.pdf`

with your real CV, keeping the same filename.

## Add your portrait

In `index.html`, replace the entire block:

```html
<div class="portrait">
  <div class="portrait-monogram">HL</div>
  <div class="portrait-caption">Replace with your portrait</div>
</div>
```

with:

```html
<img class="portrait" src="assets/profile.jpg" alt="Portrait of Hong-Liang Lin">
```

Then add your photo as `assets/profile.jpg`.

## Add project images or GIFs

You can replace the project visual blocks with images or GIFs. For example:

```html
<a class="project-visual" href="projects/polymer-sleepers.html">
  <img src="assets/polymer-sleeper.gif" alt="ABAQUS railway sleeper simulation">
</a>
```

Add this to `assets/style.css` if needed:

```css
.project-visual img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 28px;
}
```
