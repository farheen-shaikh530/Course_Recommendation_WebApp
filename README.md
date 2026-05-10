<p align="center">
  <img width="1000" height="500" alt="Course Mapping System Banner" src="https://github.com/user-attachments/assets/72d684c0-b252-446d-9aec-1d29d21540ed" />
</p>

<h1 align="center">Course Mapping System — User Guide</h1>

<p align="center">
  <b>University of the Pacific — Office of Global Education</b><br>
  <b>Live Demo:</b> <a href="https://uop-course-approval-request-form-view.netlify.app">Course Approval Request Form Viewer</a><br>
  <b>Portal:</b> <a href="https://pacific-global.via-trm.com/authV2/welcome">Pacific Global Study Abroad Portal</a>
</p>

---

## Table of Contents

1. [What is the Course Recommendation System?](#what-is-this-system)
2. [Who can use this system?](#who-is-this-for)
3. [Application Startup Guideline](#getting-started)
4. [How to Search for Courses](#how-to-search-for-courses)
5. [How to Filter Results](#how-to-filter-results)
6. [How to Export Data into Excel](#how-to-export-data)
7. [For Admins: Managing Course Approvals](#for-admins-managing-course-approvals)
8. [For Admins: Updating Data Sources](#for-admins-updating-data-sources)
9. [Frequently Asked Questions (FAQ)](#frequently-asked-questions-faq)
10. [Troubleshooting](#troubleshooting)
11. [Tech Stack & Architecture](#tech-stack--architecture)
12. [Screenshots](#screenshots)
13. [Impact & Results](#impact--results)
14. [License](#license)

---

## What is the Course Recommendation System?

The **Course Mapping System** streamlines the process of **searching, mapping, and approving international courses** for students preparing to study abroad. It enables students and staff to:

- View previously approved course equivalencies
- Reduce redundant paperwork and duplicate submissions
- Make transparent, consistent decisions for outbound study abroad participants

> **Before this system:** Students and staff had limited visibility into approved courses, submitted redundant approvals, and navigated a confusing interface that made evaluating international credits difficult.

---

## Who can use this system?

| User | What You Can Do |
|------|----------------|
| **Students** | Search approved courses, view equivalencies, export results for advising meetings |
| **Academic Advisors** | Review mapped courses, verify approvals, download records |
| **Office Coordinators** | Upload new courses, manage approvals, maintain data sources |

---

## Application Startup Guideline

### Step 1: Access the Portal

1. Navigate to the **Pacific Global Study Abroad Portal**: [pacific-global.via-trm.com](https://pacific-global.via-trm.com/authV2/welcome)
2. Click **Sign Up** (first-time users) or **Log In** (returning users)
3. Use your University of the Pacific credentials

### Step 2: Navigate to Course Mapping

Once logged in, you will see:

- A **"Brochure" section** for browsing global university programs
- The **Course Mapping System** — click to begin searching and exploring course equivalencies

### Step 3: Start Searching

Use the search bar or filters to find courses. See detailed instructions below.

> **Quick Access (No Login Required):** View the standalone course approval form at [Course Approval Request Form Viewer](https://uop-course-approval-request-form-view.netlify.app)

---

## How to Search for Courses

1. Open the **Course Mapping** module from the portal dashboard
2. Type a **course name**, **university name**, or **subject keyword** in the search bar
3. Results appear instantly — matching approved courses display with:
   - Host university name
   - Course title and code
   - UOP equivalent course
   - Approval status

> **Tip:** Use specific keywords for better results. For example, search "Calculus Madrid" instead of just "Math."

---

## How to Filter Results

Narrow your search using the filter options:

| Filter | Description |
|--------|-------------|
| **Country** | Filter by destination country |
| **University** | Filter by specific host institution |
| **Department** | Filter by UOP academic department |
| **Approval Status** | View approved, pending, or denied courses |
| **Term** | Filter by Fall, Spring, Summer, or Faculty-Led trips |

### Steps:

1. Click the **Filter** icon next to the search bar
2. Select one or more filter criteria
3. Results update automatically
4. Click **Clear Filters** to reset

---

## How to Export Data

Export your search results for advising meetings or personal records:

1. Perform a search or apply filters
2. Click the **Export** button (top-right corner of results)
3. Choose format: **CSV** or **Excel (.xlsx)**
4. File downloads automatically to your device

> **For Advisors:** Export results before advising appointments to have a printed reference of approved courses.

---

## For Admins: Managing Course Approvals

### Adding a New Course Approval

1. Log in with **admin credentials**
2. Navigate to **Admin Panel** → **Course Approvals**
3. Click **Add New Course**
4. Fill in the required fields:
   - Host university name
   - Host course title and code
   - UOP equivalent course
   - Approval decision (Approved / Denied / Pending)
   - Effective term and year
5. Click **Submit**

### Editing an Existing Approval

1. Search for the course in the admin panel
2. Click the **Edit** icon next to the entry
3. Update the relevant fields
4. Click **Save Changes**

### Removing a Course

1. Search for the course
2. Click the **Delete** icon
3. Confirm deletion

> **Important:** Deleted courses cannot be recovered. Export a backup before making bulk changes.

---

## For Admins: Updating Data Sources

The system pulls live data from **Google Sheets**. To update:

### Step 1: Access the Google Sheet

- Open the linked Google Sheet (shared with admin team)
- Each tab represents a different data category (courses, universities, departments)

### Step 2: Edit Data

- Add new rows for new courses
- Edit existing rows to update information
- Do **not** change column headers — this will break the API connection

### Step 3: Verify Changes

- Return to the Course Mapping System
- Search for the updated course to confirm changes appear
- Allow up to **5 minutes** for the Google Sheets API to sync

> **Warning:** Do not rename, reorder, or delete columns in the Google Sheet. Contact the developer if structural changes are needed.

---

## Frequently Asked Questions (FAQ)

### Q: Do I need to log in to use the system?

**A:** Yes, the full Course Mapping System requires login through the Pacific Global portal. However, the [Course Approval Request Form Viewer](https://uop-course-approval-request-form-view.netlify.app) is accessible without login.

### Q: Can I search for courses from any country?

**A:** Yes, the system includes approved courses from all partner institutions worldwide.

### Q: What if my course isn't listed?

**A:** If a course is not found, it hasn't been approved yet. Contact your academic advisor or the Office of Global Education to submit a new course approval request.

### Q: Can I save my search results?

**A:** Yes, use the **Export** button to download results as CSV or Excel.

### Q: Who do I contact for technical issues?

**A:** Email the Office of Global Education or submit a support request through the portal.

---

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Page not loading | Clear browser cache and refresh. Try a different browser (Chrome recommended). |
| Search returns no results | Check spelling. Try broader keywords. Clear filters and search again. |
| Export not downloading | Ensure pop-ups are enabled in your browser. Try right-click → "Save As." |
| Data looks outdated | Allow up to 5 minutes for Google Sheets sync. Contact admin if issue persists. |
| Login issues | Reset password through the portal. Contact IT if your account is locked. |
| Mobile layout issues | Use landscape mode for best experience. Desktop recommended for admin tasks. |

---

## Tech Stack & Architecture

| Layer | Technology |
|-------|-----------|
| **Frontend** | JavaScript, HTML, CSS, React, Angular |
| **Backend/Data** | Google Sheets API, Google Visualization API |
| **Design** | Figma, UOP Brand Guidelines |
| **Deployment** | Netlify (standalone), Via TRM Portal (integrated) |
| **Methodology** | Agile sprints, cross-functional design reviews |

### Design Principles

- **Brand-aligned** — consistent with University of the Pacific branding (colors, typography, spacing)
- **Accessible** — high contrast, semantic HTML, keyboard navigation
- **Responsive** — works across desktop, tablet, and mobile devices

---

## Screenshots

<p align="center">
  <img width="3024" height="1596" alt="Dashboard View" src="https://github.com/user-attachments/assets/d0236cee-f5ae-44fe-bffa-7d46e43f4e98" />
</p>
<h5 align="center">Dashboard — Course Search View</h5>

<p align="center">
  <img width="2966" height="1566" alt="Search Results" src="https://github.com/user-attachments/assets/7bb0766a-dd93-474f-ad29-99c565a2dbce" />
</p>
<h5 align="center">Search Results with Filters Applied</h5>

<p align="center">
  <img width="2988" height="1588" alt="Course Details" src="https://github.com/user-attachments/assets/35fd8828-3cec-4572-b655-c6a64dc7a64d" />
</p>
<h5 align="center">Course Equivalency Details</h5>

<p align="center">
  <img width="1512" height="615" alt="Admin Panel" src="https://github.com/user-attachments/assets/46a5f96b-2f5a-4ef6-b390-2e9c392fda5d" />
</p>
<h5 align="center">Admin Panel — Course Management</h5>

<p align="center">
  <img width="1504" height="596" alt="Export View" src="https://github.com/user-attachments/assets/9e6e995b-15aa-42f5-ab46-1990bdf7a870" />
</p>
<h5 align="center">Export Options</h5>

<p align="center">
  <img width="1508" height="707" alt="Mobile View" src="https://github.com/user-attachments/assets/95440206-0d62-4b6c-bff8-e02311304aef" />
</p>
<h5 align="center">Responsive Mobile View</h5>

<p align="center">
  <img width="1502" height="259" alt="Branding" src="https://github.com/user-attachments/assets/d63d161b-7334-485b-a79c-bbed8a3ca248" />
</p>
<h5 align="center">Brand-Aligned Footer</h5>

---

## Impact & Results

| Metric | Result |
|--------|--------|
| Course approval efficiency | **Improved by ~40%** |
| Duplicate submissions | **Significantly reduced** |
| User adoption | **Widely adopted by outbound study abroad students** |
| Recognition | **Recommendation letter** from supervisor for innovation and impact |

---

## License

This project was created for the **University of the Pacific — Office of Global Education**.
Unless otherwise noted, source code in this repository is released under the **MIT License**.
Logos, branding, and course data remain the property of the **University of the Pacific**.
