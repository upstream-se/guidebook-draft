# Cross-reference conventions

> This page defines the normative rules governing non-hierarchical references between pages in the guidebook.

Cross-references connect pages outside hierarchical containment.  They express conceptual relationships that are not represented through parent, sibling, or child navigation.

Cross-references must remain disciplined.  They must not duplicate structural traversal or introduce implicit hierarchy.


## Scope

This page regulates:

- Descriptor transformation when referencing other pages.
- Contextual cross-links between independent pages.
- Complementary linkage between a primary page and its auxiliary page.
- Arrow semantics for non-hierarchical references.

Hierarchical navigation is defined separately.

↗ See **[Navigation format](../../structural-governance/information-architecture/navigation-format/)** for the rules governing hierarchical traversal.


## Descriptor transformation rule

When referencing another page outside hierarchical navigation:

- The descriptor callout must be reused.
- The leading phrase “This page” must be removed.
- The remainder of the sentence must not be paraphrased.

Example descriptor:

> This page defines the structural obligations of pages that deepen or supplement another page.

Transformed form:

the structural obligations of pages that deepen or supplement another page

Descriptor reuse preserves semantic precision across references.


## Contextual cross-links

Contextual cross-links express related material without structural attachment.

Format:

↗ See **[Page]** for <transformed-descriptor>

Rules:

- Must use the arrow ↗.
- Must use the verb “See”.
- Must include the transformed descriptor.
- Must appear within the body of the page.
- Do not imply containment, sequencing, or reciprocity.

Contextual cross-links are exploratory and optional.


## Complementary linkage

Complementary linkage expresses structured auxiliary attachment between a primary page and a complementary page.

Complementary relationships are intentional and reciprocal.


### From the primary page

Format:

↘ Refer to **[Complementary page]** for <transformed-descriptor>

Rules:

- Must use the arrow ↘.
- Must use the verb “Refer to”.
- Must include the transformed descriptor.
- Must appear within the body of the primary page.
- Must have a corresponding return link on the complementary page.


### From the complementary page

Complementary pages must replace hierarchical navigation with a single contextual return entry.

Format:

↖ Return to **[Primary page]** for <transformed-descriptor>

Rules:

- Must use the arrow ↖.
- Must use the verb “Return to”.
- Must include the transformed descriptor.
- Must appear in the “Where to go next” section.
- Must be the only entry in that section.


## Misuse prevention

Cross-reference mechanisms must not:

- Duplicate hierarchical navigation.
- Create implicit structural containment.
- Introduce reciprocal obligations outside complementary linkage.
- Replace proper structural modeling.

If a relationship becomes structurally essential, it must be represented in the primary hierarchy rather than through cross-reference.


## Summary

Cross-reference conventions regulate non-hierarchical relationships between pages.  They define descriptor transformation discipline, contextual linking rules, and the reciprocal complementary linkage system.


## Where to go next

← **[Callout standard](../callout-standard/)**  
  Defines the visual and semantic conventions for descriptor, warning, version, deprecated, and other callouts.

→ **[Version annotation discipline](../version-annotation-discipline/)**  
  Defines how version notes and change annotations are expressed within pages.

↑ **[Editorial governance](../)**  
  Defines the standards governing terminology, language, formatting, referencing, and stylistic discipline in the guidebook.

↑ **[Guidebook governance](../../)**  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.
