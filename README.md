# Project30
# Namma-Skill (Self-Employment)

Namma-Skill is an Android application developed using Kotlin, Firebase, and Generative AI technologies to help rural youth and unemployed individuals discover vocational training opportunities available in nearby government and private skill development centers.

The application acts as a bridge between skill development centers and rural communities by providing information about short-term and long-term vocational courses such as Electrician, Welding, Sewing, Coding, Mobile Repair, and Computer Basics.

---

# Features

- User Registration and Login using Firebase Authentication
- Search and Filter Vocational Courses
- Filter Courses by:
  - Trade
  - Duration
  - District
  - Job Guarantee Status
- Apply for Training Programs
- Automatic Candidate Summary Generation
- Firebase Firestore Database Integration
- Google Maps Integration for Skill Center Locations
- Notifications for New Course Batches
- AI-Based Course Recommendations
- User-Friendly and Modern UI
- Offline Support using Local Storage

---

# Technologies Used

| Technology | Purpose |
|---|---|
| Kotlin | Android App Development |
| Android Studio | Development Environment |
| Firebase Authentication | User Login & Registration |
| Firebase Firestore | Cloud Database |
| Firebase Cloud Messaging | Notifications |
| Google Maps API | Skill Center Location |
| RecyclerView | Display Course Lists |
| Material Design | Professional UI |
| Generative AI / Gemini API | AI Recommendations & Chatbot |

---

# Project Structure

```plaintext
NammaSkill/
│
├── activities/
│   ├── LoginActivity.kt
│   ├── RegisterActivity.kt
│   ├── DashboardActivity.kt
│
├── adapters/
│   └── CourseAdapter.kt
│
├── models/
│   ├── Course.kt
│   └── User.kt
│
├── utils/
│   └── AIRecommendation.kt
│
├── res/layout/
│   ├── activity_login.xml
│   ├── activity_dashboard.xml
│   └── item_course.xml
│
└── AndroidManifest.xml
