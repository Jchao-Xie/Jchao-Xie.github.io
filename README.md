# Jingchao Xie Academic Homepage

A static GitHub Pages homepage inspired by minimal academic websites:

- top navigation with section anchors
- profile photo, name, position, affiliation
- LinkedIn, GitHub, Google Scholar, and email links
- Bio, News, Publications, Experience, and Education sections
- no Project Experience section

## Deploy

Create a public GitHub repository named:

```text
Jchao-Xie.github.io
```

Copy the files in this folder into the repository root:

```text
index.html
style.css
assets/
README.md
```

Commit and push:

```bash
git init
git add .
git commit -m "Initial academic homepage"
git branch -M main
git remote add origin https://github.com/Jchao-Xie/Jchao-Xie.github.io.git
git push -u origin main
```

Then open:

```text
https://Jchao-Xie.github.io
```

## Replace profile photo

Put your real portrait here:

```text
assets/profile.jpg
```

Then edit `index.html`:

```html
<img class="portrait" src="assets/profile.jpg" alt="Jingchao Xie profile photo" />
```

## Edit content

All page text is in `index.html`. The styling is in `style.css`.
