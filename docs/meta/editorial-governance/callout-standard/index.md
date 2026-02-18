# Callout standard

> This page defines the normative system for structured callouts used throughout the guidebook.

Callouts provide a controlled mechanism for expressing structured statements, formal classifications, lifecycle annotations, and structural warnings.  The system is intentionally minimal, academically neutral, and symbolically disciplined.

Callouts are structural instruments.  They are not decorative elements.


## Page descriptor callout

Every page must begin with a descriptor callout immediately after the H1 title.

Format:

> This page defines ...

Rules:

- No symbol.  
- No title.  
- Single sentence.  
- Must describe the purpose of the page.  
- Must begin with “This page …”.  
- Must be reused verbatim, minus the phrase “This page”, when referencing the page elsewhere.  

Example:

> This page defines the governance framework of the guidebook.

The descriptor callout is mandatory for all pages.


## Structured callouts

Structured callouts use the filled square symbol.

Symbol:

■

Format:

> ■ **Title**  
> Content...

The title determines semantic meaning.  The symbol remains constant.

Common titles include:

- Definition  
- Principle  
- Classification  
- Requirement  

Rules:

- The symbol must always precede the title.  
- The title must be bold.  
- The content must be structurally precise and self-contained.  
- Structured callouts must not contain historical annotations.  

Example:

> ■ **Definition**  
> A software system is ...


## Version annotation callouts

Version annotations use the empty square symbol.

Symbol:

□

Format:

> □ **Since v2.3**  
> Complementary links were removed from the final navigation section.

Other acceptable forms:

> □ **Introduced in v1.0**  
> ...

> □ **Amended in v2.4**  
> ...

Rules:

- The version must be specified.  
- The callout must appear immediately after the affected statement or section.  
- Version annotations must not introduce new normative content.  
- Version annotations serve historical and traceability purposes only.  

Version annotations are informational, not prescriptive.


## Warning callouts

Warnings use the warning symbol.

Symbol:

⚠

Format:

> ⚠ **Warning**  
> This page is under active construction.

Warnings are reserved for:

- Structural instability.  
- Substantial incompleteness.  
- Transitional states.  

Rules:

- Warnings must be rare.  
- Warnings must be temporary.  
- Warnings must not be used to signal ordinary draft content.  

Warnings signal structural or governance risk.


## Deprecation callouts

Deprecated content is explicitly marked.

Symbol:

⛔

Format:

> ⛔ **Deprecated since v2.1**  
> This concept is retained for traceability and should not be used in new material.

Rules:

- The deprecation version must be specified.  
- Deprecated content must remain visible unless formally removed by policy.  
- Deprecation callouts must not alter the original normative meaning.  


## Usage discipline

The following rules apply to all callouts:

1. Do not stack more than two callouts consecutively.  
2. Do not use callouts for stylistic emphasis.  
3. Place callouts immediately after the section or paragraph they formalize.  
4. Use consistent titles across the guidebook.  
5. Do not mix structured and version annotations in the same callout.  
6. Maintain visual restraint.  

Callouts formalize structure.  They must remain minimal and semantically controlled.


## Where to go next

← **[Formatting standard](../formatting-standard/)**  
  Defines spacing, heading conventions, capitalization, punctuation, and micro-typographic rules.

→ **[Cross-reference conventions](../cross-reference-conventions/)**  
  Defines how internal links and cross-references are written and formatted.

↑ **[Editorial governance](../)**  
  Defines the standards governing terminology, language, formatting, referencing, and stylistic discipline in the guidebook.

↑ **[Guidebook governance](../../)**  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.
