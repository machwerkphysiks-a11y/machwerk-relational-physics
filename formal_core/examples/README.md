# Applications — Formal Use of the MACHWERK Framework

This directory contains formal application examples based on the book

**MACHWERK — Formal Conditions of Physical Describability**  
(Print edition, ISBN 979-8-24410-846-0, publication date: February 1, 2026).

This repository does not reproduce the book.
It provides a formal, machine-readable reference layer derived from it.

---

## Purpose

The purpose of the applications section is to demonstrate how the
MACHWERK framework is *used*, not how it is explained.

The applications show:

- how formal calculations are performed under explicit relational assumptions
- how projections define observable structure
- where physical interpretability ends without stopping formal computation
- how different physical models become comparable without ontological mixing

These examples are designed to be readable by humans **and** processable by machines.

---

## What These Applications Are

The files in this directory are:

- formal consistency demonstrations  
- admissibility checks under projection  
- boundary analyses near loss of injectivity  
- structured reinterpretations of known physical problems  

They apply the formal core exactly as defined, without extensions.

---

## What These Applications Are Not

These applications are explicitly **not**:

- numerical simulations
- prediction engines
- empirical models
- competing physical theories
- interpretations of quantum mechanics
- speculative philosophy

No new constants are introduced.  
No experimental claims are made.

---

## Structural Rule

Every application follows the same mandatory structure:

1. Explicit relational formulation
2. Explicit projection
3. Explicit validity domain
4. Explicit admissibility check (CRA)
5. Explicit handling of boundary conditions

If any of these steps cannot be carried out,
the result is marked as *formally defined but physically inadmissible*.

This is not a failure.
It is the intended diagnostic outcome.

---

## Conceptual Scope

The applications cover representative problems from:

- classical physics
- quantum relations
- gravitation and cosmology

They focus on **boundary cases**:
situations where standard physical descriptions become ambiguous,
overextended, or implicitly inconsistent.

---

## Relation to the Formal Core

All applications strictly depend on definitions and axioms provided in:

- `formal_core/`
- `axioms/`

No application introduces new axioms.
No application modifies existing ones.

If an application cannot be expressed within the formal core,
it is excluded by design.

---

## Relation to the Book

The examples correspond to worked analyses in Parts A–C of the book.

They are provided here in reduced, non-narrative form to enable:

- independent verification
- formal comparison
- machine parsing
- non-linear access to the framework

This repository complements the book.
It does not replace it.

---

## Design Philosophy

The goal of this section is not to convince,
but to make structure explicit.

If a result feels unsatisfying, inconclusive, or restrictive,
this indicates a boundary of physical describability,
not a missing assumption.

---

## Status

This section is intentionally minimal.

Additional examples are added only if they introduce
a genuinely new admissibility pattern.

Redundancy is treated as a structural error.
