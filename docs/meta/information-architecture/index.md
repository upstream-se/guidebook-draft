# Information architecture

> This page defines how knowledge is organized, structured, and navigated within the guidebook.

Information architecture governs the structural topology of the guidebook.  It determines how pages relate through containment, sequencing, and traversal.

The guidebook is neither a linear book nor an unrestricted wiki.  It is a directed structure whose primary organization is hierarchical, while allowing disciplined graph extensions through cross-reference.

Information architecture ensures structural coherence, predictable navigation, and conceptual clarity.


## Structural model

The guidebook is organized around a primary hierarchy.

- The hierarchy has a single root.
- Every page in the primary structure has exactly one parent, except the root.
- Pages may contain other pages.
- Containment defines canonical traversal order.

Each page in the primary hierarchy must:

- Correspond to a directory containing an `index.md` file.
- Participate in canonical navigation through the “Where to go next” section.
- Preserve ordered traversal semantics.

The hierarchy encodes structural dependency, not merely thematic grouping.


## Graph extensions

Beyond containment, the guidebook allows non-hierarchical relationships.

These include:

- Contextual cross-references.
- Complementary auxiliary pages.

Such relationships must not alter the primary hierarchy.  They are governed by editorial rules.

↗ See **[Cross-reference conventions](../../editorial-governance/cross-reference-conventions/)** for the rules governing non-hierarchical references.


## Navigation principles

Hierarchical navigation must:

- Be predictable.
- Follow a fixed order.
- Preserve explicit ancestor listing.
- Avoid implicit traversal.

The “Where to go next” section encodes canonical movement within the hierarchy.

↗ See **[Navigation format](./navigation-format/)** for the rendering and ordering rules governing hierarchical navigation.


## Hierarchy and filesystem correspondence

The primary hierarchy maps directly to the repository structure.

- Each page corresponds to a directory.
- The page content resides in `index.md`.
- Contained pages reside in subdirectories.
- Complementary pages reside in the same directory as the page they supplement.

Editorial grouping may be introduced within listing sections for clarity, but it does not create additional hierarchy.

Structural containment and repository layout must remain aligned.


## Structural responsibilities

Information architecture must:

- Prevent artificial depth.
- Avoid redundant containment.
- Preserve bounded conceptual scopes.
- Ensure that structural nodes carry conceptual meaning.

If a grouping lacks conceptual responsibility, it must not become a structural node.


## Structural subdomains

- **[Navigation format](./navigation-format/)**  
  Defines the rendering rules and traversal order for hierarchical navigation.

Additional subdomains may be introduced if new structural responsibilities are defined.


## Where to go next

↓ **[Navigation format](./navigation-format/)**  
  Defines the rendering rules and traversal order for hierarchical navigation.

← **[Content model](../content-model/)**  
  Defines the structural types of pages and their specialization rules within the guidebook.

→ **[Concept taxonomy](../concept-taxonomy/)**  
  Defines the classification rules governing conceptual entities within the guidebook.

↑ **[Structural governance](../)**  
  Defines the structural rules that regulate page types, hierarchy, and navigation in the guidebook.

↑ **[Guidebook governance](../../)**  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.