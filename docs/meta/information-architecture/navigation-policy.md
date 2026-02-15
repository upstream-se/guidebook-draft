# Navigation Policy — “Where to go next”

This page defines the structural and wording rules governing the **“Where to go next”** section that appears at the end of conceptual pages in the guidebook.

The purpose of this section is to:

- maintain a coherent reading path through the guidebook,
- make the page graph explicit and disciplined,
- distinguish the primary tree traversal from alternative navigational edges, and
- ensure consistent phrasing and reader expectations.

## 1. Structural principles

Every content page must end with a section titled:

```md
## Where to go next
```

This section encodes navigation according to two different graph structures:

1. **The DFS traversal tree** — the canonical progression of the guidebook.
2. **Cross-links** — alternative edges in the page graph that do not belong to the DFS tree.

The section must reflect this distinction explicitly in wording.

## 2. Canonical progression (DFS edge)

If the page has a canonical successor in the DFS traversal of the guidebook, the first line must be:

```md
Continue to **[Next Page](./path.md)** for <descriptor>.
```

Rules:

- Use **“Continue to”** only for the canonical DFS successor.
- Only one page may be referenced using “Continue to”.
- The descriptor must briefly state what the reader will encounter on that page.
- The descriptor must follow the structure:

```md
for <concise conceptual description>
```

Example:

```md
Continue to **[Intent](./intent.md)** for the articulation of system-level commitments.
```

This line encodes the tree edge of the guidebook.

## 3. Alternative navigation (graph edges)

Additional links that are not part of the DFS traversal must follow the structure:

```md
Proceed to **[Page](./path.md)** for <descriptor>,
to **[Page](./path.md)** for <descriptor>,
or to **[Page](./path.md)** for <descriptor>.
```

Rules:

- Use **“Proceed to”** for all non-DFS links.
- Use commas between entries.
- Use “or” before the final entry.
- Do not use bullet lists.
- Do not use separate sentences.
- Each descriptor must be consistent across all references to that page.
- The phrase must always follow the pattern:

```md
Proceed to **[X]** for <descriptor>,
to **[Y]** for <descriptor>,
or to **[Z]** for <descriptor>.
```

## 4. Ancestor links

Each page must include links to its ancestors in the guidebook hierarchy:

- Immediate parent.
- Higher-level ancestor(s) up to the root.

Ancestor links are always introduced using “Proceed to”.

Example:

```md
Proceed to **[The discipline](./index.md)** for the conceptual structure of this part,
to **[Foundations](../index.md)** for the broader normative framework,
or to **[Guidebook](../../index.md)** for the complete guidebook structure.
```

Ancestor descriptors must remain consistent across all pages.

## 5. Descriptor consistency

Descriptors are part of the guidebook’s conceptual contract.

They must:

- be short,
- be stable across pages,
- avoid vague phrases such as “this part” or “overview”,
- describe what the reader will find, not what the page contains abstractly.

Example descriptor catalog:

- “the articulation of system-level commitments”
- “the definition of contextual knowledge”
- “the conceptual structure of this part”
- “the broader normative framework”
- “the complete guidebook structure”

If a descriptor changes, it must be updated consistently across all pages referencing that target.

## 6. Wording constraints

The section must:

- not use bullet points,
- not use horizontal rules,
- not use “Return to”,
- not imply that the reader previously visited a page,
- not use informal wording.

The tone must remain precise and directional.

## 7. Rationale

The “Where to go next” section serves three governance purposes:

1. It makes the intended reading order explicit.
2. It distinguishes tree structure from cross-links.
3. It stabilizes the conceptual map of the guidebook.

Navigation is treated as part of the guidebook’s normative structure, not as a cosmetic element.