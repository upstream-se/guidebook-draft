# Navigation format

> This page defines the rendering rules and traversal order governing hierarchical navigation in the guidebook.

Navigation format regulates how pages in the primary hierarchy expose canonical traversal through the “Where to go next” section.

Navigation format governs hierarchical movement only.  It does not regulate contextual cross-references or complementary linkage.


## Scope

This page defines:

- The purpose of the “Where to go next” section.
- The rendering format of navigation entries.
- The fixed traversal order.
- Inclusion and omission rules.
- Ancestor listing discipline.

Non-hierarchical references are governed separately.

↗ See **[Cross-reference conventions](../../../editorial-governance/cross-reference-conventions/)** for the rules governing contextual and complementary references.


## Purpose of hierarchical navigation

The “Where to go next” section:

- Encodes canonical traversal of the primary hierarchy.
- Makes containment and sequence explicit.
- Prevents implicit structural jumps.
- Ensures predictable reader movement.

Hierarchical navigation must remain stable across revisions.


## Rendering format

Each navigation entry is a two-line block:

- Line 1 begins with an arrow symbol.
- The arrow is followed by a single space.
- A single bold link follows.
- The line ends with two trailing spaces.
- Line 2 contains the transformed descriptor.
- Line 2 is indented by two spaces.
- Entries are separated by a single empty line.
- No bullet list syntax is used.
- No additional labels are used.

Descriptors must be reused and transformed according to editorial rules.


## Traversal order

Entries must appear in the following sequence, omitting those that do not exist:

1. ↓ First contained page  
2. ← Previous sibling  
3. → Next sibling  
4. ↑ Parent  
5. ↑ Ancestor (repeated as necessary up to the root)

The order must not be altered.


## Inclusion rules

Only include entries that exist.

Do not:

- Display placeholders.
- Collapse ancestor levels.
- Skip intermediate ancestors.
- Include non-hierarchical references.

All ancestors must be listed explicitly in ascending order.  The final ancestor listed must be the root.


## Arrow semantics (hierarchical)

The following arrows are reserved exclusively for hierarchical navigation:

- ↓ First contained page  
- ← Previous sibling  
- → Next sibling  
- ↑ Parent or ancestor  

These arrows must not be used for contextual or complementary references.


## Structural constraints

The “Where to go next” section must:

- Be the final section of the page.
- Appear exactly once.
- Preserve traversal predictability.
- Remain independent from editorial or contextual links.

Complementary and contextual references must not appear in this section.


## Summary

Navigation format defines the canonical rendering and ordering rules for hierarchical traversal within the guidebook.  It preserves structural clarity, enforces explicit ancestry, and ensures predictable navigation through the primary hierarchy.


## Where to go next

← **[Filesystem conventions](../filesystem-conventions/)**  
  Defines the naming and layout rules governing page directories and files in the repository.

↑ **[Information architecture](../)**  
  Defines how knowledge is organized, structured, and navigated within the guidebook.

↑ **[Structural governance](../../)**  
  Defines the structural rules that regulate page types, hierarchy, and navigation in the guidebook.

↑ **[Guidebook governance](../../../)**  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.
