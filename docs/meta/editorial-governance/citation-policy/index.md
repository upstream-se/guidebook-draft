# Citation policy

> This page defines the citation and bibliographic rules governing references in the guidebook.

Citations in the guidebook serve two purposes: epistemic grounding and traceability.  Normative and analytical claims must be supported by identifiable and verifiable sources when they depend on prior work.  This page defines how citations are inserted in content pages and how bibliographic entries are structured in the bibliography page.


## When citations are required

Citations are required when:

- Referencing empirical research or established theoretical results.
- Attributing definitions, models, standards, or terminology to specific sources.
- Quoting or closely paraphrasing another work.
- Making claims about the state of research or industry practice.

Citations are not required for:

- Internal conceptual definitions introduced by the guidebook.
- Structural navigation statements.
- Purely descriptive statements about the guidebook itself.


## In-text citation format

In-text citations must:

- Appear immediately after the supported statement.
- Use author-year format.
- Link to the corresponding anchor in the bibliography page.

Format:

`([Surname, Year](../resources/bibliography/#surname-year))`

Examples:

- Single author:  
  `([Lehman, 2003](#lehman-2003))`

- Two authors:  
  `([Lehman & Ramil, 2003](#lehman-ramil-2003))`

- Three or more authors:  
  `([Digkas et al., 2022](#digkas-etal-2022))`

- Institutional author:  
  `([American Psychological Association, 2020](#american-psychological-association-2020))`


## Bibliography formatting standard

References cited across the guidebook are consolidated on the Bibliography page.  Entries are listed in alphabetical order by the surname of the first author and formatted according to APA 7 ([American Psychological Association, 2020](#american-psychological-association-2020)).  Each entry includes sufficient publication metadata to enable identification and independent verification.

Each bibliography entry must include:

- A stable HTML anchor identifier.
- Full author list as required by APA 7.
- Year of publication.
- Full title.
- Venue (journal, conference, publisher).
- Volume, issue, and page range when applicable.
- DOI as a clickable URL (https://doi.org/...).


## Anchor identifier rules

Each bibliography entry must include:

```html
<a id="..."></a>
```

Anchor identifiers must:

- Be lowercase.
- Use hyphen-separated tokens.
- Contain only letters, digits, and hyphens.

Pattern rules:

- One author:  
  `surname-year`

- Two authors:  
  `surname1-surname2-year`

- Three or more authors:  
  `surname1-etal-year`

- Institutional author:  
  `institution-name-year`

If disambiguation is required, append `a`, `b`, etc., after the year (e.g., `smith-2020a`, `smith-2020b`).


## DOI requirements

If a DOI exists, it must be included as a clickable URL:

`https://doi.org/...`

The DOI must be verified and must correspond exactly to the cited publication.


## Normative compliance

Pages that introduce normative claims grounded in external work must include appropriate citations.  Missing or unverifiable citations constitute a compliance defect.

Bibliographic entries that do not follow APA 7 formatting, omit required metadata, or lack valid anchor identifiers are non-compliant.


## Summary

This page is reserved for defining citation discipline in the guidebook.  It will specify attribution requirements, citation formats, and reference management rules.


## Where to go next

← **[Version annotation discipline](../version-annotation-discipline/)**  
  Defines how version notes and change annotations are expressed within pages.

↑ **[Editorial governance](../)**  
  Defines the standards governing terminology, language, formatting, referencing, and stylistic discipline in the guidebook.

↑ **[Guidebook governance](../../)**  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.
