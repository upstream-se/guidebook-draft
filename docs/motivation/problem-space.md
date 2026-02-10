# Problem space

Before discussing challenges, limitations, or possible approaches, it is necessary to understand the **problem space** in which software systems exist and evolve.

Software systems are not isolated technical artifacts. They are created, operated, and evolved within organizational, social, economic, and regulatory contexts, and they persist over long periods of time. Their behavior, structure, and evolution are shaped not only by technical decisions, but also by human activity, organizational arrangements, and external constraints. This socio-technical nature of software systems has been widely recognized in the literature ([Baxter & Sommerville, 2011](../resources/bibliography.md#baxter-sommerville-2011)).

Moreover, software systems are subject to continuous evolution. Change is not an exception triggered by failure, but a normal condition driven by shifting requirements, technologies, organizational structures, and external pressures. Decades of research on software evolution show that long-lived software systems inevitably change and adapt over time ([Lehman & Ramil, 2003](../resources/bibliography.md#lehman-ramil-2003)).

This page describes the **baseline conditions** under which software systems are conceived and evolve. These conditions are not exceptional; they are common across domains, industries, and technologies. They provide the background against which upstream concerns emerge, without yet characterizing them as problems or proposing solutions.

The purpose of this page is therefore **descriptive**. It characterizes the environment in which software systems operate, establishing a shared understanding of the setting that motivates the rest of the guidebook.


## Software Systems as Long-Lived Entities

Software systems are commonly initiated as projects, but they rarely remain confined to the temporal boundaries of those projects.  In practice, many software systems persist for years or decades, continuing to operate and evolve long after their initial development phase has concluded.

Research on software evolution has consistently shown that long-lived systems are the norm rather than the exception.  Lehman’s work on software evolution characterizes software systems as continuously changing entities whose lifetime extends well beyond their original context of creation ([Lehman & Ramil, 2003](../resources/bibliography.md#lehman-ramil-2003)).  Once deployed and adopted, a software system becomes embedded in organizational processes and external dependencies that make its replacement costly or impractical.

As software systems persist, they typically outlive:
- the teams that originally designed and implemented them,
- the technologies and platforms on which they were first built,
- the organizational structures and business assumptions that motivated their creation.

Maintenance and evolution therefore become dominant activities over a system’s lifetime.  Empirical studies indicate that the majority of effort invested in a software system occurs after its initial delivery, as systems are adapted to new requirements, environments, and constraints ([Bennett & Rajlich, 2000](../resources/bibliography.md#bennett-rajlich-2000)).

The longevity of software systems also implies that knowledge about original intent, design rationale, and governing assumptions is subject to gradual loss.  As time passes, decisions made early in the system’s life may no longer be explicitly documented, remembered, or even recognized as decisions.  This temporal distance between decision and consequence is a defining characteristic of long-lived software systems, and it fundamentally shapes how they must be governed and evolved.

Recognizing software systems as long-lived entities is therefore essential to understanding the broader problem space addressed by this guidebook.  Longevity is not an anomaly to be corrected, but a baseline condition that must be assumed.


## Continuous Change as a Baseline Condition

Software systems do not evolve through isolated episodes of change separated by long periods of stability.  Instead, change is a **baseline condition** under which software systems operate throughout their lifetime.

Empirical and theoretical work on software evolution has shown that once a software system is deployed and used, it must continually adapt to remain useful.  Changes arise from multiple sources, including evolving user needs, organizational restructuring, regulatory requirements, technological advances, and interactions with other systems.  As a result, software systems are rarely “finished” in any meaningful sense ([Lehman & Ramil, 2003](../resources/bibliography.md#lehman-ramil-2003)).

Importantly, change is not necessarily driven by defects or failures.  Even well-functioning software systems are subject to ongoing modification as their context changes.  This observation challenges the implicit assumption—common in project-centric views—that stability is the normal state and change is an exception.  In practice, the opposite is often true: stability is temporary, while change is continuous.

Modern software engineering practice increasingly acknowledges this reality by treating evolution as an integral part of development rather than a separate phase.  Studies of continuous software engineering emphasize that systems are shaped through a steady flow of incremental changes rather than discrete handovers between development, maintenance, and operation ([Fitzgerald & Stol, 2017](../resources/bibliography.md#fitzgerald-stol-2017)).

The continuous nature of change also implies that decisions made at different points in time interact in non-trivial ways.  Early assumptions may constrain later options, while later changes may reinterpret or override earlier intent.  Understanding software systems as continuously changing entities is therefore essential for characterizing the environment in which upstream concerns arise.

Recognizing continuous change as a baseline condition does not, by itself, prescribe how change should be governed or managed.  It simply establishes that any approach to reasoning about software systems must assume ongoing evolution rather than episodic modification.


## Organizational and Social Context

Software systems are not purely technical constructs.  They are developed, operated, and evolved within organizations composed of people, roles, incentives, power structures, and communication channels.  As a result, the structure and behavior of software systems are deeply intertwined with the social and organizational contexts in which they exist.

Decisions affecting software systems are made by individuals and groups operating under constraints such as time, budgets, organizational priorities, and institutional norms.  These decisions are influenced by reporting lines, team structures, contractual arrangements, and informal practices.  Consequently, the evolution of a software system cannot be understood solely by examining its technical artifacts; it must also be understood in relation to the organizational environment that shapes it.

The influence of organizational structure on software systems has long been observed.  Conway famously noted that the structure of a system reflects the communication structure of the organization that produces it ([Conway, 1968](../resources/bibliography.md#conway-1968)).  While often cited in architectural discussions, this observation has broader implications: organizational changes—such as team reorganization, outsourcing, or changes in governance—can directly affect how software systems evolve over time.

From a broader perspective, software systems are best understood as **socio-technical systems**, in which technical components and social elements co-evolve.  Research in socio-technical systems emphasizes that technical change and organizational change are interdependent, and that attempts to address one in isolation are often insufficient ([Baxter & Sommerville, 2011](../resources/bibliography.md#baxter-sommerville-2011)).

Recognizing the organizational and social context of software systems does not imply prescribing organizational structures or management practices.  Rather, it establishes that software systems are embedded in human and institutional settings that shape their lifecycle, constraints, and evolution.  This embeddedness is a fundamental characteristic of the problem space addressed by this guidebook.


# Multiplicity of Actors and Providers

# Boundaries, Context, and Environment

# Time, Drift, and Accumulation

# Summary: Characteristics of the Problem Space
