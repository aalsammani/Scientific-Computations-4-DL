# Contributing to MTSC 821 Course Materials

Thank you for your interest in improving this course! This document provides guidelines for contributing to the repository.

## 📝 Types of Contributions

### 1. Reporting Errors
If you find errors in the course materials:
- **Typos** in lecture notes or assignments
- **Mathematical errors** in proofs or examples
- **Code bugs** in notebooks or scripts
- **Broken links** or missing files

### 2. Suggesting Improvements
- Clearer explanations for difficult concepts
- Additional examples or practice problems
- Better visualizations or diagrams
- Supplementary resources

### 3. Adding Content
- Solutions to practice problems
- Alternative proofs or derivations
- Code implementations in different languages
- Study guides or cheat sheets

---

## 🔄 How to Contribute

### Option 1: Open an Issue (Easiest)

1. Go to the [Issues](../../issues) tab
2. Click "New Issue"
3. Choose the appropriate template:
   - 🐛 Bug Report (for errors)
   - 💡 Feature Request (for suggestions)
   - 📚 Content Contribution (for new material)
4. Fill in the details and submit

### Option 2: Submit a Pull Request

For those comfortable with Git:

1. **Fork** the repository
2. **Clone** your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/MTSC821-Scientific-Computations.git
   ```
3. **Create a branch** for your changes:
   ```bash
   git checkout -b fix/typo-lecture-1
   ```
4. **Make your changes** and commit:
   ```bash
   git add .
   git commit -m "Fix typo in Lecture 1, page 5"
   ```
5. **Push** to your fork:
   ```bash
   git push origin fix/typo-lecture-1
   ```
6. **Open a Pull Request** on GitHub

---

## 📋 Contribution Guidelines

### For LaTeX Files
- Keep the existing formatting style
- Use the provided templates
- Ensure the document compiles without errors
- Include any new packages in the preamble comments

### For Jupyter Notebooks
- Clear all output before committing
- Include markdown cells explaining the code
- Use consistent variable naming
- Add comments for complex operations

### For Python Code
- Follow PEP 8 style guidelines
- Include docstrings for functions
- Add type hints where appropriate
- Write unit tests for new functions

### For Markdown Files
- Use consistent heading levels
- Include a table of contents for long documents
- Check links before submitting

---

## 🏷️ Commit Message Format

Use clear, descriptive commit messages:

```
<type>: <short description>

<optional longer description>
```

Types:
- `fix`: Bug fixes or error corrections
- `feat`: New features or content
- `docs`: Documentation changes
- `style`: Formatting changes (no code change)
- `refactor`: Code restructuring

Examples:
```
fix: Correct eigenvalue formula in Lecture 3

The formula on page 12 had a sign error in the
characteristic polynomial expansion.
```

```
feat: Add Python implementation of QR decomposition

Includes both Gram-Schmidt and Householder methods
with numerical stability comparisons.
```

---

## ✅ Review Process

1. All contributions will be reviewed by the instructor
2. You may be asked to make changes before merging
3. Accepted contributions will be credited in the acknowledgments

---

## 📞 Questions?

- Open an issue with the "question" label
- Email: aalsammani@desu.edu

Thank you for helping improve this course! 🎓
