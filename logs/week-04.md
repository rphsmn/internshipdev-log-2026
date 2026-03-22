# 📝 Week 04 Log
**Date:** March 16 - March 20, 2026

### 🎯 Weekly Goals
- [x] Implement Role-Based Access Control (RBAC) for Sidebar navigation
- [x] Integrate dual-region (PH/AU) Holiday Intelligence API
- [x] Develop Management Dashboard for real-time attendance visualization

### 💡 Key Learnings
* **Business Logic Enforcement:** Developed "Policy Guards" to handle complex HR rules, such as the 3/5/7-day notice period for leave filing.
* **State Persistence:** Utilized `localStorage` to manage UI persistence for internal events (e.g., transport strikes) and user sessions.
* **Security & Authentication:** Bolstered system security by stabilizing the Login UI and integrating Firebase for secure, delegated password recovery.
* **UI/UX Optimization:** Implemented "Smart Filing"—a seamless transition from a Calendar date-click to a pre-filled form, reducing user friction.

### 🚧 Challenges Faced
* **Complex Workflow Logic:** Resolved conflicts in single-level approval chains (HR to Admin) to ensure the system remains flexible when standard supervisors are bypassed.
* **Edge Case Handling:** Fixed logic to prevent "Birthday Leave" credit misuse by restricting selection to the employee's specific birth month.

### ✅ Achievements & Milestones
* **Employee Overhead Dashboard:** Successfully launched a high-level visual tool for management to track office attendance vs. leaves at a glance.
* **Data Longevity:** Finalized automated API synchronizations and holiday integrations synced through 2036.
* **RBAC Implementation:** Successfully restructured the application sidebar to hide/show sensitive management tabs based on official job titles.

---
*This log focuses on technical methodologies and architectural growth. No proprietary code is included.*
