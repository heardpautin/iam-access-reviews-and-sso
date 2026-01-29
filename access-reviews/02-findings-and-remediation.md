# Findings & Remediation – Access Review Output

## Purpose
This document captures what happens **after** an access review identifies issues. It records:
- What was found
- What risk it represents
- What action was taken (or approved as an exception)
- Evidence that remediation occurred

This keeps the access review process **auditable, repeatable, and defensible**.

---

## When to Use
Use this file when an access review results in:
- Over-provisioning (too much access)
- Permission creep (access accumulated over time)
- Scope creep (access outside role boundaries)
- Privileged access without justification
- Orphaned access (no manager / no valid owner)

---

## Findings Categories (quick)
- **Over-privileged access** (least privilege violation)
- **Privilege misuse risk** (standing admin / broad roles)
- **Orphaned accounts** (no manager/owner, service accounts not tracked)
- **SoD conflict** (access combination violates separation of duties)
- **Access outside role** (role mismatch or “temporary” access that became permanent)

---

## Findings Log Template

| Finding ID | User / Account | App / System | Current Access | Expected Access | Risk | Recommended Action | Owner | Due Date | Status |
|---|---|---|---|---|---|---|---|---|---|
| F-001 | (user) | (app) | (role/group) | (role/group) | (H/M/L) | Remove / Reduce / Approve Exception | (name/team) | (date) | Open/In Progress/Closed |

---

## Remediation Actions (standard)
Use consistent language so your evidence is clean:

- **Remove access** (deprovision role/group)
- **Reduce access** (move from admin → standard role)
- **Correct role mapping** (place user in correct RBAC group)
- **Convert to controlled exception** (time-bound + approved)
- **Disable / remove account** (leaver, orphan, stale)
- **Escalate to IAM Admin / App Owner** (policy or technical change required)

---

## Exception Handling (controlled exception, not a shortcut)
If business insists on access outside the role:
1. Record **business justification**
2. Ensure **manager approval**
3. Make it **time-bound**
4. Schedule **re-review date**
5. Document the outcome in the next review cycle

**Exception Register Template**

| Exception ID | User | App | Access Granted | Justification | Approver | Start | End / Re-review | Status |
|---|---|---|---|---|---|---|---|---|
| EX-001 | (user) | (app) | (role/group) | (why) | (mgr) | (date) | (date) | Active/Expired/Removed |

---

## Evidence to Capture (minimum viable)
For each closed finding, capture at least one of:
- Screenshot/export showing role/group **before**
- Screenshot/export showing role/group **after**
- Ticket/approval record (ServiceNow/Jira/email approval)
- Notes from reviewer attestation

---

## Completion Criteria
A finding is “closed” only when:
- Access was removed/reduced **OR**
- Exception was approved, time-bound, and scheduled for re-review
- Evidence exists showing the decision and the action taken
