# TaxMate — Screenshots & Feature Showcase

This README documents the app screenshots and explains the main functions / features for both user and admin flows. Place the image files under `docs/` (suggested filenames listed next to each screenshot). If you prefer, I can also upload optimized/cropped images — tell me and I'll add them in a follow-up push.

Quick intro
A short sentence about the app: "Receipt management app — scan receipts, view spending, and save categorized transactions for reporting."

How this README is organized
- User-facing screens (Sign in, Dashboard, Scan, Review & Edit)
- Admin screens (Admin Dashboard, Manage Users, Manage Categories)
- Receipts list, filters, export/share flow, and Profile
- How to add images to the repo and commit

---

## User-facing screenshots (suggested filenames)
Place these files in `docs/` with the filenames shown and commit. Each entry includes alt text, a caption, and a short description of the screen's purpose and key functions.

1. Screenshot 7 — Sign In (Welcome)
   - Filename: `images/login_page.png`
   - Alt text: "Welcome screen with app logo, 'Welcome Back' heading, email and password input fields, and a prominent 'Sign In' button."
   - Caption: Sign In — welcome & authentication
   - Description: Entry point for sign in / create account / password reset.

2. Screenshot 8 — Dashboard (Overview & Summary)
   - Filename: `images/login_page.png`
   - Alt text: "Main dashboard showing total spend, quick action buttons (Scan Receipt, All Receipts, Reports), a Spending Breakdown donut chart, and a recent activity list with transaction amounts."
   - Caption: Dashboard — total spending, quick actions, and activity feed
   - Description: Summary card, quick actions, chart and recent activity; supports drill-in on chart segments and quick navigation.

3. Screenshot 9 — Add / Scan Receipt (Camera & Capture)
   - Filename: `docs/screenshot-9.png`
   - Alt text: "Scan receipt screen with options to 'Scan with Camera' or 'Import from Gallery', and a camera capture view showing a receipt highlighted by an adjustable crop overlay."
   - Caption: Add Receipt — scan or import receipts
   - Description: Camera capture with crop overlay, filters, and shutter controls; improves OCR quality before upload.

4. Screenshot 10 — Review Receipt (Confirm & Save)
   - Filename: `docs/screenshot-10.png`
   - Alt text: "Review receipt screen showing a preview of the captured receipt image and a 'Receipt Details' card with editable fields: Vendor Name, Total Amount, Date, and Category, plus a large 'Save Receipt' button."
   - Caption: Review Receipt — edit extracted fields and save
   - Description: OCR-extracted fields editable before saving; category selector for reports.

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

## Receipts list, edit, export & profile (suggested filenames)
1. Screenshot 11 — My Receipts (List & Filter)
   - Filename: `docs/screenshot-11.png`
   - Alt text: "My Receipts list showing receipt cards with vendor, category, date and amount; a date range active filter chip at top and a 'Filter Receipts' modal example."
   - Caption: My Receipts — list view and filter modal
   - Description: View receipts, apply date/category filters, open filter modal and start exports.

2. Screenshot 12 — Edit Receipt (Review & Save Changes)
   - Filename: `docs/screenshot-12.png`
   - Alt text: "Edit Receipt screen showing a scanned receipt preview at the top and a 'Receipt Details' card with editable fields (vendor name, total amount, transaction date and category) and a 'Save Changes' button."
   - Caption: Edit Receipt — correct OCR results and save changes
   - Description: Fix OCR fields, delete receipt, and save updates which reflect in analytics.

3. Screenshot 13 — Export / Share Flow (Prepare and Share)
   - Filename: `docs/screenshot-13.png`
   - Alt text: "Receipts list with a bottom status bar preparing an export and the system share sheet overlay showing sharing targets (AirDrop, Messages, Mail, Save to Files, etc.)."
   - Caption: Export / Share — prepare export and share receipts
   - Description: Prepare CSV/PDF and open platform share sheet for saving or sharing.

4. Screenshot 14 — Profile (Account & Admin Access)
   - Filename: `docs/screenshot-14.png`
   - Alt text: "Profile screen showing user card with username and email, role badge (Admin Access), account settings (Edit Name, Admin Dashboard, Notifications, Security) and support items (Help Center, About) plus a Log Out button."
   - Caption: Profile — account settings and admin access
   - Description: Profile card, account settings, admin dashboard link and sign out.

---

## Existing earlier screenshots (if already saved)
If you already added earlier screenshots (1,2,3) under `docs/`, keep them. Suggested filenames: `docs/screenshot-1.png`, `docs/screenshot-2.png`, `docs/screenshot-3.png`.

## How to add images and commit (if you prefer to add them locally)
1. Add your screenshots to `docs/` using the filenames above.
2. Commit and push: 

```bash
git add README.md docs/screenshot-*.png
git commit -m "Add README with screenshots and descriptions"
git push
```

## Image optimization & editing tips
- Crop or rotate screenshots so the UI is centered and remove excess whitespace.
- Keep file sizes ≤ 1–2 MB for smooth GitHub rendering.
- Use PNG for clear UI elements; use optimized JPEG for photos.
- Example ImageMagick commands: 
  - Rotate 180°: `magick convert input.png -rotate 180 output.png`
  - Crop: `magick convert input.png -crop 1080x1920+0+100 output.png`
  - Resize/optimize: `magick convert input.png -resize 1200x -strip -quality 85 output.jpg`

---

## Next steps
I pushed this README to `main`. To complete the presentation I recommend adding the screenshot image files under `docs/` with the filenames above. If you want, I can prepare optimized/cropped images and push them in a follow-up commit — confirm and I will add them.
