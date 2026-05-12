# 📝 Week 10 Log
**Date:** April 27 – May 01, 2026

### 🎯 Weekly Goals
- [x] Implement dynamic Maternity Leave scaling (Solo Parent logic)
- [x] Establish Role-Based Access Control (RBAC) for Admin Managers and Supervisors
- [x] Optimize system performance via Skeleton Screens and Search Debouncing
- [x] Finalize System Documentation and Maintenance scripts

### 💡 Key Learnings

* **Complex Business Logic:** Refined Maternity Leave calculations to support **Solo Parent** status. The system now automatically scales the balance from 105 to 120 days upon selection, ensuring alignment with specific legal entitlements.
* **Security & Performance Engineering:** * **Credential Protection:** Migrated sensitive system keys to a secure vault (Environment Variables), following professional security standards to prevent data leaks.
    * **Latency Optimization:** Replaced blank loading states with **Skeleton Screens (Preview Outlines)** and implemented **Search Debouncing**. This prevents "UI stuttering" and makes the interface feel instantaneous during heavy data fetching.
* **Granular Access Control (RBAC):** Engineered a multi-tier permission system. Admin Managers now have full transparency over account logs, while Supervisors are restricted to viewing only those employees belonging to their assigned departments.
* **Error Resilience:** Integrated a **"Black Box" Logger** (System Health Monitoring). This automatically records technical "hiccups" or crashes, allowing for rapid debugging and reducing overall system downtime.

### 🚧 Challenges Faced

* **UI Redundancy & Clarity:** Identified that displaying "Department" on individual profiles was redundant due to the existing directory structure. Successfully pivoted the UI to display the **Employee's Actual Role**, providing more relevant professional context at a glance.
* **Modal UX Safety:** Addressed an issue with accidental closures of critical forms (like "Add Employee"). Removed the "on-click-outside" trigger for pop-up modals to ensure users don't lose data entry progress.
* **Vercel Deployment Debugging:** Resolved hosting issues and permission-based routing errors that initially prevented Supervisors from accessing their departmental views.

### ✅ Achievements & Milestones

* **Production Hardening:** Completed a comprehensive "performance tune-up," resulting in a faster, more secure application ready for daily HR operations.
* **Dark Mode Accessibility:** Improved visual hierarchy by adding high-contrast red outlines to status indicators (e.g., "ON LEAVE") to ensure critical information stands out in dark themes.
* **Documentation Finalized:** Updated `SYSTEM_GUIDE.md` to a production-ready state, removing all placeholders and verifying the technical accuracy of the entire feature set.
* **Part-Time Parity:** Successfully separated Part-Time leave logic from the "1-year service" requirement, granting appropriate credits for Maternity/Paternity entitlements.

---
*This log focuses on technical methodologies and architectural growth. No proprietary code is included.*
