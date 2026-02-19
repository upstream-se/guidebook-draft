# Filesystem conventions

> This page defines the naming and layout rules governing page directories and files in the repository.

The primary hierarchy of the guidebook maps directly to the repository structure.  Naming discipline ensures stability, predictability, and URL coherence.

Filesystem conventions are structural.  They must remain stable across versions.


## Scope

This page defines:

- Directory naming rules.
- File naming rules.
- Slug transformation rules.
- Correspondence between page titles and filesystem identifiers.


## Directory structure

Each page in the primary hierarchy must correspond to a directory.

- The directory must contain an `index.md` file.
- The directory name must represent the page title in normalized form.
- Contained pages must reside in subdirectories.

Example:

Page title:

Information architecture

Directory:

information-architecture/

File:

information-architecture/index.md


## Complementary pages

Complementary pages differ structurally.

- They do not create subdirectories.
- They reside in the same directory as the page they complement.
- They are individual `.md` files.
- They must follow the same naming normalization rules.

Example:

Primary page directory:

concept-definition/

Complementary page file:

concept-definition/formal-specification.md


## Naming normalization rule

Given a page title in sentence case:

- Convert all characters to lowercase.
- Replace spaces with hyphens.
- Remove punctuation.
- Use ASCII characters only.
- Do not introduce abbreviations.
- Preserve semantic clarity.

Examples:

Reader tree and meta tree  
→ reader-tree-and-meta-tree

Cross-reference conventions  
→ cross-reference-conventions

Navigation format  
→ navigation-format


## Stability requirements

Directory and file names:

- Must remain stable once published.
- Must not be renamed without versioned justification.
- Must not depend on editorial grouping.
- Must reflect structural hierarchy, not rhetorical structure.

If a title changes substantially, the slug must be evaluated for structural impact.


## Relationship with information architecture

Filesystem conventions operationalize the primary hierarchy.

The repository structure must mirror:

- Containment relationships.
- Page types.
- Complementary placement rules.

↗ See **[Information architecture](../)** for the structural rules governing hierarchy.


## Summary

Filesystem conventions ensure that page titles, directories, and files map predictably and consistently.  Titles in sentence case must be normalized to lowercase kebab-case for directory and file names.  The repository structure must remain aligned with the primary hierarchy.


## Where to go next

← **[Reader tree and meta tree](../reader-tree-and-meta-tree/)**  
  Defines the dual-tree structure of the guidebook and clarifies the separation between reader-facing content and contributor-facing governance.

→ **[Navigation format](../navigation-format/)**  
  Defines the rendering rules and traversal order governing hierarchical navigation in the guidebook.

↑ **[Information architecture](../)**  
  Defines how knowledge is organized, structured, and navigated within the guidebook.

↑ **[Structural governance](../../)**  
  Defines the structural rules that regulate page types, hierarchy, and navigation in the guidebook.

↑ **[Guidebook governance](../../../)**  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.
