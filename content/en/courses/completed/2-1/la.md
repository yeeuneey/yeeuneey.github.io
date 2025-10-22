---
title: "Linear Algebra"
summary: ""
type: course
tags: ["2-1"]

image:
  filename: "uploads/media/linear_algebra.jpg"
  focal_point: "Center"
  preview_only: true
featured: true

goals:
  - "Goal 1️⃣: Understand core linear algebra concepts such as vectors, matrices, and linear transformations."
  - "Goal 2️⃣: Learn methods for solving problems in related fields and build practical application skills."
  - "Goal 3️⃣: Develop mathematical thinking and problem-solving abilities that enable real-world applications."

instructor: "Prof. Ji-Seung Kim"
department: "School of Computer Engineering / School of IT Information Engineering / School of Computer & Artificial Intelligence, JBNU"
room: "College of Engineering Building 6, Room B15"
language: "Korean"
credit: 3

textbook:
  title: "Introduction to Linear Algebra (International Fourth Edition)"
  author: "Gilbert Strang"
  publisher: "Wellesley-Cambridge Press"
  year: 2009
---

<!--more-->

## 📘 Course Overview

| Item | Details |
|------|---------|
| **Course Title** | Linear Algebra |
| **Instructor** | Prof. Ji-Seung Kim |
| **Affiliation** | Jeonbuk National University, School of Computer Engineering (and related departments) |
| **Classroom** | Engineering Building 6, Room B15 |
| **Language** | Korean |

---

## 🎯 Course Objectives

1️⃣ Grasp the foundational elements of linear algebra, including vectors, matrices, and linear transformations.  
2️⃣ Practice solving problems in related disciplines to strengthen applied skills.  
3️⃣ Cultivate mathematical reasoning and problem-solving capabilities for real-world scenarios.

---

## 📖 Textbook

> *Introduction to Linear Algebra (International Fourth Edition)*  
> Gilbert Strang · Wellesley-Cambridge Press (2009)

---

## 🧮 Evaluation Breakdown

<canvas id="evaluationChart" width="400" height="400"></canvas>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx = document.getElementById('evaluationChart');
new Chart(ctx, {
  type: 'pie',
  data: {
    labels: ['Midterm Exam', 'Final Exam', 'Assignments', 'Attendance'],
    datasets: [{
      data: [45, 45, 10, 0],
      backgroundColor: ['#9ad0f5', '#ffb7b2', '#b5ead7', '#ffdac1'],
      borderColor: '#222',
      borderWidth: 2
    }]
  },
  options: {
    plugins: {
      legend: {
        position: 'bottom',
        labels: { color: '#ddd', font: { size: 14 } }
      }
    }
  }
});
</script>

---

## 📆 Weekly Topics

| Week | Learning Goal | Outline |
|------|---------------|---------|
| 1 | Course introduction and vector fundamentals | Course overview; vectors and linear combinations |
| 2 | Inner products and matrices | Lengths, dot products, and matrix basics |
| 3 | Linear equations and elimination | Vector equations, linear systems, and matrix elimination |
| 4 | Matrix operations and inverses | Matrix operations, inverse matrices, LU factorization |
| 5 | Transposes and vector spaces | Transposes, permutations, and spaces of vectors |
| 6 | Rank and solving linear systems | Rank, row-reduced form, solutions to `Ax = b` |
| 7 | Bases and dimensions | Linear independence, bases, dimension, and the four subspaces |
| 8 | Midterm exam | Examination |
| 9 | Orthogonality and least squares | Orthogonality, projections, and least-squares solutions |
| 10 | Determinants | Determinants, permutations, cofactors |
| 11 | Eigenvalues and diagonalization | Eigenvalues and diagonalization techniques |
| 12 | Differential equations and symmetric matrices | Applications to differential equations; symmetric matrices |
| 13 | Similar matrices and SVD | Similarity transforms and singular value decomposition |
| 14 | Linear transformations and pseudoinverses | Matrices of linear transformations; pseudoinverses |
| 15 | Final exam | Examination |

---
