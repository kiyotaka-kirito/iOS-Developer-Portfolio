# iOS-Developer-Portfolio 📱
Welcome to my detailed project showcase. Here, I break down the technical decisions and challenges I faced while building these apps.

---

### 📁 Featured Project

#### 1. [The Movie App - Entertainment]
*A movie application fouces on smooth UI transitions and real-time tracking.*

#### 🛠️ Techinical Stack
- **UI:** UIKit (Programmatic UI)
- **Architecture:** MVVM-C (Coordinator Pattern)
- **Networking:** Alamofire + Codable
- **Local DB:** Core Data for offline support

#### 🧠 Key Architectural Decisions
- **Coordinator Pattern:** This pattern, which is not often used by juniors, is used to remove navigation logic from the view controller. 
- **Dependency Injection:**  Protocol-based DI is used to make the code easier to test.

#### 📺 Demo & Screenshots
|Splash & Home | Movie List & Movie Detail | Search & Filter
| --- | --- | --- |
| ![Home]() | ![Movie]() | ![Search]()

🔗 [View Sorurce Code]()

---

#### 2. [CryptoTracker - Marketing]
*Real-time cryptocurrency price tracker using Combine and SwiftUI.*

#### 🛠 Technical Stack
- **Framework:** SwiftUI
- **Reactive:** Combine (for API polling)
- **Charts:** Swift Charts API

#### 🚀 Challenges & Solutions
- **Challenge:** There was a performance drop in the UI due to frequent data changes from the API.
- **Solution:** We reduced the number of occurrences using `debounce` and `removeDuplicates` (Combine operators).

🔗 [View Source Code]()

---

#### 🧪 Technical Skills & Standards
Even though I am a junior, I pay attention to the things that seniors watch out for:

- **Clean Code:** I follow SOLID Principles as much as possible.
- **Unit Testing:** I use XCTest to write tests for logic.
- **Git Flow:** I use Feature branches, Pull Requests, and Meaningful commit messages.
- **Performance:** I use `[weak self]` carefully to avoid Memory Leaks (Strong reference cycles).

---

#### 📈 Learning Roadmap
- [ ] Mastering **Combine** Framework
- [ ] Exploring **Modular Architecture**
- [ ] Learning **Unit Testing & UI Testing** in depth

---
