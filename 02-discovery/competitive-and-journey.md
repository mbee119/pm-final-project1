# Competitive Analysis & Journey Map (Module 2)

## Responses
- **Role, who are you solving for? (the specific user segment or profile):** Frontline delivery drivers who complete dozens of stops a day and need to confirm each one fast, represented by Diego.”
- **Goal, what is this user ultimately trying to achieve?:** To complete every stop on his route quickly and reliably, and let dispatch know it’s done, so he can finish his shift on time without relying on workarounds.”
- **Friction, the main barrier (moment of misery) stopping them from succeeding:** On every stop, a driver has to work through a slow, buried interface to record a simple fact, that the delivery is done. They skip the app and use a workaround instead: texting dispatch, keeping paper manifests, or calling the office.

The main barrier: the core actions, confirming a delivery and starting a route, take too many screens and sit too deep in the app. They are used dozens of times a day, at the moments when drivers can least afford to stop and navigate.

The moment of misery: Diego has just handed over a package, with his hands full and the clock running, and the app asks for three screens of taps to confirm it (UXR-01, BUG-2055). Starting the route has the same problem: the button a driver uses 30 times a day is buried under features he has never touched (UXR-11, BUG-2079).

Why it stops them succeeding: drivers’ goal is to complete stops and keep dispatch informed. The slow flow pushes them off the platform, so the app’s record of the day is wrong, and the dispatcher’s board goes stale.

Evidence strength: the three-screen flow is confirmed by both a user quote and a bug report (UXR-01, BUG-2055), and all seven focus group drivers put core-action speed first (UXR-12).
- **External tools, the outside platforms or tools the user is forced to use:** For Diego, the research names exactly one external tool: text messaging to his dispatcher.
- **The process, the 3 to 5 manual steps the user takes to get the job done:** 1. Hand over the package at the doorstep. The delivery itself is complete, but the app still shows the stop as open.
2. Decide to skip the app. Facing three screens of taps with a package in one hand and rain falling, he doesn’t start the Mark Delivered flow (evidenced, UXR-01).
3. Text the dispatcher that the stop is done. He composes a message identifying the stop, likely from memory or by glancing at the stop list (message format is assumed).
4. Move on to the next stop. The text is his only record of completion, so the app’s status for that stop stays unchanged.
5. Dispatcher reconciles it by hand. The dispatcher reads the text and relays or updates the board manually, which is where the status lag and trust issues in UXR-09 and BUG-2072 come from. This step happens on the dispatcher’s side, not Diego’s.
- **Core frustration, the exact moment the process feels most “broken”:** The most broken moment is step 2: just after handing over the package, when Diego has to record the delivery and the app asks for three screens of taps. His hands are full and the clock is running, and all he needs to say is that the stop is done. This is the point where he gives up on the app and texts his dispatcher instead (UXR-01, BUG-2055).

This is the most broken point because every later step follows from it. The text, the unchanged status in the app and the dispatcher’s manual catch-up all happen only because he chose to skip the app here. It is also where the mismatch is sharpest: a task that should take a second is built as a multi-screen flow, at a moment when he has the least capacity for it. It is the clearest observable point in the research where the platform loses the job to a text message.
- **The evidence, a specific quote or behavior from the research that proves this:** The strongest evidence is Diego’s own words in UXR-01:

“To mark a stop delivered I tap through three screens. In the rain, at a doorstep, with a package in one hand. I’ve started just texting my dispatcher instead.”

This one quote proves all three parts of the frustration. It names the friction (three screens to complete one action), the moment (a doorstep, with a package in hand) and the behavior (he has abandoned the app for a text message).
- **Your journey map, a shareable link, or the map file you committed (e.g. journey-map.html):** https://github.com/mbee119/pm-final-project/blob/main/02-discovery/Future%20State%20Journey.pdf
