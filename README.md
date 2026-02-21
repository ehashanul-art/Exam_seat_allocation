# Smart Exam Seat Allocation System 🎓

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)

The **Smart Exam Seat Allocation System** is a mobile application developed at **Bangladesh Army University of Science and Technology (BAUST)**. It automates and modernizes the university exam seating process using a role-based platform built with **Flutter** and **Firebase**.

## 📖 Table of Contents
* [Objectives](#-objectives)
* [Key Features](#-key-features)
* [System Architecture](#-system-architecture)
* [Screenshots](#-screenshots)
* [Technologies Used](#-technologies-used)
* [Future Work](#-future-work)

---

## 🎯 Objectives
* **Automation:** Eliminates manual, error-prone work in creating seating charts[cite: 28].
* **Fairness:** Uses an alternating seating logic to separate students by Level-Team to prevent malpractice[cite: 29].
* **Accessibility:** Provides students instant access to their hall and seat numbers via mobile[cite: 30].
* **Real-time Updates:** Uses push notifications to inform students of assignments instantly[cite: 31].

---

## ✨ Key Features

### 🔐 Multi-Role Architecture
* [cite_start]**Main Admin:** Manages users (Students/Teachers) and promotes faculty to "Exam Admin"[cite: 24, 41].
* [cite_start]**Teacher (Admin):** Performs CRUD operations on Exams and Halls, and generates the seat plan with one click[cite: 42, 43].
* [cite_start]**Student:** Logs in with a unique Roll ID to view assigned hall and seat numbers[cite: 45].

### 🛠 Administrative Power
* [cite_start]**Dynamic Hall Setup:** Teachers can define hall layouts (rows, columns, benches) with live capacity calculation[cite: 54, 135].
* [cite_start]**Seating Algorithm:** Validates concurrent exams and applies alternating logic for fairness[cite: 47, 56].
* [cite_start]**Notification System:** Firebase Cloud Messaging (FCM) alerts all involved students once a plan is generated[cite: 59].

---

## 💻 Technologies Used
* [cite_start]**Frontend:** Flutter [cite: 182]
* [cite_start]**Backend:** Firebase (Auth, Firestore, Cloud Functions) [cite: 183, 184, 186, 188]
* [cite_start]**Push Notifications:** Firebase Cloud Messaging (FCM) [cite: 187]
* [cite_start]**Prototyping:** Figma [cite: 189]
* [cite_start]**Version Control:** Git & GitHub [cite: 190]

---

## 📸 Screenshots

> **Note:** To see these images, extract them from your PDF, name them as shown below, and place them in an `assets/` folder in your repository.

### Authentication & Roles
| Get Started | Admin Login | Teacher Login | Student Login |
| :---: | :---: | :---: | :---: |
| ![Get Started](assets/fig01.png) | ![Admin Login](assets/fig02.png) | ![Teacher Login](assets/fig03.png) | ![Student Login](assets/fig04.png) |
| [cite_start]*Splash Screen* [cite: 62] | [cite_start]*Main Admin* [cite: 75] | [cite_start]*Faculty Access* [cite: 76] | [cite_start]*Student Access* [cite: 77] |

### Management Dashboards
| Admin Dashboard | Add Course | All Exams | Hall Management |
| :---: | :---: | :---: | :---: |
| ![Admin](assets/fig05.png) | ![Add Course](assets/fig08.png) | ![All Exams](assets/fig11.png) | ![Add Hall](assets/fig14.png) |
| [cite_start]*Control Center* [cite: 79] | [cite_start]*Course Linking* [cite: 82] | [cite_start]*Exam List* [cite: 103] | [cite_start]*Layout Setup* [cite: 135] |

### Generation & Results
| Seat Plan Generator | Seat Plan List | Seat Map Viewer | Student Dashboard |
| :---: | :---: | :---: | :---: |
| ![Generator](assets/fig16.png) | ![Plan List](assets/fig17.png) | ![Map](assets/fig18.png) | ![Student Dash](assets/fig19.png) |
| [cite_start]*Algorithm Logic* [cite: 177] | [cite_start]*History* [cite: 178] | [cite_start]*Visual Grid* [cite: 179] | [cite_start]*Seat Assignment* [cite: 180] |

---

## 🚀 Future Work
* [cite_start]**Advanced Schedule Solver:** A "Master Generate" button for university-wide scheduling[cite: 206].
* [cite_start]**Data Import:** Bulk upload students via .csv files[cite: 208].
* [cite_start]**Admin Analytics:** Statistics on hall utilization and seating efficiency[cite: 209].

---

## 👨‍💻 Author
[cite_start]**Ehashanul Haque** [cite: 11]  
[cite_start]ID: 0802320205101090 [cite: 12]  
[cite_start]Level: 3, Term: I [cite: 13, 14]  
[cite_start]**Department of CSE, BAUST** [cite: 2]

