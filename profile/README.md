# **RAONz: Handong Team Meeting Archiving and Exchange Web Platform** 🚀

> A web-based platform designed to enhance collaboration, documentation, and engagement within Handong University's Residential Colleges (RCs).
> 

## **📌 Project Overview**

### **🛠 Introduction**

Handong University hosts a variety of **Residential Colleges (RCs)**, where numerous **team meetings** take place regularly. These meetings play a **crucial role in fostering community and collaboration** among students. However, the current system presents several challenges:

- 🔴 **Lack of interaction** between different teams and RCs.
- 🔴 **Limited guidance for team leaders**, making leadership overwhelming.
- 🔴 **No centralized archiving system**, leading to loss of important meeting records.

### **🔍 Solution**

RAONz provides a **web-based platform** that:
✔️ Facilitates **seamless communication and collaboration** across teams.

✔️ Provides **guidance and resources** for team leaders.

✔️ Implements a **secure archiving system** for meeting materials.

✔️ Enhances engagement through **ranking, team matching, and interactive features**.

---

## **🎯 Key Features**

### **📑 Team Meeting Management**

✅ Upload and archive **meeting materials**.

✅ **Search & retrieve** past meeting records.

✅ **Automated team matching** for inter-team collaboration.

### **👥 Community Features**

✅ **Like, save, and share** team meeting posts.

✅ **RC-based ranking system** for engagement.

✅ **Event-based content sharing**.

### **🔐 Security & Performance**

✅ **Google OAuth 2.0 authentication** for secure login.

✅ **Spring Security with JWT-based authentication**.

✅ **Optimized scalability with CI/CD pipeline integration**.

### **📷 Multimedia Archiving**

✅ **Photo gallery** for storing team snapshots.

✅ **Automated content categorization and tagging**.

✅ **Intuitive UI for easy browsing**.

---

## **⚙️ System Architecture**

### **🖥 High-Level Overview**

The system follows the **Model-View-Controller (MVC) architecture**, ensuring modularity and maintainability.

### **🔹 Technology Stack**

| Component | Technology |
| --- | --- |
| **Frontend** | React.js, Redux |
| **Backend** | Spring Boot, Spring Security |
| **Database** | MySQL |
| **Authentication** | Google OAuth 2.0, JWT |
| **Deployment** | AWS EC2, Docker, Jenkins |

### **📌 C4 Model - System Context**
The RAONz platform is designed based on the **C4 Model**, ensuring a structured and scalable architecture.

#### **🖥️ System Overview**
- 🟢 **Frontend**: Built with **React.js**, providing a dynamic and intuitive user interface.
- 🟡 **Backend**: Powered by **Spring Boot**, ensuring robust API processing and business logic execution.
- 🔴 **Database**: **MySQL**, managing user data, meeting logs, and archives.

#### **📌 System Context Diagram**
<img src="https://github.com/user-attachments/assets/07fe009f-0f4b-4946-a324-b59bd099a3ee" width=70%>

#### **📌 C4 Model - Container Diagram**
<img src="https://github.com/user-attachments/assets/e13c1e84-a91c-4647-8dd5-a7daf25bc118" width=70%>

These diagrams illustrate the **interaction between users and the system**, the **data flow among key components**, and the **distribution of core application functionalities**.

### **📌 Repository Pattern**

- **Handles CRUD operations** efficiently.
- **Supports modular and maintainable code structure**.

### **📌 API Endpoints**

| Method | Endpoint | Description |
| --- | --- | --- |
| `POST` | `/auth/login` | User login |
| `POST` | `/auth/register` | User registration |
| `GET` | `/teams` | Retrieve all teams |
| `POST` | `/teams/create` | Create a new team |
| `POST` | `/meetings/create` | Upload a new meeting archive |
| `GET` | `/meetings/{id}` | Fetch specific meeting details |

*For full API documentation, refer to the `/docs` directory.*

---

## **🛠 Quality Assurance & Testing**

To ensure high reliability, security, and performance, RAONz has undergone extensive quality assurance and testing.

### **🔍 Testing Tools & Frameworks**
| Tool | Purpose |
|------|---------|
| 🟢 **SonarQube** | Code quality analysis & security vulnerability detection |
| 🟡 **JUnit** | Backend unit testing & validation |
| 🔵 **Selenium** | UI automation testing for frontend components |
| 🔴 **Jenkins** | Continuous integration & automated deployment |

---

### ✅ **Test Results & Analysis**

#### **1️⃣ JUnit - Backend Unit Testing**
✔ **100% pass rate on JUnit tests** _(except for database integration scenarios)_
<br>
<img src="https://github.com/user-attachments/assets/eeb710ce-6e2d-47eb-91f3-04afb58ecad4" width="70%">

---

#### **2️⃣ Selenium - UI Automation Testing**
✔ **All test cases passed successfully**
<br>
<img src="https://github.com/user-attachments/assets/f243fa2e-5d3d-4d96-8821-e27070985735" width="70%">

---

#### **3️⃣ SonarQube - Code Quality & Security Analysis**
✔ **No security vulnerabilities detected**
✔ **A-grade maintainability & readability**
<br>
**[SonarQube Report]**
<br>
<img src="https://github.com/user-attachments/assets/d041a204-ca43-4dd8-8be1-2105b540dfcf" width="70%">

---

#### **4️⃣ FeeDat - Static Code Analysis**
✔ **Zero critical bugs detected**
<br>
**[FeeDat Report]**
<br>
<img src="https://github.com/user-attachments/assets/4782728e-3a48-4d85-afc4-1898395233ba" width="70%">

---

By integrating these tools into our **CI/CD pipeline**, we ensure that the platform maintains **high-quality code, secure architecture, and stable performance** at all times.

---

## **🚀 Deployment & Setup**

### **1️⃣ Clone the Repository**

```bash
git clone https://github.com/your-repo/RAONz.git
cd RAONz
```

### **2️⃣ Backend Setup**

```bash
cd backend
./mvnw spring-boot:run
```

### **3️⃣ Frontend Setup**

```bash
cd frontend
npm install
npm start
```

### **4️⃣ Database Setup**

```bash
mysql -u root -p
CREATE DATABASE RAONz;
```

### **5️⃣ Access the Application**

Visit **`raonz.netlify.app`** to explore the platform.

---

## **📌 Team Members**

| Name | Role |
| --- | --- |
| **Seokjae Ma** | Project Manager |
| **Donggyu Kim** | Scrum Master |
| **Sechang Jang** | Documentation Manager |
| **Junhyeok Choi** | Backend Developer |
| **MinSeo Lee** | Frontend Developer |

---

## **🔍 Future Enhancements**

✅ **AI-powered meeting transcription**.

✅ **Real-time video integration for team meetings**.

✅ **Mobile app version for cross-platform accessibility**.

✅ **Advanced ranking and gamification features**.

---

## **📞 Contact & Contributions**

💡 We welcome contributions! Please follow our Contributing Guide.

📩 **Email:** `maasj7514@gmail.com`

---

### **🚀 Elevating Team Collaboration with RAONz!** 🎉
