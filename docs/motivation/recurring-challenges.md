# Recurring Challenges

The characteristics described in the **[Problem Space](./problem-space.md)** define the environment in which software systems exist and evolve.  Within this environment, a set of recurring patterns of difficulty arises across organizations, domains, and technological contexts.

These challenges are not isolated incidents or the result of individual mistakes.  They emerge as **systemic patterns** shaped by longevity, continuous change, organizational context, multiplicity of actors, shifting boundaries, and historical accumulation.

This page identifies and characterizes these recurring challenges.  It remains **diagnostic**: it does not propose solutions, prescribe practices, or establish norms.  Those concerns are addressed later in this guidebook.


## Implicit and Unexamined Decisions

Many decisions that shape a software system are made implicitly, without being explicitly articulated, examined, or recorded.  These include decisions about scope, boundaries, architectural assumptions, quality trade-offs, and acceptable forms of change.

Such decisions are often made under time pressure or as part of local problem solving. Once enacted, they become embedded in the system’s structure and behavior, even when they were never intended to be long-term commitments. Over time, these implicit decisions acquire normative force simply by having been made, a phenomenon that has been repeatedly observed in studies of architectural decision-making in practice ([Kruchten et al., 2015](../resources/bibliography.md#kruchten-etal-2015)).

The challenge is not that decisions are made implicitly, but that their implicit nature makes them difficult to question, revisit, or reinterpret as context changes.  As a result, later actors may inherit constraints without visibility into the assumptions that produced them.


## Loss of Intent and Rationale Over Time

Over time, the effects of implicit decisions are compounded by a second phenomenon: the gradual loss of the intent and rationale that originally justified them.

As software systems evolve, the original intent behind decisions often becomes inaccessible.  Design rationale, strategic motivations, and contextual assumptions may not be preserved, or may decay as individuals leave, documentation becomes outdated, or informal knowledge is lost. Research on design rationale and architectural knowledge has long observed that the reasons why decisions were made are often more fragile than the decisions themselves ([Perry & Wolf, 1992](../resources/bibliography.md#perry-wolf-1992); [van der Ven et al., 2006](../resources/bibliography.md#van-der-ven-etal-2006)). More recent studies confirm that architectural knowledge and decision rationale tend to decay or become inaccessible over time, a phenomenon sometimes described as architectural knowledge vaporization ([Capilla et al., 2016](../resources/bibliography.md#capilla-etal-2006)).

This loss of intent complicates later evolution.  When rationale is unavailable, changes must be made without knowing which assumptions remain valid, which constraints were deliberate, and which were incidental.  The challenge is therefore not merely one of missing documentation, but of diminished interpretability of the system’s current state.


## Fragmented Understanding of the Software System

In long-lived and multi-actor environments, understanding of a software system is typically fragmented.  Knowledge is distributed across people, teams, tools, documents, and codebases, with no single, stable point of synthesis.

Studies of large-scale and distributed development show that work is often partitioned across organizational and geographical boundaries, leading to partial and localized views of the system ([Herbsleb & Mockus, 2003](../resources/bibliography.md#herbsleb-mockus-2003); [Tamburri et al., 2018](../resources/bibliography.md#tamburri-etal-2018); [LaToza & Myers, 2010](../resources/bibliography.md#latoza-myers-2010)).  As actors change over time, these fragments are recombined imperfectly, if at all.

Fragmented understanding is not necessarily a failure of coordination or competence. It is a structural consequence of the problem space. However, it limits the ability to reason about the system as a whole, particularly when making decisions that span components, teams, or organizational boundaries, and when assessing the consequences of change beyond local modifications.


## Misalignment Between Intent and Realization

When understanding of the software system is fragmented across actors, artifacts, and time, divergence between intended direction and realized structure can emerge without being immediately recognized.

Over time, software systems may diverge from their original intent, even when they continue to function and deliver value. Strategic goals, architectural principles, or quality objectives articulated at one point in time may no longer be reflected in the system’s realized form.

This misalignment often emerges incrementally, through a sequence of locally rational changes made under evolving constraints.  No single modification may appear problematic in isolation, yet their cumulative effect can lead to a system whose structure and behavior no longer correspond to its stated or assumed intent ([de Silva & Balasubramaniam, 2012](../resources/bibliography.md#de-silva-balasubramaniam-2012); [Garcia et al., 2013](../resources/bibliography.md#garcia-etal-2013)).  Because this divergence persists across time and actors, it complicates reasoning about future change and the governance of the software system in a principled way.

The challenge here is not that systems change, but that changes occur without a clear basis for assessing whether the resulting system remains consistent with its intended role, scope, or constraints. This sets the stage for later questions of validity, without yet answering them.

This divergence often complicates efforts to evaluate and govern subsequent changes.


## Difficulty Governing Change

In environments characterized by continuous evolution, organizations often struggle to govern change effectively. Governance mechanisms may focus on process compliance, approval workflows, or control structures, without providing clear criteria for evaluating the substance of proposed changes.

As a result, it becomes difficult to determine which changes are acceptable, which are risky, and which undermine previously established intent. Decisions may be deferred, escalated, or justified retrospectively, rather than assessed against explicit and shared criteria ([ISO/IEC, 2015](../resources/bibliography.md#iso-38500-2015)).

The challenge is therefore not a lack of explicit governance mechanisms, but the absence of criteria grounded in a shared understanding of the software system and its evolving intent.  This difficulty is not primarily procedural; it reflects the absence of a stable and explicit basis for reasoning about change in relation to the system’s purpose, constraints, and context over time.


## Limited Ability to Revisit and Re-evaluate Decisions

Once decisions are embedded in a software system, they are often treated as irreversible.  Revisiting past decisions may be perceived as costly, risky, or outside the scope of ongoing work.

However, the inability to reconsider decisions is itself a recurring challenge.  As context changes, assumptions that were once valid may no longer hold.  Without structured means to re-evaluate earlier decisions, systems accumulate constraints that are no longer justified but remain operative.

This limitation concerns capability, not intent.  Even when organizations recognize the need to revisit decisions, they may lack the conceptual structures required to do so in a disciplined and non-disruptive way.  Empirical studies of architectural decision-making and technical debt show that decisions are frequently treated as irreversible, despite changing context and understanding ([Zimmermann et al., 2019](../resources/bibliography.md#zimmermann-etal-2019); [Kruchten et al., 2019](../resources/bibliography.md#kruchten-etal-2019)).


## Summary: Patterns of Recurring Challenges

The characteristics described in the **[Problem Space](./problem-space.md)** define the environment in which software systems exist and evolve.  Within this environment, a set of challenges arises repeatedly across organizations, domains, and technological contexts:

- implicit and unexamined decisions,
- loss of original intent and rationale over time,
- fragmentation of understanding of the software system,
- divergence between intent and realized structure,
- difficulty assessing and governing change,
- limited ability to revisit and re-evaluate past decisions.

These challenges are not anomalies or isolated failures. They are structural patterns that emerge from the conditions under which software systems exist and evolve.

They motivate the need for Upstream Software Engineering as a discipline capable of addressing upstream concerns explicitly. The next page examines why many existing approaches struggle to respond to these challenges.


## Where to go next

The next page, **[Limits of Current Approaches](./limits-of-current-approaches.md)**, analyzes why established methods, practices, and frameworks often fall short when confronted with these recurring challenges.
