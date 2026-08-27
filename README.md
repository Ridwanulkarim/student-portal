# International Islamic University Chittagong (IIUC) — Student Portal

![IIUC Banner](https://img.shields.io/badge/IIUC-Student%20Portal-blue?style=for-the-badge&logo=education)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A modern, responsive, and feature-rich **Student Portal System** designed and built for the students of **International Islamic University Chittagong (IIUC)** using **100% Pure HTML5 & CSS3**. This application provides a seamless digital experience for course registration, academic result tracking, fee calculations, waiver applications, IQAC evaluations, thesis supervisor submissions, transport management, and student profile updating without relying on JavaScript runtime dependencies.

---

## 🚀 Live Demonstration & Repository

- **GitHub Repository**: [https://github.com/Ridwanulkarim/student-portal](https://github.com/Ridwanulkarim/student-portal)

---

## ✨ Key Features & Functional Modules

### 📊 1. Core Dashboard & Navigation
- **Dribbble-Inspired Sidebar & Quick Actions**: Fast navigation across all student services including Pre-Registration, Course Registration, Class Routine, Exam Schedules, and Payment History.
- **Top Utility Navigation Bar**: Dropdown popovers for `Students ▾`, `Others ▾`, `TER ▾`, `Application ▾`, `💬 IQAC ▾`, and user profile.
- **User Profile Pill**: Custom avatar trigger featuring student photo and stacked 2-line name (**Mohammad Ridwanul Karim**).

### 🎓 2. Academics & Registration
- **Pre-Registration & Tutorial**: Guidelines and pre-advising module for upcoming semesters.
- **Course Add/Drop & Withdraw**: Flexible course management options.
- **Registration Summary**: Multi-semester academic breakdown with CGPA (**3.761**) and GPA figures (Spring-2026 GPA: **3.912**).
- **Print Course Registration**: Printable official course registration slip.
- **Full Syllabus & Curriculum**: Interactive semester-wise course matrix.

### 💰 3. Financial Assistance & Waivers
- **Financial Assistance on GPA**: Automated waiver calculation (GPA **3.912**, CGPA **3.761**).
- **Waiver on SSC-HSC Result**: Merit scholarship application (SSC GPA **5.00**, HSC GPA **4.17**).
- **Waiver on Siblings**: Discount application for siblings studying concurrently at IIUC.
- **Covid-19 Waiver & Special Discounts**: File upload portal for pandemic/emergency assistance.
- **Fee Calculator & Payment History**: Detailed semester fee breakdown, payment advising, and transaction history log.

### 🔬 4. IQAC & Student Evaluation
- **Course Survey (`coursesurvey.html`)**: 10-aspect evaluation rating scale (1-5) and qualitative feedback textareas.
- **Student Survey (`studentsurvey.html`)**: Comprehensive multi-category campus life evaluation questionnaire.
- **Exit Survey (`exitsurvey.html`)**: Graduation eligibility survey.
- **TER Submission (`ter.html`)**: Teacher Evaluation Report portal.

### 👨‍🏫 5. Thesis & Project Management
- **Submit Supervisor (`supervisor.html`)**: Thesis/project supervisor and co-supervisor selection portal with group remarks.
- **Submit Proposal (`proposal.html`)**: Project proposal submission tool with Title, Background, Objective, Outcome, and Methodology sections.

### 🛠️ 6. Student Utilities & Support
- **Update Transport (`updatetransport.html`)**: Route selector (*4 - Agrabad - Lucky plaza*) and stoppage selector (*Agrabad*).
- **Hostel Application (`hostelapplication.html`)**: Hall selector (Bangabandhu Hall, Male Hall, Female Hall) with academic stats.
- **Change Password (`changepassword.html`)**: Secure password update portal.
- **Update Profile (`profile.html`)**: 3-column student information grid with portrait photo and warning alerts.
- **Complain Box & Wifi Password**: Student helpdesk and campus network credential retriever.

---

## 📁 Repository Directory Structure

```micro
student-portal/
├── index.html                    # IIUC Login Portal Page
├── signup.html                   # Student Registration Page
├── dashboard.html                # Main Student Dashboard & Quick Actions
├── preregistration.html          # Pre-Registration Page
├── courses.html                  # Course Registration & Advising
├── adddrop.html                  # Add/Drop Courses Page
├── withdraw.html                 # Course Withdraw Page
├── printcourseregistration.html  # Print Registration Slip
├── registrationsummary.html      # Academic Summary & GPA Breakdown
├── coursestatus.html             # Course Status Tracking Page
├── schedule.html                 # Class Routine Page
├── mdpresult.html                # MDP Result View
├── paymenthistory.html           # Payment History & Advising
├── paymentslip.html              # Payment Slip Generator
├── feecalculator.html            # Semester Fee Calculator
├── financialassistance.html      # Financial Assistance on GPA Page
├── sschscscholarship.html        # Waiver on SSC-HSC Result
├── siblings.html                 # Waiver on Siblings Page
├── covidwaiver.html              # Waiver for Covid-19 Page
├── pendingapplication.html       # Pending Applications Status
├── specialarrangement.html       # Special Arrangement Request Page
├── specialexam.html              # Special Examination Page
├── differentforms.html           # Different Types of Downloadable Forms
├── hostelapplication.html        # Hostel Application Form
├── certificateapplication.html   # Certificate / Testimonial Application
├── coursesurvey.html             # IQAC Course Survey Form
├── studentsurvey.html            # IQAC Student Survey Questionnaire
├── exitsurvey.html               # IQAC Exit Survey Page
├── supervisor.html               # Submit Supervisor/Co-Supervisor for Thesis/Project
├── proposal.html                 # Submit Thesis/Project Proposal Page
├── updatetransport.html          # Semester Transport Update Page
├── setmajorcourses.html          # Major Selection Page
├── wifipassword.html             # Wifi Password Request Page
├── complain.html                 # Student Complain Box Page
├── recentcomplain.html           # Recent Complaints History Page
├── profile.html                  # Update Student Profile Page
├── changepassword.html           # Change Password Page
├── ter.html                      # Teacher Evaluation Report Page
├── unauthorized.html             # Unauthorized Access Handler Page
├── css/
│   └── style.css                 # IIUC Master Stylesheet
└── assets/
    └── images/
        ├── logo.png              # IIUC Official Crest Logo
        └── student.png           # Student Avatar Portrait Photo
```

---

## ⚙️ Getting Started & Installation

To run this project locally on your machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Ridwanulkarim/student-portal.git
   ```
2. **Navigate into the project directory**:
   ```bash
   cd student-portal
   ```
3. **Launch the web application**:
   - Open `index.html` or `dashboard.html` directly in any modern web browser.
   - Zero installation or build commands required.

---

## 🛠️ Technology Stack

- **HTML5**: Semantic document structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`).
- **CSS3**: Custom CSS variables, Flexbox layouts, CSS Grid systems, custom scrollbars, and responsive breakpoints.
- **Pure Static Architecture**: 100% pure HTML & CSS build without JavaScript scripts or frameworks.

---

## 👤 Default Student Profile

- **Student Name**: Mohammad Ridwanul Karim
- **Student ID**: C243237
- **Program**: B.Sc. in Computer Science & Engineering (CSE)
- **University**: International Islamic University Chittagong (IIUC)
- **Current Semester GPA**: 3.912
- **Cumulative CGPA**: 3.761

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

<p center>Copyright &copy; 2026 International Islamic University Chittagong (IIUC). Developed by IT Division IIUC.</p>
