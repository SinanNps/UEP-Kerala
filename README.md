# Kerala Urban Employment Programme — interactive demo

This is a browser-based demonstrator based on the supplied 19-page programme PDF.

## Included
- Problem statement and eligibility criteria from the PDF.
- Vacancy board with fictitious sample vacancies.
- Applicant application form.
- Three proposed exam clusters: Administration, Finance & Legal; Technical, Planning & Design; Other Trades.
- Four illustrative 2027 exam cycles, role-specific sample MCQ exams and cycle-wise ranked lists.
- Demo applicant, ASAP and host organisation portals.
- Transparency dashboard, performance framework, sector-specific host measurement form and grievance workflow.

## Source vs prototype choices
The PDF lists seven work sectors. The three clusters are a proposed grouping for this demo, not a grouping stated in the PDF. Exam questions, sample vacancy records, cycle dates, score threshold, detailed role-based performance criteria and grievance category labels are illustrative prototype data. The PDF does not specify these details. The PDF's three-month apprenticeship, ₹10,900 monthly stipend, ₹2,000 monthly Employment Enhancer Incentive, host/ASAP roles, transparency categories, performance dimensions and grievance timelines are retained.

## Run locally
Open `index.html` in a browser, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Host on GitHub Pages
1. Create a GitHub repository (for example `kerala-urban-employment-demo`).
2. Upload `index.html`, `style.css`, `app.js` and `README.md` to the repository root.
3. Open Settings → Pages.
4. Choose Deploy from a branch; select `main` and `/(root)`; Save.
5. Open the Pages URL displayed by GitHub.

## Limitations
No real authentication, backend, database, email/SMS, payment gateway, exam proctoring or official portal connection. All data is fictitious and stored in browser localStorage. Do not enter real personal data. This is not an official application or recruitment portal.
