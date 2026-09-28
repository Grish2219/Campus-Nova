<div align="center">
  <img src="docs/screenshots/banner.png" alt="Campus Nova Banner" width="100%" />

  <h1>Campus Nova</h1>
  <p><strong>Student Career Guidance & Development Platform</strong></p>

  <p><em>"Discover your direction. Build your skills. Track your progress."</em></p>

  <p>
    <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
    <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
    <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  </p>
</div>

---

## 📖 Overview

Campus Nova is a comprehensive Career Guidance System that helps students make informed, data-driven decisions about their professional future. By integrating personalized assessments, career recommendations, and actionable learning roadmaps, the platform transforms career anxiety into a structured, step-by-step development journey.

The platform features a modern, immersive UI with 3D elements and smooth animations to keep students engaged throughout their career exploration process.

---

## 🛑 The Problem

Students frequently struggle with career planning due to a lack of personalized guidance:
- **Generic Advice**: Most career advice is one-size-fits-all and ignores individual strengths.
- **Skill Uncertainty**: Students often don't know the exact skills required for their target industry.
- **Disconnected Learning**: Educational resources often feel disconnected from practical career outcomes.
- **Lack of Tracking**: There is no structured way for students to monitor their preparation over time.

---

## 💡 The Approach

Campus Nova systematically bridges the gap between a student's current position and their career goals. 

The student journey flows as follows:

**Assess** → **Recommend** → **Explain** → **Identify Skill Gap** → **Build Roadmap** → **Track Progress** → **Reassess**

---

## 🖼️ Product Preview

*(Note: Add your actual screenshots to `docs/screenshots/`)*

### Immersive 3D Experience
![3D UI Demo](docs/screenshots/campus-nova-demo.gif)

### Student Dashboard
![Student Dashboard](docs/screenshots/dashboard.png)

### Career Assessment
![Career Assessment](docs/screenshots/assessment.png)

### Personalized Recommendations
![Recommendations](docs/screenshots/recommendations.png)

### Skill Gap Analysis
![Skill Gap Analysis](docs/screenshots/skill-gap.png)

### Learning Roadmap
![Learning Roadmap](docs/screenshots/roadmap.png)

### Progress Tracking
![Progress Tracking](docs/screenshots/progress.png)

---

## ✨ Key Features

- **Immersive 3D Interface**: A modern, interactive UI that engages students with smooth animations and 3D visual effects.
- **Student Authentication & Profile Management**: Secure login and personalized dashboards for tracking individual progress.
- **Career Assessment**: Dynamic questionnaires designed to evaluate student aptitudes, interests, and current skill levels.
- **Personalized Recommendations**: Data-backed career path suggestions tailored to the student's assessment results.
- **Skill Gap Analysis**: Clear visualization comparing a student's current skills against the requirements of their chosen career.
- **Learning Roadmaps**: Actionable, step-by-step milestones to help students acquire missing skills.
- **Progress Tracking**: Visual indicators and checklists to monitor completion of roadmap milestones.
- **Admin Management**: Dedicated tools for administrators to manage users and oversee platform usage.

---

## 🏗️ Technical Architecture

Campus Nova utilizes a robust, traditional web architecture with a focus on modern frontend aesthetics and reliable backend processing.

![Architecture Diagram](docs/architecture.md)

**Flow**:
1. **Student** interacts with the **Campus Nova Web Interface** (Frontend).
2. The **Frontend** communicates with the **Backend / API Layer** (PHP).
3. **Business Logic** processes assessments and generates roadmaps.
4. Data is persistently stored and retrieved from the **MySQL Database**.

---

## 🗄️ Database Design

The relational database is designed to link users with their ongoing career development data securely.

![Database Schema](docs/database.md)

---

## 💻 Technology Stack

**Frontend**
- HTML5
- CSS3 (Custom animations, 3D effects)
- JavaScript
- Bootstrap 5

**Backend**
- PHP

**Database**
- MySQL

---

## ⚙️ Engineering Quality

- **Separation of Concerns**: Clean division between frontend views (`assets/`, `ui/`) and backend logic (`api/`, `auth/`).
- **Database-Driven Features**: All assessments, roadmaps, and profiles are dynamically generated from relational data.
- **Responsive Design**: The UI adapts seamlessly to mobile, tablet, and desktop viewports.
- **Interactive UI**: Utilizing CSS animations and JavaScript to create a modern, engaging user experience without heavy dependencies.

---

## 🔒 Security

Campus Nova implements several standard security measures:
- **Authentication**: Secure, session-based user authentication.
- **Password Protection**: Passwords are mathematically hashed before database storage.
- **Role-Based Access Control**: Protected routing separating Student, Teacher, and Admin privileges.
- **Input Validation**: Backend sanitization to prevent SQL injection and cross-site scripting (XSS).

---

## 📁 Project Structure

```text
Campus-Nova/
├── admin/               # Administrative tools and dashboard views
├── api/                 # Backend API endpoints for asynchronous requests
├── assets/              # CSS (including 3D/animations), JS, and images
├── auth/                # Authentication logic (login, registration, sessions)
├── config/              # Environment and database configuration
├── database/            # Database schema exports and seed scripts
├── docs/                # Architecture diagrams, database schemas, and screenshots
├── student/             # Student-facing views and features
├── teacher/             # Teacher/Mentor-facing views
├── index.php            # Main application entry point
└── README.md            # Project documentation
```

---

## 🚀 Installation & Setup

### Prerequisites
- PHP (v7.4 or higher)
- MySQL (v5.7 or higher)
- A local web server (Apache/XAMPP or PHP's built-in server)

### 1. Clone the repository
```bash
git clone https://github.com/Grish2219/Campus-Nova.git
cd Campus-Nova
```

### 2. Database Setup
1. Create a MySQL database named `campus_nova`.
2. Import the database schema:
```bash
mysql -u root -p campus_nova < schema_dump.sql
```

### 3. Environment Configuration
1. Navigate to the `config/` directory.
2. Update your database connection credentials (Host, Username, Password, Database Name) to match your local environment.

### 4. Running the Application
Using PHP's built-in development server:
```bash
php -S localhost:8000
```
Then navigate to `http://localhost:8000` in your web browser.

---

## 🗺️ Development Roadmap

- [x] Core Authentication & Profiles
- [x] Assessment Engine
- [x] Recommendation Logic
- [x] Skill Gap Visualization
- [x] Immersive UI/UX
- [ ] Advanced AI-driven career matching
- [ ] Real-time labor market API integrations
- [ ] Automated email notification system
- [ ] Advanced administrative analytics dashboard

---

## 🌐 Live Demo

*Live demo coming soon.*

---

## 👤 Author

**Grish**  
- GitHub: [@Grish2219](https://github.com/Grish2219)

<br />
<p align="center"><i>Turning career uncertainty into a structured path forward.</i></p>
