# Container page template

> This page provides the canonical Markdown template for container pages in the primary hierarchy.

This template must be used when creating a new Container page.  It enforces structural obligations defined in the Content model and Navigation format.

↗ See **[Container page](../../structural-governance/content-model/container-page/)** for the structural obligations of container pages.

↗ See **[Navigation format](../../structural-governance/information-architecture/navigation-format/)** for the rendering rules governing hierarchical navigation.


## Template

Copy and adapt the following template.

```markdown
# {{Container page title}}

> This page {{defines|explains|presents}} {{domain or scope of the container page}}.

Introductory text.

This introduction explains the purpose, scope, and structural position of the page within the primary hierarchy.


## {{Conceptual section title}}

Substantive content belonging to this container page.

This section provides conceptual framing for the contained pages.

Additional sections may be added as necessary.


## {{Another conceptual section title}}

Additional substantive content belonging to this container page.


## {{Contained pages section title}}

Brief explanation of grouping if necessary.

### {{Group title}}

- **[{{Child page 1}}](./{{child-page-1}}/)**  
  {{Transformed descriptor of child page 1}}

- **[{{Child page 2}}](./{{child-page-2}}/)**  
  {{Transformed descriptor of child page 2}}


### {{Another group title}}

- **[{{Child page 3}}](./{{child-page-3}}/)**  
  {{Transformed descriptor of child page 3}}


## Where to go next

↓ **[{{Child page 1}}](./{{child-page-1}}/)**  
  {{Transformed descriptor of child page 1}}

← **[{{Previous sibling}}](../{{previous-sibling}}/)**  
  {{Transformed descriptor of previous sibling}}

→ **[{{Next sibling}}](../{{next-sibling}}/)**  
  {{Transformed descriptor of next sibling}}

↑ **[{{Parent page}}](../)**  
  {{Transformed descriptor of parent page}}

↑ **[{{Ancestor page}}](../../)**  
  {{Transformed descriptor of ancestor page}}

↑ **[{{Guidebook governance}}](../../../)**  
  {{Transformed descriptor of root}}

```

Notes for contributors:
- Remove navigation entries that do not exist.
- Do not reorder navigation entries.
- Do not paraphrase descriptors.
- Replace all placeholders before publication.
-Do not include complementary or contextual links in the “Where to go next” section.


## Summary

The Container page template provides a canonical scaffold for creating container pages.  It ensures consistent structure, disciplined child listing, and compliant hierarchical navigation.


## Where to go next

↑ **[Templates](../)**  
  Defines the canonical authoring templates used to instantiate structurally compliant pages in the guidebook.

↑ **[Operational governance](../../)**  
  Defines the processes, instruments, and decision mechanisms governing how issues and changes to the guidebook are proposed, reviewed, classified, and authorized.

↑ **[Guidebook governance](../../../)**  
  Defines the governance framework that regulates the structure, authorship, evolution, and authority of the guidebook.
