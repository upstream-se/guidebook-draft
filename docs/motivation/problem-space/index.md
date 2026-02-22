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

Software systems are developed, operated, and evolved within organizations composed of people, roles, incentives, power structures, and communication channels.  As a result, the structure and behavior of software systems are intertwined with the social and organizational contexts in which they exist.

Decisions affecting software systems are made by individuals and groups operating under constraints such as time, budgets, organizational priorities, and institutional norms.  These decisions are shaped by reporting lines, team structures, contractual arrangements, and informal practices.  The evolution of a software system therefore cannot be understood solely by examining technical artifacts; it must also be understood in relation to the organizational environment that produces, maintains, and changes those artifacts.

The influence of organizational structure on software systems has long been observed.  Conway noted that the structure of a system reflects the communication structure of the organization that produces it ([Conway, 1968](../resources/bibliography.md#conway-1968)).  This observation has broader implications over time: organizational changes such as reorganization, outsourcing, and shifts in governance can directly affect how software systems evolve.

Software systems are therefore best understood as **socio-technical systems**, in which technical components and social elements co-evolve.  Research in socio-technical systems emphasizes that technical change and organizational change are interdependent, and that attempts to address one in isolation are often insufficient ([Baxter & Sommerville, 2011](../resources/bibliography.md#baxter-sommerville-2011)).

Recognizing organizational and social context does not imply prescribing organizational structures or management practices.  It establishes that software systems are embedded in human and institutional settings that shape their lifecycle, constraints, and evolution.


## Multiplicity of actors and providers

Software systems are rarely produced or evolved by a single, stable group of actors.  They are typically shaped by a **multiplicity of roles, teams, and providers** that contribute at different moments and from different organizational positions.

Within an organization, software systems often involve multiple teams with distinct responsibilities, expertise, and priorities.  Over time, responsibilities may shift as teams are reorganized, merged, or dissolved.  In addition, external actors such as vendors, consultants, and service providers may participate in construction, maintenance, or operation.  These arrangements are common in large organizations and long-lived systems, introducing additional layers of coordination and dependency.

Research on large-scale and distributed software development shows that development and evolution frequently occur across organizational and geographical boundaries ([Herbsleb & Mockus, 2003](../resources/bibliography.md#herbsleb-mockus-2003)).  Work is divided among multiple units, often with limited shared context and varying degrees of autonomy.  As a result, no single actor may hold a complete or enduring understanding of the software system as a whole.

Multiplicity also entails diversity in perspectives, incentives, and constraints.  Different stakeholders may interpret system goals, quality priorities, or acceptable trade-offs differently.  These differences are not anomalies but inherent characteristics of collaborative and multi-actor environments.

Over the lifetime of a software system, actors and providers may change repeatedly while the system persists.  Knowledge is transferred imperfectly across handovers, contracts, and organizational boundaries.  Software systems must therefore be understood as artifacts shaped by successive configurations of actors whose composition and relationships evolve.

Multiplicity is not presented here as a deficiency to be corrected.  It is a structural characteristic of environments in which software systems are developed and evolved.  Software systems commonly exist within arrangements of actors whose composition and relationships change as organizational conditions shift.

As multiple actors and providers interact with a software system, perspectives on what constitutes the system and what lies in its environment naturally diverge and evolve.


## Boundaries, context, and environment

Software systems do not exist in isolation.  They operate within environments composed of other software systems, technical infrastructure, organizational arrangements, regulatory constraints, and external actors.  Their behavior and evolution are shaped not only by internal structure but also by how they are situated within this broader context.

In practice, the boundaries of a software system are rarely fixed or universally agreed upon.  What is considered inside or outside a system may vary depending on perspective, responsibility, or purpose.  Boundaries may shift as systems are integrated, decomposed, replaced, or reinterpreted in response to contextual change.

Systems engineering and software architecture literature emphasize that understanding a system requires explicit consideration of its environment and its relationships with external elements.  Software systems are often components within larger systems-of-systems, where independently governed systems interact while retaining distinct objectives ([Maier, 1998](../resources/bibliography.md#maier-1998)).

Software architecture standards similarly stress the importance of distinguishing a system from its context while explicitly representing their interaction.  Descriptions that omit stakeholders, external systems, or environmental constraints risk oversimplifying the conditions under which systems operate and evolve ([ISO/IEC/IEEE 42010, 2011](../resources/bibliography.md#iso-42010-2011)).

Variability in boundaries and context is therefore a structural characteristic of long-lived software systems.  Decisions about what constitutes the system, what lies in its environment, and how these elements relate are themselves subject to interpretation and revision.

Boundary-setting and contextualization are not incidental activities.  They are inherent aspects of reasoning about software systems situated within complex environments.

Decisions concerning boundaries and context accumulate and interact.  As these decisions are revised or reinterpreted, they influence the long-term trajectory of the system.


## Time, drift, and accumulation

Software systems evolve across extended periods during which decisions, assumptions, and modifications accumulate.  Time is not merely a background condition; it shapes how systems are structured, interpreted, and changed.

Decisions made at different moments do not remain isolated.  Earlier design choices may constrain later options, while subsequent modifications may reinterpret, bypass, or invalidate earlier assumptions.  The system that exists at any given moment reflects layered historical decisions rather than a single coherent act of design.

This gradual divergence between original architectural intent and realized structure is often described as **drift**.  Architectural drift and erosion literature observe that incremental modifications can cause systems to deviate from their initial architectural principles without any single change appearing decisive ([Perry & Wolf, 1992](../resources/bibliography.md#perry-wolf-1992)).  Drift emerges gradually through the accumulation of locally rational decisions made under changing constraints.

In parallel, knowledge about earlier decisions and their rationale may diminish as individuals leave, documentation becomes outdated, or assumptions remain implicit.  The system retains the consequences of prior decisions even when the reasons for those decisions are no longer visible.

Research on technical debt highlights how accumulated design and implementation choices influence future evolution ([Kruchten, Nord, & Ozkaya, 2012](../resources/bibliography.md#kruchten-nord-ozkaya-2012)).  While often framed in evaluative terms, the underlying descriptive observation is that present states of software systems are shaped by layers of historical commitments whose effects persist.

Accumulation, reinterpretation, and gradual divergence between declared intent and realized structure are structural characteristics of long-lived software systems.  Their current configuration reflects layered historical trajectories rather than solely present intention.


## Structural characteristics of the problem space

The preceding sections describe baseline conditions under which software systems are conceived, operated, and evolved.  Taken together, these conditions characterize the structural environment of long-lived software systems as follows:

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

- **Historically layered and subject to drift**  
  Their current state reflects layers of past decisions, assumptions, and modifications, subject to drift and loss of original rationale.

These characteristics are not anomalies to be corrected.  They are defining structural features of the environment in which software systems exist and evolve.  They form the baseline against which recurring challenges can be examined.


## Where to go next

→ **[Recurring challenges](./recurring-challenges.md)**  
  Identifies and characterizes recurring structural challenges arising within the problem space.

↑ **[Motivation](./)**  
  Introduces the problem space and structural rationale for Upstream Software Engineering.

↑ **[Guidebook](../)**  
  Provides an overview of Upstream Software Engineering and its guidebook.
