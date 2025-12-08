# Student Record Management System 
Live Demo: https://ggthedeveloper.github.io/SRMS-Project/

A fully interactive **Student Record Management System (SRMS)** built using **HTML**, **Tailwind CSS**, **JavaScript**, and modern UI components.  
This portal allows administrators to manage student records, calculate CGPA, manage courses, view analytics, and export data — all with a clean dashboard interface.

---

## Features

### **Login & Authentication**
- Username, password, and captcha verification  
- Admin onboarding with profile setup  
- LocalStorage support for persistent login  

---

## **Admin Dashboard**
- Overview cards:
  - Total Students
  - CSE Department Count
  - Average CGPA
  - Probation/Fail Count
- Live analytics using **Chart.js**:
  - Department-wise student bar chart  
  - CGPA distribution bar chart  
  - Year-wise student count line chart  

---

## Students Directory
- Add, edit, delete student profiles  
- Upload profile photos  
- Search by ID / name / department  
- Auto-generated section list (A–Z, AA–AF)  
- Restricts max **67 students per section**  
- Auto CGPA category coloring  
- Nationality, residency, year, semester & specialization selection  

---

## Course Management + CGPA Calculator
- Add enrolled courses  
- Grade → point mapping  
- Auto CGPA calculation with credit-weighted formula  
- Apply updated CGPA directly to student profile  
- Inline course deletion  
- Shows total credits earned  

---

## Charts & Analytics (Chart.js)
- Department-wise statistics  
- CGPA bracket classification  
- Year-wise student distribution  
- Dynamic updates when records change  

---

## Export to Excel
Uses **SheetJS (XLSX)** to generate downloadable Excel reports:

Includes fields:
- ID  
- Name  
- Email  
- Dept & Specialization  
- Year, Semester, Section  
- CGPA  
- Residency  
- Nationality  
- Status  
- Courses & details  

---

## Technology Stack

| Feature | Technology |
|--------|------------|
| Styling | Tailwind CSS |
| Icons | Lucide Icons |
| Charts | Chart.js |
| Excel Export | SheetJS (XLSX) |
| Persistence | LocalStorage |
| UI Logic | JavaScript |
| Font | Google Fonts – Inter |

---

