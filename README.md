# Lab 1 – Requirements Engineering & UML Use-Case Modelling

**PES University – Dept. of CSE**

**Name:** Rohit R  
**SRN:** PES2UG24AM137  
**Section:** AIML-B

---

## Problem Statement

**Community Tool & Equipment Library** (Problem Statement #52)

A neighborhood resource-sharing library where members check out power tools, camping gear, and lawnmowers, track deposit calculations, manage return dates, and log damage assessments.

---

## Actors

1. **Community Member** – borrows and returns equipment
2. **Library Custodian** – manages inventory and assesses equipment damage
3. **Depot Locker System** – external system managing physical locker availability

---

## Deliverables

| File | Description |
|------|-------------|
| `Requirements_Table.xlsx` | 5 Functional Requirements (FR-001 to FR-005) and 2 Non-Functional Requirements (NFR-001 to NFR-002) with acceptance criteria, rationale, and comments |
| `Use_Case_Diagram.pdf` | UML Use-Case Diagram with 7 use cases, 3 actors, `<<include>>` and `<<extend>>` relationships |
| `Use_Case_Flow.docx` | Detailed use-case flow for UC-03 — Borrow/Reserve Equipment |
| `Use_Case_Flow.pdf` | PDF export of the use-case flow document |

---

## Use Cases

| ID | Use Case | Primary Actor |
|----|----------|---------------|
| UC-01 | Search Equipment | Community Member |
| UC-02 | Check Equipment Availability | Community Member |
| UC-03 | Borrow/Reserve Equipment | Community Member |
| UC-04 | Return Equipment | Community Member |
| UC-05 | Calculate Deposit & Loan Terms | System |
| UC-06 | Assess Equipment Damage | Library Custodian |
| UC-07 | Manage Equipment Inventory | Library Custodian |

---

## Relationships

- **`<<include>>`**: UC-03 Borrow/Reserve Equipment includes UC-05 Calculate Deposit & Loan Terms
- **`<<extend>>`**: UC-06 Assess Equipment Damage extends UC-04 Return Equipment

---

## Main Detailed Use Case

**UC-03 — Borrow/Reserve Equipment**

The use-case flow document covers preconditions, a 12-step main success scenario, one alternate flow (overdue equipment), and postconditions.
