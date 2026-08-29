# MediSphere

**An Appointment Management System**  
*Level-2 Term-1 Database Project | BUET CSE*

MediSphere is a web-based hospital management system designed to streamline interactions between **Patients**, **Doctors**, and **Admins**. It provides features for appointment booking, schedule management, prescriptions, diagnostics, and user dashboards.

---

## Features

### Patient
- Sign up / Login
- Browse doctors by specialty
- Book and manage appointments
- View past & upcoming appointments
- Access prescriptions and diagnostic reports
- Update profile

### Doctor
- Sign up / Login
- Set and update availability schedule
- View and manage appointments
- Write prescriptions
- View patient history
- Manage profile

### Admin
- Manage doctors and patients
- View system-wide appointments
- Oversee diagnostics and reports
- Dashboard with overall statistics

---

## Tech Stack

| Layer       | Technology              |
|-------------|-------------------------|
| Backend     | Node.js, Express.js     |
| Frontend    | EJS, HTML, CSS, JavaScript |
| Database    | Oracle / SQL            |
| Architecture| MVC                     |

---

## Project Structure
MediSphere/
├── Database/          # Database query modules
├── Middlewares/       # Authentication & authorization
├── Routes/            # Express routes
├── views/             # EJS templates
├── queries/           # SQL queries
├── db.js              # Database connection
└── README.md
