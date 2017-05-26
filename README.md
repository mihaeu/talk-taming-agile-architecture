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
  - CRC cards
  - whiteboard sketches
  - avoid architecture/technical debt
  - use retrospection for architectural issues
  - TDD/BDD helps come up with testable (i.e. better) architecture
  - design consistency through tool support and retrospective

#  medium size
  - conways law, organic architecture often reflects the organizational structure

# large size
  - landing zones?
  - architecture spikes? XP
  - risk-reduction backlogs?
  - set-based design?

SMART

# risk management
 - don't be an ostrich
 - integrate often
 - foote and yoder: factor your system so that artifacts which change at similar rates are together
    reduces cuts across the system
 - don't overdesign, don't underarchitect

 - is there a need for architects on agile teams
 - how do we minimize architectural risks
    - architecture is everything that's hard to change
 - can agile projects not use micro-services?
    - beware of the distributed monolith connected via a database

What do we want?
as little architecture as needed