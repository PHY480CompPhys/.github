# PHY 480: Computational Physics - Syllabus

## Michigan State University - Spring 2026

### Professor Sean Couch  

## Course Description

This three-credit upper-level undergraduate course intended for Physics and Astrophysics majors introduces the core concepts of computational physics. You will develop competency in numerical modeling, scientific programming in Python, and validating computational results. You will also practice communicating scientific reasoning and results.

## Course Information

**Meeting Times:** Tuesdays & Thursdays, 10:20–11:40 am  
**Location:** Holden Hall C132  
**Instructor:** Prof. Sean Couch, <scouch@msu.edu>, Zoom: [msu.zoom.us/my/scouch](https://msu.zoom.us/my/scouch)  
**Office Hours:** TBA, 3260 BPS  
**Teaching Assistant:**  
**ULA Help sessions:** (TBA)  
**Course Webpages**: [D2L](https://d2l.msu.edu/d2l/home/2375781), [GitHub](https://github.com/PHY480CompPhys)

## Course Materials

### Required Text

- [*Computational Physics* by Mark Newman (2013)](https://catalog.lib.msu.edu/Record/folio.in00006419680)

### Additional recommended texts (available electronically from MSU Library)

- [*Numerical Methods in Physics with Python* — Alex Gezerlis (2023)](https://catalog.lib.msu.edu/Record/hlm.ebs102833158e?sid=86547236)
- [*Computational Quantum Mechanics* — Joshua Izaac & Jingbo Wang (2018)](https://catalog.lib.msu.edu/Record/hlm.ebs20080450e?sid=86547241)
- [*Mathematical Methods using Python* — Vasilis Pagonis & Christopher W. Kulp (2024)](https://catalog.lib.msu.edu/Record/hlm.ebs104769156e?sid=86547247)
- [*An Introduction to Computational Physics* — Tao Pang (2006)](https://catalog.lib.msu.edu/Record/hlm.ebs1031061e?sid=86547255)
- [*Introduction to Computational Physics for Undergraduates* — Omair Zubairi & Fridolin Weber (2018)](https://catalog.lib.msu.edu/Record/hlm.ebs17094069e?sid=86547270)
- [*Basic Concepts in Computational Physics* — Benjamin A. Stickler & Ewald Schachinger (2016)](https://catalog.lib.msu.edu/Record/hlm.ebs26997396e?sid=86547277)

### Software

- Python (3.x)
- Jupyter (occasionally)
- VS Code
- Docker (via VS Code Dev Containers)
- Git/GitHub (via GitHub Classroom)

### Course environment (important)

We will standardize on a shared, containerized Python environment so that everyone (Windows/macOS/Linux) runs the same versions of Python and scientific packages. Most work will be done by opening assignment repositories in **VS Code Dev Containers**.

### Platforms

- **D2L** for content, PCA quizzes, in-class quiz delivery, and announcements.  
- **GitHub + GitHub Classroom** for assignment distribution, submission, feedback, and (as used) course discussions.

## Class Meetings

You should plan to attend all in-person class meetings that you are reasonably able to. Classes will be a mix of short lectures reviewing key concepts and in-class programming exercises. Your ability to succeed at the assignments and quizzes will be greatly helped by attendance.

## Learning Outcomes

By the end of the term, students who fully engage in the course will be able to:

1. Implement and analyze core numerical algorithms (root-finding, interpolation, numerical integration), assessing accuracy and stability.
1. Formulate and solve ordinary and partial differential equations numerically (finite-difference and spectral methods) and validate solutions.
1. Apply linear algebra and eigenvalue techniques to large-system problems, choosing efficient algorithms for practical computation.
1. Use Fourier/spectral methods and Monte Carlo techniques for signal analysis, sampling, and uncertainty quantification.
1. Develop reproducible computational experiments in Python with version control and containerization (Docker), including tests and documentation.

## Coursework & Assessments

Your course grade will be based on the following components.

## Pre-Class Assignments (PCA Quizzes) — 15%

- Short reading preparation followed by a brief D2L quiz.  
- Due **before class starts**; late PCA quizzes may be submitted until the last day of classes for **half credit**.  
- Expect roughly one to two per week.
- Completing the reading and PCAs will be critical to your success in this course! Not all material assessed in homework and quizzes will be explicitly covered during in-class lectures.

## In-Class Assignments (ICAs) — 35%

- Most classes will include in-class programming exercises built on the material covered in the PCAs.
- While you will be individually responsible for fully completing and submitting all ICAs, during class you will typically be paired with a partner to co-work on the exercises.
- ICAs will be submitted via GitHub and will be due one-week after the ICA is assigned.
- Late ICAs will be accepted until the last day of classes for **half credit**.  
- Completion and comprehension of ICAs will be critical to success on quizzes.

## In-Class Quizzes — 24%

- **Four** in-class, ~40-minute quizzes delivered via D2L using lockdown browser.  
- The lowest of your quiz scores will be dropped from your course grade.
- Each quiz will be **8%** of the course grade.  
- Quizzes will be comprised of a mixture of multiple choice and short answer/short essay questions.  
- You will make a **one-page crib sheet** with any information you like to help you take the quiz. These will be collected at the end of the quiz and are required to receive quiz credit.
- Make-up quizzes will *only* be permitted if arranged more than **24 hours** before the scheduled quiz.
- Quiz dates:
  - Quiz 1: Thursday, February 5
  - Quiz 2: Thursday, February 26
  - Quiz 3: Thursday, March 26
  - Quiz 4: Thursday, April 16

## Midterm Programming Project - 13%

You will complete a midterm individual coding project, chosen from a menu of project descriptions. As part of this midterm, you will perform a multi-step peer code review that will count as part of your midterm grade. Your initial midterm project submission will be due by the end of day on 3/10/2026.

## Final Programming Project - 13%

You will complete and submit a final coding project that will build directly from your midterm project. Your final project will be due by the end of day on 5/1/2026.

## Grading Scale

| Grade Points | Overall % |
|--------------|-----------|
| 4.0          | ≥ 90      |
| 3.5          | 85–89     |
| 3.0          | 80–84     |
| 2.5          | 75–79     |
| 2.0          | 70-74     |
| 1.5          | 65-69     |
| 1.0          | 60-64     |
| 0.0          | < 60      |

## Guidelines & Practices

## Collaboration & Academic Integrity

Collaborative learning is encouraged, but **all submitted work must be your own**. If you work with peers, list collaborators and their contributions. The **Spartan Code of Honor Academic Pledge** applies. Suspected violations will be handled per university procedure.

## Use of AI / Coding Assistants

- **Allowed (use it like a tutor):** brainstorming approaches, interpreting error messages, asking for debugging strategies, looking up API usage, and improving readability (naming, docstrings, comments).  
- **Not allowed:** submitting AI-generated **final solutions** (code or writing) that you cannot explain. Do not paste in large blocks of generated code and treat it as “done.”  
- **Your responsibility:** anything you submit should be work you understand and could reproduce or defend at the whiteboard.
- **Transparency (required when used):** if an AI tool meaningfully helped (beyond spelling/grammar), include a brief “AI Acknowledgment” describing the tool and what it helped with (e.g., “debugging hint for a failing test,” “explained a NumPy function,” “suggested a refactor”).
- **Rationale:** these tools can accelerate learning, but the goal of this course is to build *your* computational reasoning and problem-solving skills.

## Make-Up, Extensions, & Life Happens

If something outside your control disrupts your learning, reach out **as early as you can**. We will aim for reasonable, equitable arrangements. For prolonged issues (illness, caregiving, etc.), we may coordinate with advising or RCPD.

## Contingency Plans

If you must miss more than a week, contact me promptly so we can plan a path to completion. If I have an unexpected short absence, readings and online materials will proceed while quizzes/homework may shift; for extended absence, the department will arrange coverage.

## Accessibility & Title IX

- **Requesting accommodations:** Contact the [Resource Center for Persons with Disabilities (RCPD)](https://rcpd.msu.edu/) to request academic accommodations. After you receive an accommodation VISA, please share it with me as early as possible so we can implement approved adjustments.
- **Title IX & reporting:** MSU provides resources and reporting options for sexual misconduct and discrimination at [titleix.msu.edu](https://titleix.msu.edu/). If you need confidential support, see the counseling resources listed below or contact confidential advocacy services through the Title IX site.

## Student Resources & Wellness

- **Tutoring & academic support:** Free tutoring and academic support services: [tutoring.msu.edu](https://tutoring.msu.edu/).
- **Library research help:** Research guides, consultations, and subject librarians: [lib.msu.edu/research](https://lib.msu.edu/research/).
- **Counseling & mental health:** [Counseling and Psychological Services (CAPS)](https://caps.msu.edu/) (emergency after-hours support available).
- **Safety & emergency:** [MSU Police & Public Safety](https://police.msu.edu/) or call 911 for immediate emergencies.

## Inclusive Learning Environment

- Michigan State University is committed to providing access and promoting/protecting freedom of speech in an inclusive learning environment. **Discrimination and harassment based on a protected identity are prohibited.** Please review MSU’s **Notice of Non-Discrimination, Anti-Harassment, and Non-Retaliation** (linked on D2L).  
- In this class, we will work together to **create and maintain a respectful** teaching and learning environment where we engage in conversations that **challenge our perspectives and understanding**.  
- Please let me know if you would like me to use a **name** for you that is not reflected in the University system or if there is anything else I can do to **support your access** to this class.

## Tentative Schedule & Topics

The general outline of topics covered will be:

- **Weeks 1–2:** GitHub, best practices, numerical accuracy
- **Weeks 3–4:** Numerical integration and differentiation
- **Weeks 5–6:** Solving linear and non-linear problems
- **Weeks 7-8:** Fourier transforms
- **Weeks 9–10:** Solving ordinary differential equations
- **Weeks 11-12:** Solving partial differential equations
- **Weeks 13–15:** Random processes and machine learning

