# Taming Agile Architecture

## Myths

 - agile means no architecture
    - understandable reaction
    - but balance is required (some upfront thinking for complex projects, continuous improvement otherwise)
 - agile means no documentation
 - agile teams always win
 - good architecture always emerges from good design practices
 - you can make significant architecture changes at the last moment, because you're agile
 -

> Individuals and interactions over processes and tools

Ask questions!

## Questions

 - do we need up-front architecture/when do we need architecture?
 - how much architecture do we need?

 alistair cockburn chart project criticality vs size

# architecture for small teams
  - CRC cards (Kent Beck - MVC example)
  - whiteboard sketches
  - avoid architecture/technical debt
  - use retrospection for architectural issues
  - TDD/BDD helps come up with testable (i.e. better) architecture
  - design consistency through tool support and retrospective

#  medium size
  - conways law, organic architecture often reflects the organizational structure

# large size
  - landing zones?
  - architecture spikes?
        similar to XP spikes, prototype focused on a single problem
        failure IS an option
        limited time
  - risk-reduction backlogs?
  - set-based design?

SMART

Traditional architecture vs agile architecture
    what models do we create
    how long do they last
    are they meant to or able to change?
    agile: testable architecture, hands-on, no ivory tower designs
    where is the architect?
    most of the tasks a traditional architect does should be done by tools or developers

design stamina hypothesis
you can wrap bad code, you can't wrap bad architecture
software architecture is not like building a house

You're not agile just because you're using Jira ...

# risk management
 - don't be an ostrich
 - integrate often
 - foote and yoder: factor your system so that artifacts which change at similar rates are together
    reduces cuts across the system
 - don't overdesign, don't underarchitect

 - is there a need for architects on agile teams
 - how do we minimize architectural risks
    - "[Architecture] is the stuff that's hard to change" - Martin Fowler
    - vs. tradition definition
 - can agile projects not use micro-services?
    - beware of the distributed monolith connected via a database

What do we want?
    as little architecture as needed
    a good design allows major decisions to be deferred
    vertical vs horizontal slicing (does not mean micro-services)
    think big, act small, fail fast, learn rapidly
    architects must be involved in code
    accountability, collaboration, pragmatic/utilitarian

# Quotes

 "Beware of people who love to think about abstractions more than coding software." - Steve Green
 "All models are wrong, some models are useful." - George Box
 "Architecture is not all about diagrams; it's about promoting collaboration and communication of the critical parts of the system." - Martin Fowler
 "An architect's value is inversely proportional to the number of decisions she/he makes." - Martin Fowler

 Sources
  - Just Enough Software Architecture
  - Agile Software Architecture
  - Lean Architecture
  - Microservices - Grundlagen flexibler Softwarearchitekturen