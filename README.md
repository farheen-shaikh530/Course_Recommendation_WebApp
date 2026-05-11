<p align="center">
  <img width="1000" alt="Course Mapping System Banner" src="https://github.com/user-attachments/assets/72d684c0-b252-446d-9aec-1d29d21540ed" />
</p>

<h1 align="center">Course Mapping System — User Guide</h1>

<p align="center">
  <b>University of the Pacific — Office of Global Education</b><br>
  <b>Live Demo:</b> <a href="https://uop-course-approval-request-form-view.netlify.app">Course Approval Request Form Viewer</a><br>
  <b>Portal:</b> <a href="https://pacific-global.via-trm.com/authV2/welcome">Pacific Global Study Abroad Portal</a>
</p>

---

## Table of Contents

- [1. What is the Course Mapping System?](#1-what-is-the-course-mapping-system)
- [2. Who Can Use This System?](#2-who-can-use-this-system)
- [3. How Does the System Work End-to-End?](#3-how-does-the-system-work-end-to-end)
- [4. Step-by-Step Guide](#4-step-by-step-guide)
  - [4.1 Sign In to the Portal](#41-sign-in-to-the-portal)
  - [4.2 Explore Study Abroad Programs](#42-explore-study-abroad-programs)
  - [4.3 Search for Course Equivalencies](#43-search-for-course-equivalencies)
  - [4.4 View Course Mapping Results](#44-view-course-mapping-results)
  - [4.5 Review Course Details](#45-review-course-details)
  - [4.6 Export Results](#46-export-results)
  - [4.7 Submit the Course Approval Request (CAR) Form](#47-submit-the-course-approval-request-car-form)
- [5. For Admins: Managing Course Data](#5-for-admins-managing-course-data)
- [6. Frequently Asked Questions (FAQ)](#6-frequently-asked-questions-faq)
- [7. Troubleshooting](#7-troubleshooting)
- [8. Tech Stack & Architecture](#8-tech-stack--architecture)
- [9. Impact & Results](#9-impact--results)
- [10. License](#10-license)

---

## 1. What is the Course Mapping System?

The **Course Mapping System** streamlines the process of **searching, mapping, and approving international courses** for students preparing to study abroad. It enables students and staff to:

- View previously approved course equivalencies across global partner institutions
- Search and filter courses by major, country, university, and course code
- Export matched courses for advising meetings
- Submit a **Course Approval Request (CAR) Form** to an advisor for final approval

> **Before this system:** Students and staff had limited visibility into approved courses, submitted redundant approvals, and navigated a confusing interface that made evaluating international credits difficult.

---

## 2. Who Can Use This System?

| User | What You Can Do |
|------|----------------|
| **Students** | Search approved courses, view equivalencies, export results, submit CAR form to advisor |
| **Academic Advisors** | Review mapped courses, verify approvals, approve/deny CAR submissions |
| **Study Abroad Advisors** | Manage course data, upload new equivalencies, maintain data sources |

---

## 3. How Does the System Work End-to-End?

Here is the complete journey from login to course approval:

```
Sign In → Explore Programs → Search Courses → View Equivalencies → Export Results → Submit CAR Form → Advisor Approval
```

| Step | Action | Outcome |
|------|--------|---------|
| 4.1 | Sign in to Pacific Global Portal | Access the dashboard |
| 4.2 | Explore study abroad programs | Browse programs by country, term, and type |
| 4.3 | Search for course equivalencies | Find pre-approved international courses matching your major |
| 4.4 | View course mapping results | See matched universities with expandable course details |
| 4.5 | Review course details | Verify Pacific Major, Class Code, Credits, and Approval Period |
| 4.6 | Export results | Download matched courses as CSV/Excel for your records |
| 4.7 | Submit CAR form | Fill in selected courses and send to advisor for approval |

---

## 4. Step-by-Step Guide

---

### 4.1 Sign In to the Portal

<p align="center">
  <img width="800" alt="Welcome Login Page" src="https://github.com/user-attachments/assets/d0236cee-f5ae-44fe-bffa-7d46e43f4e98" />
</p>
<h5 align="center">Fig 4.1 — Welcome Screen: Sign in through University of the Pacific Portal</h5>

1. Navigate to the **Pacific Global Study Abroad Portal**: [pacific-global.via-trm.com](https://pacific-global.via-trm.com/authV2/welcome)
2. You will see the **Welcome** screen with the University of the Pacific logo
3. **If you have a UOP login:** Click **"Go to Portal >"** to sign in with your university credentials
4. **If you do not have a UOP login:** Click **"Sign Up"** to create a new account, or **"Sign In"** if you already registered

> **Note:** You must have an active University of the Pacific account to access the full system.

---

### 4.2 Explore Study Abroad Programs

Once logged in, you will see the **Program Search** dashboard with university names, subject areas, program types, and location tags.

<p align="center">
  <img width="800" alt="Program Search Dashboard" src="https://github.com/user-attachments/assets/35fd8828-3cec-4572-b655-c6a64dc7a64d" />
</p>
<h5 align="center">Fig 4.2a — Program Search Dashboard</h5>

#### 4.2.1 Navigation Sidebar

On the left panel, you have access to review your applications, selected programs, and registered events:

| Menu Item | Use Case |
|-----------|----------|
| **Explore Programs** | Browse all available study abroad programs |
| **Register Travel** | Register your travel plans |
| **Dashboard** | View your personal dashboard |
| **Messages** | Check messages from advisors |
| **My Programs** | View programs you've saved or applied to |
| **My Travel** | Manage your travel details |
| **My Events** | View upcoming events |
| **My Profile** | Update your personal information |

#### 4.2.2 Searching Programs

1. Use the **Search Programs** bar at the top to type a program name, country, or university
2. Use the **Sort by** dropdown (e.g., "Internal A-Z to Affiliate A-Z") to reorder results
3. Apply filters to narrow results:

| Filter | Description |
|--------|-------------|
| **Term Name** | Filter by Fall, Spring, Winter, Summer |
| **Dates** | Filter by specific date ranges |
| **Subject Areas** | Filter by academic discipline |
| **Locations** | Filter by country or city |
| **Program Type** | Filter by Study Abroad, Exchange, Faculty-Led, Internship |
| **Favorites Only** | Show only programs you've favorited (♡) |
| **More Filters** | Access additional filter options |
| **Clear All** | Reset all filters |

4. Browse program cards showing:
   - Program name and destination
   - Location (city, country)
   - Program type (Study Abroad, Exchange, Faculty-Led, Group Travel)
   - Term and dates
   - Subject areas covered
   - Click ♡ to save as a favorite

<p align="center">
  <img width="800" alt="Search Results with Filters" src="https://github.com/user-attachments/assets/7bb0766a-dd93-474f-ad29-99c565a2dbce" />
</p>
<h5 align="center">Fig 4.2b — Search Results: Exchange programs across Germany, Japan, France, and more</h5>

---

### 4.3 Search for Course Equivalencies

1. Navigate to the **Study Abroad Course Search** page
2. You will see a description:

> *"This tool is designed to help you identify pre-approved course equivalents from our foreign partner institutions. If you find matching courses, please list them on your Course Approval Request (CAR) form."*

3. If you cannot find courses in your discipline, you may still submit a CAR form
4. For questions, contact: **studyabroad@pacific.edu**

#### 4.3.1 Search Panel Home Screen

<p align="center">
  <img width="800" alt="Course Search Panel" src="https://github.com/user-attachments/assets/46a5f96b-2f5a-4ef6-b390-2e9c392fda5d" />
</p>
<p align="center">
  <img width="800" alt="Search Results Accordion" src="https://github.com/user-attachments/assets/9e6e995b-15aa-42f5-ab46-1990bdf7a870" />
</p>

<h5 align="center">Fig 4.3a — Course Search Panel: Pacific Courses (Left) vs International Equivalents (Right)</h5>

The search panel is divided into two sections:

| Pacific Courses (Left) | International Course Equivalents (Right) |
|------------------------|------------------------------------------|
| **Majors** — Select your UOP major | **Country** — Select the destination country |
| **Course Code** — Enter a specific code (e.g., HIST 120) | **University / Institution** — Select the partner university |

#### 4.3.2 How to Search

1. Fill in one or more fields on either side (or both)
2. Click the **Search** button (orange) to find matches
3. Click the **Clear** button (gray) to reset all fields and start over

> **Tip:** You don't need to fill in every field. Searching by just **Majors** or just **Country** will return all matching results.

<img width="3014" height="1504" alt="image" src="https://github.com/user-attachments/assets/9a8f3f84-32df-496a-8ca4-27f0bc82db94" />

<h5 align="center">Fig 4.3b — Search Results with Export Options</h5>

---

### 4.4 View Course Mapping Results

<p align="center">
  <img width="800" alt="Course Mapping Results" src="https://github.com/user-attachments/assets/0e9fae98-b274-4876-ac99-98b017b96e25" />
</p>
<h5 align="center">Fig 4.4 — Expandable University Cards with Course Mapping Results</h5>

After clicking **Search**, results appear as expandable university cards:

- Each card shows the **University Name**, **Country**, and **Program Type**
  - Example: "Universidad de Sevilla (Spain — ISEP)"
  - Example: "Hanyang University (South Korea — Pacific Exchange program)"
  - Example: "Shanghai University (China — USAC)"
- Cards are color-coded in **orange** for easy visibility
- Click on any card to **expand** and view the course mapping details

---

### 4.5 Review Course Details

Click on a university card to expand it. You will see a **detailed course mapping table**:

<p align="center">
  <img width="800" alt="Course Details Expanded" src="https://github.com/user-attachments/assets/d63d161b-7334-485b-a79c-bbed8a3ca248" />
</p>
<h5 align="center">Fig 4.5 — Expanded Course Details: Yonsei University (South Korea)</h5>

#### 4.5.1 Column Descriptions

| Column | Description |
|--------|-------------|
| **Pacific Major** | Your UOP major (e.g., History) |
| **Pacific Class Code** | UOP course code (e.g., HIST TLD) |
| **Pacific Class Title** | UOP course title (shown in red if "No name" — data pending) |
| **Pacific Credit** | Number of UOP credits (e.g., 4) |
| **Class Code** | International course code (shown as "No Info" if unavailable) |
| **Class Title** | International course title (e.g., Modern Korean History) |
| **Approval Period** | When this equivalency was approved (e.g., Spring 2023) |

#### 4.5.2 What to Do with This Information

1. **Review** the course equivalencies for your major
2. **Note down** the courses that match your degree requirements
3. **Export** the results (see Step 4.6) for your advising appointment
4. **List these courses** on your **Course Approval Request (CAR) Form** (see Step 4.7)

> **Note:** If a field shows **"No name"** (in red) or **"No Info"**, this means the data is pending or unavailable. Contact the Office of Global Education for clarification.

---

### 4.6 Export Results (Work In Progress)
- Each selected courses and its equivalent will come to the CAR form with no loggedin user name and its pacific id and degree name, with blank advisor sign firled. Students can take the signtature from advisor and attached with he VIA TRM application in additional documentation field. 
- 
<p align="center">
  <img width="800" alt="Export Options" src="https://github.com/user-attachments/assets/95440206-0d62-4b6c-bff8-e02311304aef" />
</p>
<h5 align="center">Fig 4.6 — Export Options: Download Results as CSV or Excel</h5>

Export your search results for advising meetings or personal records:

1. After performing a search, locate the **Export** section
2. Click **Search** to load results, then use the export option
3. Choose format: **CSV** or **Excel (.xlsx)**
4. File downloads automatically to your device

> **For Advisors:** Export results before advising appointments to have a printed reference of pre-approved courses for the student.

---

### 4.7 Submit the Course Approval Request (CAR) Form

The **CAR Form** is the final step in the course approval process. After identifying matching courses through the Course Mapping System, students must submit this form to their advisor for review and approval.

#### 4.7.1 How to Submit

1. Click the **[Course Approval Request (CAR) form](https://uop-course-approval-request-form-view.netlify.app)** link on the Study Abroad Course Search page
2. Fill in the following details:
   - Your name and student ID
   - Study abroad program and destination university
   - International course(s) you want to take (from the mapping results)
   - UOP equivalent course(s) (from the mapping table)
   - Number of credits
3. Review all information for accuracy
4. Submit the form — it is sent directly to your academic advisor

#### 4.7.2 What Happens Next

| Stage | Description |
|-------|-------------|
| **Submitted** | Your CAR form is sent to your advisor |
| **Under Review** | Advisor reviews the course equivalency and your degree requirements |
| **Approved** | Course is approved — you can register for the international course |
| **Denied** | Advisor provides feedback — you may submit an alternative course |

> **Important:** Submit your CAR form **before** your advising appointment so your advisor has time to review it. Do not wait until the last minute.

---

## 5. For Admins: Managing Course Data

### 5.1 Updating the Google Sheet Data Source

The system pulls live data from **Google Sheets**. To update:

1. **Access** the linked Google Sheet (shared with the admin team)
2. Each tab represents a different data category (courses, universities, departments)
3. **Add** new rows for new course equivalencies
4. **Edit** existing rows to update information
5. **Do not** change column headers — this will break the API connection
6. Allow up to **5 minutes** for the Google Sheets API to sync changes

> **Warning:** Do not rename, reorder, or delete columns. Contact the developer if structural changes are needed.

### 5.2 Admin Search Panel

Admins can use the same search panel to verify data:

1. Log in with **admin credentials**
2. Use the **Pacific Courses** fields (Majors, Course Code) and **International Course Equivalents** fields (Country, University/Institution) to search
3. Verify that newly added courses appear correctly
4. Check for entries with **"No name"** or **"No Info"** and update the Google Sheet accordingly

---

## 6. Frequently Asked Questions (FAQ)

| # | Question | Answer |
|---|----------|--------|
| 1 | Do I need to log in to use the system? | Yes, the full system requires login through the Pacific Global portal. However, the [CAR Form Viewer](https://uop-course-approval-request-form-view.netlify.app) is accessible without login. |
| 2 | Can I search for courses from any country? | Yes, the system includes approved courses from all partner institutions worldwide. Use the **Country** filter to narrow results. |
| 3 | What if my course isn't listed? | It hasn't been pre-approved yet. You may still submit a CAR form for advisor review. Contact **studyabroad@pacific.edu** for guidance. |
| 4 | What does "No name" or "No Info" mean? | The data is pending or unavailable. Contact the Office of Global Education to request an update. |
| 5 | Can I save my search results? | Yes, use the **Export** option to download results as CSV or Excel. |
| 6 | How long does CAR form approval take? | It depends on your advisor's availability. Submit at least **one week** before your advising appointment. |
| 7 | Can I submit multiple CAR forms? | Yes, you can submit separate CAR forms for different courses or programs. |
| 8 | Who do I contact for technical issues? | Email **studyabroad@pacific.edu** or submit a support request through the portal. |

---

## 7. Troubleshooting

| # | Issue | Solution |
|---|-------|----------|
| 1 | Cannot sign in | Verify your UOP credentials. Try "Sign Up" if first-time user. Reset password if locked out. |
| 2 | Page not loading | Clear browser cache and refresh. Try Chrome (recommended). |
| 3 | Search returns no results | Check spelling. Try broader criteria (e.g., just Country or just Major). Click **Clear** and search again. |
| 4 | "No name" / "No Info" in results | Data is pending. Contact the Office of Global Education for updates. |
| 5 | Export not downloading | Ensure pop-ups are enabled. Try right-click → "Save As." |
| 6 | CAR form not submitting | Check all required fields are filled. Try a different browser. |
| 7 | Data looks outdated | Allow up to 5 minutes for Google Sheets sync. Contact admin if issue persists. |
| 8 | Mobile layout issues | Use landscape mode for best experience. Desktop recommended for searches. |

---

## 8. Tech Stack & Architecture

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

## 9. Impact & Results

| # | Metric | Result |
|---|--------|--------|
| 1 | Course approval efficiency | **Improved by ~40%** |
| 2 | Duplicate submissions | **Significantly reduced** |
| 3 | Support queries | **Reduced by 70%** through self-serve documentation |
| 4 | User adoption | **Widely adopted by outbound study abroad students** |
| 5 | Recognition | **Recommendation letter** from supervisor for innovation and impact |

---

## 10. License

This project was created for the **University of the Pacific — Office of Global Education**.
Unless otherwise noted, source code in this repository is released under the **MIT License**.
Logos, branding, and course data remain the property of the **University of the Pacific**.
