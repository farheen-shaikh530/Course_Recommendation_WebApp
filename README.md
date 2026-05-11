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

1. [What is the Course Mapping System?](#what-is-the-course-mapping-system)
2. [Who Can Use This System?](#who-can-use-this-system)
3. [How System work End-to-End?](#end-to-end-workflow)
4. [Step 1: Sign In to the Portal](#step-1-sign-in-to-the-portal)
5. [Step 2: Explore Study Abroad Programs](#step-2-explore-study-abroad-programs)
6. [Step 3: Search for Course Equivalencies](#step-3-search-for-course-equivalencies)
7. [Step 4: View Course Mapping Results](#step-4-view-course-mapping-results)
8. [Step 5: Review Course Details](#step-5-review-course-details)
9. [Step 6: Export Results](#step-6-export-results)
10. [Step 7: Add Details and Submit the Course Approval Request (CAR) Form](#step-7-submit-the-course-approval-request-car-form)
11. [For Admins: Managing Course Data](#for-admins-managing-course-data)
12. [Frequently Asked Questions (FAQ)](#frequently-asked-questions-faq)
13. [Troubleshooting](#troubleshooting)
14. [Tech Stack & Architecture](#tech-stack--architecture)
15. [Impact & Results](#impact--results)
16. [License](#license)

---

## What is the Course Mapping System?

The **Course Mapping System** streamlines the process of **searching, mapping, and approving international courses** for students preparing to study abroad. It enables students and staff to:

- View previously approved course equivalencies across global partner institutions
- Search and filter courses by major, country, university, and course code
- Export matched courses for advising meetings
- Submit a **Course Approval Request (CAR) Form** to an advisor for final approval

> **Before this system:** Students and staff had limited visibility into approved courses, submitted redundant approvals, and navigated a confusing interface that made evaluating international credits difficult.

---

## Who Can Use This System?

| User | What You Can Do |
|------|----------------|
| **Students** | Search approved courses, view equivalencies, export results, submit CAR form to advisor |
| **Academic Advisors** | Review mapped courses, verify approvals, approve/deny CAR submissions |
| **Study Abroad Advisorss** | Manage course data, upload new equivalencies, maintain data sources |

---

## End-to-End Workflow

Here is the complete journey from login to course approval:

```
Sign In → Explore Programs → Search Courses → View Equivalencies → Export Results → Submit CAR Form → Advisor Approval
```

| Step | Action | Outcome |
|------|--------|---------|
| 1 | Sign in to Pacific Global Portal | Access the dashboard |
| 2 | Explore study abroad programs | Browse programs by country, term, and type |
| 3 | Search for course equivalencies | Find pre-approved international courses matching your major |
| 4 | View course mapping results | See matched universities with expandable course details |
| 5 | Review course details | Verify Pacific Major, Class Code, Credits, and Approval Period |
| 6 | Export results | Download matched courses as CSV/Excel for your records |
| 7 | Submit CAR form | Fill in selected courses and send to advisor for approval |

---

## Step 1: Sign In to the Portal

1. Navigate to the **Pacific Global Study Abroad Portal**: [pacific-global.via-trm.com](https://pacific-global.via-trm.com/authV2/welcome)
2. You will see the **Welcome** screen with the University of the Pacific logo
3. **If you have a UOP login:** Click **"Go to Portal >"** to sign in with your university credentials
4. **If you do not have a UOP login:** Click **"Sign Up"** to create a new account, or **"Sign In"** if you already registered

<p align="center">
  <img width="1000" alt="Program Search Dashboard" src="https://github.com/user-attachments/assets/d0236cee-f5ae-44fe-bffa-7d46e43f4e98" />
</p> 

> **Note:** You must have an active University of the Pacific account to access the full system.

---

## Step 2: Explore Study Abroad Programs

Once logged in, you will see the **Program Search** dashboard with university names, subject area, program type, and location name tags. 
<p align="center">
  <img width="1000" alt="Study Abroad Course Search" src="https://github.com/user-attachments/assets/35fd8828-3cec-4572-b655-c6a64dc7a64d" />
</p>

<h5 align="center">Search results showing exchange programs across Germany, Japan, France, and more</h5>


### What is the use of Navigation Sidebar?

On the left panel, you have access to review your applications, programs selected, event registered

| Menu Item | Use CAse    |
|-----------|-------------|
| **Explore Programs** | Browse all available study abroad programs |
| **Register Travel** | Register your travel plans |
| **Dashboard** | View your personal dashboard |
| **Messages** | Check messages from advisors |
| **My Programs** | View programs you've saved or applied to |
| **My Travel** | Manage your travel details |
| **My Events** | View upcoming events |
| **My Profile** | Update your personal information |

### Searching Programs

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
  <img width="1000" alt="Search Results with Filters" src="https://github.com/user-attachments/assets/7bb0766a-dd93-474f-ad29-99c565a2dbce" />
</p>



---

## Step 3: Search for Course Equivalencies

1. Navigate to the **Study Abroad Course Search** page
2. You will see a description:

> *"This tool is designed to help you identify pre-approved course equivalents from our foreign partner institutions. If you find matching courses, please list them on your Course Approval Request (CAR) form."*

3. If you cannot find courses in your discipline, you may still submit a CAR form. For questions, contact: **studyabroad@pacific.edu**

### Search by Course Mapping

<p align="center">
  <img width="1000" alt="Search Results Accordion" src="https://github.com/user-attachments/assets/9e6e995b-15aa-42f5-ab46-1990bdf7a870" />
</p>

<p align="center">
  <img width="1000" alt="Course Search Panel" src="https://github.com/user-attachments/assets/46a5f96b-2f5a-4ef6-b390-2e9c392fda5d" />
</p>


The search panel is divided into two sections:

| Pacific Courses (Left) | International Course Equivalents (Right) |
|------------------------|------------------------------------------|
| **Majors** — Select your UOP major | **Country** — Select the destination country |
| **Course Code** — Enter a specific code (e.g., HIST 120) | **University / Institution** — Select the partner university |

### How to Search Your Course:

1. Fill in one or more fields on either side (or both)
2. Click the **Search** button (orange) to find matches
3. Click the **Clear** button (gray) to reset all fields and start over

> **Tip:** You don't need to fill in every field. Searching by just **Majors** or just **Country** will return all matching results.

---

## Step 4: View Course Mapping Results


<img width="3020" height="1572" alt="image" src="https://github.com/user-attachments/assets/0e9fae98-b274-4876-ac99-98b017b96e25" />

After clicking **Search**, results appear as expandable university cards:

- Each card shows the **University Name**, **Country**, and **Program Type** (e.g., "Universidad de Sevilla (Spain — ISEP)")
- Cards are color-coded in **orange** for easy visibility
- Click on any card to **expand** and view the course mapping details

---

## Step 5: Review Course Details


Click on a university card to expand it. You will see a **detailed course mapping table** with the following columns:

| Column | Description |
|--------|-------------|
| **Pacific Major** | Your UOP major (e.g., History) |
| **Pacific Class Code** | UOP course code (e.g., HIST TLD) |
| **Pacific Class Title** | UOP course title (shown in red if "No name" — meaning data is pending) |
| **Pacific Credit** | Number of UOP credits (e.g., 4) |
| **Class Code** | International course code (shown as "No Info" if unavailable) |
| **Class Title** | International course title (e.g., Modern Korean History) |
| **Approval Period** | When this equivalency was approved (e.g., Spring 2023) |

### What to Do with This Information:

1. **Review** the course equivalencies for your major
2. **Note down** the courses that match your degree requirements
3. **Export** the results (see Step 6) for your advising appointment
4. **List these courses** on your **Course Approval Request (CAR) Form** (see Step 7)

> **Note:** If a field shows **"No name"** (in red) or **"No Info"**, this means the data is pending or unavailable. Contact the Office of Global Education for clarification.

---

## Step 6: Export Results

<p align="center">
  <img width="1000" alt="Export Options" src="https://github.com/user-attachments/assets/95440206-0d62-4b6c-bff8-e02311304aef" />
</p>

Export your search results for advising meetings or personal records:

1. After performing a search, locate the **Export** section
2. Click **Search** to load results, then use the export option
3. Choose format: **CSV** or **Excel (.xlsx)**
4. File downloads automatically to your device

> **For Advisors:** Export results before advising appointments to have a printed reference of pre-approved courses for the student.

---

## Step 7: Submit the Course Approval Request (CAR) Form

The **CAR Form** is the final step in the course approval process. After identifying matching courses through the Course Mapping System, students must submit this form to their advisor for review and approval.

### How to Submit:

1. Click the **[Course Approval Request (CAR) form](https://uop-course-approval-request-form-view.netlify.app)** link on the Study Abroad Course Search page
2. Fill in the following details:
   - **Your name** and **student ID**
   - **Study abroad program** and **destination university**
   - **International course(s)** you want to take (from the mapping results)
   - **UOP equivalent course(s)** (from the mapping table)
   - **Number of credits**
3. **Review** all information for accuracy
4. **Submit** the form — it is sent directly to your academic advisor

### What Happens Next:

| Stage | Description |
|-------|-------------|
| **Submitted** | Your CAR form is sent to your advisor |
| **Under Review** | Advisor reviews the course equivalency and your degree requirements |
| **Approved** | Course is approved — you can register for the international course |
| **Denied** | Advisor provides feedback — you may submit an alternative course |

> **Important:** Submit your CAR form **before** your advising appointment so your advisor has time to review it. Do not wait until the last minute.

---

## For Admins: Managing Course Data

### Updating the Google Sheet Data Source

The system pulls live data from **Google Sheets**. To update:

1. **Access** the linked Google Sheet (shared with the admin team)
2. Each tab represents a different data category (courses, universities, departments)
3. **Add** new rows for new course equivalencies
4. **Edit** existing rows to update information
5. **Do not** change column headers — this will break the API connection
6. Allow up to **5 minutes** for the Google Sheets API to sync changes

> **Warning:** Do not rename, reorder, or delete columns. Contact the developer if structural changes are needed.

### Admin Search Panel

Admins can use the same search panel to verify data:

1. Log in with **admin credentials**
2. Use the **Pacific Courses** fields (Majors, Course Code) and **International Course Equivalents** fields (Country, University/Institution) to search
3. Verify that newly added courses appear correctly
4. Check for entries with **"No name"** or **"No Info"** and update the Google Sheet accordingly

---

## Frequently Asked Questions (FAQ)

### Q: Do I need to log in to use the system?
**A:** Yes, the full Course Mapping System requires login through the Pacific Global portal. However, the [Course Approval Request Form Viewer](https://uop-course-approval-request-form-view.netlify.app) is accessible without login.

### Q: Can I search for courses from any country?
**A:** Yes, the system includes approved courses from all partner institutions worldwide. Use the **Country** filter to narrow results.

### Q: What if my course isn't listed?
**A:** If a course is not found, it hasn't been pre-approved yet. You may still submit a CAR form for advisor review. Contact **studyabroad@pacific.edu** for guidance.

### Q: What does "No name" or "No Info" mean in the results?
**A:** This means the data is pending or unavailable in the system. Contact the Office of Global Education to request an update.

### Q: Can I save my search results?
**A:** Yes, use the **Export** option to download results as CSV or Excel.

### Q: How long does CAR form approval take?
**A:** Processing time depends on your advisor's availability. Submit your form at least **one week** before your advising appointment for timely review.

### Q: Can I submit multiple CAR forms?
**A:** Yes, you can submit separate CAR forms for different courses or programs.

### Q: Who do I contact for technical issues?
**A:** Email **studyabroad@pacific.edu** or submit a support request through the portal.

---

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Cannot sign in | Verify your UOP credentials. Try "Sign Up" if you're a first-time user. Reset password if locked out. |
| Page not loading | Clear browser cache and refresh. Try Chrome (recommended). |
| Search returns no results | Check spelling. Try broader criteria (e.g., just Country or just Major). Click **Clear** and search again. |
| "No name" / "No Info" in results | Data is pending. Contact the Office of Global Education for updates. |
| Export not downloading | Ensure pop-ups are enabled. Try right-click → "Save As." |
| CAR form not submitting | Check all required fields are filled. Try a different browser. |
| Data looks outdated | Allow up to 5 minutes for Google Sheets sync. Contact admin if issue persists. |
| Mobile layout issues | Use landscape mode for best experience. Desktop recommended for searches. |

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

## Impact & Results

| Metric | Result |
|--------|--------|
| Course approval efficiency | **Improved by ~40%** |
| Duplicate submissions | **Significantly reduced** |
| Support queries | **Reduced by 70%** through self-serve documentation |
| User adoption | **Widely adopted by outbound study abroad students** |
| Recognition | **Recommendation letter** from supervisor for innovation and impact |

---

## License

This project was created for the **University of the Pacific — Office of Global Education**.
Unless otherwise noted, source code in this repository is released under the **MIT License**.
Logos, branding, and course data remain the property of the **University of the Pacific**.
