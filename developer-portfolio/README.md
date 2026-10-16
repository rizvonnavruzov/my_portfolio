# Rizvon — Developer Portfolio

A responsive dark-themed portfolio built with HTML, CSS, and a small amount of JavaScript.

## Project structure

```text
developer-portfolio/
├── index.html   # Page content and sections
├── style.css    # Theme, layout, responsive styles
├── script.js    # Mobile navigation interaction
└── README.md    # Setup and publishing notes
```

## Run locally

No framework or package installation is required.

1. Download or extract this folder.
2. Open `index.html` in your browser.
3. For a better development workflow, open the folder in VS Code and use the Live Server extension.

## Personalize before publishing

Search `index.html` for these placeholders and replace them:

- `YOUR_EMAIL@example.com`
- `https://www.linkedin.com/`
- `https://github.com/`
- The example project repository link
- The second internship organization and dates
- Any skills or project descriptions that don't reflect your actual experience

Only describe work you personally did. Do not publish confidential code, private company details, credentials, or API keys.

## Publish with GitHub Pages

1. Create a GitHub repository named `your-username.github.io` (replace with your GitHub username).
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then save.
6. Wait for the deployment to finish. Your site should be available at `https://your-username.github.io/`.

GitHub may take a few minutes to publish the first version.

## Suggested next step: Django

Keep this static site as version 1. When you're ready to practice backend development, create a separate Django project that stores project information in a database and exposes an API. You can then connect the frontend to that API. A static portfolio does not need Django just to display content.
