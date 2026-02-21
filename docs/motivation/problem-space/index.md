# Problem space

> This page describes the problem space in which software systems are conceived and evolve.

Software systems exist and evolve within complex and enduring environments.  Understanding these environments is necessary before examining the structural characteristics that shape long-lived software systems.

Software systems are not isolated technical artifacts.  They are created, operated, and evolved within organizational, social, economic, and regulatory contexts, and they persist over extended periods of time.  Their behavior, structure, and evolution are shaped not only by technical decisions, but also by human activity, institutional arrangements, and external constraints.  

Software systems are also subject to continuous evolution.  Change is not an exception triggered by failure, but a normal condition driven by shifting requirements, technologies, organizational structures, and external pressures.  Research on software evolution shows that long-lived systems inevitably change and adapt over time.  

This page describes the **baseline conditions** under which software systems are conceived and evolve.  These conditions are not exceptional; they are common across domains and industries.  They provide the descriptive background necessary for understanding the environment in which upstream concerns arise.

The purpose of this page is descriptive.  It establishes a shared understanding of the environment in which software systems operate and evolve.


## Software systems as long-lived entities

Software systems are commonly initiated as projects, but they rarely remain confined to the temporal boundaries of those projects.  In practice, many systems persist for years or decades, continuing to operate and evolve long after their initial development phase has concluded.

Research on software evolution consistently characterizes long-lived systems as the norm rather than the exception.  Lehman’s work describes software systems as continuously changing entities whose lifetime extends well beyond their original context of creation ([Lehman & Ramil, 2003](../resources/bibliography.md#lehman-ramil-2003)).  Once deployed and adopted, a system becomes embedded in organizational processes and external dependencies that make replacement costly or impractical.

As software systems persist, they typically outlive:

- the teams that originally designed and implemented them,
- the technologies and platforms on which they were first built,
- the organizational structures and business assumptions that motivated their creation.

Maintenance and evolution therefore become dominant activities over a system’s lifetime.  Empirical studies indicate that the majority of effort invested in a software system occurs after its initial delivery, as systems are adapted to new requirements, environments, and constraints ([Bennett & Rajlich, 2000](../resources/bibliography.md#bennett-rajlich-2000)).

Longevity also affects knowledge.  Intent, design rationale, and governing assumptions are subject to gradual loss as individuals leave, documentation becomes outdated, and implicit knowledge remains uncodified.  The temporal distance between decision and consequence is a defining characteristic of long-lived software systems.

Longevity is not an anomaly to be corrected.  It is a baseline condition under which software systems exist and evolve.


## Continuous change as a baseline condition

Software systems do not evolve through isolated episodes of change separated by long periods of stability.  Change is a **baseline condition** under which software systems operate throughout their lifetime.

Research on software evolution shows that once a system is deployed in a real-world environment, it must continually adapt or it becomes progressively less satisfactory ([Lehman & Ramil, 2003](../resources/bibliography.md#lehman-ramil-2003)).  Changes arise from evolving user needs, organizational restructuring, regulatory requirements, technological advances, and interactions with other systems.

Change is not necessarily driven by defects or failures.  Even well-functioning systems undergo ongoing modification as their context shifts.  Stability, when it occurs, is temporary rather than permanent.

Modern software engineering practice increasingly reflects this condition by integrating development, maintenance, and operation rather than treating them as strictly separated phases.  Studies of continuous software engineering describe systems as shaped through a steady flow of incremental changes rather than discrete handovers ([Fitzgerald & Stol, 2017](../resources/bibliography.md#fitzgerald-stol-2017)).

Continuous change shapes how decisions accumulate and relate to one another over time.  Earlier assumptions may constrain later options, and later modifications may reinterpret or override earlier intent.  Evolution is therefore cumulative rather than episodic.

Continuous change is not a deviation from a stable norm.  It is a structural condition of long-lived software systems.

Recognizing continuous change as a baseline condition does not imply a particular method of managing change.  It establishes that reasoning about software systems requires assuming ongoing evolution rather than episodic modification.

Change occurs through decisions and actions taken within specific organizational settings.  Understanding continuous evolution therefore requires examining the contexts in which those decisions are made.




## Organizational and social context

Software systems are not purely technical constructs.  They are developed, operated, and evolved within organizations composed of people, roles, incentives, power structures, and communication channels.  As a result, the structure and behavior of software systems are deeply intertwined with the social and organizational contexts in which they exist.

Decisions affecting software systems are made by individuals and groups operating under constraints such as time, budgets, organizational priorities, and institutional norms.  These decisions are influenced by reporting lines, team structures, contractual arrangements, and informal practices.  Consequently, the evolution of a software system cannot be understood solely by examining its technical artifacts; it must also be understood in relation to the organizational environment that shapes it.

The influence of organizational structure on software systems has long been observed.  Conway famously noted that the structure of a system reflects the communication structure of the organization that produces it ([Conway, 1968](../resources/bibliography.md#conway-1968)).  While often cited in architectural discussions, this observation has broader implications: organizational changes—such as team reorganization, outsourcing, or changes in governance—can directly affect how software systems evolve over time.

From a broader perspective, software systems are best understood as **socio-technical systems**, in which technical components and social elements co-evolve.  Research in socio-technical systems emphasizes that technical change and organizational change are interdependent, and that attempts to address one in isolation are often insufficient ([Baxter & Sommerville, 2011](../resources/bibliography.md#baxter-sommerville-2011)).

Recognizing the organizational and social context of software systems does not imply prescribing organizational structures or management practices.  Rather, it establishes that software systems are embedded in human and institutional settings that shape their lifecycle, constraints, and evolution.  This embeddedness is a fundamental characteristic of the problem space addressed by the Upstream Software Engineering discipline.

Within these organizational and social contexts, software systems are rarely shaped by a single, stable group, but instead by a succession of actors and providers over time.


## Multiplicity of actors and providers

Software systems are rarely produced or evolved by a single, stable group of actors.  Instead, they are typically shaped by a **multiplicity of roles, teams, and providers** that contribute at different points in time and from different organizational positions.

Within an organization, software systems often involve multiple teams with distinct responsibilities, expertise, and priorities.  Over time, responsibilities may shift as teams are reorganized, merged, or dissolved.  In parallel, external actors—such as vendors, consultants, and service providers—may participate in the construction, maintenance, or operation of the system.  These arrangements are common in large organizations and long-lived systems, and they introduce additional layers of coordination and dependency.

Research on large-scale and distributed software development highlights that development and evolution frequently occur across organizational and geographical boundaries.  Work is divided among multiple units, often with limited shared context and varying degrees of autonomy ([Herbsleb & Mockus, 2003](../resources/bibliography.md#herbsleb-mockus-2003)).  As a result, no single actor may hold a complete or enduring understanding of the software system as a whole.

Multiplicity of actors also implies diversity in perspectives, incentives, and constraints.  Different stakeholders may have differing interpretations of system goals, quality priorities, or acceptable trade-offs.  These differences are not anomalies; they are inherent to collaborative and multi-actor environments.

Over the lifetime of a software system, actors and providers may change repeatedly, while the system itself remains.  Knowledge is transferred imperfectly across handovers, contracts, and organizational boundaries.  Understanding software systems as artifacts shaped by a succession of actors and providers is therefore essential to characterizing the environment in which they evolve.

This observation does not imply that multiplicity is undesirable or should be reduced.  Rather, it establishes that software systems commonly exist within ecosystems of actors whose composition and relationships change over time, forming a key dimension of the problem space addressed by the Upstream Software Engineering discipline.

As multiple actors and providers interact with a software system, perspectives on what constitutes the system and its environment naturally diverge and evolve.


## Boundaries, context, and environment

Software systems do not exist in isolation.  They operate within an environment composed of other software systems, technical infrastructure, organizational arrangements, regulatory constraints, and external actors.  Their behavior and evolution are therefore shaped not only by their internal structure, but also by how they are situated within this broader context.

In practice, the boundaries of a software system are rarely fixed or universally agreed upon.  What is considered “inside” or “outside” a system may vary depending on perspective, responsibility, or purpose.  Over time, these boundaries may shift as systems are integrated, decomposed, replaced, or reinterpreted in response to contextual change.

Systems engineering and software architecture literature emphasize that understanding a system requires explicit consideration of its environment and the relationships it maintains with external elements.  Software systems are often part of larger systems-of-systems, where independent systems interact while retaining their own objectives and governance structures ([Maier, 1998](../resources/bibliography.md#maier-1998)).

Similarly, software architecture standards highlight the importance of distinguishing a system from its context while explicitly representing their interaction.  Descriptions of software systems that ignore stakeholders, external systems, and environmental constraints risk oversimplifying the conditions under which those systems operate and evolve ([ISO/IEC/IEEE 42010, 2011](../resources/bibliography.md#iso-42010-2011)).

The fact that boundaries and context are variable and perspective-dependent is a fundamental characteristic of the problem space addressed by Upstream Software Engineering as a discipline.  Addressing upstream concerns requires acknowledging that decisions about what constitutes the system, what lies in its environment, and how those elements interact are themselves subject to interpretation and change over time.

This observation does not prescribe how boundaries should be defined or represented.  It establishes that boundary-setting and contextualization are unavoidable aspects of reasoning about software systems and their evolution within complex environments.

Over time, decisions about boundaries and context accumulate, interact, and change in ways that shape the long-term trajectory of the software system.


## Time, drift, and accumulation

Software systems evolve over extended periods of time, during which decisions, assumptions, and modifications accumulate.  The passage of time is therefore not a neutral background condition; it actively shapes the state and meaning of a software system.

Decisions made at different moments in a system’s lifetime interact in ways that are not always anticipated.  Early design choices may constrain later options, while later changes may reinterpret, bypass, or invalidate earlier assumptions.  Over time, the system that exists may differ significantly from the system that was originally envisioned, even if it continues to serve its intended purpose.

This phenomenon is often described in terms of **drift**.  Architectural drift and erosion literature observes that, as systems are modified incrementally, their structure may diverge from their original architectural intent without any single change being clearly responsible ([Perry & Wolf, 1992](../resources/bibliography.md#perry-wolf-1992)).  Drift emerges gradually, through the accumulation of locally rational decisions made under changing constraints.

In parallel, knowledge about the system accumulates unevenly and decays over time.  Rationale for past decisions may be lost as individuals leave, documentation becomes outdated, or implicit knowledge remains uncodified.  The system retains the consequences of past decisions, even when the reasons for those decisions are no longer visible.

Research on technical debt further highlights how accumulated design and implementation choices can shape future evolution.  While often framed in evaluative terms, technical debt literature underscores a descriptive reality: present states of software systems reflect layers of historical decisions whose effects persist over time ([Kruchten, Nord, & Ozkaya, 2012](../resources/bibliography.md#kruchten-nord-ozkaya-2012)).

The combined effects of time, drift, and accumulation constitute a defining dimension of the problem space addressed by Upstream Software Engineering as a discipline.  Reasoning about software systems in such environments requires acknowledging that current structures, constraints, and possibilities are the result of historical trajectories, not solely of present intent.

This observation does not prescribe how drift should be prevented, corrected, or managed.  It establishes that temporal accumulation and interpretive drift are inherent characteristics of long-lived, evolving software systems.


## Summary: Characteristics of the problem space

The preceding sections describe a problem space in which software systems are conceived, operated, and evolved under conditions that are common across domains and technologies.

Taken together, these conditions characterize software systems as:

- **Long-lived**  
  Software systems typically persist beyond the lifespan of individual projects, teams, technologies, and organizational structures.

- **Continuously evolving**  
  Change is a baseline condition, driven by shifting requirements, environments, and constraints rather than by exceptional failure.

- **Socio-technical**  
  Software systems are shaped by human, organizational, and institutional factors as much as by technical decisions.

- **Multi-actor and multi-provider**  
  Their construction and evolution involve multiple roles, teams, and organizations whose composition changes over time.

- **Context-dependent**  
  Software systems operate within broader environments, with boundaries and interfaces that are variable and perspective-dependent.

- **Historically accumulated**  
  Their current state reflects layers of past decisions, assumptions, and modifications, subject to drift and loss of original rationale.

These characteristics are not anomalies to be corrected.  They are defining features of the environment in which software systems exist and evolve.

This problem space is addressed by Upstream Software Engineering as a discipline.  The guidebook conveys this discipline by defining the conceptual structures and reasoning needed to operate within these conditions, which are introduced in the subsequent parts.


## Where to go next

The characteristics described on this page define the environment in which software systems exist and evolve.  The next page, **[Recurring challenges](./recurring-challenges.md)**, examines the recurring difficulties that arise within this problem space, without yet proposing solutions or norms.
