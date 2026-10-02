# Inside the Industry

This directory contains the operational framework and output for the "Inside the Industry" initiative, where students analyze actual biotech companies.

## Dual-Output Model

Each company analysis cycle produces **two deliverables** from the same research:

1. **Blog Post (Long-Form):** Comprehensive analysis (1,200–2,000 words) published on the Sageloom website. Contains the full depth: data landscape, end-to-end pipeline, teams & roles, skills map, industry context, and critical analysis.
2. **LinkedIn Post (Short-Form):** Highlight reel (400–600 words) posted on LinkedIn. Captures the most interesting insights and links back to the full blog post, driving traffic to the website.

No information is discarded — everything goes into the blog. LinkedIn gets the hook.

## Structure

- **`sops/`**: The operational machinery for running these cycles.
  - `Sageloom_Inside_the_Industry_Plan.md`: The strategic overview of the initiative.
  - `Sageloom_Universal_Company_Research_Template.md`: The base template students use to structure their analysis.
  - `Student_Company_Intake_Template.md`: The form students complete when selecting a company.
  - `Research_Validation_Rubric.md`: The grading/validation criteria for student submissions.
  - `Blog_Post_Template.md`: Full-length blog post framework for the website (long-form output).
  - `LinkedIn_Post_Template.md`: Short-form LinkedIn post framework with blog link (short-form output).
  - `Company_Pipeline_12_Weeks.md`: The schedule of companies to be analyzed.

- **`cycles/`**: The actual executed work, organized by company cycle (e.g., `cycle-01-medgenome/`). Each cycle folder contains the research drafts, audit reports, and final deliverables (both blog post and LinkedIn draft) for that specific company.

## Production Workflow

```
Student Research (Universal Template)
        ↓
Faculty/Mentor Review
        ↓
  ┌─────┴─────┐
  ↓           ↓
Blog Post   LinkedIn Post
(long-form)  (short-form + blog link)
  ↓           ↓
  └─────┬─────┘
        ↓
Board Approval (both submitted together)
        ↓
  ┌─────┴─────┐
  ↓           ↓
Publish to   Publish to
Website      LinkedIn
```
