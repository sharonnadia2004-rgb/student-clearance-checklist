# Group 4 — Student Clearance Checklist

A responsive web application designed to help university students and administrative staff track graduation clearance requirements across key university offices.

- **GitHub Repository:** https://github.com/sharonnadia2004-rgb/student-clearance-checklist
- **Live Application:** https://sharonnadia2004-rgb.github.io/student-clearance-checklist/

---

## 1. Problem Statement
Final-year university students often face confusion, delays, and repeated office visits when completing their graduation clearance across multiple departments. Without a centralized checklist, students struggle to track which requirements are cleared, which tasks remain pending, and how close they are to full clearance.

## 2. Intended Users
- **Final-Year Students:** Track overall clearance progress, filter pending tasks, and mark requirements as complete.
- **Registry Staff:** Manage academic and final results clearance records.
- **Library Staff:** Verify the return of borrowed books and library materials.
- **Finance Staff:** Track tuition fee clearance and financial obligations.

---

## 3. Key Features
- **Departmental Clearance Display:** Displays sample and custom clearance requirements organized by university office (**Registry**, **Library**, and **Finance**).
- **Interactive Status Toggling:** Users can mark any requirement as **Complete** or **Pending** with instant visual feedback (color-coded left borders and status badges).
- **Dual Filtering:** Filter checklist items dynamically by **Office** (`All offices`, `Registry`, `Library`, `Finance`) and **Status** (`All`, `Pending`, `Complete`).
- **Real-Time Progress Tracking:** Automatically calculates the completion percentage, updates the visual `<progress>` bar, and lists all remaining pending items.
- **Form Validation & Duplicate Prevention:** Allows users to add new clearance requirements while blocking empty office selections, descriptions under 3 characters, and duplicate requirements within the same office.
- **Responsive & Accessible Design:** Built with semantic HTML5 landmarks, keyboard focus indicators, and responsive CSS Grid/Flexbox layouts for desktop, tablet, and mobile screens.

---

## 4. Current Limitations
- **Client-Side Storage Only:** Requirements are stored in an in-memory JavaScript array (`requirements`), meaning newly added items or status changes reset when the browser page is refreshed.
- **No User Authentication:** There are no separate login roles or permissions distinguishing students from university staff.
- **Static Office List:** Offices are currently limited to **Registry**, **Library**, and **Finance**.
- **No Document Uploads:** Users cannot attach receipts or clearance forms directly to a checklist item.

---

## 5. Team Members & Individual Responsibilities

| Team Member | Primary Role | Assigned Files / Artifacts | Key Responsibilities |
| :--- | :--- | :--- | :--- |
| **Sserushaago Mwizerwa Umar** | JavaScript & Application Logic Lead | `script.js` | Implemented DOM manipulation, dual filtering, real-time percentage calculation, status toggling, and form validation. |
| **Aniku Sunday** | HTML Structure & Content Lead | `index.html` | Built semantic HTML5 landmarks (`header`, `main`, `section`, `footer`), accessible form labels, and the native `<progress>` bar. |
| **Ejidra Herbert** | UI/UX Design & Responsive CSS Lead | `Style.css` | Designed the color system (`:root`), CSS Grid/Flexbox card layouts, status badges, and responsive breakpoints (`800px` and `520px`). |
| **Sharon Nadia** | Quality Assurance & Cross-Device Testing Lead (Repo Anchor) | `screen-shots/` & QA Checks | Managed the main GitHub repository, verified form validation edge cases, tested keyboard focus accessibility, and captured responsive screenshots. |
| **Amaguru Bibian** | Project Planning, Documentation & Deployment Lead | `README.md` & Workflow | Defined the problem statement and user workflow, authored project documentation, and coordinated GitHub Pages deployment and the 5-minute demo. |

---

## 6. Individual Contribution Statements

- **Sserushaago Mwizerwa Umar:** "I developed `script.js` to power the application's interactivity, including real-time completion percentage calculations, dual filtering by office and status, dynamic checklist rendering, and input validation against empty or duplicate entries."
- **Aniku Sunday:** "I structured `index.html` using semantic HTML5 elements, accessible `<label>` associations, filter dropdowns, the native `<progress>` element, and the requirement submission form."
- **Ejidra Herbert:** "I created `Style.css` using CSS custom properties, CSS Grid, and Flexbox to style the progress dashboard, status badges, focus outlines, and responsive layouts across desktop, tablet, and mobile viewports."
- **Sharon Nadia:** "I hosted and maintained the group repository, conducted end-to-end QA testing on validation rules and 100% completion states, and captured testing evidence across desktop, tablet, and phone screen sizes."
- **Amaguru Bibian:** "I mapped the user workflow, compiled the project documentation and limitations in `README.md`, and coordinated repository organization, live deployment, and the group presentation."

---

## 7. Testing Evidence (Responsive Layouts)
The application was tested across desktop (`>800px`), tablet (`≤800px`), and mobile (`≤520px`) screen sizes. Visual evidence is stored in the `screen-shots/` folder:

- **Desktop View:** `screen-shots/desktop.png.png`
- **Tablet View:** `screen-shots/tablet.png.png`
- **Mobile View:** `screen-shots/phone.png.png`

---

## 8. How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/sharonnadia2004-rgb/student-clearance-checklist.git
   ```
2. Navigate into the project folder:
   ```bash
   cd student-clearance-checklist
   ```
3. Open `index.html` in any modern web browser.
