# Release discipline

> This page defines the criteria, authorization requirements, and publication rules governing guidebook releases.

Release discipline regulates when and how new versions of the guidebook are formally published.

Its purpose is to:

- Prevent premature or uncontrolled releases.
- Ensure that normative changes are deliberate and reviewable.
- Guarantee transparency of lifecycle transitions.
- Maintain coherence across version lines.


## Scope of release discipline

Release discipline governs:

- Authorization of major releases.
- Authorization of minor and patch releases.
- Lifecycle state transitions (Next → Current → Prior).
- Declaration of maintenance windows.
- Publication and communication obligations.

It does not define version numbering semantics or maintenance rules.  Those are defined in the Versioning and Maintenance models.


## Major releases

A major release establishes a new major version line and therefore a new normative state.

A major release may occur only when:

- Changes affecting the normative core (Foundations) have been finalized.
- The Metamodel and Plays are internally consistent.
- Cross-references and structural coherence have been validated.
- Release documentation has been prepared.

Upon release of version N+1:

- N+1 becomes **Current**.
- The previously Current version N becomes **Prior** and enters maintenance status.
- The maintenance status of previous Prior versions that are still in maintenancs (surely N-1, may be N-2 and earlier) must be decided and declared.

Major releases must be explicitly authorized according to Operational governance.


## Minor releases

A minor release refines the Current major version line without altering its normative state.

A minor release may occur when:

- Clarifications are introduced.
- Informative or guiding content is added or improved.
- Structural refinements are applied that do not affect validity conditions.

Minor releases apply only to the Current major version line.


## Patch releases

A patch release applies editorial corrections that do not affect meaning.

Patch releases may apply to:

- The Current major version line.
- Prior major version lines that are under maintenance.

Patch releases do not require full release review but must be logged.


## Declaration obligations

At each major release, the following must be explicitly declared:

- The new Current major version line.
- The Prior major version line.
- Which Prior version lines remain under maintenance.
- Which Prior version lines become immutable.

These declarations must be documented in the Change log.


## Publication and visibility

A release is considered valid only when:

- The version identifier is updated.
- The content is published under the appropriate path.
- Lifecycle state transitions are reflected in navigation.
- The Change log has been updated.

Preview versions under `/next` do not constitute released versions.


## Summary

Release discipline governs when and how versions of the guidebook are formally established.

- Major releases create new normative states.
- Minor releases refine the Current version.
- Patch releases correct defects.
- Lifecycle transitions and maintenance declarations occur only at major releases.
- All releases must be authorized and documented.

This discipline ensures controlled, transparent evolution of the guidebook.


## Where to go next

← **[Maintenance model](../maintenance-model/)**  
  Defines how Prior major version lines are maintained and when maintenance may be closed.

→ **[Quality assurance](../quality-assurance/)**  
  Defines validation and readiness criteria applied before release.

↑ **[Lifecycle governance](../)**  
  Defines the governance framework regulating versioning, maintenance, release, and controlled evolution of the guidebook.

↑ **[Guidebook governance](../../)**  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.
