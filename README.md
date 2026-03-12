# Dev Toolkit - Contributors Wall

A community-driven project where developers add their profile card by contributing a simple JSON file. Built to help beginners make their **first open-source contribution**.

## Live Preview

Open `index.html` in your browser to see all contributor profile cards displayed in a beautiful grid.

## How to Contribute

1. **Fork** this repository
2. **Clone** your fork locally
3. **Create a branch** for your contribution
4. **Add your JSON file** in the `contributors/` folder
5. **Open a Pull Request**

See the full step-by-step guide in [CONTRIBUTING.md](CONTRIBUTING.md).

## Contributor JSON Format

Create a file named `<your-github-username>.json` inside the `contributors/` folder:

```json
{
  "name": "Your Name",
  "github": "your-github-username",
  "avatar": "https://github.com/your-github-username.png",
  "bio": "A short bio about yourself",
  "skills": ["Skill 1", "Skill 2", "Skill 3"],
  "social": {
    "twitter": "",
    "linkedin": "",
    "website": ""
  }
}
```

## Project Structure

```
dev-toolkit/
├── contributors/        ← Add your JSON file here!
│   └── naol.json
├── assets/
│   ├── css/
│   │   └── style.css
│   └── images/
├── index.html
├── script.js
├── README.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── LICENSE
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
