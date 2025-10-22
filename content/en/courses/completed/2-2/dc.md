---
title: "Data Communications"
summary: ""
type: course
tags: ["2-2"]

goals:
  - "Goal 1️⃣: Learn the technical elements—transmission media, signals, and equipment—required to transfer data between heterogeneous computers."
  - "Goal 2️⃣: Understand communication procedures and network configuration principles that enable reliable, loss-free transmission."
  - "Goal 3️⃣: Build the ability to analyze the theoretical foundations and practical applications of computer networks."

instructor: "Prof. Ki-Hwan Cho"
department: "School of Computer Engineering / School of IT Information Engineering / School of Intelligent IT Engineering / School of Computer & Artificial Intelligence, JBNU"
room: "College of Engineering Building 3, Room 311"
language: "Korean"
credit: 3

textbook:
  title: "Data & Computer Communications (10th Edition)"
  author: "William Stallings"
  publisher: "Prentice Hall"
  year: 2014
---

<!--more-->

## 📘 Course Overview

| Item | Details |
|------|---------|
| **Course Title** | Data Communications |
| **Instructor** | Prof. Ki-Hwan Cho |
| **Affiliation** | Jeonbuk National University, School of Computer Engineering (and related departments) |
| **Classroom** | Engineering Building 3, Room 311 |
| **Language** | Korean |

---

## 🎯 Course Objectives

1️⃣ Study the media, signals, and network devices necessary for transferring data across computers.  
2️⃣ Understand the end-to-end communication process and how networks are structured to prevent data loss.  
3️⃣ Gain competency in analyzing both the theoretical underpinnings and practical usage of computer networks.

---

## 📖 Textbook

> *Data & Computer Communications (10th Edition)*  
> William Stallings · Prentice Hall (2014)

---

## 🧮 Evaluation Breakdown

<canvas id="evaluationChart" width="400" height="400"></canvas>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx = document.getElementById('evaluationChart');
new Chart(ctx, {
  type: 'pie',
  data: {
    labels: ['Midterm Exam', 'Final Exam', 'Attendance', 'Assignments', 'Other'],
    datasets: [{
      data: [35, 35, 10, 16, 4],
      backgroundColor: ['#9ad0f5', '#ffb7b2', '#ffdac1', '#b5ead7', '#c7ceea'],
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
| 1 | Introduce data communications | Concepts of data communication; computer communication vs. networking |
| 2 | Understand protocol architectures | Compare OSI and TCP/IP models; roles and functions |
| 3 | Grasp transmission fundamentals | Types of transmission media and their physical properties |
| 4 | Explore transmission media | Characteristics and use cases of wired/wireless media *(Quiz 1)* |
| 5 | Learn signal coding techniques I | Analog and digital signal types and conversions |
| 6 | Study modulation & error control | PCM; error detection and correction schemes |
| 7 | Master data link control I | Flow control concepts and sliding-window algorithms |
| 8 | Midterm exam | Examination |
| 9 | Master data link control II | HDLC structure; error types and countermeasures |
| 10 | Understand multiplexing | Characteristics of FDMA, TDMA, CDMA |
| 11 | Learn LAN fundamentals I | LAN topologies and protocol architectures |
| 12 | Learn LAN fundamentals II | CSMA/CD algorithm; hubs and switches |
| 13 | Examine high-speed LANs | Structure and operation of Ethernet *(Quiz 2)* |
| 14 | Explore wireless LANs | Wi-Fi, CSMA/CA algorithm, and applications |
| 15 | Final exam | Examination |

---
