# Project Planning Documents & Release Planning

## 1. Test Plan

### Definition
A **Test Plan** is a formal document that describes the scope, objectives, approach, resources, schedule, and activities required for testing a software system.

It explains **what will be tested, how it will be tested, who will test it, and when testing will be performed**.

### Purpose
- Define the scope and objectives of testing.
- Identify the testing strategy and approach.
- Assign testing responsibilities to team members.
- Estimate the required time and resources.
- Identify risks and dependencies related to testing.
- Establish the criteria for starting and completing testing.
- Ensure that the software meets functional and quality requirements.

### Components of a Test Plan
1. **Test Plan ID** – Unique identifier of the test plan.
2. **Introduction** – Brief description of the project and testing purpose.
3. **Test Objectives** – What testing is expected to achieve.
4. **Scope** – Features and modules included in and excluded from testing.
5. **Testing Strategy** – Types and levels of testing to be used.
6. **Test Environment** – Hardware, software, browsers, operating systems, databases, etc.
7. **Test Resources** – Testers, developers, tools, and infrastructure.
8. **Test Schedule** – Timeline for test preparation and execution.
9. **Test Deliverables** – Test cases, test reports, defect reports, and test summary.
10. **Entry Criteria** – Conditions that must be satisfied before testing starts.
11. **Exit Criteria** – Conditions required to complete testing.
12. **Risks and Mitigation** – Possible testing problems and their solutions.
13. **Defect Management** – Process for reporting, tracking, and resolving defects.

### Advantages
- Provides a clear testing roadmap.
- Improves coordination between team members.
- Helps identify risks early.
- Ensures systematic and organized testing.
- Reduces the chance of missing important test activities.
- Helps estimate time, cost, and resources.
- Provides a reference for evaluating testing progress.

---

## 2. Release Plan

### Definition
A **Release Plan** is a plan that specifies which features or product increments will be delivered in a particular release and when the release is expected to occur.

It connects the **product backlog, sprints, development work, testing, and final delivery**.

### Release Goals
- Define the features and improvements to be included in the release.
- Deliver valuable functionality to users.
- Set a realistic release date.
- Establish quality expectations.
- Coordinate development, testing, deployment, and documentation.
- Ensure that the release satisfies business and customer requirements.

### Release Schedule
A release schedule specifies the timeline for delivering the product.

Typical activities include:

**Requirements → Planning → Development Sprints → Testing → User Acceptance → Deployment → Release**

A release schedule may contain:
- Release name/version
- Target release date
- Sprints included
- Features/user stories included
- Testing period
- Deployment date
- Responsible team members
- Dependencies and milestones

### Benefits
- Gives the team a common delivery target.
- Helps prioritize features.
- Improves stakeholder communication.
- Makes resource and capacity planning easier.
- Helps identify dependencies and risks.
- Provides visibility into product progress.
- Supports predictable and controlled releases.

---

## 3. Sprint

### What is a Sprint?
A **Sprint** is a fixed-length time-box in Scrum during which a team works to create a usable and potentially releasable product increment.

A sprint commonly lasts **1 to 4 weeks**, with 2 weeks being common.

### Sprint Lifecycle
The typical sprint lifecycle is:

**Sprint Planning → Development & Daily Scrum → Sprint Review → Sprint Retrospective → Next Sprint**

#### 1. Sprint Planning
The team decides:
- What work can be completed.
- Which product backlog items will be selected.
- What the Sprint Goal will be.
- How the selected work will be implemented.

#### 2. Sprint Execution
Developers and other team members work on the selected items.

A **Daily Scrum** is used to inspect progress and plan the next day's work.

#### 3. Sprint Review
The team demonstrates the completed increment to stakeholders and collects feedback.

#### 4. Sprint Retrospective
The team discusses:
- What went well.
- What did not go well.
- What can be improved in the next sprint.

### Sprint Goal
A **Sprint Goal** is a short statement describing the main objective the team intends to achieve during a sprint.

Example:

> "Enable users to register, log in, and securely manage their profiles."

A good Sprint Goal provides focus and helps the team make decisions when unexpected work appears.

---

## 4. User Stories

### Definition
A **User Story** is a short description of a software requirement written from the perspective of an end user.

It describes **who needs something, what they need, and why they need it**.

### Format
The standard format is:

> **As a [user], I want [functionality], so that [benefit/value].**

Example:

> As a customer, I want to add products to my cart, so that I can purchase multiple products together.

### Acceptance Criteria
**Acceptance Criteria** are specific conditions that a user story must satisfy to be accepted as complete.

Example for the cart story:
- User can add a product to the cart.
- The selected product appears in the cart.
- Quantity can be increased or decreased.
- The total price is updated correctly.
- User can remove an item from the cart.

Acceptance criteria should be:
- Clear
- Specific
- Testable
- Unambiguous
- Related to the user story

---

## 5. Epic

### Definition
An **Epic** is a large body of work or high-level requirement that is too large to complete in a single sprint and is therefore divided into smaller user stories.

Example:

**Epic: Online Shopping**

Possible user stories:
- User can register an account.
- User can log in.
- User can search for products.
- User can add products to a cart.
- User can place an order.
- User can track an order.

### Relationship with User Stories

**Epic → User Stories → Tasks**

An epic represents the larger goal, while user stories represent smaller pieces of functionality that provide user value.

Example:

**Epic: Payment System**
- User Story 1: User can select a payment method.
- User Story 2: User can pay using a card.
- User Story 3: User receives payment confirmation.
- User Story 4: User can view payment history.

---

## 6. Story Points

### Definition
**Story Points** are a relative estimation unit used in Agile/Scrum to estimate the overall effort required to complete a user story.

Story points do **not directly represent hours or days**.

They usually consider:
- Complexity
- Amount of work
- Uncertainty
- Technical difficulty
- Dependencies

### Estimation Techniques

#### 1. Planning Poker
Team members independently select cards representing story-point values and reveal them together. Differences are discussed until the team reaches a reasonable estimate.

#### 2. Fibonacci Sequence
Common values are:

**1, 2, 3, 5, 8, 13, 21, ...**

The increasing gaps represent increasing uncertainty in larger work items.

#### 3. T-Shirt Sizing
Work can be estimated as:

**XS → S → M → L → XL**

This is useful for quick high-level estimation.

#### 4. Relative Estimation
A story is compared with previously estimated stories.

Example:
- Login feature = 3 points
- Payment integration is more complex = 8 points

### Important Point
Story points measure **relative effort**, not exact time.

---

## 7. Definition of Ready (DoR)

### Meaning
The **Definition of Ready (DoR)** is a checklist of conditions that a user story should satisfy before the team considers it ready to be taken into a sprint.

A story may be considered Ready when:
- Requirements are clear.
- User story follows the required format.
- Acceptance criteria are defined.
- Dependencies are identified.
- Required designs or technical information are available.
- The story is small enough for a sprint.
- The team understands the expected outcome.
- The story can be estimated.

### Importance
- Prevents unclear work from entering a sprint.
- Reduces misunderstandings.
- Improves sprint planning.
- Makes estimation more reliable.
- Reduces rework.
- Helps the development team start work confidently.

---

## 8. Definition of Done (DoD)

### Meaning
The **Definition of Done (DoD)** is a shared checklist that specifies the conditions that must be satisfied for a product backlog item or increment to be considered completely finished.

A typical DoD may require:
- Code is implemented.
- Code review is completed.
- Unit tests are written and passed.
- Integration testing is completed where required.
- Bugs/defects are resolved or appropriately handled.
- Acceptance criteria are satisfied.
- Documentation is updated where necessary.
- The feature is integrated into the required branch/build.
- The product increment meets the team's quality standards.

### Importance
- Creates a common understanding of "complete."
- Prevents unfinished work from being treated as finished.
- Improves product quality.
- Increases transparency.
- Supports consistent delivery.
- Helps stakeholders understand the quality level of completed work.

### DoR vs DoD

| Definition of Ready (DoR) | Definition of Done (DoD) |
|---|---|
| Determines whether work is ready to start. | Determines whether work is complete. |
| Used mainly before development. | Used mainly after implementation and verification. |
| Focuses on clarity and preparedness. | Focuses on completion and quality. |
| Example: acceptance criteria are available. | Example: tests pass and acceptance criteria are satisfied. |

---

## 9. Risk Planning

**Risk Planning** is the process of identifying, analyzing, prioritizing, and preparing responses for events that may negatively affect a project.

### Risk Identification
Risk identification means finding possible risks before or during project execution.

Common software-project risks:
- Requirement changes
- Technical failure
- Lack of skilled resources
- Schedule delays
- Budget limitations
- Security problems
- Integration issues
- Third-party service failure
- Data loss
- Unexpected defects

Useful methods include:
- Brainstorming
- Checklists
- Historical project data
- Expert judgment
- Team discussions

### Risk Assessment
Risk assessment determines how serious each risk is.

A common approach considers:

**Risk Exposure = Probability × Impact**

For example:

| Risk | Probability | Impact | Priority |
|---|---|---|---|
| Requirement changes | High | High | Very High |
| Server failure | Medium | High | High |
| Minor UI defect | High | Low | Medium |

Risks can be prioritized as **Low, Medium, High, or Very High**.

### Risk Mitigation
Risk mitigation means taking actions to reduce the probability or impact of a risk.

Examples:
- **Requirement changes:** Confirm requirements early and maintain change control.
- **Technical failure:** Create prototypes and conduct technical reviews.
- **Schedule delay:** Add realistic estimates and monitor progress.
- **Data loss:** Maintain regular backups.
- **Security issues:** Perform security testing and code reviews.
- **Resource shortage:** Cross-train team members and maintain backup resources.

---

## 10. Resource Planning

**Resource Planning** is the process of identifying, estimating, allocating, and managing the resources required to complete a project successfully.

Resources can include:
- People
- Time
- Budget
- Hardware
- Software
- Infrastructure
- Tools and services

### Team Allocation
Team allocation means assigning suitable people to appropriate project activities based on skills, availability, and workload.

Example:

| Role | Responsibility |
|---|---|
| Project Manager/Scrum Master | Planning and coordination |
| UI/UX Developer | Interface and user experience |
| Frontend Developer | Client-side development |
| Backend Developer | Server-side logic and APIs |
| Database Developer | Database design and management |
| Tester/QA | Testing and defect reporting |

Good team allocation:
- Matches skills with tasks.
- Avoids overloading individuals.
- Makes responsibilities clear.
- Improves productivity.

### Time Estimation
Time estimation determines how long project activities are expected to take.

Common approaches:
- Expert judgment
- Historical data
- Three-point estimation
- Story points and team velocity in Agile

For three-point estimation:

**Expected Time = (Optimistic + 4 × Most Likely + Pessimistic) / 6**

Example:

Optimistic = 2 days  
Most Likely = 4 days  
Pessimistic = 8 days

Expected Time:

**(2 + 4×4 + 8) / 6 = 4.33 days**

### Budget Planning
Budget planning estimates and controls the financial resources required for the project.

Possible costs:
- Salaries/team cost
- Cloud hosting
- Software licenses
- Hardware
- Development tools
- Testing tools
- Training
- Maintenance

A basic project budget can be represented as:

**Total Budget = Labor Cost + Infrastructure Cost + Tool/License Cost + Other Costs + Contingency**

### Capacity Planning
**Capacity Planning** determines how much work a team can realistically complete during a given period.

In Scrum, team capacity depends on:
- Number of team members
- Available working days
- Working hours
- Holidays and leave
- Meetings and other commitments
- Previous team velocity

Capacity planning helps avoid overcommitting during a sprint.

---

# Quick Revision

### Test Plan
**Plan for testing** — defines what, how, who, when, resources, risks, and completion criteria.

### Release Plan
**Plan for delivery** — defines what features will be released and when.

### Sprint
**Time-boxed development cycle** — team creates a usable product increment.

### User Story
**Small user-focused requirement** — describes functionality from the user's perspective.

### Epic
**Large requirement** — broken into multiple user stories.

### Story Points
**Relative effort estimation** — measures complexity, effort, and uncertainty rather than exact time.

### DoR
**Ready to start** — conditions required before a story enters development.

### DoD
**Ready to finish** — conditions required for a story to be considered complete.

### Risk Planning
**Prepare for uncertainty** — identify, assess, and mitigate project risks.

### Resource Planning
**Plan project resources** — allocate people, time, budget, tools, and capacity.

---

# Overall Agile Planning Flow

**Epic**
↓
**User Stories**
↓
**Acceptance Criteria**
↓
**Definition of Ready**
↓
**Story Point Estimation**
↓
**Sprint Planning**
↓
**Sprint Execution**
↓
**Testing**
↓
**Definition of Done**
↓
**Sprint Review**
↓
**Release Planning / Release**
