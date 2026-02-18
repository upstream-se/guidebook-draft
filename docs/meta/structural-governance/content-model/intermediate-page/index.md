# Intermediate page

> This page defines the structural obligations of pages that contain other pages in the primary hierarchy.

An intermediate page is a tree node that directly contains other tree nodes.  It contributes conceptual content while also serving as a structural container.

Intermediate pages are part of the primary hierarchy.  They must balance substantive exposition with structural indexing.


## Definition

An intermediate page is a page that:

- Has one or more contained pages in the primary hierarchy.
- Corresponds to a directory containing an `index.md` file.
- Lists its contained pages using the descriptor reuse convention.
- Provides canonical navigation through the “Where to go next” section.

An intermediate page is not merely a listing.  It must provide conceptual framing for its contained pages.


## Structural obligations

An intermediate page must include:

- A descriptor callout immediately after the H1 title.
- One or more substantive sections introducing its conceptual scope.
- A section that enumerates the pages directly contained within it.
- A “Where to go next” section at the end of the page.

The section that enumerates contained pages must:

- Use bold links.
- Reuse the child descriptor without the phrase “This page”.
- Preserve indentation discipline.
- Avoid paraphrasing the descriptor.

The section title used for listing contained pages must be conceptually meaningful.  It must not be mechanically titled “Contained pages” unless such wording is substantively appropriate.


## Conceptual responsibility

An intermediate page must provide:

- Conceptual orientation for its domain.
- Clarification of scope and boundaries.
- Explanation of how contained pages relate to each other.

It must not:

- Exist solely to split a long list.
- Introduce artificial hierarchy.
- Duplicate content from its contained pages.


## Relationship with editorial grouping

Editorial grouping within the contained-page listing is permitted.  Groups may be introduced to improve readability or thematic clarity.

However, editorial groups:

- Do not imply additional hierarchy.
- Do not require corresponding directories.
- Do not create additional tree nodes.
- Must not alter navigation structure.

Grouping is rhetorical, not structural.


## Navigation format

The “Where to go next” section must use a fixed order and a fixed rendering format.  Each navigation entry must include the linked page descriptor.

Rendering format:

Each navigation entry is a two-line block.

Line 1 begins with an arrow symbol, followed by a single space, followed by a single link, and ends with two spaces.

Line 2 contains the linked page descriptor, indented by two spaces.

The descriptor must reuse the linked page descriptor by removing the leading phrase “This page”.  The remainder of the sentence must not be paraphrased.

Each entry must be separated from the next entry by a single empty line.

No bullet list syntax is used.  No additional labels are used.

Order:

Entries must appear in the following sequence, omitting those that do not exist:

↓ First contained page

← Previous sibling

→ Next sibling

↑ Parent

↑ Ancestor  
(Repeated as necessary up to the root)

Rules:

Only include entries that exist.  Do not display placeholders.

Preserve the order defined above.

List all ancestors explicitly in ascending order.  The last ancestor listed is the root.

The section must be the final section of the page.

Complementary pages and contextual cross-links must not appear in this section.  They must be placed contextually within the page body.


## Where to go next

→ [Leaf page](../leaf-page/)  
  Defines the structural obligations of pages that do not contain child pages in the primary hierarchy.

↑ [Content model](../)  
  Defines the page types, structural obligations, and specialization rules that govern how content is constructed in the guidebook.

↑ [Structural governance](../../)  
  Defines the structural rules that govern how the guidebook is organized, modeled, and navigated.

↑ [Guidebook governance](../../../)  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.
