# 📝 Week 09 Log
**Date:** April 20 – April 24, 2026

### 🎯 Weekly Goals
- [x] Integrate Republic Act 11210 (Maternity/ETP) compliance logic
- [x] Implement real-time Employee ID validation and conflict detection
- [x] Refine Mobile UI for the Employee Status page post-feature expansion
- [x] Global CSS polish for Dark Mode consistency

### 💡 Key Learnings

* **Legal Compliance Engineering:** Researched and integrated RA 11210 logic for Maternity Leave and Emergency Termination of Pregnancy (ETP)/Miscarriage.

*Implemented "No Pause" logic to ensure leave duration counts are continuous and compliant with labor standards.

*Added informative tooltips referencing specific RA sections to increase employee awareness regarding their leave entitlements.

* **Database Integrity & Validation:** Improved the "Add Employee" workflow to track real-time and historical data. The system now prevents HR from assigning an ID that is already linked to an archived or former employee, ensuring a unique "Single Source of Truth" for every record.

* **UI/UX Refinement:**  Dark Mode Optimization: Polished the "Add Employee" form and "History Page" to ensure high visual clarity and professional aesthetics across all color themes.

*Code Maintainability: Refactored the activation/reactivation logic to be more modular and easier to maintain as the employee database grows.


### 🚧 Challenges Faced

* **Layout Regressions:** Discovered that adding new leave types (Maternity/ETP) and admin forms caused the **Employee Status page** layout to break on smaller screens. Dedicated April 22nd to re-polishing the mobile view for cross-device compatibility.

* **Data Conflict Management:** Solving the "Duplicate ID" issue required querying both active and archived collections to ensure no ID overlaps occurred during new registrations.



### ✅ Achievements & Milestones

* **Compliance Ready:** The HRIS now legally accounts for specialized leave types with proper documentation and employee guidance.

* **Mobile-First Maturity:** Finalized responsive layouts for most pages, ensuring the portal is fully functional on smartphones and tablets.

* **System Robustness:** Implemented real-time hotfixes and UI improvements based on initial deployment feedback.

---
*This log focuses on technical methodologies and architectural growth. No proprietary code is included.*
