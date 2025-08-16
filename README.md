# GitHub Actions Workflow Setup

This project uses **GitHub Actions** to enforce linting rules with ESLint.  
All workflow files must be stored in a specific folder structure so that GitHub can detect and run them automatically.

---

## 📂 Folder Structure

Your repository should look like this:
my-project/
├── .github/
│ └── workflows/
│ └── your-github-action-file-name.yml
├── src/
│ └── index.js
├── package.json
├── eslint.config.js
└── README.md
