"Receipt management app — scan receipts, view spending, and save categorized transactions for reporting."

How this README is organized
- User-facing screens (Sign in, Dashboard, Scan, Review & Edit)
- Admin screens (Admin Dashboard, Manage Users, Manage Categories)
- Receipts list, filters, export/share flow, and Profile


Sign In (Welcome)
![image alt](https://github.com/gmuslih/Final-Year-Project/blob/70a2f2797d038784bf16641fab99fe8c621a287f/images/login_page.png)
"Welcome screen with app logo, 'Welcome Back' heading, email and password input fields, and a prominent 'Sign In' button."
Sign In — welcome & authentication
Entry point for sign in / create account / password reset.

Dashboard (Overview & Summary)
![image alt](https://github.com/gmuslih/Final-Year-Project/blob/e7f185384b0a6f46a91966f3eae61ff4697f81e9/images/dashboard_page.png)
"Main dashboard showing total spend, quick action buttons (Scan Receipt, All Receipts, Reports), a Spending Breakdown donut chart, and a recent activity list with transaction amounts."
Dashboard — total spending, quick actions, and activity feed
Summary card, quick actions, chart and recent activity; supports drill-in on chart segments and quick navigation.

Add / Scan Receipt (Camera & Capture)
![image alt](https://github.com/gmuslih/Final-Year-Project/blob/e7f185384b0a6f46a91966f3eae61ff4697f81e9/images/scanning_page.png)
"Scan receipt screen with options to 'Scan with Camera' or 'Import from Gallery', and a camera capture view showing a receipt highlighted by an adjustable crop overlay."
Add Receipt — scan or import receipts
Camera capture with crop overlay, filters, and shutter controls; improves OCR quality before upload.

Review Receipt (Confirm & Save)
![image alt](https://github.com/gmuslih/Final-Year-Project/blob/e7f185384b0a6f46a91966f3eae61ff4697f81e9/images/view_receipt_page.png)
"Review receipt screen showing a preview of the captured receipt image and a 'Receipt Details' card with editable fields: Vendor Name, Total Amount, Date, and Category, plus a large 'Save Receipt' button."
Review Receipt — edit extracted fields and save
OCR-extracted fields editable before saving; category selector for reports.

Receipts (List & Filter)
![image alt](https://github.com/gmuslih/Final-Year-Project/blob/e7f185384b0a6f46a91966f3eae61ff4697f81e9/images/filter_page.png)
"Receipts list showing receipt cards with vendor, category, date and amount; a date range active filter chip at top and a 'Filter Receipts' modal example."
Receipts — list view and filter modal
View receipts, apply date/category filters, open filter modal and start exports.

Edit Receipt (Review & Save Changes)
![image alt](https://github.com/gmuslih/Final-Year-Project/blob/e7f185384b0a6f46a91966f3eae61ff4697f81e9/images/receipt_detail_page.png)
"Edit Receipt screen showing a scanned receipt preview at the top and a 'Receipt Details' card with editable fields (vendor name, total amount, transaction date and category) and a 'Save Changes' button."
Edit Receipt — correct OCR results and save changes
Fix OCR fields, delete receipt, and save updates which reflect in analytics.

Export / Share Flow (Prepare and Share)
![image alt](https://github.com/gmuslih/Final-Year-Project/blob/e7f185384b0a6f46a91966f3eae61ff4697f81e9/images/export_receipt_page.png)
"Receipts list with a bottom status bar preparing an export and the system share sheet overlay showing sharing targets (AirDrop, Messages, Mail, Save to Files, etc.)."
Export / Share — prepare export and share receipts
Prepare CSV/PDF and open platform share sheet for saving or sharing.

Profile (Account & Admin Access)
![image alt](https://github.com/gmuslih/Final-Year-Project/blob/e7f185384b0a6f46a91966f3eae61ff4697f81e9/images/profile_page.png)
"Profile screen showing user card with username and email, role badge (Admin Access), account settings (Edit Name, Admin Dashboard, Notifications, Security) and support items (Help Center, About) plus a Log Out button."
Profile — account settings and admin access
Profile card, account settings, admin dashboard link and sign out.

---

## Admin-facing screenshots (suggested filenames)
1. Screenshot 4 — Admin Dashboard (Overview & Analytics)
   - Filename: `docs/screenshot-4.png`
   - Alt text: "Admin Dashboard mobile UI with Overview cards (total users, receipts uploaded, transaction volume, avg. receipt) and a Spending Breakdown donut chart in the Analytics section."
   - Caption: Admin Dashboard — Overview cards and Spending Breakdown chart
   - Description: At-a-glance metrics, analytics chart with drill-in and navigation to management tools.

2. Screenshot 5 — Manage Users
   - Filename: `docs/screenshot-5.png`
   - Alt text: "Manage Users screen listing accounts with email/label, role (admin/special user/user), and an activation toggle for each account."
   - Caption: Manage Users — view and moderate user accounts
   - Description: Role badges, activate/suspend toggles, and user moderation actions.

3. Screenshot 6 — Manage Categories
   - Filename: `docs/screenshot-6.png`
   - Alt text: "Manage Categories screen showing an 'Add New Category' input with a plus button and a scrollable list of existing categories, each with a delete/trash icon."
   - Caption: Manage Categories — add, edit, remove global categories
   - Description: Create, delete and manage categories applied globally to users.

---
