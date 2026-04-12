📝 Week 07 Log Entry (April 06 - April 10, 2026)
🎯 Weekly Goals

Implement Dedicated Sick Leave (SL) logic and Medical Certificate requirements.

Author and deploy Firestore Security Rules for enhanced Data Privacy.

Integrate Regional Holiday Intelligence with visual country indicators.

Develop "Export CSV" functionality for payroll and audit transparency.

💡 Key Learnings

Security Architecture: Authored granular Firestore Security Rules to enforce strict data silos. Employees are now restricted to viewing/modifying only their own records, while HR maintains administrative oversight.

Business Logic Enforcement:

Conditional Validation: Engineered logic that dynamically requires Medical Certificate uploads only for Sick Leave requests spanning 3+ days.

Tenure-Based Restrictions: Built a policy guard to restrict new hires (<1 year service) to specific leave categories (SL, Birthday, LWOP).

UI/UX Engineering:

State-Driven UI: Implemented a Dark Mode toggle using a moon/sun switch, ensuring high-fidelity branding remains consistent across themes.

Interactive Elements: Added "Click-to-Copy" clipboard functionality for profile fields and real-time validation for leave balances.

Real-Time Notification Systems: Upgraded the alert system with "Smart Inbox" history, browser tab counters, and professional audio cues for new requests.

🚧 Challenges Faced

Data Reconciliation: Conducted a manual audit of digital records against physical HR files, correcting over-deducted balances for specific employees to ensure 100% database accuracy.

Unit Standardization: Successfully migrated all legacy hourly/minute-based records to the new 0.5/1.0 day standard to align with updated company policy.

✅ Achievements & Milestones

Payroll Readiness: Launched the "Export CSV" feature with optimized spreadsheet templates for immediate HR monthly audits.

Regional Intelligence: The system is now fully "region-aware," using 🇵🇭 and 🇦🇺 flags to clearly distinguish holidays across dual-country operations.

Data Integrity: Implemented Duplicate Submission Prevention by immediately disabling the "Submit" button after the first click to prevent race conditions.

This log focuses on technical methodologies and architectural growth. No proprietary code is included.
