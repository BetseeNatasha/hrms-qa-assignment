# Quality Reflection

## 1. Do you personally write tests?

Honestly, I have not had a consistent habit of writing automated tests in my academic and personal projects. Most of my projects were developed as learning projects where I focused on implementing functionality first and manually testing features. This assignment helped me understand how automated testing can prevent production issues and improve software reliability.

---

## 2. Describe a bug you shipped or found.

During this HRMS QA assignment, I found multiple production issues. One major issue was that dropdown menus in the Job Advertisement page were completely non-functional. Another issue was that employee and job seeker update pages remained stuck on loading screens because API requests were returning 404 errors.

This experience showed me that features can appear complete visually while failing completely for users. It reinforced the importance of end-to-end testing and API validation.

---

## 3. What does this team need most right now?

The team needs an automated CI pipeline.

Without automated checks, developers can unknowingly introduce bugs into production. A CI pipeline creates immediate feedback and prevents broken functionality from being deployed.

---

## 4. How would you convince the senior developer?

I would not start with theory. Instead, I would demonstrate how automated tests catch real bugs that already exist in the application. By showing that a small automated test could have detected the dropdown and API failures before release, I would focus on saving developer time rather than enforcing process.

---

## 5. Connect your test strategy to something personal.

As a student, I manage assignments, certifications, internship applications, and placement preparation using structured checklists. The system works because it matches how I actually work rather than being overly complex. Similarly, a quality process should be simple, practical, and easy for the team to follow consistently.