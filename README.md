# Git & GitHub Workshop Portfolio Template

A customizable portfolio template for the Git & GitHub Workshop. Showcase your GitHub projects, skills, and personal details in a clean, interactive web page.

## Features

- **Responsive Design**: Works on desktop and mobile devices.
- **Interactive Elements**: Hover effects, toggles, and dynamic content.
- **Easy Customization**: Edit HTML, CSS, and JavaScript to personalize.
- **GitHub Integration**: Display your repositories and stats.
- **Workshop Ready**: Includes submission instructions for the workshop.

## Getting Started

### 1. Fork the Repository
- Go to [https://github.com/GitHer-Muna/GitHub-Workshop](https://github.com/GitHer-Muna/GitHub-Workshop).
- Click **Fork** in the top-right corner to create your own copy.

### 2. Clone Your Fork
Open your terminal and run:
```bash
git clone https://github.com/yourusername/GitHub-Workshop.git
```
Replace `yourusername` with your GitHub username.

### 3. Customize the Portfolio
Edit the following files in your code editor:

- **`index.html`**: Update your name, bio, projects, skills, and contact info. Add personal touches like hobbies or achievements.
- **`styles.css`**: Modify colors, fonts, layouts, and animations to match your style.
- **`script.js`**: Add or tweak JavaScript for interactivity (e.g., random facts, toggles).

**Tips for Customization:**
- Use emojis to add personality.
- Add links to your GitHub repositories.
- Include images or icons from free sources.
- Test changes locally by opening `index.html` in a browser.

### 4. Commit and Push Changes
```bash
git add .
git commit -m "Customize portfolio with my details"
git push origin main
```

### 5. Deploy to GitHub Pages
- Go to your forked repo on GitHub.
- Click **Settings** > **Pages**.
- Under **Source**, select **Deploy from a branch** and choose `main`.
- Click **Save**. Your site will be live at `https://yourusername.github.io/GitHub-Workshop`.

## Workshop Submission

After customizing and deploying your portfolio:

1. In your cloned repo, edit `submissions.html` to add your details (name, email, semester, roll number, and portfolio link).
2. Create a new branch: `git checkout -b submit-student-[your-number]`
3. Commit and push: `git add submissions.html && git commit -m "Submit portfolio" && git push origin submit-student-[your-number]`
4. Create a Pull Request to the original repo: [https://github.com/GitHer-Muna/GitHub-Workshop](https://github.com/GitHer-Muna/GitHub-Workshop).

## Prerequisites

- A GitHub account.
- Git installed on your computer ([download here](https://git-scm.com/)).
- Basic knowledge of HTML/CSS (optional, but helpful for customization).

## Support

If you have questions:
- Check the workshop's main README for detailed instructions.
- Ask your instructor or peers.
- Open an issue in this repo for technical help.

Happy coding! 🚀
