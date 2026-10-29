# Ledgerline — Technical Design Document

> **Template.** Ahmed writes this document; the mentor reviews it. Replace each instruction (in _italics_) with your own content. Keep it short and specific: a reviewer should understand the system in 15 minutes. This is a living document: update it whenever the design changes, and note the change in the changelog at the bottom.

| | |
|---|---|
| **Author** | _Your name_ |
| **Status** | _Draft / In review / Approved_ |
| **Last updated** | _YYYY-MM-DD_ |
| **Reviewers** | _Who reviewed it_ |

---

## 1. Problem

_What problem does Ledgerline solve, and for whom? Two or three sentences. Why does it exist (as a product, and as a portfolio piece)?_

## 2. Goals and non-goals

### Goals
_A short bulleted list of what this project must achieve. Make each goal checkable._

### Non-goals
_What you are deliberately **not** doing, and why. This is as important as the goals._

## 3. Requirements

### Functional requirements
_What the system must do. Number them (FR-1, FR-2, …) so user stories and tests can refer to them._

### Non-functional requirements
_Qualities the system must have: security, correctness of money, performance, accessibility, browser support, testability, observability. Make them measurable where you can._

### User stories
_Link to the GitHub Issues / Project board. List the epics here, with a one-line summary each._

## 4. Architecture

_A high-level diagram (Mermaid) and a short description of the main parts and how they talk to each other: frontend, backend layers, database, and any later additions. Link to the relevant ADRs._

## 5. Data model

_The ERD (link or embed from `docs/diagrams/`) and a short explanation of each table, its key constraints, and any important design choices (for example, how balances relate to ledger entries)._

## 6. API design

_A table of endpoints: method, path, purpose, auth required, main status codes. Describe the error format and the versioning approach. Link to the OpenAPI/Swagger docs once they exist._

| Method | Path | Purpose | Auth | Status codes |
|---|---|---|---|---|
| _…_ | _…_ | _…_ | _…_ | _…_ |

## 7. Key flows

_Sequence diagrams (embed from `docs/diagrams/`) for the most important flows, starting with a transfer. Call out where each flow can fail and what happens when it does._

## 8. Security

_Authentication, authorization, password storage, input validation, secrets management, audit logging, and the OWASP risks most relevant to this app. For each: what the risk is and how the design handles it._

## 9. Testing strategy

_What you test at each level (unit, slice, integration with Testcontainers, end-to-end), what tools you use, what "enough testing" means for this project, and which tests matter most for a bank (for example, concurrency and money correctness)._

## 10. Risks and open questions

_Technical and schedule risks, each with a likelihood, impact and mitigation. List open questions that still need a decision (and turn them into ADRs when decided)._

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| _…_ | _…_ | _…_ | _…_ |

---

## Changelog

| Date | Change | Why |
|---|---|---|
| _YYYY-MM-DD_ | _First draft_ | _—_ |
