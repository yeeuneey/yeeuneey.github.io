---
title: "Linux Programming"
summary: ""
type: course
tags: ["2-1"]

goals:
  - "Goal 1️⃣: Develop proficiency with the command-line interface (CLI) in a Linux environment."
  - "Goal 2️⃣: Understand Linux system administration concepts and the structure of the operating system."
  - "Goal 3️⃣: Build skills for managing network services and performing systems programming on Linux."

instructor: "Prof. A-Mi Kim"
department: "School of Computer Engineering / School of IT Information Engineering / School of Computer & Artificial Intelligence, JBNU"
room: "College of Engineering Building 7, Room 204"
language: "Korean"
credit: 3

textbook:
  title: "Principles and Practice of Linux Programming"
  author: "Byeong-Mo Chang"
  publisher: "Saengneung Publishing"
  year: 2022
---

<!--more-->

## 📘 Course Overview

| Item | Details |
|------|---------|
| **Course Title** | Linux Programming |
| **Instructor** | Prof. A-Mi Kim |
| **Affiliation** | Jeonbuk National University, School of Computer Engineering (and related departments) |
| **Classroom** | Engineering Building 7, Room 204 |
| **Language** | Korean |

---

## 🎯 Course Objectives

1️⃣ Gain confidence using the Linux command line to execute everyday tasks.  
2️⃣ Learn the architecture of the Linux operating system and essential administration skills.  
3️⃣ Manage network services and practice systems programming techniques within Linux.

---

## 📖 Textbook

> *Principles and Practice of Linux Programming*  
> Byeong-Mo Chang · Saengneung Publishing (2022)

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
      data: [35, 35, 10, 20],
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
| 1 | Introduction and installation | Linux overview and installation |
| 2 | Linux system & commands | Setting up the system; essential commands *(Lab Assignment 1)* |
| 3 | Directory and file management | Managing directories and files in the CLI *(Lab Assignment 2)* |
| 4 | Users and permissions | Understanding permissions; user management *(Lab Assignment 3)* |
| 5 | Processes & I/O redirection | Process concepts and redirection *(Lab Assignment 4)* |
| 6 | Additional utilities | Frequently used commands such as search and compression *(Lab Assignment 5)* |
| 7 | C programming on Linux | Developing C programs in the Linux environment |
| 8 | Midterm exam | Examination |
| 9 | System calls & file I/O I | System calls; low-level file I/O *(Lab Assignment 6)* |
| 10 | File I/O II | High-level file I/O *(Lab Assignment 7)* |
| 11 | Memory & process management | Dynamic memory; process creation/execution/termination *(Lab Assignment 8)* |
| 12 | IPC — signals & shared memory | Inter-process communication *(Lab Assignment 9)* |
| 13 | IPC — sockets & threads | Network sockets and thread programming *(Lab Assignment 10)* |
| 14 | Parallel programming | Parallel programming concepts and thread usage |
| 15 | Final exam | Examination |

---
