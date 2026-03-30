# 📝 Week 05 Log
**Date:** March 23 - March 27, 2026

### 🎯 Weekly Goals
- [x] Migrate local mock data to live Firebase/Firestore backend
- [x] Implement robust Session Persistence (F5/Refresh handling)
- [x] Automate Leave Credit & PTO logic based on employee tenure
- [x] Enhance Calendar Management for HR administrative control

### 💡 Key Learnings
* **Authentication & Session Security:** Resolved a critical "Refresh Bug" by implementing persistent login states. Users now remain authenticated across page refreshes until a manual logout is triggered.
* **Database Architecture (Firestore):** Refined the NoSQL database structure to handle real-time updates for leave requests, employee profiles, and government ID records.
* **Automated Business Logic:** * Developed a **Workday Calculator** that dynamically excludes weekends and regional holidays from leave counts.
    * Implemented **Tenure-Based PTO**: System now auto-calculates 5, 7, or 8 days of Paid Time Off based on years of service.
    * Added **Gender-Specific Validation** for Maternity and Paternity leave categories.
* **Workflow Correction:** Re-engineered the multi-level approval chain to ensure Staff, Supervisors, and Managers follow the correct hierarchical path (e.g., Supervisor → HR).

### 🚧 Challenges Faced
* **Data Integrity:** Transitioning from `localStorage` to **Firebase** required careful mapping to ensure no user data was lost.
* **Calendar Redundancy:** Fixed a logic bug where holidays were duplicating. Implemented a filter to intelligently toggle between PH and AU regional data.

### ✅ Achievements & Milestones
* **HR Administrative Power:** Launched the Calendar Management tool, allowing HR to push company-wide events directly to the system.
* **UI Personalization:** Added a "Birthday Celebrant" trigger that greets users upon their first login on their birthday.
* **System Stability:** Strengthened the "Auth Guard" to ensure the dashboard remains inaccessible to unauthorized or unauthenticated sessions.

---
*This log focuses on technical methodologies and architectural growth. No proprietary code is included.*
