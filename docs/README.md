# 📚 GenAI Documentation

## 📝 Overview

**GenAI** is a Python project that serves as a testing ground for various development tools and best practices, including:

- **Poetry** for dependency management
- **GitHub Actions** for CI/CD automation
- **Renovate** for automated dependency updates
- **Pre-commit hooks** for code quality enforcement

This document provides guidelines on how to install, use, and contribute to the project.

---

## 🚀 Quick Start

### **1️⃣ Install Poetry**

Ensure you have **Poetry** installed. If not, install it with:

```sh
curl -sSL https://install.python-poetry.org | python3 -
```

Verify installation:

```sh
poetry --version
```

### **2️⃣ Clone the Repository**

```sh
git clone https://github.com/NexelAI/GenAI.git
cd GenAI
```

### **3️⃣ Install Dependencies**

```sh
poetry install
```

### **4️⃣ Run the Application**

```sh
poetry run python src/main.py
```

---

## 🧪 Running Tests

To execute all tests:

```sh
poetry run pytest tests/
```

To run a specific test:

```sh
poetry run pytest tests/test_main.py
```

---

## 🔄 Keeping Dependencies Updated

We use **Renovate** to manage dependencies automatically.
However, if you want to update manually:

```sh
poetry update
```

---

## 🛠 Development Guide

### **Code Style & Linting**

This project enforces **PEP8, Black, isort, and pylint** via **pre-commit hooks**.
To format and lint your code before committing:

```sh
pre-commit run --all-files
```

### **Pre-commit Setup**

```sh
poetry self add pre-commit
pre-commit install
```

---

## 🔧 GitHub Actions

This project uses **GitHub Actions** for CI/CD.

- **`ci.yml`**: Runs tests and linting on each push.
- **`renovate.json`**: Handles automated dependency updates.

---

## 🤝 Contributing

Contributions are welcome! Please read our CONTRIBUTING.md file for guidelines on how to contribute.

---

## 🌟 License

This project is licensed under the **GPL-3.0-only** License.
See the [`LICENSE`](../LICENSE) file for details.

---

## 😇 Support & Questions

For general questions, visit our **[GitHub Discussions](https://github.com/NexelAI/GenAI/discussions)**.
For bug reports or feature requests, check out our **[Issue Tracker](https://github.com/NexelAI/GenAI/issues)**.

---

🚀 **Happy Coding!**
