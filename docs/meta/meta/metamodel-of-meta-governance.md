---
title: Meta-Model of Meta-Governance
sidebar_position: 2
---

# Meta-Model of Meta-Governance

> **Domain:** System Charter  
> **Artifact Kind:** Rule  
> **Authority Level:** Mandatory  
> **Stability:** Very High  
> **Applies To:** All meta artifacts  
> **Owner:** Editorial Board  
> **Last Reviewed:** 2026-02-15  

This page defines the formal model governing meta artifacts.

Meta artifacts are classified along two orthogonal axes:

1. **Artifact Kind** — What the artifact is.
2. **Authority Level** — How strongly the artifact binds contributors.

Not all combinations are valid.  
This page defines the allowed combinations.

---

# 1. Artifact Kind

Each meta artifact must declare exactly one of the following kinds.

| Artifact Kind | Definition |
|---------------|------------|
| **Rule** | Defines a constraint, requirement, or normative statement. |
| **Structure** | Defines required form, layout, or structural composition. |
| **Procedure** | Defines a workflow or operational process. |
| **Template** | Canonical reusable structure for creating artifacts. |
| **Reference** | Registry, mapping, or structured reference information. |
| **Record** | Historical entry documenting a decision or change. |

---

# 2. Authority Level

Each meta artifact must declare exactly one authority level.

| Authority Level | Meaning |
|------------------|---------|
| **Mandatory** | Must be followed without exception. |
| **Required** | Expected to be followed; exceptions must be justified. |
| **Recommended** | Strong guidance; deviation allowed. |
| **Advisory** | Informative suggestion. |
| **Illustrative** | Non-binding example. |
| **Archival** | Immutable historical record. |

---

# 3. Allowed Combinations

The following matrix defines valid pairings.

## 3.1 Rule

| Authority Level | Allowed |
|------------------|----------|
| Mandatory | Yes |
| Required | Yes |
| Recommended | Yes |
| Advisory | Yes |
| Illustrative | No |
| Archival | No |

Rules may vary in strength but cannot be purely illustrative or archival.

---

## 3.2 Structure

| Authority Level | Allowed |
|------------------|----------|
| Mandatory | Yes |
| Required | Yes |
| Recommended | Yes |
| Advisory | No |
| Illustrative | No |
| Archival | No |

Structures define form. They must carry normative weight.

---

## 3.3 Procedure

| Authority Level | Allowed |
|------------------|----------|
| Mandatory | Yes |
| Required | Yes |
| Recommended | Yes |
| Advisory | Yes |
| Illustrative | No |
| Archival | No |

Procedures may range from strict workflows to suggested processes.

---

## 3.4 Template

| Authority Level | Allowed |
|------------------|----------|
| Mandatory | Yes |
| Required | Yes |
| Recommended | Yes |
| Advisory | No |
| Illustrative | No |
| Archival | No |

Templates define canonical structure and must carry normative intent.

---

## 3.5 Reference

| Authority Level | Allowed |
|------------------|----------|
| Mandatory | No |
| Required | No |
| Recommended | No |
| Advisory | No |
| Illustrative | Yes |
| Archival | Yes |

References are informational.  
They cannot impose binding authority.

---

## 3.6 Record

| Authority Level | Allowed |
|------------------|----------|
| Mandatory | No |
| Required | No |
| Recommended | No |
| Advisory | No |
| Illustrative | No |
| Archival | Yes |

Records are immutable historical artifacts.

---

# 4. Invalid Combinations

The following combinations are explicitly forbidden:

- Record with any level other than Archival.
- Reference with Mandatory, Required, Recommended, or Advisory.
- Template with Illustrative.
- Structure with Advisory or Illustrative.
- Any artifact with multiple authority levels.

Invalid combinations must be corrected before publication.

---

# 5. Design Rationale

The separation between Artifact Kind and Authority Level:

- Prevents semantic confusion.
- Enables precise governance scaling.
- Supports automation and validation.
- Avoids collapsing ontology into enforcement strength.

The allowed combinations ensure:

- Informational artifacts do not become binding.
- Historical records remain immutable.
- Structural artifacts retain normative force.
- Governance intensity is explicit and controllable.

This model governs all meta artifacts in the guidebook.