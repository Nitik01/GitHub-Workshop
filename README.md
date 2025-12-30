# Git & GitHub Workshop Portfolio Template

A simple, beginner-friendly portfolio template for the Git & GitHub Workshop. Create your own GitHub portfolio website to showcase projects, skills, and your coding journey—even if you're new to coding!

## Features

- **Easy to Edit**: Clear instructions and placeholders make customization simple for all skill levels.
- **Responsive Design**: Looks great on desktop and mobile.
- **Interactive Elements**: Skills toggle, project links, and auto-updating date.
- **GitHub-Focused**: Highlight your repositories, stars, and contributions.
- **Workshop-Ready**: Includes submission form and deployment guide.

## Getting Started

### 1. Fork the Repository
- Visit [https://github.com/GitHer-Muna/Git-GitHub-Workshop](https://github.com/GitHer-Muna/Git-GitHub-Workshop).
- Click **Fork** in the top-right corner to create your own copy.

### 2. Clone Your Fork
Open your terminal and run:
```bash
git clone https://github.com/yourusername/Git-GitHub-Workshop.git
cd Git-GitHub-Workshop
```
Replace `yourusername` with your GitHub username.

### 3. Customize Your Portfolio
Open `index.html` in a text editor (like VS Code). Follow the comments for easy editing:

- **Header**: Replace `[Your Name]` with your name and update the intro.
- **About Me**: Add your bio and a fun fact.
- **Skills**: List your technologies; add more `<li>` items.
- **Projects**: Follow the numbered steps in the comments to add your GitHub projects (name, description, stars, language, link).
- **Learning**: Update with what you're studying.
- **Contact**: Add your email and GitHub profile link.
- **Footer**: The date updates automatically—no need to edit!

**Tips**:
- Replace text in `[brackets]` with your info.
- For projects, check your GitHub repo for stars and language.
- Test locally: Open `index.html` in your browser.
- No coding experience needed—just text editing!

### 4. Commit and Push Changes
```bash
git add .
git commit -m "Customize my portfolio"
git push origin main
```

### 5. Deploy to GitHub Pages
- Go to your forked repo on GitHub.
- Click **Settings** > **Pages**.
- Under **Source**, select **Deploy from a branch** and choose `main`.
- Your site goes live at `https://yourusername.github.io/Git-GitHub-Workshop` (may take a few minutes).

## Workshop Submission

After customizing and deploying your portfolio:

1. In your cloned repo, edit `submissions.html` to add your details (name, email, semester, roll number, and portfolio link).
2. Create a new branch: `git checkout -b submit-student-[your-number]`
3. Commit and push: `git add submissions.html && git commit -m "Submit portfolio" && git push origin submit-student-[your-number]`
4. Create a Pull Request to the original repo: [https://github.com/GitHer-Muna/Git-GitHub-Workshop](https://github.com/GitHer-Muna/Git-GitHub-Workshop).

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
