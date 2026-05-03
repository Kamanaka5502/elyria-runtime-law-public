<div align="center">

# ⚖️ Elyria Runtime Law

## Public Proof Surface

### Consequence Admission Before Effect

**ELYRIA SYSTEMS — VA**  
**Samantha Revita · Terry Snyder**

<br/>

![Status](https://img.shields.io/static/v1?label=STATUS&message=PUBLIC%20PROOF%20SURFACE&color=D4AF37&style=for-the-badge)
![Runtime](https://img.shields.io/static/v1?label=RUNTIME&message=PROTECTED%20PRIVATE%20LAYER&color=111827&style=for-the-badge)
![License](https://img.shields.io/static/v1?label=LICENSE&message=PROPRIETARY%20%7C%20EVALUATION%20ONLY&color=B91C1C&style=for-the-badge)

![Implementation](https://img.shields.io/static/v1?label=IMPLEMENTATION&message=NOT%20INCLUDED&color=6B7280&style=for-the-badge)
![Open Source](https://img.shields.io/static/v1?label=OPEN%20SOURCE&message=NO&color=DC2626&style=for-the-badge)
![Disclosure](https://img.shields.io/static/v1?label=DISCLOSURE&message=CONTROLLED&color=7C3AED&style=for-the-badge)

![Boundary](https://img.shields.io/static/v1?label=BOUNDARY&message=CONSEQUENCE%20ADMISSION&color=2563EB&style=flat-square)
![Admissibility](https://img.shields.io/static/v1?label=ADMISSIBILITY&message=BEFORE%20EFFECT&color=0F766E&style=flat-square)
![Replay](https://img.shields.io/static/v1?label=REPLAY&message=DIRECTIONAL%20PROOF&color=4B5563&style=flat-square)
![Receipts](https://img.shields.io/static/v1?label=RECEIPTS&message=PROTECTED%20PRIVATE&color=111827&style=flat-square)
![Runtime Law](https://img.shields.io/static/v1?label=RUNTIME%20LAW&message=CATEGORY%20SURFACE&color=7C3AED&style=flat-square)

<br/>

> **Runtime law for consequence-bearing systems.**

Most systems decide whether something may run.  
**Elyria determines whether consequence may bind.**

</div>

---

## Purpose

This repository is a clean public proof surface for **Elyria Runtime Law**.

It is intentionally:

- non-runnable
- non-implementation-bearing
- non-open-source
- non-deployment-ready
- stripped of source code, schemas, tests, examples, receipts, and runtime internals

It exists to communicate the category, boundary model, admissibility framing, runtime outcomes, and protected-scope distinction without exposing the commercial/runtime layer.

---

## Core Category

### Consequence admission before effect

Elyria Runtime Law addresses a specific execution-governance gap:

> When an AI system, automated system, agent, workflow, or control plane is about to produce consequence, where is the deterministic boundary that can say no — and prove it?

This is not monitoring after action.

This is not audit after effect.

This is not authorization alone.

This is the boundary where proposed motion is resolved before consequence becomes real.

---

## What This Is / Is Not

| This public repo is | This public repo is not |
|---|---|
| Category framing | Source code |
| Boundary language | Runtime implementation |
| Public proof surface | Open-source release |
| Outcome vocabulary | Deployment package |
| Protected-scope notice | Client corridor logic |
| Controlled-disclosure front door | Receipt/replay internals |

---

## Distinction

A system can be:

- authenticated
- policy-aware
- workflow-complete
- semantically valid
- technically executable

and still be inadmissible as consequence.

Elyria Runtime Law separates:

| Layer | Question |
|---|---|
| Path / existence | Can a constructible transition form? |
| Admissibility | May that transition carry consequence? |
| Binding | Does consequence become real? |
| Replay | Can the decision be reproduced under the same conditions? |

---

## Boundary Model

```text
Proposed motion
      ↓
Path / existence resolution
      ↓
Admissibility resolution
      ↓
Consequence binding decision
      ↓
Receipt / replay direction
```

The governing split:

```text
No path
→ no transition
→ no state
→ no admissibility

Path exists but fails admissibility
→ state is representable
→ consequence does not bind

Path exists and admissibility holds
→ consequence may bind
```

---

## Runtime Outcomes

| Outcome | Meaning |
|---|---|
| **EXECUTE** | consequence may bind under current state |
| **REFUSE** | proposed consequence lacks standing |
| **HALT** | continuation stops; support is no longer sufficient |
| **REDIRECT** | intent may continue only through a lawful alternate corridor |
| **ESCALATE** | authorized review is required before effect |
| **REBOUND** | unsupported pressure returns; motion cannot continue forward |
| **RESTART** | lawful re-entry after judged halt or recovery condition |

---

## Public Proof Claim

The public proof claim is simple:

```text
same request + same state + same policy + same boundary context
= same decision direction
```

This public repository does not expose the protected implementation that performs runtime evaluation.

It shows the category and boundary structure only.

---

## Protected Scope

The following are not included and are not licensed through this repository:

- source code
- runtime evaluators
- schemas
- tests
- examples
- client corridors
- receipt-generation internals
- replay-verification internals
- deployment instructions
- private proof packages
- commercial runtime substrate

For deeper evaluation, controlled access requires written terms, NDA, or scoped diligence authorization.

---

## Controlled Review Path

```text
Public surface
→ category and boundary review

Controlled review
→ private access under written evaluation terms

Commercial diligence / pilot
→ scoped packet, protected implementation, no derivative-use rights
```

---

## Core Sentence

> **Most systems govern whether something may run. Elyria governs whether consequence may bind.**

---

<div align="center">

### ELYRIA SYSTEMS — VA

**Samantha Revita · Terry Snyder**

Public proof surface only. Protected implementation remains private.

</div>
