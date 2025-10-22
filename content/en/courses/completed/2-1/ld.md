---
title: "Logic Design"
summary: ""
type: course
tags: ["2-1"]

image:
  filename: "uploads/media/logic_design.jpg"
  focal_point: "Center"
  preview_only: true
featured: true

goals:
  - "Goal 1️⃣: Understand the core concepts and operating principles of digital systems to approach digital design with a broad perspective."
  - "Goal 2️⃣: Learn the fundamentals of combinational and sequential circuits, along with the devices that compose logic circuits."
  - "Goal 3️⃣: Build the ability to analyze and apply digital systems based on logic-circuit design skills."

instructor: "Prof. Soo-Kyung Yoon"
department: "School of Computer Engineering / School of IT Information Engineering / School of Intelligent IT Engineering / School of Computer & Artificial Intelligence, JBNU"
room: "College of Engineering Building 7, Room 534"
language: "Korean"
credit: 3

textbook:
  title: "Introduction to Digital Logic Circuits"
  author: "Seok-Gu Lim, Kyung-Ho Hong"
  publisher: "Hanbit Academy"
  year: 2016
---

<!--more-->

## 📘 Course Overview

| Item | Details |
|------|---------|
| **Course Title** | Logic Design |
| **Instructor** | Prof. Soo-Kyung Yoon |
| **Affiliation** | Jeonbuk National University, School of Computer Engineering (and related departments) |
| **Classroom** | Engineering Building 7, Room 534 |
| **Language** | Korean |

---

## 🎯 Course Objectives

1️⃣ Gain a broad understanding of digital systems by studying their fundamental concepts and behavior.  
2️⃣ Master the principles behind combinational and sequential logic circuits, including the basic components that form them.  
3️⃣ Apply logic-design knowledge to comprehend and build practical digital systems.

---

## 📖 Textbook

> *Introduction to Digital Logic Circuits*  
> Seok-Gu Lim & Kyung-Ho Hong · Hanbit Academy (2016)

---

## 🧮 Evaluation Breakdown

<canvas id="evaluationChart" width="400" height="400"></canvas>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx = document.getElementById('evaluationChart');
new Chart(ctx, {
  type: 'pie',
  data: {
    labels: ['Midterm Exam', 'Final Exam', 'Attendance', 'Assignments'],
    datasets: [{
      data: [40, 40, 10, 10],
      backgroundColor: ['#9ad0f5', '#ffb7b2', '#ffdac1', '#b5ead7'],
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
| 1 | Introduce digital systems | Overview of digital systems and the course |
| 2 | Number systems | Number systems used in digital computing |
| 3 | Logic gates | NOT, AND, OR, NAND, NOR, and other gates |
| 4 | Boolean algebra I | Boolean algebra basics, canonical forms, algebraic laws |
| 5 | Boolean algebra II & simplification I | Converting logic expressions; Karnaugh maps |
| 6 | Logic simplification II | Karnaugh-map practice *(Assignment 1)* |
| 7 | Combinational logic I | Designing combinational circuits |
| 8 | Midterm exam | Examination |
| 9 | Combinational logic II | Advanced combinational design |
| 10 | Flip-flops I | Operation of SR, D, and JK flip-flops |
| 11 | Flip-flops II | Applications of flip-flops |
| 12 | Sequential circuits | Overview and design of sequential circuits |
| 13 | Counters & registers I | Asynchronous/synchronous counters and registers *(Assignment 2)* |
| 14 | Counters & registers II | Advanced counter and register design |
| 15 | Final exam | Examination |

---
