# Carlos Maldonado — Engineering Portfolio

Live portfolio site built with HTML/CSS. Deployed via GitHub Pages.

## 🚀 How to deploy (step by step)

### 1. Create a GitHub account
Go to https://github.com and create a free account if you don't have one.

### 2. Create a new repository
- Click the **+** icon → **New repository**
- Name it exactly: `carlosmaldonado224.github.io`
  *(replace `carlosmaldonado224` with your actual GitHub username)*
- Set it to **Public**
- Click **Create repository**

### 3. Upload your files
- Click **uploading an existing file**
- Drag and drop all files from this folder:
  - `index.html`
  - `README.md`
  - Any images you add to the `images/` folder
  - Your CV PDF (rename it `Carlos_Maldonado_CV.pdf`)
- Click **Commit changes**

### 4. Enable GitHub Pages
- Go to your repo → **Settings** → **Pages** (left sidebar)
- Under **Source**, select **Deploy from a branch**
- Select branch: `main`, folder: `/ (root)`
- Click **Save**

### 5. Your site is live!
After ~2 minutes, your portfolio will be at:
`https://carlosmaldonado224.github.io`

---

## 📁 File structure

```
your-repo/
├── index.html          ← Main portfolio page
├── README.md           ← This file
├── Carlos_Maldonado_CV.pdf  ← Your CV (add this)
└── images/             ← Create this folder for project images
    ├── thesis-cryo.jpg
    ├── atv-steering.jpg
    ├── fork-granta.jpg
    └── sempertex.jpg
```

---

## 🖼️ Adding project images

1. Create a folder called `images/` in your repository
2. Upload your images there
3. In `index.html`, find each `<div class="project-img-placeholder">` and replace it with:

```html
<img src="images/your-image-name.jpg" alt="Project description" class="project-img">
```

**Recommended image size:** 800×450px (16:9), under 500KB each.

For the Granta project, you can use screenshots of your Ashby diagrams from the report.

---

## 📝 How to update content

Open `index.html` in any text editor (Notepad, VS Code, etc.) and search for the text you want to change. The file is organized in clear sections with comments.

---

## 🔗 Where to add the portfolio link

Once live, add the URL to:
- Your CV (next to LinkedIn)
- Your Tesla application profile
- Your LinkedIn "Website" field

---

*Built for the Tesla European Graduate Development Program application, Fall 2026.*
