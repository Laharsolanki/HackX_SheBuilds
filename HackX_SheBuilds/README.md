# HackX_SheBuilds
# 🌆 NagarUjjwal – Crowdsourced Civic Issue Reporting System  

**Live Demo:** [hackx-shebuilds-nagarujjwal.vercel.app](https://hackx-shebuilds-nagarujjwal.vercel.app)  

---

## 🧩 Overview  
**NagarUjjwal** is a web-based platform built under the **HackX SheBuilds** initiative that empowers citizens to report civic issues such as unclean areas, broken roads, and waterlogging, while enabling administrators to manage and resolve them transparently.  
This version focuses on the **frontend prototype** developed with **HTML, CSS, and Vanilla JavaScript**, designed to visualize the full workflow from reporting to resolution tracking.

---

## 🏙️ Problem Statement  
Urban areas often face communication gaps between citizens and municipal authorities. Complaints are either delayed, untracked, or unresolved due to lack of a transparent digital system.  
**NagarUjjwal** bridges this gap by providing:  
- A platform for citizens to raise issues with photos and descriptions  
- Status tracking of every complaint  
- Administrative panel for progress updates  

---

## ✨ Features  
### 👤 User Module
- Role-based login (User / Admin)
- File and submit new complaints with description and category  
- Track status of existing complaints (Submitted → In Review → In Progress → Resolved)  
- View issue history  

### 🧑‍💼 Admin Module
- Manage and monitor submitted complaints  
- Update progress and resolution status  
- Provide feedback and mark issues as resolved  

### 🌐 Common  
- Fully responsive layout  
- Modern beige–brown–green color palette inspired by cleanliness and eco-consciousness  
- Hosted via **Vercel** for real-time deployment  

---

## ⚙️ Tech Stack
| Component | Technology |
|------------|-------------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Deployment | Vercel |
| Data Handling | LocalStorage (for demo purpose) |
| Design Tool | Figma |

---

## 🧭 Folder Structure
```
HackX_SheBuilds
├──data(Sample)
├──src/
|   ├── admin/ # Admin pages
|   ├── user/ # User pages
|   ├── images/ # Logos and assets
|   ├── index.html # Role selection / main entry
|   ├── css/ # Global and page styles
|   ├── js/ # Frontend logic scripts
├──Demo_Video.mp4
├──poster.pdf
├──presentation.pptx
├──README.md
├──requirements.txt
```

---

## 💻 Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Laharsolanki/HackX_SheBuilds.git
cd HackX_SheBuilds
``` 

### 2️⃣ Open in your editor
```bash
code .
``` 

### 3️⃣ Run locally
Simply open index.html in your browser — no dependencies required.

### 📈 Future Enhancements
- Integrate backend (Node.js + Express + MongoDB)
- AI-based image classification for complaint auto-tagging
- Push notifications for updates
- Admin dashboard analytics and map-based issue visualization

### 👥 Team Details
Team: SheBuilds
Project Name: NagarUjjwal – My Dream Clean City
Institution: U.V. Patel College of Engineering
| Name               | Role / Contribution                                                    | Department |
| ------------------ | ---------------------------------------------------------------------- | ---------- |
| **Lahar Solanki**  | Created **Role Selection**, **Login**, and **User Dashboard** pages    | IT         |
| **Muskan Isarani** | Designed **Admin-side webpages** and prepared the **PPT presentation** | IT         |
| **Moksha Parikh**  | Designed the **Project Poster** and worked on branding visuals         | IT         |
| **Hiral Madhu**    | Developed **User-side Tracking** and **Report Problem** pages          | CE         |

