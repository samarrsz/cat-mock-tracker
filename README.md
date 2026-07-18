# cat-mock-tracker
CAT 2026 Mock Tracker
A lightweight, fully offline-capable web app for serious CAT aspirants to track mock performance, log errors, and monitor improvement over time.
Built as a single HTML file — no frameworks, no backend, no setup required.
Features
📊 Mock Log
	•	Log every mock attempt with date and platform (TIME, CL, IMS, etc.)
	•	Section-wise entry for VARC, LRDI, and QA — attempts, correct, and wrong
	•	Scores auto-calculated using the real CAT marking scheme (+3 correct, −1 wrong)
	•	Percentile and time management rating per mock
	•	One-line notes for gut-feel observations right after the mock
❌ Error Log
	•	Log every wrong or unsure question with full context
	•	Tag by error type: Wrong (Concept), Wrong (Silly), Wrong (Misread), Correct but Unsure, Left (Time), Left (Hard)
	•	Track each error through a revision lifecycle: To Revise → Revised Once → Mastered
	•	Record your approach vs. the correct approach, the concept gap, and your action item
	•	Filter by status and section
📈 Dashboard
	•	Score trend bar chart across all mocks
	•	Best score, average score, average percentile
	•	Section-wise averages (VARC / LRDI / QA)
	•	Error type breakdown with visual bar chart
	•	Revision status summary (To Revise / Revised Once / Mastered)
💾 Data & Backup
	•	All data saves automatically to browser localStorage — no account needed
	•	One-click JSON export for backup
	•	Import backup to restore data or move between devices
Tech Stack
|Layer       |Technology                         |
|------------|-----------------------------------|
|Structure   |HTML5                              |
|Styling     |Pure CSS (responsive, mobile-first)|
|Logic       |Vanilla JavaScript (ES6+)          |
|Storage     |Browser localStorage               |
|Dependencies|None                               |
How to Use
Option 1 — Netlify Drop (recommended, 2 min)
	1.	Go to app.netlify.com/drop
	2.	Drag and drop CAT_Mock_Tracker.html
	3.	Get a live link instantly
	4.	On iPhone: Safari → Share → Add to Home Screen
Option 2 — GitHub Pages
	1.	Create a new GitHub repository
	2.	Upload CAT_Mock_Tracker.html and rename it index.html
	3.	Go to Settings → Pages → Deploy from main branch
	4.	Your tracker is live at https://yourusername.github.io/repo-name
Option 3 — Local
Just open the file in any browser. Works fully offline.
workflow
During mock     →  Note Q numbers, LRDI set times, guesses in notebook
Right after     →  Fill Mock Log (5 min)
After solutions →  Fill Error Log for every wrong/unsure question
Weekly          →  Review Dashboard — identify dominant error type
                   Plan the next week's revision around it
Screenshots

Motivation
Most CAT aspirants track scores in scattered notes or generic Excel sheets. This tracker is purpose-built for CAT — with the right marking scheme, the right error taxonomy, 
and a revision workflow that converts each mock into a targeted study plan.
Author
Sam · NSUT Delhi · CAT 2026Built with help from Claude (Anthropic)
License
MIT — free to use, fork, and modify.