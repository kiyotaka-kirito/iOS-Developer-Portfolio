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

🔗 https://github.com/kiyotaka-kirito/Cinemax.git

---

#### 1. [Vigil - Personal Finance Tracker]
*A secure, native iOS app for tracking expenses, managing budgets, and visualizing financial data.*

#### 🛠 Technical Stack
- **Framework:** SwiftUI
- **Architecture:** Modular MVVM
- **Database:** SwiftData
- **Security:** LocalAuthentication (Face ID / PIN)

#### 🚀 Challenges & Solutions
- **Challenge:** Managing complex state and avoiding tangled code as multiple features (Budgets, Analytics, Transactions) scaled.
- **Solution:** Implemented a strict **Modular MVVM architecture** to cleanly separate business logic from the UI, ensuring highly maintainable code and seamless SwiftData integration.

#### 📺 Demo & Screenshots
| Security / PIN | Dashboard | Budget Tracker | Visual Analytics |
|---|---|---|---|
| <img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 Pro - 2026-05-22 at 00 23 09" src="https://github.com/user-attachments/assets/301d3331-b109-4bf9-9baa-e85589814df6" /> | <img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 Pro - 2026-05-22 at 00 23 17" src="https://github.com/user-attachments/assets/116be655-8ca4-4688-bc16-cf9226abaac1" /> | <img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 Pro - 2026-05-22 at 00 23 30" src="https://github.com/user-attachments/assets/80fe1a4f-e94c-4e92-a147-40fde5f233f0" /> | <img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 Pro - 2026-05-22 at 00 23 38" src="https://github.com/user-attachments/assets/0ceedf9f-dd5b-452a-ab02-de2ab90db997" /> |

🔗 https://github.com/yourusername/Vigil.git

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
