<div align="center">

# Elyria Runtime Law

## Public Proof Surface

### Consequence Admission Before Effect

**ELYRIA SYSTEMS — VA**  
**Samantha Revita · Terry Snyder**

![Status](https://img.shields.io/badge/status-public%20proof%20surface-gold)
![Runtime](https://img.shields.io/badge/runtime-protected%20private%20layer-black)
![License](https://img.shields.io/badge/license-proprietary-red)

**Runtime law for consequence-bearing systems.**

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

## Core Sentence

> **Most systems govern whether something may run. Elyria governs whether consequence may bind.**

---

<div align="center">

**ELYRIA SYSTEMS — VA**  
**Samantha Revita · Terry Snyder**

Public proof surface only. Protected implementation remains private.

</div>
