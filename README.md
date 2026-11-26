# Kerala Urban Employment Programme — redesigned interactive portal

## Files
- `index.html` — programme overview, application, vacancies, assessment and portals.
- `styles.css` — responsive visual design.
- `app.js` — synthetic records, filters, charts, application and portal interactions.

## Demo content
- Programme overview includes the 1,472 ASAP recruitment-partner figure, host organisation types, 90-day duration and ₹363 daily stipend figure.
- 100 synthetic applicant profiles, including age, gender, social category (GEN / SC / ST / OBC), qualification, sector, location, cycle and sample application status.
- 100 synthetic vacancies across the seven sectors and roles listed in the programme proposal.
- Government dashboard with demographic, gender, sector, location and pipeline charts; filters; equity table; JSON export.
- Applicant application form and dashboard, sample assessment and cycle-based merit register.
- ASAP and host organisation workspaces.
- Post-specific workplace progress form and grievance register.

## Run locally
Extract the ZIP and open `index.html` in a modern browser. An internet connection is needed for Google Fonts and Chart.js (loaded from CDN).

## Publish with GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `styles.css`, `app.js`, and `README.md` into the repository root.
3. Open Settings → Pages.
4. Select Deploy from a branch, choose `main` and `/(root)`, then Save.
5. Wait for publication and open the URL GitHub provides.

## Important limitations
- All 100 applicants and 100 vacancies are synthetic, not real beneficiaries, employers or open vacancies.
- Data is stored in each browser's localStorage. This is not a shared multi-user database.
- Authentication, identity verification, secure exam delivery, payments, SMS, email, APIs and official recruitment are not implemented.
- Do not enter real personal information or use this prototype for recruitment decisions.
- Social category is collected only to demonstrate equity monitoring. A production deployment requires appropriate legal basis, data minimisation, role-based access, encryption, retention controls and safeguards.
- Four exam cycles, sample exam questions and sample rankings are demo mechanics. The programme proposal does not specify exam dates, questions, cut-offs, tie-break rules or list validity.
- The proposal's page 5 projection is 77,900 unemployed urban graduates aged 20–24 in 2025. This interface displays 79,000 as the rounded planning figure requested.
- Programme costs and four stipend funding models are transcribed from the proposal and should be validated before formal budgeting or sanction.
