# Feature Roadmap, Module 4 · RouteLogic Velocity

**Team:** 2 engineers + 1 designer + 1 CS lead

## Strategic anchors
- **Persona:** Frontline Delivery Drivers
- **Primary metric:** In-app completion rate (tops marked complete in the app ÷ total completed stops (in-app + text).)
- **Moment of misery:** Drivers don’t trust the app enough to rely on it alone, so they carry paper as insurance. What they ask for is not more features but faster, more dependable core actions.
- **Guardrail:** Weekly use of the specialized enterprise features (eg: reporting, AI predictive ETA)

## Scoring
| Feature | Value | Effort | Quadrant | Decision | Rationale |
|---|---|---|---|---|---|
| B1 One-Click Compliance Checklist | 5 | 2 | Quick Win | Now | Removes the 14.6-min step that pushes drivers back to paper and text. It is the most direct lever on in-app completion rate, scoped to pre-fill only so it can ship in time to be measured. |
| B2 Smart Daily Report Auto-Fill | 3 | 4 | Time Sinker | Cut |  Serves the reporting guardrail but not the driver’s core friction. AI scope cannot be delivered or measured in 4 weeks, so we are not spending pilot capacity on it. |
| B3 Shift Handoff Wizard | 3 | 3 | Time Sinker | Later | A credible time saving (~6.8 min/day) that sits outside the stop-completion flow. Revisit once core actions are dependable. |
| B4 Mobile-First Coordinator Dashboard | 2 | 5 | Time Sinker | Cut | Targets coordinators, not our driver persona, and is the largest build on the list. It does not address why drivers keep paper. |
| B5 Step Progress Indicator | 2 | 1 | Fill-In | Next | Low-cost polish that improves orientation but won’t move completion rate in the pilot window. Only if there is spare capacity  |
| B6 Driver Alert Notifications | 3 | 4 | Time Sinker | Later | Reliable alerts build the trust that replaces paper, but that trust accrues over weeks and the build exceeds the pilot. Start post-pilot with compliance-flag alerts, which reinforce B1. |
| B7 Contextual AI ETA Display | 3 | 2 | Fill-In | Next | Protects the enterprise-feature guardrail at low cost by putting an existing capability (11% adoption) in front of drivers. It stays passive so it doesn’t add friction to core actions. |
| B8 Fleet Analytics Manager View | 1 | 5 | Time Sinker | Cut | An executive and Sales-driven feature with no driver benefit and the highest cost. It does not serve the Velocity objective. |
| B9 Compliance Audit Trail Export | 2 | 3 | Time Sinker | Later | Serves auditors, not drivers. It becomes a low-cost by-product once B1 produces structured compliance data. |
| B10 In-App Coordinator Training | 1 | 3 | Time Sinker | Cut | Aimed at the wrong persona and unrelated to driver trust or speed, so it falls outside the initiative’s scope. |

## Roadmap
### NOW, Pilot (4 weeks, 3 accounts)
- **B1 One-Click Compliance Checklist**, Removes the 14.6-min step that pushes drivers back to paper and text. It is the most direct lever on in-app completion rate, scoped to pre-fill only so it can ship in time to be measured.

### NEXT, GA Release (weeks 5-8)
- **B5 Step Progress Indicator**, Low-cost polish that improves orientation but won’t move completion rate in the pilot window. Only if there is spare capacity
- **B7 Contextual AI ETA Display**, Protects the enterprise-feature guardrail at low cost by putting an existing capability (11% adoption) in front of drivers. It stays passive so it doesn’t add friction to core actions.

### LATER, backlog
- **B3 Shift Handoff Wizard**, A credible time saving (~6.8 min/day) that sits outside the stop-completion flow. Revisit once core actions are dependable.
- **B6 Driver Alert Notifications**, Reliable alerts build the trust that replaces paper, but that trust accrues over weeks and the build exceeds the pilot. Start post-pilot with compliance-flag alerts, which reinforce B1.
- **B9 Compliance Audit Trail Export**, Serves auditors, not drivers. It becomes a low-cost by-product once B1 produces structured compliance data.

### ✂ Cut List
- **B2 Smart Daily Report Auto-Fill**, Serves the reporting guardrail but not the driver’s core friction. AI scope cannot be delivered or measured in 4 weeks, so we are not spending pilot capacity on it.
- **B4 Mobile-First Coordinator Dashboard**, Targets coordinators, not our driver persona, and is the largest build on the list. It does not address why drivers keep paper.
- **B8 Fleet Analytics Manager View**, An executive and Sales-driven feature with no driver benefit and the highest cost. It does not serve the Velocity objective.
- **B10 In-App Coordinator Training**, Aimed at the wrong persona and unrelated to driver trust or speed, so it falls outside the initiative’s scope.
