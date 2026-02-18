# Page

> This page defines the base structural type that governs all pages in the guidebook.

Page is the fundamental structural unit of the guidebook.  All other page types specialize this type and inherit its structural invariants.

A Page defines how content is organized, identified, and navigated within the guidebook.


## Structural invariants

Every Page must:

- Begin with a single H1 title.
- Include a descriptor callout immediately after the title.
- Contain substantive body content.
- Conclude with a “Where to go next” section.
- Comply with navigation rendering rules.
- Comply with cross-reference conventions.
- Comply with callout usage rules.

These invariants ensure structural consistency across the guidebook.


## Descriptor

Every Page must include a descriptor callout of the form:

> This page <verb> <object>.

The descriptor:

- Must be a single sentence.
- Must be declarative.
- Must describe the structural or conceptual purpose of the page.
- Must remain stable across revisions unless the page scope changes.

↗ See **[Callout standard](../../../editorial-governance/callout-standard/)** for the normative system for structured callouts used throughout the guidebook.

↗ See **[Cross-reference conventions](../../../editorial-governance/cross-reference-conventions/)** for how descriptors are transformed in navigation and contextual cross-links.


## Navigation

A Page must conclude with a “Where to go next” section rendered according to the Navigation format.

The navigation section:

- Must appear as the final section of the page.
- Must follow the prescribed arrow order.
- Must transform descriptors according to the defined rules.
- Must omit entries that do not exist.

↗ See **[Navigation format](../../information-architecture/navigation-format/)** for the rendering rules of the “Where to go next” section.


## Specialization

Page serves as the base type for all structural page roles.

It is specialized into:

- Container page
- Content page
- Complementary page

Specialized page types inherit these invariants and may introduce additional constraints appropriate to their structural role.

↗ See **[Content model](../)** for the structural types of pages and their specialization rules within the guidebook.


## Summary

Page establishes the structural invariants that govern all pages in the guidebook.  It defines the minimal requirements for title, descriptor, body content, and navigation, ensuring consistent organization and traversal across the guidebook.


## Where to go next

→ **[Container page](../container-page/)**  
  Defines pages that aggregate and contextualize contained pages within the primary hierarchy.

↑ **[Content model](../)**  
  Defines the structural types of pages and their specialization rules within the guidebook.

↑ **[Structural governance](../../)**  
  Defines the structural rules that regulate page types, hierarchy, and navigation in the guidebook.

↑ **[Guidebook governance](../../../)**  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.
