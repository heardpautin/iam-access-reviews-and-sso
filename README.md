# IAM Operations: Access Reviews & SSO in Microsoft Entra ID

## Overview
This project demonstrates a practical, operational approach to Identity and Access Management (IAM) in regulated environments. It focuses on stabilizing access through access reviews, implementing role-based access control (RBAC), and integrating applications using Single Sign-On (SSO) in Microsoft Entra ID.

The emphasis is on repeatable, auditable, and supportable IAM operations that reduce risk while allowing business processes to function efficiently—particularly in small teams operating under real-world constraints.

---

## Project Goals
- Establish a clear access baseline through access reviews
- Reduce permission sprawl and ad-hoc access
- Demonstrate RBAC as a source of truth for provisioning
- Integrate applications with Entra ID for SSO
- Support audit readiness through documentation and traceability

---

## Scope of This Project
This project reflects **operational IAM**, not greenfield architecture.

Included:
- Access review methodology
- RBAC role and group design
- SSO application onboarding (Entra ID)
- Troubleshooting access and sign-in issues
- Audit-supporting evidence and documentation

Out of scope:
- Advanced automation pipelines
- Full IGA platform implementation
- Custom identity development

---

## Phase 1: Access Reviews (Stabilization First)
Access reviews are used to understand the current state before making changes.

Focus areas:
- Validate user access against job roles
- Identify over-provisioned or orphaned access
- Detect scope creep and least-privilege violations
- Produce evidence suitable for audit review

Artifacts:
- RBAC matrix (roles → permissions)
- Access review checklists
- Findings and remediation notes

---

## Phase 2: RBAC as the Access Baseline
Roles are treated as the authoritative source for access—not memory or ad-hoc decisions.

RBAC principles used:
- Permissions are assigned to roles, not users
- Roles are mapped to Entra ID security groups
- Group membership drives access
- Exceptions are time-bound and documented

Artifacts:
- Role definitions
- Group-to-role mappings
- Exception handling examples

---

## Phase 3: SSO Application Integration
Applications are integrated into Entra ID to centralize authentication and access control.

SSO concepts covered:
- App registration and enterprise applications
- Group-based access assignment
- Token issuance and claims
- Common access failure scenarios

Troubleshooting focuses on:
- Group membership
- Conditional Access evaluation
- Sign-in logs and error codes

---

## Audit & Compliance Alignment
Throughout the project, IAM operations are aligned to support audits by ensuring access is:
- Documented
- Reviewable
- Traceable
- Defensible

This mirrors how IAM functions as a **continuous control**, not a one-time task.

---

## Why This Matters
In regulated environments, IAM failures rarely come from lack of tools—they come from inconsistent operations.

This project demonstrates how disciplined IAM operations:
- Reduce risk
- Support audits
- Enable business continuity
- Scale even with small teams

---

## Disclaimer
This project is for demonstration and learning purposes and does not contain production credentials, real user data, or proprietary configurations.
