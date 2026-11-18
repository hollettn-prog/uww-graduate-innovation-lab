# UWW Graduate Innovation Lab

A GitHub Pages-ready, static demonstration repository for exploring practical graduate education workflows at the University of Wisconsin–Whitewater. Prepared for a conversation with Andrea Ednie, interim dean of graduate studies.

## What is included

The site contains eleven interactive tools:

1. Student time and credit planner
2. Canvas course builder
3. Strategic planning studio
4. Governance mapper
5. Resource library
6. Decision coach
7. Graduate application review assistant (fictional rubric design only)
8. Enrollment journey
9. Online learning orientation
10. Student journey audit
11. AI opportunity and risk assessment builder

Every tool has a fictional starting scenario, contextual coaching, working form interactions, and a downloadable plain-text summary when a summary is produced. The resource library filters policy and campus support references.

## Run locally

Open `index.html` in a browser, or serve this folder with any static web server. There is no build step, package manager, API, database, or app backend. Form data is processed in the current browser tab only; the hosting provider may retain routine page request logs.

## Deploy with GitHub Pages

1. Create a GitHub repository named `uww-graduate-innovation-lab` and add these files at its root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then select **Save**.
5. After GitHub finishes publishing, open the Pages URL shown on that settings page.

Use the `main` branch/root option because this repository is plain HTML, CSS, and JavaScript. A custom domain is optional. GitHub Pages is public: do not add protected information, real student/applicant examples, credentials, or internal materials to the repository or public demo.

## Andrea demonstration walkthrough (about 12 minutes)

1. **Set the boundary (1 min).** Open the site and point out the “Fictional data only” banner. Explain that the static demo has no login, data submission, uploads, analytics, or backend; refreshing clears tool inputs.
2. **Start with student capacity (2 min).** Open the Student time & credit planner. Use its fictional Jordan scenario, change weekly study hours, and show the estimate and downloaded summary. Ask how the program could help students make realistic workload decisions.
3. **Show reusable course design (2 min).** Open the Canvas course builder, adjust the number of modules and outcome, and generate the module outline. Discuss how a consistent module rhythm could help online learners.
4. **Move from priorities to decisions (2 min).** Demonstrate the strategic planning studio, governance mapper, and decision coach. Highlight that owners and approval authority must be confirmed through current UWW processes.
5. **Trace the student experience (2 min).** Walk through the enrollment journey, online learning orientation, and student journey audit. Invite discussion about unclear handoffs, recurring questions, and support contacts.
6. **Address admissions and AI safeguards (2 min).** Show the application review assistant as a rubric/process design aid only; no application materials can be uploaded or reviewed. In the AI risk builder, choose a student/applicant or confidential data category to show the “Pause & escalate” guidance.
7. **Close with references and next steps (1 min).** Review the policy links, ask which pilot would be useful, identify the process owner and data steward, and agree that any operational version requires university review and approved systems.

## Privacy, data classification, and limits

- This is a public educational demonstration, not an official UW–Whitewater service, admissions system, Canvas integration, or approved decision workflow.
- Do not enter real applicant or student records, personally identifiable information, employee information, unpublished research, internal university documents, sensitive, confidential, or proprietary data.
- There is no file upload or network submission. Form values are held only in the current page and are not persisted by this app. Downloaded summaries are created locally by the browser and are the user’s responsibility.
- The admissions tool demonstrates fictional criteria and human-review checkpoints. It cannot score actual candidates or recommend admission decisions.
- The AI risk tool is an initial conversation prompt, not an official data classification, security review, privacy review, legal opinion, or authorization.
- Confirm current requirements and approved systems with UW–Whitewater and Universities of Wisconsin before operational use. When uncertain, stop and contact the Registrar, IT/security, privacy/records, procurement, accessibility, or policy owner as appropriate.

## Policy reference links

References were reviewed November 18, 2026. Confirm the current versions before operational use.

- [UW–Whitewater Allowable and Prohibited AI Uses](https://www.uww.edu/ai/allowable-and-prohibited-uses)
- [UW–Whitewater Faculty and Staff AI Guidelines](https://www.uww.edu/ai/guidelines/faculty-and-staff-guidelines)
- [UW–Whitewater FERPA](https://www.uww.edu/registrar/ferpa)
- [UW–Whitewater Information Security Policies](https://www.uww.edu/policies/policies-by-category/information-security-policies)
- [UW–Whitewater Graduate Studies](https://www.uww.edu/gradstudies)

## Accessibility and design

Semantic landmarks, keyboard-operable controls, visible focus styles, skip navigation, responsive layouts, live result announcements, and reduced-motion support are included. Review all content and run accessibility checks before adopting or extending the site. Typography uses local system font stacks; the site does not load third-party font resources.

## Files

- `index.html` — page structure and policy/privacy notices
- `styles.css` — responsive UW–Whitewater-inspired visual system
- `app.js` — tool content, interactions, calculations, and local text downloads

