# 🎓 Educational Organisation Management System (ServiceNow)

## 📌 Project Overview
The **Educational Management System (EMS)** is built on the **ServiceNow** platform to enhance administrative efficiency in educational institutions.  
It manages student and teacher data, simplifies the admission process, and provides tools for tracking academic progress.  

Key Benefits:
- Centralized student & admission management  
- Automated workflows for error-free operations  
- Dynamic forms & scripts for validation  
- Customizable for various institutions  

---

## ⚙️ Setup Instructions

### 1. Get a ServiceNow Developer Instance
1. Visit [ServiceNow Developer Portal](https://developer.servicenow.com)  
2. Sign up for a **free developer account**  
3. Request a **Personal Developer Instance**  
4. Use the provided credentials to log in  

### 2. Create an Update Set
- Navigate to: `All > Local Update Sets`  
- Create a new update set named **Educational Organisation**  
- Click **Make Current** to start tracking changes  

### 3. Create Required Tables
- **Salesforce Table** → Manages student info  
  - Fields: Admin Number, Grade, etc.  
- **Admission Table** → Extends Salesforce  
  - Fields: Admission Number, Grade, School, Pincode, Status, etc.  

### 4. Configure Forms
- Use **Form Designer** for Salesforce, Admission, and Student Progress tables  

### 5. Number Maintenance
- Auto-generate Admin Numbers in format: `ADM0001`  

### 6. Create Process Flows
- Stages: `New → InProgress → Joined → Rejected → Rejoined → Closed → Cancelled`  

---

## 🖥️ Automation via Client Scripts
- **Auto-Populate Admission Fields** (student details)  
- **Pincode-Based Field Updates** (city, district)  
- **Disable Fields** (for calculated fields like totals)  
- **Auto Total Calculation** (from subject marks)  

---

## ✅ Results
- Centralized student & admission management  
- Automated workflows & validations  
- Easy tracking of student progress  

---

## 📸 Screenshots (to be added in repo)
- Table & form configurations  
- Process flow  
- Script execution in forms  

---

## 📊 Advantages
- Cloud-based, accessible anywhere  
- Reduces manual workload  
- Customizable & secure  
- Integrated system for admissions, records, and performance  

---


---

## 🚀 Future Scope
- Integration with **Power BI/Tableau** for analytics  
- Teacher scheduling & performance tracking  
- Mobile app support (ServiceNow Mobile Studio)  
- API integration with external databases  
- AI-driven student performance insights  

---

## 👨‍💻 Author
Developed as part of an **Educational Organisation Project** using ServiceNow.  
