# 🤝 Contribution Guidelines

Thank you for considering contributing to **CodePilot**! Contributions of all kinds are welcome — bug reports, feature requests, documentation improvements, and code changes.

---

## 📋 Before You Start

1. **Read the [setup guide](setup.md)** to get the project running locally.
2. **Check existing issues** to avoid duplicating effort.
3. **Open an issue first** if you plan to make a significant change, so we can discuss it before you invest time coding.

---

## 🌿 Branching Strategy

We follow a simple branching model:

| Branch | Purpose |
|--------|---------|
| `main` | Stable, production-ready code |
| `dev` | Active development branch |
| `feature/<name>` | New features |
| `fix/<name>` | Bug fixes |
| `docs/<name>` | Documentation updates |

Always branch off from `main` (or `dev` if specified in the issue).

---

## 🔧 Making Changes

### 1. Fork the Repository

Click **Fork** at the top of the GitHub page to create your own copy.

### 2. Clone Your Fork

```bash
git clone https://github.com/your-username/y-CodePilot_DeepSeek_R1.git
cd y-CodePilot_DeepSeek_R1
```

### 3. Create a Feature Branch

```bash
git checkout -b feature/your-feature-name
```

### 4. Make Your Changes

- Keep commits small and focused.
- Write clear, descriptive commit messages.
- Follow existing code style and conventions.

### 5. Test Your Changes

Ensure the app runs correctly after your changes:

```bash
streamlit run app.py
```

### 6. Push and Open a Pull Request

```bash
git push origin feature/your-feature-name
```

Then open a **Pull Request** against the `main` branch on GitHub.

---

## ✅ Pull Request Checklist

Before submitting a PR, please confirm:

- [ ] The app runs without errors locally
- [ ] Code follows the existing style
- [ ] Relevant documentation is updated
- [ ] The PR description clearly explains *what* changed and *why*

---

## 🐛 Reporting Bugs

Open a [GitHub Issue](https://github.com/your-username/y-CodePilot_DeepSeek_R1/issues) with the following information:

- **Description:** What happened?
- **Steps to reproduce:** How can we replicate it?
- **Expected behavior:** What should happen?
- **Environment:** OS, Python version, Ollama version

---

## 💡 Suggesting Features

Open a GitHub Issue with the label `enhancement` and describe:

- The problem you're trying to solve
- Your proposed solution
- Any alternatives you've considered

---

## 📝 Code of Conduct

Please be respectful and constructive in all interactions. We follow a standard open-source code of conduct — be kind, inclusive, and collaborative.
