# Maintenance model

> This page defines how Prior major version lines are maintained and when maintenance may be closed.

The maintenance model governs the limited evolution of major version lines after they transition from **Current** to **Prior**.

Its purpose is to:

- Allow correction of editorial defects discovered after supersession.
- Preserve continuity for ongoing compliance assessments.
- Prevent continued evolution of older normative states.
- Ensure predictable lifecycle transitions across major releases.


## Scope of maintenance

During maintenance, only **patch increments** are permitted.

Patch increments must not:

- Alter definitions in **Foundations**.
- Modify the **Metamodel**.
- Change transformation **Plays**.
- Affect validity conditions.

If a correction would affect normative meaning, it must be introduced through a new major version line.


## Baseline maintenance rule

Let N denote the **Current** major version line.

At any given time:

- N is Current and maintained.
- N−1 is **Prior** and must be under maintenance.
- N−2 and earlier are Prior with no maintenance.

This establishes a baseline in which exactly one Prior major version line (the most recently superseded one) is guaranteed to be under maintenance.


## Maintenance at major releases

Maintenance windows are opened and closed only at major releases.

When a new major version line N+1 is released:

- N+1 becomes Current.
- N becomes Prior and must enter maintenance.
- N−1 remains Prior.

At that moment, lifecycle governance may decide whether the maintenance window for N−1:

- remains open (so that both N and N−1 are under maintenance), or
- is closed (so that only N remains under maintenance).

Maintenance windows must not be opened or closed outside of major releases.


## Closure of maintenance

When maintenance is closed for a Prior major version line X:

- X remains normative and citable.
- X becomes immutable.
- No further increments (major, minor, or patch) are permitted on X.

Maintenance closure decisions must occur only at major releases.
p

## Summary

The maintenance model defines how Prior major version lines are governed after supersession.

- The most recent Prior major version line is always under maintenance.
- Older Prior version lines may or may not remain under maintenance.
- Maintenance permits only patch increments.
- Maintenance windows may be opened or closed only at major releases.
- Once maintenance is closed, a Prior major version line becomes immutable.

This model ensures continuity across major releases while preventing uncontrolled evolution of historical normative states.


## Where to go next

← **[Versioning model](../versioning-model/)**  
  Defines how guidebook versions are structured, incremented, and transitioned across lifecycle states.

→ **[Release discipline](../release-discipline/)**  
  Defines release criteria, authorization requirements, and publication cadence.

↑ **[Lifecycle governance](../)**  
  Defines the temporal governance framework that regulates versioning, maintenance, deprecation, and controlled evolution of the guidebook.