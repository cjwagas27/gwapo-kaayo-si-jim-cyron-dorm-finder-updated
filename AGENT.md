# AGENTS.md
# DormFinder – Project and Design Instructions

## 1. Project Overview

DormFinder is a Web-Based Dormitory Search and Management System developed as a capstone project by team SYNVEX.

The system helps students discover dormitories, boarding houses, and apartments in Minglanilla, Cebu.

The system has three primary user roles:

- Student / Boarder
- Property Owner
- Administrator

The existing application uses Python Flask, HTML, CSS, JavaScript, and SQLite.

## 2. Required Documentation

Before making significant changes, inspect these files:

- README.md – Project documentation and functionality.
- DESIGN.md – Visual identity and UI/UX design guidelines.
- AGENTS.md – Permanent development instructions.

Always follow the latest approved design direction.

## 3. Impeccable Design Skill

Use the installed Impeccable skill whenever the task involves frontend design, UI/UX improvements, visual reviews, or interface refinement.

Follow its official skill instructions and available commands.

Recommended workflow:

- `/impeccable init` – Establish product context.
- `/impeccable critique` – Evaluate existing interface design.
- `/impeccable shape` – Plan interface improvements before implementation.
- `/impeccable audit` – Review accessibility, responsiveness, and technical quality.
- `/impeccable polish` – Perform final design refinements.
- `/impeccable adapt` – Improve layouts across different screen sizes.

Do not execute design commands automatically when the user has only requested analysis.

Use Impeccable as a design assistant, not as permission to ignore existing project requirements.

## 4. Design Philosophy

DormFinder should look like a professional, modern accommodation discovery platform.

Design inspiration may come from Airbnb, Booking.com, and modern property management platforms.

However, do not directly copy their branding or interfaces.

The design must be:

- Modern and professional
- Clean and minimalist
- Student-friendly
- Visually consistent
- Easy to navigate
- Responsive
- Accessible
- Practical for real users

Avoid generic AI-generated website designs, excessive gradients, unnecessary animations, excessive rounded cards, and decorative elements without purpose.

## 5. Brand Identity

Maintain the DormFinder brand identity.

Preferred colors:

| Color | Hex |
|---|---|
| Dark Navy | #080F20 |
| Secondary Navy | #111B30 |
| Primary Blue | #2563EB |
| Accent Yellow | #FFC928 |
| White | #FFFFFF |
| Light Gray | #CBD5E1 |
| Border Gray | #26344D |
| Success Green | #16A34A |
| Danger Red | #DC2626 |

Use consistent typography, spacing, borders, shadows, buttons, and interactive states.

Do not introduce unrelated colors without a clear design reason.

Follow DESIGN.md for the approved visual system.

## 6. Existing Project Architecture

Current project files include:

- apy.py – Flask application and backend.
- dormfinder.db – SQLite database.
- index.html – Landing page.
- browser.html – Accommodation browsing page.
- signin.html – Sign-in page.
- signup.html – Registration page.
- student-dashboard.html – Student dashboard.
- owner-dashboard.html – Owner dashboard.
- admin-dashboard.html – Administrator dashboard.

Inspect the actual project before assuming its architecture or dependencies.

## 7. Critical System Preservation Rules

The existing system functionalities are already implemented.

Unless explicitly authorized by the user:

1. Never remove existing functionalities.
2. Never modify database tables or records.
3. Never delete or rename existing files.
4. Never change Flask routes.
5. Never rewrite backend logic.
6. Never replace working JavaScript functionality.
7. Never break authentication or user-role permissions.
8. Never change database relationships.
9. Never replace real data with fabricated information.
10. Never introduce unnecessary dependencies.

Frontend improvements must preserve existing functionality.

If a requested design improvement requires backend changes, explain why and request approval first.

## 8. Frontend Development Standards

- Reuse existing CSS and JavaScript where practical.
- Create reusable UI components when appropriate.
- Keep HTML, CSS, and JavaScript organized.
- Avoid unnecessary duplicated code.
- Use semantic HTML.
- Use consistent naming conventions.
- Maintain readable and maintainable code.
- Ensure forms have appropriate validation.
- Ensure interactive elements work correctly.
- Include loading, error, success, and empty states where appropriate.

## 9. Responsive Design

All redesigned pages must support:

- Desktop
- Laptop
- Tablet
- Mobile phone

Check navigation, property cards, forms, dashboards, tables, and maps at different screen sizes.

Avoid horizontal overflow and broken layouts.

## 10. Implementation Workflow

For every major design task:

1. Inspect the relevant existing files.
2. Understand the current functionality.
3. Review DESIGN.md.
4. Use Impeccable when relevant.
5. Explain the proposed implementation.
6. Make changes only within the approved scope.
7. Preserve existing backend and database behavior.
8. Test the affected pages and interactions.
9. Review the rendered result in the browser.
10. Fix visible layout and responsiveness issues.
11. Report the files changed and tests performed.

Do not claim that something works without testing it.

## 11. Git and Project Safety

- Do not overwrite unrelated changes.
- Do not reset or delete Git history.
- Do not commit or push without user approval.
- Preserve existing project files.
- Recommend creating a Git checkpoint before major redesigns.

## 12. Communication

The user is a BSIT student developing DormFinder as a capstone project.

Explain technical decisions in simple English.

Before major implementation changes, explain what will be modified and why.

Work one approved task at a time.

Do not redesign the entire system when the user requests only one page.

## 13. Final Objective

Transform DormFinder into a professional, production-quality accommodation discovery and management platform while preserving its existing functionalities, database, and backend architecture.

**Design quality and system stability must work together.**