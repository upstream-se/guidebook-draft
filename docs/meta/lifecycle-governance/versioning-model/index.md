# Versioning model

> This page defines how guidebook versions are structured and incremented.

The guidebook is a normative artifact. Its versioning model is designed to preserve stability of the discipline’s core definitions while allowing controlled refinement of explanatory and guiding content.

Versioning ensures that:

- Normative claims remain reproducible.
- Compliance assessments can reference stable definitions.
- The discipline can evolve without silent drift.
- Readers can distinguish between structural change and editorial refinement.


## Major version lines and lifecycle states

Each **major version line** (vN.x.y) represents a distinct normative state of the discipline. It defines a stable configuration of Foundations against which validity and compliance may be assessed.

A major version line may exist in one of three sequential lifecycle states:

- **Next** — The forthcoming major version under development. It may be publicly visible (e.g., under `/next`) but does not constitute a normative reference.
- **Current** — The latest released major version line. It is the default normative reference and may receive minor and patch increments.
- **Prior** — A previously Current major version line. It remains normative and citable but is no longer the default reference. Its maintenance behavior is governed by the Maintenance model.

Only released major version lines (Current or Prior) constitute normative references.


## Version number structure

Versions are expressed as MAJOR.MINOR.PATCH.

Within a given major version line:

- A **minor version** represents a refinement of that major version. It incorporates clarifications or non-normative improvements while preserving the normative state defined by the major version.
- A **patch version** represents an editorially corrected state of a minor version. It addresses defects in expression without affecting interpretation or validity conditions.

A change in the MAJOR component establishes a new major version line and therefore a new normative state.

A change in the MINOR component introduces refinements or clarifications that do not alter validity conditions.

A change in the PATCH component applies editorial corrections that do not affect meaning.

Minor and patch increments do not establish a new normative state. Version increments are determined by the nature of the change, not by its size.


## Major version increments

A major version increment is required when changes alter the normative core of the discipline.

This includes:

- Modifications to formal definitions in **Foundations**.
- Changes to the **Metamodel**.
- Changes to transformation **Plays**.
- Any alteration that affects validity conditions.

Upon release of a new major version line:

- The new version becomes **Current**.
- The previously Current version becomes **Prior**.


## Minor version increments

A minor version increment is required for changes that do not alter the normative core but affect interpretation, explanation, or guidance.

This includes:

- Clarifications within Foundations that do not change validity conditions.
- Changes to Motivation, Guidelines, or Resources.
- Additions of informative material.
- Structural refinements that do not modify normative meaning.

Minor increments apply only within the **Current** major version line and are recorded with an explicit version note.


## Patch increments

Patch increments are reserved for editorial corrections that do not affect meaning.

This includes:

- Typographical errors.
- Formatting corrections.
- Broken links.
- Non-substantive editorial fixes.

Patch increments may apply within Current and, subject to the Maintenance model, within Prior major version lines.

Patch increments do not introduce normative or interpretive change.


## Preview and forthcoming versions

Work on a forthcoming major version line occurs in the **Next** state.

A preview of the forthcoming major version line may be made available under the dedicated path `/next`.

Preview versions do not constitute normative references. Normative claims must refer to a released major version line.


## Archival and citation

All released major version lines remain accessible.

Normative claims, compliance assessments, and scholarly references must specify the major version to which they refer.


## Summary

The guidebook follows a structured MAJOR.MINOR.PATCH versioning model.

- Each major version line defines a distinct normative state.
- Minor and patch increments refine a major version line without redefining its normative core.
- Major version lines progress through the states Next → Current → Prior.
- Maintenance behavior for Prior versions is defined separately in the Maintenance model.

This model preserves normative stability while allowing controlled evolution of the guidebook.


## Where to go next

→ **[Maintenance model](../maintenance-model/)**  
  Defines how Prior major version lines are maintained and when maintenance may be closed.

→ **[Release discipline](../release-discipline/)**  
  Defines release criteria, authorization requirements, and publication cadence.

↑ **[Lifecycle governance](../)**  
  Defines the rules governing versioning, release discipline, deprecation, and controlled evolution of the guidebook.

↑ **[Guidebook governance](../../)**  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.