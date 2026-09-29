<div align="center">

<img src="https://img.shields.io/badge/Learn_School-Employee_Self_Service_Portal-1B6A3B?style=for-the-badge&logo=react&logoColor=white" alt="Learn School ESS" />

# 👨‍💼 Learn School — Employee Self Service Portal

**A modern, role-based ESS portal for Employees, Teachers & Admins of Learn School**  
*Built with React + TypeScript + Vite + Tailwind CSS, fully integrated with ERPNext (Frappe Framework)*

[![React](https://img.shields.io/badge/React-18.3-61DAFB?style=flat-square&logo=react&logoColor=white)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.6-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Vite](https://img.shields.io/badge/Vite-6.0-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev)
[![Tailwind](https://img.shields.io/badge/Tailwind-3.4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![ERPNext](https://img.shields.io/badge/ERPNext-Frappe-0089FF?style=flat-square&logo=frappe&logoColor=white)](https://erpnext.com)
[![License](https://img.shields.io/badge/License-MIT-22C55E?style=flat-square)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)](http://makeapullrequest.com)
[![Maintained](https://img.shields.io/badge/Maintained-Yes-22C55E?style=flat-square)](https://github.com/QADEER-AHMED-cs/Learn-School-Employee-Self-Service-Portal-ESS)

[Features](#-features) • [Roles](#-role-based-access) • [Tech Stack](#-tech-stack) • [Getting Started](#-getting-started) • [Workflow](#-project-workflow) • [Structure](#-project-structure)

</div>

---

## 🎭 Role-Based Access

This portal serves **3 distinct roles** with tailored dashboards and features. Each role sees only what they need.

<table>
<tr>
<td width="33%" align="center">

### 👨‍💼 Employee

Own records & services

</td>
<td width="33%" align="center">

### 👨‍🏫 Teacher / Faculty

Classes & students

</td>
<td width="33%" align="center">

### 👨‍💼 Academic / Admin

Manage everyone & everything

</td>
</tr>
</table>

| Role | Access Scope |
|:-----|:-------------|
| **Employee** | Own attendance, leave, payroll, tasks, profile, notices |
| **Teacher** | Student attendance, assignments, classes, leave, payroll |
| **Academic / Admin** | Manage employees & teachers, reports, approvals, payroll processing |

---

## ✨ Features

### 🌐 Common (All Roles)

- 📊 **Dashboard** — Role-specific overview with KPIs
- 📅 **Attendance** — Daily check-in / check-out with regularization requests
- 🏖️ **Leave Management** — Apply, track, approve, view balance
- 💰 **Payroll** — Monthly salary slips, download PDF
- 📝 **Tasks / To-Do** — Assigned tasks with status tracking
- 📢 **Notice Board** — School announcements & circulars
- 🔔 **Notifications** — Real-time updates dropdown
- 👤 **Profile** — Personal & employment details
- 🔐 **Login Activity** — Account security log

### 👨‍🏫 Teacher / Faculty Specific

- 🎓 **My Classes** — Course & classroom management
- ✅ **Mark Attendance** — Student attendance marking
- 📚 **Assignments** — Assign, view, grade student submissions
- 👥 **Student Activity** — Track student engagement
- 📝 **Assessments** — Create & review assessments
- 📊 **View Results** — Class-wise results

### 👨‍💼 Academic / Admin Specific

- 👥 **Manage Employees** — Full CRUD on employee records
- 👨‍🏫 **Manage Teachers** — Teacher profiles & assignments
- 📅 **Admin Attendance** — All-staff attendance monitoring
- 📝 **Leave Approvals** — Approve/reject employee leaves
- 💼 **Payroll Processing** — Generate salary slips
- 📊 **Reports & Analytics** — Revenue, attendance, group counts
- 🏫 **Sections & Programs** — Academic structure management
- 🎓 **Student Groups** — Group creation & management
- 📢 **Publish Notices** — School-wide announcements
- 🔍 **Audit Log** — Track all system activities
- 📈 **CEO Schedule** — Executive calendar view
- 👥 **Teacher Profiles** — Comprehensive teacher data

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology |
|:------|:-----------|
| **Frontend Framework** | ![React](https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) |
| **Build Tool** | ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |
| **Styling** | ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **Icons** | ![Lucide](https://img.shields.io/badge/Lucide_React-F56565?style=flat-square&logo=lucide&logoColor=white) |
| **Backend** | ![ERPNext](https://img.shields.io/badge/ERPNext-Frappe-0089FF?style=flat-square&logo=frappe&logoColor=white) |
| **Auth** | ![Google](https://img.shields.io/badge/Google_OAuth-4285F4?style=flat-square&logo=google&logoColor=white) |
| **HTTP Client** | ![Fetch API](https://img.shields.io/badge/Fetch_API-000000?style=flat-square&logo=javascript&logoColor=white) |

</div>

---

## 🚀 Getting Started

### 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** `v18.0.0` or higher — [Download](https://nodejs.org)
- **npm** `v9.0.0` or higher (comes with Node.js)
- **Git** — [Download](https://git-scm.com)
- **Access** to an **ERPNext** instance (backend)

### 📦 Installation

```bash
# 1. Clone the repository
git clone https://github.com/QADEER-AHMED-cs/Learn-School-Employee-Self-Service-Portal-ESS.git

# 2. Navigate into the project
cd Learn-School-Employee-Self-Service-Portal-ESS

# 3. Install dependencies
npm install

# 4. Set up environment variables
# Create .env file with your ERPNext credentials (see below)

# 5. Run the development server
npm run dev
```

Open **[http://localhost:3000](http://localhost:3000)** in your browser.

### 🔐 Environment Variables

Create a `.env` file in the root directory:

```env
# ERPNext Configuration
VITE_ERP_BASE_URL=https://your-erpnext-instance.com
VITE_ERP_API_KEY=your_api_key_here
VITE_ERP_API_SECRET=your_api_secret_here

# Optional: Google OAuth (if classroom integration used)
VITE_GOOGLE_CLIENT_ID=your_google_client_id
```

> ⚠️ 

### 🏗️ Build for Production

```bash
npm run build
npm run preview
```

The production build will be in the `dist/` folder.

---

## 🗺️ Project Workflow

The complete portal workflow — from login to all role-based modules:

```
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│              🏫  LEARN SCHOOL ESS PORTAL                     │
│                                                              │
└──────────────────────────┬───────────────────────────────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │   🌐  LOGIN         │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │   🔐  AUTH          │
                │   (Session + CSRF)  │
                └──────────┬──────────┘
                           │
           ┌───────────────┼───────────────┐
           │               │               │
           ▼               ▼               ▼
    ┌─────────────┐ ┌─────────────┐ ┌─────────────┐
    │ 👨‍💼 EMPLOYEE │ │👨‍🏫 TEACHER  │ │👨‍💼 ACADEMIC │
    │             │ │  / FACULTY  │ │  / ADMIN    │
    └──────┬──────┘ └──────┬──────┘ └──────┬──────┘
           │               │               │
           └───────────────┼───────────────┘
                           │
                           ▼
              ┌─────────────────────────┐
              │   📊  DASHBOARD         │
              │  (Role-specific view)   │
              └────────────┬────────────┘
                           │
     ┌─────────────────────┼─────────────────────┐
     │                     │                     │
     ▼                     ▼                     ▼
┌──────────┐        ┌──────────┐          ┌──────────┐
│ EMPLOYEE │        │ TEACHER  │          │  ADMIN   │
│ MODULES  │        │ MODULES  │          │ MODULES  │
└────┬─────┘        └────┬─────┘          └────┬─────┘
     │                   │                     │
     ├─ Attendance       ├─ My Classes         ├─ Manage Employees
     ├─ Leave            ├─ Mark Attendance    ├─ Manage Teachers
     ├─ Payroll          ├─ Assignments        ├─ Leave Approvals
     ├─ Tasks            ├─ Student Activity   ├─ Payroll Processing
     ├─ Notices          ├─ Assessments        ├─ Reports & Analytics
     ├─ Profile          ├─ View Results       ├─ Sections/Programs
     └─ Login Activity   └─ Leave/Payroll      ├─ Student Groups
                                                ├─ Audit Log
                                                ├─ Revenue Stats
                                                └─ CEO Schedule
                           │
                           ▼
              ┌─────────────────────────┐
              │  🔔  NOTIFICATIONS      │
              │  📢  NOTICE BOARD       │
              └─────────────────────────┘
```

---

## 📁 Project Structure

```
Learn-School-Employee-Self-Service-Portal-ESS/
│
├── 📁 auth/                              # Authentication
│   ├── AuthContext.tsx                   # Auth state & user context
│   └── env.ts                            # Environment helpers
│
├── 📁 components/                        # Reusable UI components
│   ├── Layout.tsx                        # Main layout wrapper
│   ├── MainLayout.tsx                    # Role-aware layout
│   ├── Topbar.tsx                        # Top navigation
│   ├── NotificationDropdown.tsx          # Notifications
│   ├── LeaveApplicationModal.tsx         # Leave form modal
│   ├── AttendanceRegularizationModal.tsx # Attendance fix
│   ├── StudentActivityView.tsx           # Student activity
│   ├── TeacherAttendanceSection.tsx      # Teacher attendance
│   ├── Allinvoicestable.tsx              # Invoice table
│   ├── KpiCard.tsx                       # KPI card
│   ├── WarningCard.tsx                   # Warning card
│   ├── Badge.tsx                         # Badge component
│   └── Shared.tsx                        # Shared components
│
├── 📁 config/                            # Configuration
│   └── layout.config.ts                  # Sidebar/route config
│
├── 📁 hooks/                             # Custom React hooks
│   ├── useAttendance.ts                  # Attendance data
│   ├── useLeave.ts                       # Leave applications
│   ├── useSalarySlip.ts                  # Salary slips
│   ├── useEmployee.ts                    # Employee data
│   ├── useFaculty.ts                     # Faculty data
│   ├── useDashboard.ts                   # Dashboard data
│   ├── useAdminStudentAttendance.ts      # Admin student att.
│   ├── Useadmin.ts                       # Admin dashboard
│   ├── Useadminemployees.ts              # Manage employees
│   ├── Useadminleaveapplications.ts      # Leave approvals
│   ├── Useadminsalaryslips.ts            # Payroll processing
│   ├── Useadminreports.ts                # Reports
│   ├── Useadminstudents.ts               # Manage students
│   ├── Useadminstudentgroups.ts          # Student groups
│   ├── UseAcad*.ts                       # Academic module hooks
│   ├── Useacadstudents.ts                # Academic students
│   ├── Usestudents.ts                    # Students
│   ├── Usenoticeboard.ts                 # Notices
│   ├── Usetodo.ts                        # To-do tasks
│   ├── Usecalendar.ts                    # Calendar
│   ├── Useschedule.ts                    # Schedule
│   ├── Useassessment.ts                  # Assessments
│   ├── Useprograms.ts                    # Programs
│   ├── Userevenuestats.ts                # Revenue stats
│   ├── Useceoschedule.ts                 # CEO schedule
│   ├── Useceoteacherprofiles.ts          # Teacher profiles
│   ├── useAssignments.ts                 # Assignments
│   ├── useStudentActivityLog.ts          # Activity log
│   └── ... (more)
│
├── 📁 pages/                             # Route pages (role-based)
│   ├── LoginPage.tsx                     # Login
│   ├── Dashboard.tsx                     # Default dashboard
│   ├── EssDashboardPage.tsx              # Employee dashboard
│   ├── AcademicDashboard.tsx             # Academic dashboard
│   ├── Admindashboardpage.tsx            # Admin dashboard
│   ├── AttendancePage.tsx                # Attendance
│   ├── LeavePage.tsx                     # Leave
│   ├── SalarySlipPage.tsx                # Payroll
│   ├── TodoPage.tsx                      # Tasks
│   ├── ProfilePage.tsx                   # Profile
│   ├── Schedulepage.tsx                  # Schedule
│   ├── FacultyPage.tsx                   # Faculty view
│   ├── FacultyClassroomPage.tsx          # Classroom
│   ├── FacultyStudentActivityPage.tsx    # Student activity
│   ├── Markattendancepage.tsx            # Mark attendance
│   ├── AssignmentsPage.tsx               # Assignments
│   ├── Assessmentpage.tsx                # Assessment
│   ├── Viewresultspage.tsx               # Results
│   ├── Adminemp.tsx                      # Manage employees
│   ├── Adminstudentspage.tsx             # Manage students
│   ├── Adminleaveapprovalpage.tsx        # Leave approvals
│   ├── Adminsalaryslippage.tsx           # Payroll
│   ├── Adminreportspage.tsx              # Reports
│   ├── Adminrevenuepage.tsx              # Revenue
│   ├── Adminstudentgroupspage.tsx        # Student groups
│   ├── AdminStudentAttendancePage.tsx    # Student attendance
│   ├── AdminStudentActivityPage.tsx      # Student activity
│   ├── Acad*.tsx                         # Academic pages
│   ├── Ceoschedulepage.tsx               # CEO schedule
│   ├── Ceoteacherprofilespage.tsx        # Teacher profiles
│   └── ... (more)
│
├── 📁 server/                            # Local backend helpers
│   ├── index.js                          # Express server
│   ├── env.js                            # Env loader
│   ├── googleAuth.js                     # Google OAuth
│   ├── classroomClient.js                # Classroom client
│   ├── classroomLive.js                  # Live classroom
│   ├── tokenStore.js                     # Token storage
│   └── routes/                           # API routes
│       ├── auth.js
│       └── classroom.js
│
├── 📁 services/                          # API services
│   ├── api.ts                            # Main API client
│   └── classroomService.ts               # Classroom API
│
├── 📁 types/                             # TypeScript types
│   └── classroom.ts
│
├── 📁 utils/                             # Utilities
│   └── helpers.ts
│
├── 📄 App.tsx                            # Main app
├── 📄 index.tsx                          # Entry point
├── 📄 index.html                         # HTML entry
├── 📄 style.css                          # Global styles
├── 📄 types.ts                           # Shared types
├── 📄 vite.config.ts                     # Vite config
├── 📄 tsconfig.json                      # TS config
├── 📄 package.json                       # Dependencies
├── 📄 README.md                          # You're here!
└── 📄 .gitignore                         # Git ignore
```

---

## 🔐 Security

This project follows security best practices:

| Layer | Protection |
|:------|:-----------|
| **Authentication** | ERPNext session-based auth |
| **CSRF** | Token-based request signing |
| **Roles** | Employee / Teacher / Academic / Admin enforcement |
| **Backend** | Role-level permissions in ERPNext |
| **Route Guards** | Client-side role-based route protection |
| **Environment** | Secrets in `.env` (gitignored) |

### 🛡️ Role Permissions (ERPNext)

| Role | Access Level |
|:-----|:-------------|
| `Employee` | Read own records only |
| `Teacher` | Read own + student data (read-only) |
| `Academics User` | Read & write academic data |
| `System Manager` | Full CRUD access |

---

## 🎨 Design System

### 🎨 Color Palette

| Purpose | Color | Hex |
|:--------|:------|:----|
| Primary Brand | ![](https://via.placeholder.com/15/1B6A3B/1B6A3B) Green | `#1B6A3B` |
| Secondary | ![](https://via.placeholder.com/15/16A34A/16A34A) Emerald | `#16A34A` |
| Success | ![](https://via.placeholder.com/15/22C55E/22C55E) Green | `#22C55E` |
| Warning | ![](https://via.placeholder.com/15/F59E0B/F59E0B) Amber | `#F59E0B` |
| Error | ![](https://via.placeholder.com/15/EF4444/EF4444) Red | `#EF4444` |
| Neutral | ![](https://via.placeholder.com/15/6B7280/6B7280) Gray | `#6B7280` |

### 🖋️ Typography

- **Font Family:** System fonts + custom (`style.css`)
- **Weights:** 400, 500, 600, 700, 800

### 🎭 Components

- **Card-based layouts** with subtle shadows
- **Badge components** for status
- **Modal components** for forms
- **Responsive design** (mobile-first)
- **Consistent spacing** grid

---

## 🧪 Testing Checklist

- [x] Login as Employee
- [x] Login as Teacher / Faculty
- [x] Login as Academic / Admin
- [x] Employee → Apply for leave
- [x] Employee → View payroll
- [x] Teacher → Mark attendance
- [x] Teacher → View class assignments
- [x] Admin → Approve leave
- [x] Admin → Manage employees
- [x] Admin → Generate salary slips
- [x] Admin → View reports & revenue
- [x] Notifications dropdown
- [x] Notice board
- [x] Role-based routing works
- [x] Login activity log

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

---

## 📞 Contact & Support

<div align="center">

**Qadeer Ahmed**

[![GitHub](https://img.shields.io/badge/GitHub-QADEER--AHMED--cs-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/QADEER-AHMED-cs)
[![Repository](https://img.shields.io/badge/Repository-ESS--Portal-1B6A3B?style=for-the-badge&logo=github&logoColor=white)](https://github.com/QADEER-AHMED-cs/Learn-School-Employee-Self-Service-Portal-ESS)

</div>

---

---

<div align="center">


**Built with ❤️ for Learn School**

[![Made with React](https://img.shields.io/badge/Made_with-React-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev)
[![Made in Pakistan](https://img.shields.io/badge/Made_in-Pakistan_🇵🇰-22C55E?style=for-the-badge)](https://en.wikipedia.org/wiki/Pakistan)
[![Powered by ERPNext](https://img.shields.io/badge/Powered_by-ERPNext-0089FF?style=for-the-badge&logo=frappe&logoColor=white)](https://erpnext.com)

</div>
