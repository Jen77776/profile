# 💻 Jen Kang | Full-Stack Engineer & AI/XR Developer

---

### ✨ Overview

This is a personal portfolio and technical blog built using the **Hugo** static site generator and the **Hugo Profile** theme. It serves as a comprehensive showcase of my technical skills, engineering projects, and academic background.

The site is hosted and automatically deployed via **Netlify**, ensuring fast performance and continuous integration from the connected GitHub repository.

* **Live Site**: [Replace with your Netlify domain, e.g., https://jen-kang-portfolio.netlify.app]
* **GitHub**: https://github.com/Jen77776

---

### 🛠️ Core Technology Stack

| Domain | Key Technologies |
| :--- | :--- |
| **Languages/Frameworks** | Java, Python, C#, React.js, Node.js, Flask, Spring Boot, Unity |
| **Cloud/DevOps** | AWS (EC2, S3), Microsoft Azure (AAD), Docker, Kubernetes, CI/CD Pipelines |
| **Databases** | MySQL, MongoDB, Redis, PostgreSQL |
| **AI/XR** | Google Gemini API, OpenAI DALL·E, TensorFlow, AR Foundation, VR/MR |

---

### 📂 Highlighted Projects

This repository features several engineering initiatives, including academic and work-related projects:

#### 1. AI Tutor Platform (Software Engineering Internship)
* **Description**: Architected a full-stack AI platform for the Applied Biostatistics course, providing real-time, AI-driven feedback to over 100 students.
* **Tech Stack**: Python (Flask), React.js, Google Gemini API, CI/CD.

#### 2. Rental Recommender System (Big Data Lab Internship)
* **Description**: Developed a scalable rental recommender system that uses a custom collaborative filtering algorithm, improving recommendation accuracy by 20%.
* **Tech Stack**: Java, Spring Boot, MySQL/Redis, AWS (EC2), Docker/Kubernetes.

#### 3. MR Virtual Pet
* **Description**: Developed a Mixed Reality (MR) virtual pet application for Unity, featuring environment detection for real-time obstacle avoidance and spatial mapping.
* **Tech Stack**: Unity, C#, VR/MR Devices, AR Foundation.

#### 4. AI Art Museum
* **Description**: Full-stack platform enabling real-time AI artwork generation via OpenAI DALL·E and a hybrid recommendation system.
* **Tech Stack**: Python (Flask), React.js, PostgreSQL, AWS S3.

---

### ⚙️ Local Development Guide

To run and modify the site locally, follow these steps:

#### 1. Prerequisites
Ensure you have **Hugo** (version `v0.152.2` or higher) and **Git** installed.

#### 2. Clone the Repository
```bash
# Clone your repository
git clone [https://github.com/Jen77776/profile.git](https://github.com/Jen77776/profile.git) 
cd profile
```
#### 3. Initialize Theme Submodule
```bash
git submodule update --init --recursive
```
#### 4. Run the Development Server
```bash
hugo server
```
#### 5.Deploy Changes
After making modifications, commit and push your changes to the master branch. Netlify will automatically trigger a new deployment.
```bash
git add .
git commit -m "Updated content and links"
git push origin master
```