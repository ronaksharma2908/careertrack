
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:8b5cf6,100:06b6d4&height=220&section=header&text=CareerTrack&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%"/>
</p>

 # 🚀 CareerTrack
 
<p align="center">
  <strong>💼 Your Personal Internship & Job Application Command Center</strong>
</p>

<p align="center">
  Track applications • Manage interviews • Analyze progress • Build your career
</p>

<p align="center">
  A modern, responsive MERN-stack platform designed to help students and job seekers organize their entire career-search journey in one beautiful workspace.
</p>

<br>

<p align="center">

<a href="#-features">
<img src="https://img.shields.io/badge/✨_Features-6366F1?style=for-the-badge"/>
</a>

<a href="#-uiux-design">
<img src="https://img.shields.io/badge/🎨_UI%2FUX-8B5CF6?style=for-the-badge"/>
</a>

<a href="#-installation">
<img src="https://img.shields.io/badge/⚙️_Installation-06B6D4?style=for-the-badge"/>
</a>

<a href="#-roadmap">
<img src="https://img.shields.io/badge/🗺️_Roadmap-10B981?style=for-the-badge"/>
</a>

</p>

<br>

<p align="center">

<img src="https://img.shields.io/badge/MERN-Stack-6366F1?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Node.js-20-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Express.js-4-000000?style=for-the-badge&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>

</p>

---

# 🌟 What is CareerTrack?

**CareerTrack** is a full-stack career management platform built with the MERN stack.

It helps students and job seekers manage their complete internship and job-search process without relying on scattered spreadsheets, bookmarks, emails, or notes.

### 🎯 One Dashboard. One Career Journey.

```text
🔍 Discover
     ↓
💼 Apply
     ↓
📊 Track
     ↓
📅 Interview
     ↓
🎉 Get Selected
     ↓
📈 Analyze & Improve
```

> **CareerTrack turns a messy job search into an organized, measurable workflow.**

---

# 🎨 UI/UX Design

CareerTrack follows a **modern SaaS dashboard design philosophy** focused on simplicity, speed, and visual clarity.

<div align="center">

|    🎯 Principle   | 💡 Approach                          |
| :---------------: | :----------------------------------- |
|     ⚡ **Fast**    | Quick actions and minimal clicks     |
|   🎨 **Modern**   | Clean cards and visual hierarchy     |
| 📱 **Responsive** | Desktop, tablet and mobile           |
|   🧠 **Simple**   | Minimal cognitive load               |
|   📊 **Visual**   | Charts, badges and status indicators |
|  ♿ **Accessible** | Clear typography and contrast        |

</div>

---

# 🖥️ Dashboard Preview

```text
┌────────────────────────────────────────────────────────────────────┐
│ 🚀 CareerTrack                              🔔 Notifications  👤   │
├────────────────┬───────────────────────────────────────────────────┤
│                │                                                   │
│ 🏠 Dashboard   │  Good morning! 👋                                │
│                │                                                   │
│ 💼 Applications│  ┌──────────┐ ┌──────────┐ ┌──────────┐         │
│                │  │    42    │ │     8    │ │     3    │         │
│ 📅 Interviews  │  │   Apps   │ │ Interviews│ │  Offers  │         │
│                │  └──────────┘ └──────────┘ └──────────┘         │
│ 📊 Analytics   │                                                   │
│                │  📈 Application Overview                         │
│ 📄 Resumes     │  ┌───────────────────────────────────────────┐  │
│                │  │        ▄                                   │  │
│ 🔔 Reminders   │  │   ▄    ███       ▄██                       │  │
│                │  │  ███   ████     █████                      │  │
│ ⚙️ Settings    │  └───────────────────────────────────────────┘  │
│                │                                                   │
└────────────────┴───────────────────────────────────────────────────┘
```

> 💡 **Note:** The dashboard above is a conceptual preview. Replace it with an actual application screenshot once the UI is implemented.

---

# ✨ Features

<table>
<tr>
<td width="50%" valign="top">

### 🔐 Authentication

Secure account management with:

* JWT authentication
* Password hashing
* Protected routes
* Login / Register
* Session persistence
* User-specific data

</td>

<td width="50%" valign="top">

### 💼 Application Tracker

Manage every internship and job application:

* Company
* Position
* Location
* Salary / Stipend
* Application date
* Deadline
* Status
* Notes
* Job URL

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📅 Interview Manager

Keep every interview organized:

* Interview date
* Time
* Interview round
* Interview type
* Preparation notes
* Interview notes

</td>

<td width="50%" valign="top">

### 📊 Analytics Dashboard

Understand your job-search performance:

* Application trends
* Success rate
* Interview conversion
* Offer conversion
* Status distribution
* Monthly statistics

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🔎 Smart Search & Filters

Find applications quickly using:

* Company
* Position
* Status
* Location
* Job type
* Application date

</td>

<td width="50%" valign="top">

### 📄 Resume Manager

Organize multiple resume versions and associate the appropriate resume with each application.

</td>
</tr>
</table>

---

# 🟣 Application Status System

CareerTrack uses a visual application pipeline.

```text
┌───────────────┐
│ 💜  Wishlist  │
└───────┬───────┘
        ↓
┌───────────────┐
│ 🔵  Applied   │
└───────┬───────┘
        ↓
┌────────────────┐
│ 🟡 Assessment  │
└───────┬────────┘
        ↓
┌────────────────┐
│ 🟠  Interview  │
└───────┬────────┘
        ↓
┌────────────────┐
│ 🟢  Selected   │
└────────────────┘

        ↘
      🔴 Rejected
```

### 🎨 Status Indicators

| Status     | Indicator | Meaning               |
| :--------- | :-------: | :-------------------- |
| Wishlist   |     🟣    | Interested            |
| Applied    |     🔵    | Application submitted |
| Assessment |     🟡    | Assessment / test     |
| Interview  |     🟠    | Interview stage       |
| Selected   |     🟢    | Successful            |
| Rejected   |     🔴    | Application rejected  |

---

# 💼 Application Card

Example application card:

```text
╭──────────────────────────────────────────────╮
│ 🟢 Google                                    │
│                                              │
│ Software Engineering Intern                 │
│                                              │
│ 📍 Bangalore        💰 ₹40K/month           │
│ 📅 Applied: Aug 12                           │
│                                              │
│ Status: 🟠 Interview                         │
│                                              │
│ [ 👁 View ]  [ ✏️ Edit ]  [ 🗑 Delete ]      │
╰──────────────────────────────────────────────╯
```

The final application card will use responsive components and interactive buttons.

---

# 📊 Analytics Dashboard

CareerTrack converts application data into meaningful insights.

### Example Metrics

<table>
<tr>
<td align="center">

### 💼 Applications

# 42

Total applications

</td>

<td align="center">

### 📅 Interviews

# 8

Interview stages

</td>

<td align="center">

### 🎉 Offers

# 3

Successful applications

</td>

<td align="center">

### 🎯 Success Rate

# 7.1%

Application success

</td>
</tr>
</table>

---

# 📈 Career Analytics

Example application trend:

```text
Applications

│
│                            ████
│                     ████   ████
│              ████   ████   ████
│       ████   ████   ████   ████
│ ████  ████   ████   ████   ████
└────────────────────────────────────
   May     Jun     Jul     Aug
```

### Planned analytics

* 📈 Applications over time
* 🎯 Success rate
* 💼 Company-wise applications
* 📅 Monthly trends
* 🔄 Interview conversion
* 🏆 Offer conversion
* 📊 Status distribution

---

# 📱 Responsive Design

CareerTrack is designed to provide a consistent experience across devices.

### 💻 Desktop

```text
Sidebar
   +
Dashboard
   +
Analytics
   +
Application Management
```

### 📱 Mobile

```text
┌────────────────────────┐
│ 🚀 CareerTrack      ☰  │
├────────────────────────┤
│                        │
│ Good morning! 👋       │
│                        │
│ ┌────────┐ ┌────────┐ │
│ │   42   │ │    8   │ │
│ │  Apps  │ │ Inter. │ │
│ └────────┘ └────────┘ │
│                        │
│ Recent Applications    │
│                        │
└────────────────────────┘
```

---

# 🧩 UI Component System

The frontend is designed around reusable components.

```text
components/
│
├── 🎨 Navbar
├── 📚 Sidebar
├── 💳 StatCard
├── 💼 ApplicationCard
├── 📅 InterviewCard
├── 🔍 SearchBar
├── 🎛️ FilterPanel
├── 🪟 Modal
├── 🔔 Notification
├── 📊 Chart
└── 📝 Form
```

### Why reusable components?

* ♻️ Less duplicate code
* 🧹 Cleaner codebase
* 🚀 Faster development
* 🎨 Consistent UI
* 🔧 Easier maintenance
* 📈 Easier scalability

---

# 🛠️ Tech Stack

<div align="center">

| Layer                | Technology   |
| :------------------- | :----------- |
| 🎨 Frontend          | React.js     |
| 💅 Styling           | Tailwind CSS |
| 🧭 Routing           | React Router |
| 🔄 API Requests      | Axios        |
| 📊 Charts            | Recharts     |
| ⚙️ Backend           | Node.js      |
| 🚀 Server            | Express.js   |
| 🗄️ Database         | MongoDB      |
| 🔗 ODM               | Mongoose     |
| 🔐 Authentication    | JWT          |
| 🔑 Password Security | bcrypt       |
| 🧰 Version Control   | Git + GitHub |

</div>

---

# 🏗️ System Architecture

```text
                         👤 USER
                           │
                           ▼
                ┌─────────────────────┐
                │   ⚛️ React Frontend │
                │                     │
                │ Tailwind + Router   │
                └──────────┬──────────┘
                           │
                         Axios
                           │
                           ▼
                ┌─────────────────────┐
                │    🚀 REST API      │
                │                     │
                │ Express + Node.js   │
                └──────────┬──────────┘
                           │
                 ┌─────────┴─────────┐
                 │                   │
                 ▼                   ▼
        ┌────────────────┐   ┌────────────────┐
        │ 🔐 Auth        │   │ 📦 Controllers │
        └────────┬───────┘   └────────┬───────┘
                 │                    │
                 └──────────┬─────────┘
                            │
                            ▼
                    🔗 Mongoose ODM
                            │
                            ▼
                 ┌─────────────────────┐
                 │ 🗄️ MongoDB Database │
                 └─────────────────────┘
```

---

# 📁 Project Structure

```text
CareerTrack/
│
├── client/
│   ├── public/
│   └── src/
│       │
│       ├── components/
│       │   ├── Navbar/
│       │   ├── Sidebar/
│       │   ├── ApplicationCard/
│       │   ├── InterviewCard/
│       │   ├── StatCard/
│       │   └── Modal/
│       │
│       ├── pages/
│       │   ├── Login/
│       │   ├── Register/
│       │   ├── Dashboard/
│       │   ├── Applications/
│       │   ├── Interviews/
│       │   ├── Analytics/
│       │   └── Profile/
│       │
│       ├── context/
│       ├── hooks/
│       ├── services/
│       ├── utils/
│       ├── App.jsx
│       └── main.jsx
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── server.js
│
├── docs/
│   └── screenshots/
│
├── .gitignore
├── package.json
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/careertrack.git
cd careertrack
```

## 2️⃣ Install Backend Dependencies

```bash
cd server
npm install
```

## 3️⃣ Install Frontend Dependencies

```bash
cd ../client
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file inside the `server` directory.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### ⚠️ Important

Never commit your `.env` file.

Add the following to `.gitignore`:

```text
.env
node_modules/
```

---

# ▶️ Running the Project

### 🚀 Start Backend

```bash
cd server
npm run dev
```

### ⚛️ Start Frontend

Open another terminal:

```bash
cd client
npm run dev
```

Open the application at:

```text
http://localhost:5173
```

---

# 🔌 REST API

<details>
<summary>🔐 Authentication API</summary>

<br>

|  Method | Endpoint             | Description         |
| :-----: | :------------------- | :------------------ |
| 🟢 POST | `/api/auth/register` | Register a new user |
| 🟢 POST | `/api/auth/login`    | Login               |
|  🔵 GET | `/api/auth/me`       | Get current user    |

</details>

<details>
<summary>💼 Applications API</summary>

<br>

|   Method  | Endpoint                | Description        |
| :-------: | :---------------------- | :----------------- |
|   🔵 GET  | `/api/applications`     | Get applications   |
|  🟢 POST  | `/api/applications`     | Create application |
|   🔵 GET  | `/api/applications/:id` | Get application    |
|   🟡 PUT  | `/api/applications/:id` | Update application |
| 🔴 DELETE | `/api/applications/:id` | Delete application |

</details>

<details>
<summary>📅 Interviews API</summary>

<br>

|   Method  | Endpoint              | Description      |
| :-------: | :-------------------- | :--------------- |
|   🔵 GET  | `/api/interviews`     | Get interviews   |
|  🟢 POST  | `/api/interviews`     | Create interview |
|   🟡 PUT  | `/api/interviews/:id` | Update interview |
| 🔴 DELETE | `/api/interviews/:id` | Delete interview |

</details>

---

# 🗺️ Roadmap

### 🟢 Phase 1 — MVP

* [x] Project setup
* [ ] Authentication
* [ ] Dashboard
* [ ] Application CRUD
* [ ] Search
* [ ] Filters
* [ ] Status tracking

### 🔵 Phase 2 — Productivity

* [ ] Interview tracker
* [ ] Resume manager
* [ ] Deadline reminders
* [ ] Notifications
* [ ] Kanban board
* [ ] Calendar integration
* [ ] Dark mode

### 🟣 Phase 3 — Analytics

* [ ] Application charts
* [ ] Success rate
* [ ] Conversion analytics
* [ ] Monthly reports
* [ ] CSV export
* [ ] PDF reports

### 🔥 Phase 4 — AI

* [ ] AI Resume Analyzer
* [ ] Resume-job matching
* [ ] Job description analyzer
* [ ] AI interview questions
* [ ] AI interview preparation
* [ ] Personalized career recommendations

---

# 🤖 AI Career Assistant — Future Vision

The future AI layer can transform CareerTrack from an application tracker into a complete career assistant.

```text
                 📄 RESUME
                     │
                     ▼
          ┌────────────────────┐
          │   🤖 AI ANALYZER   │
          └──────────┬─────────┘
                     │
                     ▼
             🧠 SKILL EXTRACTION
                     │
                     ▼
          ┌────────────────────┐
          │ 💼 JOB DESCRIPTION │
          └──────────┬─────────┘
                     │
                     ▼
               🎯 MATCH SCORE
                     │
                     ▼
          ┌────────────────────┐
          │ 💡 RECOMMENDATIONS │
          └────────────────────┘
```

### Example

```text
🎯 Resume Match

██████████████████░░  87%

✓ React
✓ JavaScript
✓ HTML
✓ CSS
✓ Git

⚠ Missing Skills

• TypeScript
• Testing

💡 Recommendation

Build a TypeScript + React project
to improve your job match score.
```

---

# 🔐 Security

CareerTrack follows common application security practices:

* 🔐 JWT authentication
* 🔑 bcrypt password hashing
* 🛡️ Protected API routes
* 🔒 Environment variables
* 👤 User-specific data access
* ✅ Input validation
* 🚫 Unauthorized request protection

---

# 🧪 Testing

Planned testing ecosystem:

```text
Frontend
├── Vitest
└── React Testing Library

Backend
├── Jest
└── Supertest

API Testing
└── Postman
```

---

# 📸 Screenshots

Once the frontend is implemented, add screenshots here.

### 🏠 Dashboard

<p align="center">
  <img src="docs/screenshots/dashboard.png" width="90%" alt="CareerTrack Dashboard"/>
</p>

### 💼 Applications

<p align="center">
  <img src="docs/screenshots/applications.png" width="90%" alt="CareerTrack Applications"/>
</p>

### 📅 Interviews

<p align="center">
  <img src="docs/screenshots/interviews.png" width="90%" alt="CareerTrack Interview Tracker"/>
</p>

### 📊 Analytics

<p align="center">
  <img src="docs/screenshots/analytics.png" width="90%" alt="CareerTrack Analytics"/>
</p>

---

# 📈 Project Evolution

CareerTrack is designed to grow beyond a basic CRUD application.

```text
        🟢 BASIC CRUD
              │
              ▼
       ⚛️ MERN APPLICATION
              │
              ▼
       🎨 SaaS DASHBOARD
              │
              ▼
       📊 ANALYTICS PLATFORM
              │
              ▼
       🤖 AI CAREER ASSISTANT
              │
              ▼
       🚀 PRODUCTION PRODUCT
```

---

# 🤝 Contributing

Contributions are welcome!

### Create a feature branch

```bash
git checkout -b feature/new-feature
```

### Stage your changes

```bash
git add .
```

### Commit

```bash
git commit -m "Add new feature"
```

### Push

```bash
git push origin feature/new-feature
```

Then open a Pull Request.

---

# ⭐ Support CareerTrack

If you like this project:

<p align="center">

⭐ **Star** the repository

🍴 **Fork** the project

🐛 **Report** bugs

💡 **Suggest** features

🤝 **Contribute**

</p>

---

# 👨‍💻 Author

<p align="center">

## Ronak Sharma

🎓 **B.Tech CSE — AI & ML**

💻 Full-Stack Developer
🤖 AI/ML Enthusiast
🧠 DSA Learner
🚀 Building Real-World Projects

</p>

---

# 📬 Connect

<p align="center">

<a href="https://github.com/ronaksharma2908">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://linkedin.com/in/ronak29sharma">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

</p>

---

# 📜 License

This project is licensed under the **MIT License**.

---

<p align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:8b5cf6,100:6366f1&height=140&section=footer" width="100%"/>

<br>

### 🚀 CareerTrack

**Organize your applications. Track your progress. Build your career.**

<br>

⭐ **If you like this project, give it a star!**

</p>

.....
......
