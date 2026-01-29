# architecture-for-flow-guide

In my view, the Architecture for Flow change loop has the following generic phases:
1. **Phase 1 - Strategy**: Clarify purpose and direction before changing structure or systems. This phase establishes why the system exists, what value it must deliver, and what success means.
2. **Phase 2 - Discovery**: Understand the current reality and where flow is actually blocked. This phase makes today’s system visible, including teams, dependencies, and change friction, and identifies where fast flow really matters.
3. **Phase 3 – Design**: Reshape the system so change can move locally instead of globally. This phase designs clear boundaries and relationships in the solution space to reduce coupling and enable independent change.
4. **Phase 4 – Enable flow for teams**: Make the designed system workable for real teams over time. This phase aligns ownership, cognitive load, platforms, and interaction modes so teams can operate and adapt without constant coordination overhead. 

Important:
- This loop describes a system optimisation process for improving flow of change and feedback.
- It is not linear, not a checklist, and not a maturity model.
- Each phase represents a distinct intent.
- Methods may change; the intent of each step does not.

## Approach - Designing a Legacy System for Flow
In my experience, this approach fits the best with typical traditional organisations (for example public sector)
It's largely based on chapter 9 of Architecture for Flow:

### Phase 1 - Strategy

#### Address the why of the business
**Intent:** Establish a shared understanding of why the system exists and what success means.

**Methods:**
- Wardley Mapping strategy cycle (purpose, users, needs)
- Conversations with key business and market stakeholders

### Phase 2 - Discovery

#### Examine the teams of today
**Intent:** Make current responsibilities, handoffs, and dependencies visible.

**Methods:**
- Analysis of existing functional silo teams.
- Observation of handover mechanisms.


#### Assess the current flow of change
**Intent:** Identify what blocks or slows down change and feedback.

**Methods:**
- Value Stream Mapping


#### Visualise the current landscape
**Intent:** Create a shared picture of users, value, and dependencies.

**Methods:**
- Wardley Mapping (current state landscape): User Need Mapping, Evolution mapping.


#### Identify suitable streams of change
**Intent:** Decide where speed and learning matter most.

**Methods:**
- Using user needs on the Wardley Map as candidates for streams of change


#### Discover the problem domain
**Intent:** Build shared understanding of the domain and identify what is core.

**Methods:**
- Strategic Domain-Driven Design: Subdomain classification (core, supporting, generic)
- Competitive differentiation discussions with stakeholders

---

### Phase 3 – Design

#### Modularise the solution space (design bounded contexts)
**Intent:** Create coherent boundaries so change is local, not global.

**Methods:**
- Big Picture EventStorming
- Domain Storytelling (as a complementary approach)


#### Design context maps
**Intent:** Make relationships between boundaries explicit and deliberate.

**Methods:**
- Context Mapping with Context map patterns (Shared Kernel, Open Host Service, Published Language, Anticorruption Layer, Conformist)

---

#### Visualise the future landscape
**Intent:** Align architectural choices with strategy and investment.

**Methods:**
- Wardley Mapping (future state)
- Mapping bounded contexts to evolution stages
- Efficiency gap analysis

---

### Phase 4 – Enable flow for teams

#### Define suitable team ownership boundaries
**Intent:** Align responsibility with architectural boundaries.

**Methods:**
- Using bounded contexts as fracture planes
- Stream-aligned team concept from Team Topologies


#### Optimise team cognitive load
**Intent:** Ensure teams can understand and operate their scope.

**Methods:**
- Team cognitive load heuristics
- Wardley Map position heuristics
- Cynefin domain classification


#### Identify platform services supporting flow of change
**Intent:** Remove handoffs by enabling self-service.

**Methods:**
- Platform thinking
- Identification of X-as-a-Service platform candidates
- Thinnest Viable Platform approach


#### Apply team types and interaction modes
**Intent:** Shape collaboration to minimise coordination overhead.

**Methods:**
- Team Topologies team types
- Team interaction modes

---

#### Identify capability gaps and enable dynamic reteaming
**Intent:** Make missing system and skill capabilities explicit and support adaptation.

**Methods:**
- Capability gap identification
- Dynamic Reteaming
