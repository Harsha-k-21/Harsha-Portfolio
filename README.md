# Harsha K. — Portfolio

Responsive personal portfolio website showcasing my skills, projects, experience, education, and certifications across **Data Analytics, Data Engineering, Machine Learning, and Full Stack Development**.

## Tech Stack

- HTML5
- CSS3
- Responsive Web Design
- Google Fonts

## Project Structure

```text
Harsha-Portfolio/
├── index.html
├── css/
│   └── style.css
├── assets/
│   └── profile.png
└── README.md
```

## Run Locally

No build tools or frameworks are required.

1. Download or clone this repository.
2. Open `index.html` in a browser.

For a local development server, you can also use VS Code's **Live Server** extension.

## Deploy on GitHub Pages

### Option 1 — Deploy from the repository root

1. Create a new GitHub repository, for example `portfolio`.
2. Upload these files and folders while keeping the structure unchanged:
   - `index.html`
   - `css/style.css`
   - `assets/profile.png`
   - `README.md`
3. Commit and push the files.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select your main branch and the `/ (root)` folder.
7. Save.
8. GitHub will provide your portfolio URL.

### Option 2 — Git commands

```bash
git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

Then enable GitHub Pages from **Settings → Pages** using the `main` branch and `/ (root)`.

## Important

Keep `index.html` in the **root of the repository**. The stylesheet path is:

```html
<link rel="stylesheet" href="css/style.css">
```

and the profile image path is:

```html
<img src="assets/profile.png" alt="Harsha K.">
```

This makes the project work correctly on GitHub Pages without embedding the image directly inside the HTML.

## Contact

- GitHub: https://github.com/Harsha-k-21
- LinkedIn: https://www.linkedin.com/in/venkata-sivarama-sri-harsha-kota-5912261a8/
- Email: imharshak21@gmail.com
