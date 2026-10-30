# Experimentation Plan (Module 5)

## Get your documents ready
- **From M3, your hypothesis sentence:** Based on research showing that drivers like Diego skip a three-screen “mark delivered” flow and text their dispatcher instead, and on internal data showing falling usage among fleet coordinators, I believe that reducing delivery confirmation to a single quick action for frontline drivers will make the app the place deliveries are recorded, as measured by a 30% relative increase in the share of stops marked complete in the app within 90 days. I will protect weekly use of specialized enterprise features (no meaningful drop from baseline) and will make a go/no-go decision after a 90-day pilot, with a checkpoint at 30 days.
- **From M3, your primary success metric & guardrail metric:** Primary success: The share of stops marked complete in the app (instead of by text).
Guardrail metric:Weekly use of the specialized enterprise features (eg: reporting, AI predictive ETA
- **From M4, the feature you scoped in your PRD this is what you're testing:** One-Click Compliance Checklist (narrow scope) feature. It pre-fills the compliance checklist from existing stop and route data, so drivers confirm it in one click instead of spending 14.6 minutes filling it in.

## Define your experiment parameters
- **Feature under test pull from your M4 PRD:** One-Click Compliance Checklist
- **Persona pull your M2 persona:** Frontline Delivery Drivers
- **Expected outcome the behaviour change you expect, from your M3 hypothesis:** Drivers record each delivery in the app with one quick action, instead of texting their dispatcher.
- **Primary success metric the one number that defines success, from M3:** The share of stops marked complete in the app (instead of by text).
- **Baseline rate today's rate of your primary metric, from your M3 data:** 65% (based on compliance checklist for drivers)
- **Guardrail metric & boundary what must not break, and how far it can move before you investigate:** Guardrail metric: Weekly use of the specialized enterprise features 
Boundary: Weekly use must not fall more than 14% (median for AI predictive ETA for drivers, coordinator and managers)
- **Minimum Detectable Effect (MDE) the smallest improvement worth shipping, your floor:** +5 points
- **Sample size per arm use the calculator in the builder, baseline + MDE:** 1377
- **Traffic split & test duration 50/50 standard · cover ≥ 2 weekly cycles:** 50/50
- **Significance threshold p < 0.05 is standard, explain any deviation:** p< 0.05

## Define your control and variant
- **Control (A) the current experience, reference your M2 moment of misery and M3 funnel/workflow data:** On every stop, a driver has to work through a slow, buried interface to record a simple fact, that the delivery is done. They skip the app and use a workaround instead: texting dispatch, keeping paper manifests, or calling the office. Per M3 funnel, Drivers abandon RouteLogic where its multi-screen steps are slowest, Assign Routes (8.2 vs 4.0 min) and Log Compliance Checks (14.6 vs 3.0 min), and turn to manual workarounds.
- **Variant (B) your single change, copy the relevant screens & functional requirements from your M4 PRD:** One-Click Compliance Checklist feature. It pre-fills the compliance checklist from existing stop and route data and submission receipt
- **Isolation check, what has NOT changed? list everything identical between arms (app version, recommendation engine, notifications, onboarding). If something changed inadvertently, your test is compromised.:** the application version, the core application and the mark delivery flow

## Formalize your hypothesis & shipping criteria
- **Your hypothesis (filled in):** I believe that reducing delivery confirmation to a single quick action for frontline drivers will result in the app becoming the place deliveries are recorded, with drivers marking stops done in one action instead of texting dispatch, as measured by a 20% relative increase in in-app completion rate (the share of completed stops marked complete in the app) within 90 days. We will protect weekly use of specialized enterprise features (reporting and AI predictive ETA) throughout the test, with no meaningful drop from baseline.
- **Your shipping criteria (filled in):** We will SHIP if in-app completion rate improves by ≥ 5 percentage points (64% to 69% or higher) at 95% confidence (p < 0.05), and weekly use of reporting and AI predictive ETA does not fall more than 15% relative to baseline after 90 days.

We will ITERATE if direction is positive but lift is below 5 percentage points.

We will KILL if in-app completion rate shows no improvement or moves negatively.

The read date is fixed at day 90, and no results are reviewed before this date.
- **Hardest parameter to define, and did it change your hypothesis? quick debrief:** increase in-app completion as this related to habitual change of the drivers. Reduced to 20%
