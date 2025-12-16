# 📰 News Broadcast Updates (NBU)

**Final Year Project — BS Software Engineering**  
COMSATS University Islamabad, Abbottabad Campus

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

| Screen | Preview | Description |
|------|--------|-------------|
| Home Page | ![](UI/Front%20End/home_page.jpg) | Main landing page displaying latest local news |
| Crime Section | ![](UI/Front%20End/crime_section_page.jpg) | Crime-related news feed |
| Technology Section | ![](UI/Front%20End/tech_section_page.jpg) | Technology news feed |
| My News | ![](UI/Front%20End/user_mynews_page.jpg) | User-submitted news articles |
| News Description | ![](UI/Front%20End/news_description_page.jpg) | Detailed view of a news article |
| Favourite News | ![](UI/Front%20End/favourite_news_page.jpg) | Saved and favorited news |
| Settings | ![](UI/Front%20End/settings_page.jpg) | User settings and preferences |
| Edit Profile | ![](UI/Front%20End/profile_edit_page.jpg) | Profile update interface |
| Change Location | ![](UI/Front%20End/location_edit_page.jpg) | Update user location |
| Reset Password | ![](UI/Front%20End/password_reset_page.jpg) | Password reset interface |

---

### 🛠️ Backend — Admin Screens

| Screen | Preview | Description |
|------|--------|-------------|
| Promotional News Upload | ![](UI/Back%20End/promotional_news_upload_page.jpg) | Upload promotional news |
| News Moderation | ![](UI/Back%20End/admin_moderation_page.jpg) | Review and approve/reject user submissions |
| Admin Settings | ![](UI/Back%20End/admin_setting_page.jpg) | Admin configuration and controls |

---

## 🧪 Testing & Quality Assurance

The system was validated using:
