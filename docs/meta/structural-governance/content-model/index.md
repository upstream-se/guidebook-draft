# Content model

> This page defines the page types, structural obligations, and specialization rules that govern how content is constructed in the guidebook.

The content model specifies how individual pages are structured and how different page types behave within the conceptual hierarchy.  It ensures consistency of composition, clarity of intent, and structural predictability across the entire guidebook.

The model distinguishes between tree nodes and complementary pages.  It also defines the obligations that intermediate and leaf pages must satisfy to preserve architectural coherence.


## Structural obligations

The content model establishes non-negotiable structural requirements that apply across page types.  These obligations preserve architectural invariants and prevent structural drift.

These include:

- The mandatory descriptor callout.
- The disciplined reuse of descriptors in child listings.
- The correct placement of the “Where to go next” section.
- The separation between structural navigation and contextual linking.
- The directory-per-node convention for tree nodes.

Additional obligations are specified within each page type definition.


## Page type specialization

The content model supports specialized page types that extend the base types defined in this section.  Specialized page types inherit the structural obligations of exactly one base type.

A specialized page type may introduce:

- Additional mandatory sections.
- Additional callout requirements.
- Additional structural constraints.
- Domain-specific rules.

However, a specialized page type must not:

- Remove mandatory sections required by its base type.
- Alter the placement or form of the descriptor callout.
- Modify the structural meaning of the “Where to go next” section.
- Violate the directory-per-node convention.

Specialization preserves architectural invariants while enabling domain-specific rigor.


## Relationship with information architecture

The content model operates in coordination with information architecture.  Information architecture defines the topology of the guidebook.  The content model defines how pages are constructed within that topology.

Topology governs relationships between pages.  Composition governs the internal structure of each page.


## Page types

### Base page types

- **[Intermediate page](./intermediate-page/)**  
  Defines the structural obligations of pages that contain other pages in the primary hierarchy.

- **[Leaf page](./leaf-page/)**  
  Defines the structural obligations of pages that do not contain child pages in the primary hierarchy.

- **[Complementary page](./complementary-page/)**  
  Defines the structural role and placement rules for pages that deepen or contextualize a tree node without belonging to the primary hierarchy.


### Specialized page types

This group is populated as specialized page types are introduced.

- None yet.


## Where to go next

↓ **[Intermediate page](./intermediate-page/)**  
  Defines the structural obligations of pages that contain other pages in the primary hierarchy.

← **[Information architecture](../information-architecture/)**  
  Defines the structural topology, navigation model, and relational conventions of the guidebook.

→ **[Concept taxonomy](../concept-taxonomy/)**  
  Defines the classification rules for conceptual entities in the guidebook.

↑ **[Structural governance](../)**  
  Defines the structural rules that govern how the guidebook is organized, modeled, and navigated.

↑ **[Guidebook governance](../../)**  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.
