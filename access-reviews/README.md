# Access Reviews – IAM Operations

## Purpose
This module demonstrates how Identity & Access Management (IAM) access reviews are performed in a regulated environment to ensure least privilege, reduce risk, and maintain audit readiness while allowing business operations to continue.

Access reviews are a core operational IAM control and serve as a primary mechanism to detect:
- Over-provisioning
- Permission creep
- Scope creep
- Violations of least privilege

---

## What an Access Review Is
An access review is a structured, repeatable process used to validate that users have:
- The **correct access**
- For the **correct role**
- For the **correct business reason**
- At the **correct point in time**

Reviews provide documented evidence that access decisions are intentional, approved, and traceable.

---

## Why Access Reviews Matter
In regulated environments (financial services, healthcare, government), access reviews:
- Support internal and external audits
- Provide evidence for SOX, HIPAA, and similar requirements
- Reduce the risk of unauthorized access
- Prevent long-term permission sprawl

Access reviews are not just a compliance exercise — they are an operational risk-management control.

---

## Operational Review Approach
Access reviews are conducted using a standardized, documented workflow:

1. Identify the application or system under review
2. Extract current user access (roles, groups, entitlements)
3. Compare assigned access against approved role definitions
4. Validate access with business or application owners
5. Document approvals, removals, and exceptions
6. Remediate inappropriate access
7. Retain evidence for audit purposes

This approach ensures reviews are **repeatable, reviewable, and auditable**.

---

## Artifacts in This Folder
- **access-review-template.md**  
  Standard template used to document access reviews and approvals

- **sample-access-review.csv**  
  Example dataset showing user access, review decisions, and outcomes

- **findings-and-remediation.md**  
  Example review findings, identified risks, and corrective actions taken

---

## Key Outcomes Demonstrated
- Controlled access decisions (not ad-hoc or memory-based)
- Clear business ownership of access approvals
- Traceability from user → role → access → justification
- Audit-ready documentation

---

## How This Scales
While this example demonstrates a manual access review process, the same principles apply when reviews are automated through IAM or IGA tools. Automation improves efficiency, but governance logic remains the same.

---

## Summary
Access reviews are a foundational IAM operation that:
- Enforce least privilege
- Reduce organizational risk
- Support audits
- Enable business operations in a controlled, defensible manner

This module represents a complete, audit-ready access review process.
