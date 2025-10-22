---
title: "Computer Architecture"
summary: ""
type: course
tags: ["2-2"]

goals:
  - "Goal 1️⃣: Understand the internal components of a computer system and how they operate together."
  - "Goal 2️⃣: Learn how instructions are interpreted and the principles behind processor design."
  - "Goal 3️⃣: Grasp pipelining and memory hierarchies to recognize how computer performance can be improved."

instructor: "Prof. Soo-Kyung Yoon"
department: "School of Computer Engineering / School of IT Information Engineering / School of Intelligent IT Engineering / School of Computer & Artificial Intelligence, JBNU"
room: "College of Engineering Building 7, Room 534"
language: "Korean"
credit: 3

textbook:
  title: "Computer Organization and Design RISC-V Edition: The Hardware/Software Interface"
  author: "David A. Patterson, John L. Hennessy"
  publisher: "Morgan Kaufmann"
  year: 2017
---

<!--more-->

## 📘 Course Overview

| Item | Details |
|------|---------|
| **Course Title** | Computer Architecture |
| **Instructor** | Prof. Soo-Kyung Yoon |
| **Affiliation** | Jeonbuk National University, School of Computer Engineering (and related departments) |
| **Classroom** | Engineering Building 7, Room 534 |
| **Language** | Korean |

---

## 🎯 Course Objectives

1️⃣ Understand the structure and behavior of the key elements inside a computer system.  
2️⃣ Study the instruction execution pipeline and the design concepts behind processors.  
3️⃣ Explore pipelining and memory hierarchy strategies to learn how performance is enhanced.

---

## 📖 Textbook

> *Computer Organization and Design RISC-V Edition: The Hardware/Software Interface*  
> David A. Patterson & John L. Hennessy · Morgan Kaufmann (2017)

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
      data: [45, 45, 10, 0],
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
| 1 | Introduce the course and overview computer architecture | Introduction to Computer Architecture |
| 2 | Understand abstraction layers in computers | Computer Abstractions and Technology |
| 3 | Study instruction formats and performance I | Instruction set (RISC-V) and number representation |
| 4 | Study instruction formats and performance II | RISC addressing modes; translating and starting a program |
| 5 | Study instruction formats and performance III | Advanced RISC-V instruction set topics |
| 6 | Study instruction formats and performance IV | Program translation and execution flow |
| 7 | Explore computer arithmetic I | Arithmetic for computers: integer and floating-point operations |
| 8 | Midterm exam | Examination |
| 9 | Explore computer arithmetic II | Floating-point arithmetic and advanced techniques |
| 10 | Explore computer arithmetic III | ALU design and performance considerations |
| 11 | Learn processor structure I | Datapath, control, pipelining, and hazards |
| 12 | Learn processor structure II | Pipelining control flow and hazard handling |
| 13 | Understand memory hierarchy I | Cache design and memory technologies |
| 14 | Understand memory hierarchy II | Virtual memory and cache performance tuning |
| 15 | Final exam | Examination |

---
