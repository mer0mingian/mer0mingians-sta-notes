# mer0mingians-sta-notes
Some notes and learnings about playing Star Trek Adventures.

## How to add new subpages

Based on the repository structure, here's how you can organize subpages in your GitHub Pages site:

1. Create a directory for your pages: Add HTML files in the pages directory following your current LCARS style.
```bash
.
├── index.html
├── pages/
│   ├── milestones.html
│   ├── values.html
│   └── scars.html
```

2. Modify your navigation in index.html to link to the subpages: Create a new HTML file for each subpage using the existing lcars-standard-picard.html as a template. Each page should use the same CSS and JavaScript assets.

```css
<nav id="secondary-nav">
    <a href="pages/values.html">Values</a>
    <a href="pages/milestones.html">Milestones</a>
    <a href="pages/scars.html">Scars</a>
</nav>
```

3. Redeploy: The pages will be accessible at: `yourusername.github.io/mer0mingians-sta-notes/pages/pagename.html`

Remember to add navigation back to the main page in each subpage:
```css
<nav id="primary-nav">
    <a href="../index.html">Main Page</a>
</nav>
```
