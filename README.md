<img width="1152" height="2496" alt="Screenshot_20251115-233507" src="https://github.com/user-attachments/assets/35afcad0-b1e1-4fa0-8ba5-ab3f43f6a94d" /># Smart Exam Seat Allocation System 🎓

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
* **Automation:** Eliminates manual, error-prone work in creating seating charts.
* **Fairness:** Uses an alternating seating logic to separate students by Level-Team to prevent malpractice.
* **Accessibility:** Provides students instant access to their hall and seat numbers via mobile.
* **Real-time Updates:** Uses push notifications to inform students of assignments instantly.

---

## ✨ Key Features

### 🔐 Multi-Role Architecture
* **Main Admin:** Manages users (Students/Teachers) and promotes faculty to "Exam Admin".
* **Teacher (Admin):** Performs CRUD operations on Exams and Halls, and generates the seat plan with one click.
* **Student:** Logs in with a unique Roll ID to view assigned hall and seat numbers.

### 🛠 Administrative Power
* **Dynamic Hall Setup:** Teachers can define hall layouts (rows, columns, benches) with live capacity calculation.
* **Seating Algorithm:** Validates concurrent exams and applies alternating logic for fairness.
* **Notification System:** Firebase Cloud Messaging (FCM) alerts all involved students once a plan is generated.

---

## 💻 Technologies Used
* **Frontend:** Flutter 
* **Backend:** Firebase (Auth, Firestore, Cloud Functions) 
* **Push Notifications:** Firebase Cloud Messaging (FCM) 
* **Prototyping:** Figma 
* **Version Control:** Git & GitHub

---

## 📸 Screenshots

> **Note:** To see these images, extract them from your PDF, name them as shown below, and place them in an `assets/` folder in your repository.

### Authentication & Roles
| Get Started | Admin Login | Teacher Login | Student Login |
| :---: | :---: | :---: | :---: |
| ![Get Started](<img width="1152" height="2496" alt="Screenshot_20251115-233009" src="https://github.com/user-attachments/assets/9ad06415-fbef-44ca-a6c6-2ac892984504" />) | ![Admin Login](<img width="1152" height="2496" alt="Screenshot_20251115-233017" src="https://github.com/user-attachments/assets/fc7de341-bc88-456a-acda-9a91f83fd611" />) | ![Teacher Login](<img width="1152" height="2496" alt="Screenshot_20251115-233245" src="https://github.com/user-attachments/assets/68717e93-5b3b-40a0-a553-be2f5bb5bd45" />) | ![Student Login](<img width="1152" height="2496" alt="Screenshot_20251115-233614" src="https://github.com/user-attachments/assets/3fc38a73-116e-4c90-813a-5b418b645d15" />) |
| *Splash Screen*  | *Main Admin*  | *Faculty Access*  | *Student Access*  |

### Management Dashboards
| Admin Dashboard | Add Course | All Exams | Hall Management |
| :---: | :---: | :---: | :---: |
| ![Admin](<img width="1152" height="2496" alt="Screenshot_20251115-233037" src="https://github.com/user-attachments/assets/f8fd1ea9-e40b-4d77-981d-ba465ee94d5a" />) | ![Add Course](<img width="1152" height="2496" alt="Screenshot_20251115-233100" src="https://github.com/user-attachments/assets/c34afd31-819e-4fcc-8325-a85eb69059b6" />) | ![All Exams](<img width="1152" height="2496" alt="Screenshot_20251115-233335" src="https://github.com/user-attachments/assets/694eecb1-b25c-49bf-b76a-b66151259241" />) | ![Add Hall](<img width="1152" height="2496" alt="Screenshot_20251115-233407" src="https://github.com/user-attachments/assets/97786c27-12d2-43db-980e-7f31a9d53d26" />) |
| *Control Center*  | *Course Linking*  | *Exam List*  | *Layout Setup*  |

### Generation & Results
| Seat Plan Generator | Seat Plan List | Seat Map Viewer | Student Dashboard |
| :---: | :---: | :---: | :---: |
| ![Generator](<img width="1152" height="2496" alt="Screenshot_20251115-233448" src="https://github.com/user-attachments/assets/764c6053-4a28-4dee-94b7-b06f748b180c" />) | ![Plan List](<img width="1152" height="2496" alt="Screenshot_20251115-233501" src="https://github.com/user-attachments/assets/564eca30-9594-4667-a95b-cd03d5f0c199" />) | ![Map](<img width="1152" height="2496" alt="Screenshot_20251115-233507" src="https://github.com/user-attachments/assets/600f5d0b-f69f-4dfd-bbc6-637da6c63b88" />) | ![Student Dash](<img width="1152" height="2496" alt="Screenshot_20251115-233609" src="https://github.com/user-attachments/assets/38a195b8-7cce-4d65-9fa8-71b79c06a9a5" />) |
| *Algorithm Logic*  | *History*  | *Visual Grid*  | *Seat Assignment*  |

---

## 🚀 Future Work
* **Advanced Schedule Solver:** A "Master Generate" button for university-wide scheduling .
* **Data Import:** Bulk upload students via .csv files.
* **Admin Analytics:** Statistics on hall utilization and seating efficiency.
  
---

## 👨‍💻 Author
**Ehashanul Haque**  
ID: 0802320205101090 
[cite_start]Level: 3, Term: I [cite: 13, 14]  
[cite_start]**Department of CSE, BAUST** [cite: 2]




