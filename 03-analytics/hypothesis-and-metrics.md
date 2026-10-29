# Hypothesis & Success Metrics (Module 3)

## Pre-work · Hypothesis check
- **Role , who you are solving for (from M2):** Frontline Delivery Drivers
- **Goal , what this user is ultimately trying to achieve:** Complete every stop quickly and reliably, and let dispatch know it's done, so he finishes his shift on time without workarounds.
- **Friction / moment of misery , the specific pain blocking their goal:** On every stop, a slow, buried flow to confirm a delivery pushes drivers to text dispatch instead. Diego: three screens, package in hand, clock running.
- **Current workaround , the external tool or manual process they rely on (M2):** Diego, a delivery driver, works around the app using one external tool: text messaging to his dispatcher. Marking a stop complete in the app takes three screens of taps, which is impractical when he is standing at a doorstep with a package in his hand. So he skips the app and texts the dispatcher instead.

How the manual process works

1. Complete the delivery. Diego hands over the package at the doorstep, but the app still shows the stop as open.
2. Bypass the app. Faced with the multi-screen flow, he chooses not to start it.
3. Text the dispatcher. He sends a message saying the stop is done, identifying it from memory or by glancing at the stop list. 
4. He heads to the next stop. The text is now his only record of completion, and the app’s status for that stop never changes which says it's not delivered.
- **Problem Hook , your one-sentence framing of the business crisis (M1):** We must solve the growing risk of customer churn and market share loss by addressing the operational complexity that is reducing frontline adoption, driving customers to evaluate simpler competitors, and weakening our position as the platform of choice for fleet operations.
- **Value Proposition , the outcome your initiative promised to deliver (M1):** or frontline fleet coordinators, we will help them complete time-sensitive operational tasks faster by surfacing only the tools they need and hiding unnecessary complexity, because users are already turning to simpler alternatives and enterprise customers are beginning to evaluate competitors.

## Read your data snapshots
- **Does the funnel data confirm your M2 friction point, or does it tell a different story? Note where the numbers align with the qualitative pain you found and where they diverge.:** _(not filled in)_
- **Do the retention patterns align with the workaround your M2 persona used to find content? Note what the Mo. 0→1 drop suggests about the onboarding experience your persona described as frustrating.:** _(not filled in)_
- **Does the LTV gap and the content mix (61% trending for Wanderers) confirm the moment of misery your persona described? Note which segment your persona is in and whether the data confirms their pain.:** _(not filled in)_
- **Does the low adoption confirm your persona is burdened by tools they don’t use? Note whether the low scheduling adoption (42%) for coordinators matches your M2 moment of misery.:** Yes
- **Does the workflow data match the manual process or hack you documented in M2? Note whether the specific drop-offs or time gaps explain why your persona avoids the digital tool.:** Yes it does. The drop offs is clearly evidenced from workflow steps "Assign routes via optimizer" and "Log Compliance Checks" when the frontline deliver delivers the package (avg time of 8.2 and 14.6 respectively as compared to benchmark). We can see that the extended time taken is due to the multi-screens they need to navigate in order to complete the checks which contributes to their frustrations. Hence, they have abandoned the tool and identifed manual workarounds.
- **Look at the CSAT heatmap. Which specific cell most directly maps to your persona’s friction? Note how the NPS trend justifies the urgency of your M1 Problem Hook.:** Compliance (2.8) and scehduling (1.9),

## Step 3 · Craft your hypothesis
- **Qualitative evidence (from M2) , quote the specific friction / moment of misery for your persona:** On every stop, a slow, buried flow to confirm a delivery pushes drivers to text dispatch instead. Diego: three screens, package in hand, clock running.
- **Quantitative evidence (from M3) , name the metric or data point that confirms the pain; cite the number:** There are a few namely
- **Persona , role, goal, and the friction you confirmed in the reconciliation steps:** Frontline Delivery Drivers
- **Problem you are solving , one sentence describing the specific friction this initiative removes:** Frontline delivery drivers can’t record a delivery quickly inside RouteLogic, so they text it to dispatchers instead, and the platform stops being the source of truth
- **Strategic outcome , what behaviour change do you expect, and how does it map to retention / revenue / churn?:** Behaviour changes we'd expect:
- Drivers mark a stop done in the app in one quick action, instead of texting the dispatcher.
- Dispatchers see the board update on its own, instead of updating it by hand.
-Dispatchers trust the system and stop cross-checking it against texts.
-Frontline staff come to see RouteLogic as the fastest way to do the job, not an admin burden.

If drivers and dispatchers find RouteLogic quick and reliable, they will use it for all their daily work, and customers will find it hard to replace. That protects our revenue, starting with the largest account that is trialing a competitor because we are too slow. Fixing the core action removes their reason to leave, and winning back frontline usage reduces the risk of losing other accounts too. Once fleets rely on RouteLogic every day, they are more likely to buy more, and accurate real-time data makes our premium reporting and compliance features more valuable to them.
- **Primary success metric (initiative signal) , the leading indicator that tells you the gap is closing:** The share of stops marked complete in the app (instead of by text).
- **Guardrail metric (product signal) , the metric that must NOT drop; it protects your existing base:** Weekly use of the specialized enterprise features (eg: reporting, AI predictive ETA
- **Decision window , how much time or data before you scale, pivot, or kill? minimum threshold to proceed?:** 90 days after launch to the pilot group, with a checkpoint at every 30 days and a final decision at 90
- **Draft your full hypothesis sentence , one to three sentences; quote the metric, name the persona, name the outcome:** Based on research showing that drivers like Diego skip a three-screen “mark delivered” flow and text their dispatcher instead, and on internal data showing falling usage among fleet coordinators, I believe that reducing delivery confirmation to a single quick action for frontline drivers will make the app the place deliveries are recorded, as measured by a 30% relative increase in the share of stops marked complete in the app within 90 days. I will protect weekly use of specialized enterprise features (no meaningful drop from baseline) and will make a go/no-go decision after a 90-day pilot, with a checkpoint at 30 days.
