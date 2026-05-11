# iOS-Developer-Portfolio 📱
Welcome to my detailed project showcase. Here, I break down the technical decisions and challenges I faced while building these apps.

---

### 📁 Featured Project

#### 1. [Cinemax App - Entertainment]
*A movie provides a seamless user experience for discovering movies, managing watchlists, and viewing detailed information using the TMDB API.*

#### 🛠️ Techinical Stack
- **UI:** SwiftUI
- **Architecture:** Clean Architecture
- **Networking:** URLSession + Codable
- **Local DB:** Core Data for offline support

#### 🧠 Key Architectural Decisions
- **Clean Architecture:**  Domain, Data, and Presentation layers for high testability and separation of concerns. 
- **Dependency Injection:**  Protocol-based DI is used to make the code easier to test.

#### 📺 Demo & Screenshots
| Home | Search | Movie Details | Watchlist |
|---|---|---|---|
| <img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 Pro - 2026-05-12 at 00 22 49" src="https://github.com/user-attachments/assets/32c73bf2-a9a6-4060-826e-3655e5cce815" /> | <img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 Pro - 2026-05-12 at 00 24 11" src="https://github.com/user-attachments/assets/707e8e55-233f-4f27-87d9-bc38cec5f78c" /> | <img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 Pro - 2026-05-12 at 00 26 50" src="https://github.com/user-attachments/assets/9ed82326-7b85-473a-9085-95b71aa1f0d1" /> | <img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 Pro - 2026-05-12 at 00 29 02" src="https://github.com/user-attachments/assets/eda4bf8f-93e4-4a94-a223-ecb061371328" /> |

🔗 [[View Sorurce Code]()](https://github.com/kiyotaka-kirito/Cinemax.git)

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
