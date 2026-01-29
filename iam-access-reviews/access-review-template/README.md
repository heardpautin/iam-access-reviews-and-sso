# Access Review Template – Usage Guide

## Purpose
This folder contains the standardized template used to perform identity and access reviews in a repeatable, auditable, and defensible manner.

The goal of this template is to ensure users have the **right access for their role**, prevent permission creep, and produce clear evidence suitable for audits and compliance reviews.

---

## Folder Structure

```
access-review-template/
├── README.md                    # Instructions for using the template
└── ACCESS_REVIEW_TEMPLATE.md    # Fillable access review artifact
```

---

## When to Use This Template
Use `ACCESS_REVIEW_TEMPLATE.md` when performing:
- Periodic access reviews (quarterly, semi-annual, annual)
- Privileged access reviews
- Event-driven reviews (joiner, mover, leaver follow-ups)
- Targeted reviews for audits or investigations

---

## How to Use the Template

1. **Copy the template**
   - Create a new file using `ACCESS_REVIEW_TEMPLATE.md`
   - Rename it using a clear naming convention, for example:
     ```
     Access-Review_Q1-2026_Finance-App.md
     ```

2. **Populate the template**
   - Complete scope, applications, and population reviewed
   - Document reviewers and review date
   - Record findings, approvals, and exceptions

3. **Attestation**
   - Line-of-business reviewers attest to access correctness
   - IAM validates role alignment and resolves anomalies

4. **Finalize**
   - Save completed review as evidence
   - Store according to organizational retention requirements

---

## What This Template Is (and Is Not)

**This template IS:**
- A standardized access review artifact
- Audit-ready documentation
- A repeatable operational control

**This template is NOT:**
- A policy document
- A troubleshooting guide
- A place for process explanations or narratives

Process documentation should live outside the completed review artifact.

---

## Evidence & Audit Readiness
Completed templates may be used as evidence for:
- Internal audits
- External audits
- Compliance assessments
- Risk reviews

Ensure all exceptions are:
- Documented
- Time-bound
- Approved
- Re-reviewed on the next cycle

---

## Ownership
- **Primary Reviewers:** Line-of-Business Managers
- **IAM:** Validation, remediation, enforcement
- **Security / Compliance:** Oversight and evidence review (as required)

---

## Version Control
- Update the template only when process requirements change
- Do not modify completed access review artifacts after attestation

“This folder contains standardized access review artifacts and supporting evidence used to execute periodic and event-driven IAM access reviews.”
