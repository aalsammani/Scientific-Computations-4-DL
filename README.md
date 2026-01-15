# MTSC 821: Scientific Computations

<p align="center">
  <img src="docs/assets/banner.png" alt="Course Banner" width="800">
</p>

<p align="center">
  <strong>Graduate Course in Scientific Computing</strong><br>
  Delaware State University • Spring 2026
</p>

<p align="center">
  <a href="#-course-overview">Overview</a> •
  <a href="#-lectures">Lectures</a> •
  <a href="#-assignments">Assignments</a> •
  <a href="#-projects">Projects</a> •
  <a href="#-resources">Resources</a>
</p>

---

## 📋 Course Overview

**Instructor:** Dr. Abdallah Alsammani  
**Email:** aalsammani@desu.edu  
**Office Hours:** By appointment  
**Course Website:** [https://your-username.github.io/MTSC821-Scientific-Computations](https://your-username.github.io/MTSC821-Scientific-Computations)

### Course Description

This graduate-level course provides a comprehensive foundation in scientific computing, covering numerical linear algebra, optimization, and their applications to machine learning and data science. Students will develop both theoretical understanding and practical programming skills.

### Prerequisites

- Linear Algebra (undergraduate level)
- Calculus (multivariable)
- Programming experience (Python preferred)

### Learning Objectives

Upon completion of this course, students will be able to:

1. ✅ Master fundamental concepts in linear algebra and their computational aspects
2. ✅ Implement and analyze numerical algorithms for scientific computing
3. ✅ Apply optimization techniques to machine learning problems
4. ✅ Develop research-level understanding of advanced topics
5. ✅ Produce publication-quality research in scientific computing

---

## 📚 Lectures

| Week | Topic | Materials | Notebooks |
|:----:|-------|-----------|-----------|
| 1 | **Linear Algebra Foundations** | [PDF](lectures/pdf/Lecture01_LinearAlgebra.pdf) • [LaTeX](lectures/tex/Lecture01_LinearAlgebra.tex) | [Notebook](lectures/notebooks/Lecture01_LinearAlgebra.ipynb) |
| 2 | Matrix Decompositions | Coming Soon | Coming Soon |
| 3 | Eigenvalues & Eigenvectors | Coming Soon | Coming Soon |
| 4 | Singular Value Decomposition | Coming Soon | Coming Soon |
| 5 | Numerical Linear Algebra | Coming Soon | Coming Soon |
| 6 | Iterative Methods | Coming Soon | Coming Soon |
| 7 | Optimization Fundamentals | Coming Soon | Coming Soon |
| 8 | **Midterm Review** | — | — |
| 9 | Gradient Methods | Coming Soon | Coming Soon |
| 10 | Constrained Optimization | Coming Soon | Coming Soon |
| 11 | Machine Learning Applications | Coming Soon | Coming Soon |
| 12 | Deep Learning Foundations | Coming Soon | Coming Soon |
| 13 | Advanced Topics | Coming Soon | Coming Soon |
| 14 | Project Presentations | — | — |
| 15 | **Final Review** | — | — |

### Quick Access to Lectures

```
lectures/
├── pdf/           # Compiled PDF lecture notes
├── tex/           # LaTeX source files
└── notebooks/     # Interactive Jupyter notebooks
```

---

## 📝 Assignments

| # | Topic | Due Date | Files |
|:-:|-------|----------|-------|
| 1 | Vector Spaces & Linear Independence | Week 3 | [PDF](assignments/HW01.pdf) • [Solutions](assignments/HW01_solutions.pdf) |
| 2 | Matrix Operations & Decompositions | Week 5 | Coming Soon |
| 3 | Eigenvalue Problems | Week 7 | Coming Soon |
| 4 | SVD & Applications | Week 9 | Coming Soon |
| 5 | Optimization Methods | Week 11 | Coming Soon |
| 6 | Machine Learning Applications | Week 13 | Coming Soon |

---

## 🔬 Research Projects

Four publication-track research opportunities are available:

| Project | Title | Primary Area | Target Venue |
|:-------:|-------|--------------|--------------|
| 1 | Adaptive Streaming SVD | Numerical Linear Algebra | SIAM J. Sci. Comput. |
| 2 | Geometry-Aware Hybrid Optimization | Optimization Theory | NeurIPS / ICML |
| 3 | Interpretable Sparse PCA | Statistical Learning | JMLR / AISTATS |
| 4 | Spectral Learning Rate Adaptation | Deep Learning | ICLR / TMLR |

📄 [View Full Project Descriptions](projects/Graduate_Research_Projects.pdf)

---

## 💻 Code Examples

### Python Setup

```bash
# Clone the repository
git clone https://github.com/your-username/MTSC821-Scientific-Computations.git
cd MTSC821-Scientific-Computations

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Running Notebooks

```bash
# Start Jupyter Lab
jupyter lab

# Or Jupyter Notebook
jupyter notebook
```

---

## 📁 Repository Structure

```
MTSC821-Scientific-Computations/
│
├── 📂 lectures/
│   ├── pdf/                    # Compiled lecture PDFs
│   ├── tex/                    # LaTeX source files
│   └── notebooks/              # Jupyter notebooks with code examples
│
├── 📂 assignments/
│   ├── HW01.pdf               # Assignment PDFs
│   └── solutions/             # Solution files (posted after due date)
│
├── 📂 projects/
│   ├── Graduate_Research_Projects.pdf
│   └── templates/             # Project report templates
│
├── 📂 code/
│   ├── python/                # Python implementations
│   └── matlab/                # MATLAB implementations
│
├── 📂 resources/
│   ├── textbooks.md           # Recommended reading
│   ├── software.md            # Software installation guides
│   └── cheatsheets/           # Quick reference sheets
│
├── 📂 docs/
│   └── assets/                # Images and media files
│
├── 📂 templates/
│   ├── lecture_template.tex   # LaTeX template for lectures
│   ├── homework_template.tex  # LaTeX template for homework
│   └── notebook_template.ipynb # Jupyter notebook template
│
├── 📄 README.md               # This file
├── 📄 SYLLABUS.md             # Course syllabus
├── 📄 CONTRIBUTING.md         # How to contribute
├── 📄 requirements.txt        # Python dependencies
└── 📄 LICENSE                 # License information
```

---

## 📖 Resources

### Required Textbooks

1. **Linear Algebra and Optimization for Machine Learning** by Aggarwal
2. **Numerical Linear Algebra** by Trefethen & Bau
3. **Convex Optimization** by Boyd & Vandenberghe ([Free PDF](https://web.stanford.edu/~boyd/cvxbook/))

### Supplementary Materials

- [MIT OpenCourseWare - Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/)
- [3Blue1Brown - Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
- [Stanford CS229 - Machine Learning](https://cs229.stanford.edu/)

### Software

- **Python:** NumPy, SciPy, Matplotlib, PyTorch
- **MATLAB:** Optimization Toolbox, Statistics Toolbox
- **LaTeX:** TeX Live or MiKTeX

📄 [Full Software Installation Guide](resources/software.md)

---

## 📊 Grading

| Component | Weight |
|-----------|--------|
| Homework Assignments | 30% |
| Midterm Exam | 20% |
| Research Project | 35% |
| Final Presentation | 15% |

---

## 🗓️ Important Dates

| Event | Date |
|-------|------|
| First Day of Class | January 13, 2026 |
| Project Proposal Due | February 3, 2026 |
| Midterm Exam | March 2, 2026 |
| Project Draft Due | April 13, 2026 |
| Final Presentations | April 27-29, 2026 |
| Project Final Submission | May 4, 2026 |

---

## 🤝 Contributing

Students are encouraged to contribute to this repository by:
- Reporting errors or typos
- Suggesting improvements to lecture materials
- Sharing useful resources

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 📜 License

This course material is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

You are free to:
- **Share** — copy and redistribute the material
- **Adapt** — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit
- **NonCommercial** — You may not use the material for commercial purposes
- **ShareAlike** — You must distribute contributions under the same license

---

<p align="center">
  <strong>Delaware State University</strong><br>
  Division of Physics, Engineering, Mathematics, and Computer Science<br>
  © 2026 Dr. Abdallah Alsammani
</p>
