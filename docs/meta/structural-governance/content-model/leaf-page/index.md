# Leaf page

> This page defines the structural obligations of pages that do not contain child pages in the primary hierarchy.

A leaf page is a terminal node in the primary hierarchy.  It does not contain other tree nodes.  Its responsibility is to fully develop a defined conceptual unit.

Leaf pages are content-complete units.  They provide exposition, clarification, and synthesis within a bounded scope.


## Definition

A leaf page is a page that:

- Does not contain child pages in the primary hierarchy.
- Corresponds to a directory containing an `index.md` file.
- May contain complementary pages in the same directory.
- Must provide a complete treatment of its conceptual scope.

A leaf page is structurally terminal but conceptually substantive.


## Structural obligations

A leaf page must include:

- A descriptor callout immediately after the H1 title.
- One or more substantive sections developing its conceptual content.
- A section titled “Summary”.
- A “Where to go next” section at the end of the page.

A leaf page must not include a section that lists contained pages in the primary hierarchy.


## Conceptual responsibility

A leaf page must:

- Clearly define or develop its conceptual object.
- Maintain a bounded scope.
- Avoid introducing artificial hierarchy.

A leaf page may reference complementary pages contextually within its content.  Such references must not appear in the “Where to go next” section.


## Relationship with complementary pages

Complementary pages may reside in the same directory as a leaf page.  They deepen, justify, or contextualize the leaf page content.

Complementary pages are not part of the primary hierarchy.  Their presence does not alter the leaf page status.


## Navigation constraints

The “Where to go next” section of a leaf page must preserve canonical traversal of the primary hierarchy.  It must not include complementary pages or contextual cross-links.

It must include, when applicable:

- The previous sibling page.
- The next sibling page.
- The parent page.
- Each ancestor in the hierarchy, up to the root.


## Navigation format

The “Where to go next” section must use a fixed order and a fixed rendering format.  Each navigation entry must include the linked page descriptor.


### Rendering format

Each navigation entry is a two-line block:

- Line 1 begins with an arrow symbol, followed by a single space, followed by a single bold link, and ends with two spaces.
- Line 2 contains the linked page descriptor, indented by two spaces.
- The descriptor must reuse the linked page descriptor by removing the leading phrase “This page”.  The remainder of the sentence must not be paraphrased.
- Each entry must be separated from the next entry by a single empty line.
- No bullet list syntax is used in the navigation section itself.
- No additional labels are used.


### Order

Entries must appear in the following sequence, omitting those that do not exist:

- ← Previous sibling
- → Next sibling
- ↑ Parent
- ↑ Ancestor  
  (Repeated as necessary up to the root)


### Rules

- Only include entries that exist.  Do not display placeholders.
- Preserve the order defined above.
- List all ancestors explicitly in ascending order.  The last ancestor listed is the root.
- The section must be the final section of the page.
- Complementary pages and contextual cross-links must not appear in this section.  They must be placed contextually within the page body.


## Summary

A leaf page is a terminal node in the primary hierarchy.  It does not contain child pages and must provide a complete treatment of its conceptual scope.  Leaf pages must include a “Summary” section and the canonical “Where to go next” section, while referencing complementary pages only contextually within the page body.


## Where to go next

← **[Intermediate page](../intermediate-page/)**  
  Defines the structural obligations of pages that contain other pages in the primary hierarchy.

→ **[Complementary page](../complementary-page/)**  
  Defines the structural role and placement rules for pages that deepen or contextualize a tree node without belonging to the primary hierarchy.

↑ **[Content model](../)**  
  Defines the page types, structural obligations, and specialization rules that govern how content is constructed in the guidebook.

↑ **[Structural governance](../../)**  
  Defines the structural rules that govern how the guidebook is organized, modeled, and navigated.

↑ **[Guidebook governance](../../../)**  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.
