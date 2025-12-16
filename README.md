# 📰 News Broadcast Updates (NBU)

**🎓 Final Year Project — BS Software Engineering**  
COMSATS University Islamabad, Abbottabad Campus

![Visitors](https://komarev.com/ghpvc/?username=abdullahahmadd&repo=fyp-news-broadcast-updates&label=Visitors&color=0e75b6&style=flat)
![React Native](https://img.shields.io/badge/React%20Native-61DAFB?logo=react)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab)
![Final Year Project](https://img.shields.io/badge/Final%20Year%20Project-BS%20Software%20Engineering-blue?logo=graduation-cap)
---

## 📑 Table of Contents

1. [Overview](#-overview)
2. [Problem Statement](#-problem-statement)
3. [Key Features](#-key-features)
4. [System Architecture](#-system-architecture)
5. [Technologies Used](#-technologies-used)
6. [Core Functionalities](#-core-functionalities)
7. [User Interface (UI)](#-user-interface-ui)
8. [Testing & Quality Assurance](#-testing--quality-assurance)
9. [Project Outcome](#-project-outcome)
10. [Future Enhancements](#-future-enhancements)
11. [Project Team](#-project-team)

---

## 📌 Overview

**News Broadcast Updates (NBU)** is a mobile-based application designed to deliver **hyper-local news updates** through a community-driven platform. The system allows users to browse, submit, and engage with news content relevant to their location, while administrators ensure credibility through a structured moderation process.

The application addresses challenges such as **misinformation**, **lack of local news coverage**, and **information overload** by combining user-generated content with administrative verification and real-time notifications.

---

## 🎯 Problem Statement

Traditional news platforms primarily focus on national or global news, often overlooking events that directly impact local communities. At the same time, the rise of user-generated content has increased the spread of misinformation.

**NBU aims to:**
- Provide reliable, location-based news  
- Enable community participation  
- Maintain content authenticity through admin moderation  

---

## ✨ Key Features

### 👤 User Features
- User registration & secure authentication  
- Browse news based on location and category  
- Submit news with text, images, or videos  
- Edit submissions while under review  
- Receive real-time notifications  
- Profile management & saved news  

### 🛠️ Admin Features
- Review and moderate user-submitted news  
- Approve or reject content with feedback  
- Upload promotional news  
- Manage users and restrict accounts  
- Receive submission notifications  

### 🤖 AI-Powered Feature
- Automatic video summarization for faster content review  
- Generates concise textual summaries from uploaded videos  

---

## 🧱 System Architecture

The system follows the **MVVM (Model–View–ViewModel)** architectural pattern to ensure:
- Clear separation of concerns  
- Improved maintainability and scalability  
- Easier testing and future enhancements  

---

## 🧰 Technologies Used

### Frontend
- Expo  
- React Native  
- JavaScript  

### Backend & Database
- Firebase Authentication  
- Firebase Firestore  
- Firebase Storage  

### AI & Processing
- Python  
- Flask  
- Google Colab (video summarization model)  

---

## 🔄 Core Functionalities
- Location-based news filtering  
- Real-time updates and notifications  
- Secure media storage and retrieval  
- Admin-controlled content verification  
- AI-assisted moderation workflow  

---

## 📱 User Interface (UI)

All application user interfaces are organized under the `UI/` directory for documentation and presentation.

---

### 👤 Frontend — User Screens

| 1. Home Page |
|-------------|
| ![](UI/Front%20End/home_page.jpg) |
| Main landing page displaying latest local news. |

---

| 2. Crime Section |
|----------------|
| ![](UI/Front%20End/crime_section_page.jpg) |
| Crime-related news feed. |

---

| 3. Technology Section |
|----------------------|
| ![](UI/Front%20End/tech_section_page.jpg) |
| Technology-focused news feed. |

---

| 4. My News |
|-----------|
| ![](UI/Front%20End/user_mynews_page.jpg) |
| User-submitted news articles and status tracking. |

---

| 5. News Description |
|--------------------|
| ![](UI/Front%20End/news_description_page.jpg) |
| Detailed view of a selected news article. |

---

| 6. Favourite News |
|------------------|
| ![](UI/Front%20End/favourite_news_page.jpg) |
| Saved and favorited news articles. |

---

| 7. Settings |
|------------|
| ![](UI/Front%20End/settings_page.jpg) |
| User settings and application preferences. |

---

| 8. Edit Profile |
|----------------|
| ![](UI/Front%20End/profile_edit_page.jpg) |
| Interface for updating user profile details. |

---

| 9. Change Location |
|-------------------|
| ![](UI/Front%20End/location_edit_page.jpg) |
| Update user location for localized news. |

---

| 10. Reset Password |
|-------------------|
| ![](UI/Front%20End/password_reset_page.jpg) |
| Password recovery and reset interface. |

---

### 🛠️ Backend — Admin Screens

| 1. Promotional News Upload |
|----------------------------|
| ![](UI/Back%20End/promotional_news_upload_page.jpg) |
| Upload promotional and featured news content. |

---

| 2. News Moderation |
|--------------------|
| ![](UI/Back%20End/admin_moderation_page.jpg) |
| Review, approve, or reject user-submitted news. |

---

| 3. Admin Settings |
|-------------------|
| ![](UI/Back%20End/admin_setting_page.jpg) |
| Administrative configuration and system controls. |

---

## 🧪 Testing & Quality Assurance

The system was validated using:
