<p align="center">
  <img src="frontend/public/images/EDusphere.png" alt="EduSphere Banner" width="400"/>
</p>

<p align="center">
  🚀 <a href="https://edusphare.netlify.app/" target="_blank"><strong>Live Frontend Demo</strong></a> | 🔧 <a href="https://edusphare.pythonanywhere.com" target="_blank"><strong>Live Backend API</strong></a>
</p>





---

### 📚 Resources
- [👥 Team Members](#-team-members)
- [📘 Project Description](#-project-description)
- [✨ Key Highlights](#-key-highlights)
- [🎯 Stakeholders](#-stakeholders)
- [📋 SRS - Functional Requirements](#-srs---functional-requirements)
- [📈 Diagrams](#-diagrams)
- [🖼️ Application Screenshots](#-application-screenshots)
- [🛠 Tech Stack](#-tech-stack)
- [🧑‍💻 Getting Started](#-getting-started)
- [📏 Development Guidelines](#-development-guidelines)
- [📘 View Devlog](devlog.md)



---

 ## 👥 Team Members

  <p align="left">
    <a href="https://github.com/mhtasnia" target="_blank" style="text-decoration: none;">
      <img alt="mhtasnia" src="https://img.shields.io/badge/mhtasnia-Profile-blue?style=flat-square&logo=github" />
    </a>
    <a href="https://github.com/reshadMajumder" target="_blank" style="text-decoration: none;">
      <img alt="reshadMajumder" src="https://img.shields.io/badge/reshadMajumder-Profile-blue?style=flat-square&logo=github" />
    </a>
    <a href="https://github.com/Rokibul-Islam-Robi" target="_blank" style="text-decoration: none;">
      <img alt="Rokibul-Islam-Robi" src="https://img.shields.io/badge/Rokibul--Islam--Robi-Profile-blue?style=flat-square&logo=github" />
    </a>
  </p>


---

**👨‍🏫 Mentor:** Minhazul Hasan

---

## 📘 Project Description
EduSphere is a dynamic online platform designed to enhance university learning through:

- Personalized learning pathways  
- Academic collaboration  
- Peer teaching opportunities  
- Resource sharing

It empowers students to seamlessly transition between the roles of learner and mentor, improving outcomes and fostering community.

---

## ✨ Key Highlights
- 📚 **Academic Resource Hub** – Share study materials, notes, etc.  
- 🤝 **Peer-to-Peer Collaboration** – Group projects, discussions  
- 🧠 **Teach What You Know** – Students mentor others  
- 🏫 **Community Building** – Strong academic network

---

## 🎯 Stakeholders
| Role   | Description |
|--------|-------------|
| 👩‍🎓 **Student** | Primary users, access & share learning resources |
| 👨‍💼 **Admin**   | Oversees system, maintains integrity & security |

---

## 📋 Software Requirements Specification (SRS) - Functional Requirements

| ID     | Feature                      | Description                                              | Stakeholders     |
|--------|------------------------------|----------------------------------------------------------|------------------|
| FR01   | Login                        | User login with credentials                              | Student, Admin   |
| FR02   | Signup                       | Register with name, email, university, etc.              | Student          |
| FR07   | Make Contributions           | Share notes, videos, etc.                                | Student          |
| FR10   | Search Contributions         | Search by name or contribution type                      | Student, Admin   |
| FR12   | Filter by University/Dept    | Narrow resources based on institution                    | Student, Admin   |
| FR14   | Help & Support               | Assistance on platform usage                             | Student          |
| FR15   | Report a Contribution        | Flag inappropriate or inaccurate materials               | Student, Admin   |
| FR16   | Download Materials           | Download PDFs of shared notes                            | Student          |
| FR17   | Take Notes                   | Make timestamped notes on video lectures                 | Student          |
| FR18   | Make Payment                 | Pay to access peer-created premium content               | Student          |
| FR19   | Request Refund               | Submit refund request with reason                        | Student          |



---

## 📈 Diagrams

### 📊 Data Flow Diagram
![Data Flow Diagram](frontend/public/images/DFD.png)


### 📊 Entity Relationship Diagram
![Entity Relationship Diagram](frontend/public/images/Entity.png)

---
---
## 🖼️ Application Screenshots

### 🏠 Home Page

![Home Page](frontend/public/images/homepage.png)

### 📊 Contribution Page

![Dashboard](frontend/public/images/contributionpage.png)

### 📚 Course Detail View

![Course Detail](frontend/public/images/contriview.png)
![Course Resources](frontend/public/images/resourcesincontri.png)

### 💳 Payment Page

Shows the interface where users complete transactions to access premium study materials.

![Payment Page](frontend/public/images/payment.png)
![Payment Success](frontend/public/images/payment_success.png)

---

### 🔒 Before Buying Contribution Page

Displays a locked view of a contribution before purchase, encouraging users to buy access.

![Before Buying Contribution Page](frontend/public/images/contribeforeaccess.png)

---

### ➕ Add Contribution Page

Enables students to upload notes, videos, or other academic resources to the platform.

![Add Contribution Page](frontend/public/images/addcontri1.png)
![Add Contribution submit](frontend/public/images/addcontri3.png)


---
## 🛠 Tech Stack

**Frontend:**  
- ⚛️ ReactJS  

**Backend:**  
- 🐍 Django ,DRF 
- 🗃️ PostgreSQL/sqlite3  
- 🔄 Django ORM  

**Other Tools:**  
- 📝 Markdown (logs, docs)  
- 🔀 Git & GitHub  
- 🚀 Deployment (TBD)

---

## 🧑‍💻 Getting Started

```bash
# Clone the repository
git clone https://github.com/Learnathon-By-Geeky-Solutions/pipinstallc.git

#create virtual environment& activate
# Install dependencies
cd frontend && npm install
cd backend && pip install -r requirements.txt

# Start development
npm start   # for frontend
python manage.py runserver  # for backend
