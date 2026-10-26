# 🎓 India Education & Career Pathways Map

An interactive, web-based career decision roadmap and downward flow tree designed for Indian students and career counselors. This tool visualizes the complete academic and career journey in India—from Class 10th board exams all the way through 10+2 streams, Bachelor's degrees, Master's specializations, Ph.D. Doctorates, and top C-suite or administrative leadership positions.

url: https://naveenkumararemanda.github.io/Education-Career-Navigator/
---

## 🌟 Key Features

* **Complete Downward Hierarchy**:
  * **Tier 1:** Class 10th (Secondary Schooling)
  * **Tier 2:** 10+2 Streams (PCM, PCB, Commerce, Arts, Defence, Teaching, Law, Design, Vocational)
  * **Tier 3:** Undergraduate / Bachelor’s Degrees & Professional Programs
  * **Tier 4:** Postgraduate / Master’s & Specializations
  * **Tier 5:** Ph.D. Doctorates, DM/M.Ch, Super-Specialties & Fellowships
  * **Tier 6:** Senior Industry Leadership, IAS Officers, Flag Officers, Chief Scientists & Professors

* **Comprehensive Stream Coverage**:
  * **Science (PCM):** Computer Science & AI, Core Engineering (Mech/Civil), Pure Sciences, Aviation (CPL), Merchant Navy.
  * **Science (PCB):** MBBS, BDS Dental, Pharmacy (Pharm.D/M.Pharm R&D), Biotechnology & Life Sciences.
  * **Defence Forces:** NDA (Army, Navy, Air Force) after 12th, Technical Entry Schemes, CDS/AFCAT/JAG entry after graduation, leading up to Flag Officers and CDS.
  * **Education & Academia:** School Teaching (B.Ed/CTET/PGT) & Higher Education Professorship (Master's $\rightarrow$ UGC-NET/CSIR-NET JRF $\rightarrow$ Ph.D. $\rightarrow$ Assistant Professor $\rightarrow$ Vice-Chancellor).
  * **Commerce & Finance:** Chartered Accountancy (CA - ICAI), CS, CMA, B.Com/BBA, IIM IPM Integrated, CAT/MBA, C-Suite Management.
  * **Arts, Humanities & Public Service:** Civil Services (IAS, IPS, IFS, IRS via UPSC CSE), Mass Communication & Media, Clinical Psychology (RCI Licensed), Chief Secretaries.
  * **Law & Judicial Services:** 5-Year Integrated B.A. LL.B (CLAT), State Judicial Services (PCS-J Judgeship), High Court / Supreme Court Advocacy, Senior Counsel.
  * **Design & Architecture:** B.Arch (NATA/COA License), B.Des UI/UX & Industrial Design (UCEED/NID), Chief Design Officers.
  * **Vocational & Technical:** Polytechnic Diplomas, Lateral Entry B.Tech, Industrial Automation Specialists.

* **Interactive D3.js Downward Tree Visualization**:
  * **Collapsible & Expandable Nodes**: Click on any node to expand or collapse sub-branches.
  * **Stream Color Coding**: Distinct visual color themes for quick identification of paths.
  * **Interactive Search & Path Tracing**: Real-time search engine with auto-expansion and glowing Bezier path tracing from 10th grade down to target doctorate or career roles.
  * **Slide-over Detailed Drawer Panel**: Displays duration, salary/stipend estimates (in LPA), premier Indian institutes (IITs, AIIMS, IIMs, NLUs, IISc, TIFR), national entrance exams (JEE, NEET, CLAT, CAT, GATE, UPSC), and core skills.
  * **Canvas Controls**: Smooth pan/zoom canvas, Zoom In/Out, Expand All, Collapse All, Reset View, and category quick-filter tabs.

---

## 🚀 How to Run locally

This project is a **single-file web application** (`index.html`) built with vanilla HTML, Tailwind CSS, and D3.js (v7). No complex build steps or Node.js environment required!

1. **Download/Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/indian-career-pathways-map.git
   cd indian-career-pathways-map
   ```

2. **Open the Application**:
   * Double-click on `index.html` to open it directly in any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
   * **OR** serve it using VS Code's *Live Server* extension or python:
     ```bash
     python -m http.server 8000
     ```
     Then navigate to `http://localhost:8000` in your browser.

---

## 🛠️ Built With

* **HTML5 & CSS3**
* **Tailwind CSS**: Utility-first CSS framework for modern, responsive dark-mode styling.
* **D3.js (v7)**: Data-driven visualization engine used for rendering the expandable downward tree hierarchy and dynamic path connections.
* **Font Awesome (v6)**: Vector icons for streams, badges, and interface buttons.

---

## 📌 Usage Guide

1. **Navigating the Tree**:
   * **Click any node** to expand or collapse its child branches.
   * **Drag canvas** to pan around.
   * **Scroll mouse wheel** (or use bottom-right `+` / `-` buttons) to zoom in and out.
2. **Filtering by Stream**:
   * Click any category button on the top filter bar (e.g., *Science (PCB)*, *Defence & Armed Forces*, *Law & Judiciary*) to automatically focus on that specific discipline.
3. **Searching for Careers & Exams**:
   * Type in the search box (e.g., "NDA", "UGC-NET", "IAS", "Neurosurgery", "AI", "CLAT").
   * Select a result from the dropdown to automatically trace the exact node and highlight the path from Class 10th to that goal.
4. **Exploring Details**:
   * Click on any node box to open the slide-over detail panel containing entrance exams, premier institutions, salary ranges, and necessary skills.

---

## 🤝 Contribution Guidelines

Contributions, issues, and feature requests are welcome! If you would like to add more specific sub-specialties, specialized entrance exams, or additional streams:
1. Fork the Project.
2. Update the `treeData` object inside `index.html`.
3. Create your Feature Branch (`git checkout -b feature/AddSpecializedStream`).
4. Commit your Changes (`git commit -m 'Add New Medical Specialization Path'`).
5. Push to the Branch (`git push origin feature/AddSpecializedStream`).
6. Open a Pull Request.

---

## 📜 License

Distributed under the **MIT License**. Free for educational and personal use by students, parents, and educators across India.
