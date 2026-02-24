# Customer Central: Talking Points

**Total Time:** 20 minutes
**Style:** Conversational, energetic, narrative-driven (NotebookLM-inspired)
**Audience:** Justworks Engineering and Design leaders (they have read the proposal)

---

## Slide 1 — Customer Central

"Thanks for being here. Today we're diving into something big. Not just an improvement — a fundamental shift in how Justworks scales support and serves its customers."

"You've read the proposal, so I'm not going to walk you through it page by page. What I want to do is walk you through the strategic reasoning behind the decisions — the *why*, not just the *what*."

"Take a look at this question on the screen. *What if agents already knew everything before the customer said hello?* This isn't just a catchy phrase. This is our North Star. It's the gold standard for what a customer experience should feel like. The agent knows everything before the customer even finishes their greeting. Smart. Fast. One step ahead."

"But let's be honest — a vision is one thing. The reality on the ground can be pretty different. So what does that reality look like right now?"

---

## Slide 2 — The Ideal Encounter

"Before we get into the problems, I want you to picture something."

"A customer calls. Before the agent says a single word, their screen already shows the caller's name, their company, their open tickets, their health score. The agent says: 'Hi Sarah, I can see you have an open ticket about your last payroll run — let me pull that up.' Thirty seconds. Done."

*(pause)*

"That's not science fiction. The data already exists inside Justworks — it's just scattered across five systems that don't talk to each other. So the question isn't *can we do this*. It's *why haven't we yet*."

"Now let me show you what agents are actually dealing with today."

---

## Slide 3 — The Agent's Reality Today

"To really get why this project is so crucial, we've got to step into the shoes of our agents for a minute. I've started calling it the Agent's Scavenger Hunt. And honestly, that's exactly what it is."

"5 to 6. Just let that sink in. For every single call, every chat, every email — our agents are juggling five to six different disconnected systems. Zendesk over here, Salesforce over there, the production database, billing, payroll, Slack. They're spending their days switching tabs, copying and pasting, just trying to piece together the customer's story."

"Look at this timeline. Phone rings — who is this? Open Salesforce, find the company. Open Zendesk, check ticket history. Check billing. Check payroll. By T-plus-120 seconds, the customer has already repeated themselves, and the agent can *finally* start helping."

"They're forced to be detectives instead of what they should be — problem solvers."

---

## Slide 4 — Six Compounding Problems

"And here's the crazy part. Despite this chaotic scavenger hunt, our agents are absolute rockstars. Plus-60 NPS. Nine Stevie Awards. That's incredible. But let's be real — this quality is built on pure human heroics. They're winning *in spite of* their tools, not because of them. And that model? It just doesn't scale."

"We've dug in and broken the scavenger hunt down into six major pain points."

"The context-switching tax — every time an agent switches screens, they lose focus and time. The caller identity problem — that first minute of every call wasted just figuring out who they're talking to. The repeat-yourself problem — the one customers hate the most. And on top of that, agents are flying blind. No real-time account status. No way to spot chances to be proactive. No idea what other teams might be doing for the same customer."

"These aren't little annoyances. This stuff adds up to serious wasted time, agent frustration, and a choppy experience for our customers. P1 through P4 map directly to our Phase 1 MVP. P5 and P6 need the data foundation we build first."

"So now that you feel the pain — let me show you where we're going."

---

## Slide 5 — The Grand Vision

"Before I show you the plan, I want you to see the destination. This is the end state. This is what Customer Central becomes when all three phases are complete."

*(let the Phase 3 screenshot breathe)*

"Look at this screen. AI-generated summaries before every call. Churn prediction flagging at-risk accounts weeks before they cancel. An agent copilot suggesting next actions in real time. Upsell intelligence. Cross-functional signals flowing to product, sales, marketing, and leadership — not just support."

"This isn't just a better agent tool. This is Customer Central as the intelligence core of the entire business. Every customer interaction generates data. That data trains models. Those models create insights that feed every team in the company."

"That's the vision. Now — how do we get there?"

---

## Slide 6 — The Strategic Case

"But first, why does this matter strategically? For leadership — for everyone in this room — this is about changing our scaling equation."

"Nine Stevie Awards. Plus-60 NPS. Ten thousand customer companies. A 27-billion-dollar PEO market growing at 10% CAGR. The quality is exceptional."

"But here's the crossroads. As we bring on more customers, we're faced with a tough choice. Either our headcount grows right along with our customer base — which is incredibly expensive — or we let service quality slip. And I think we can all agree neither of those options is on the table."

"The old model is linear. More customers means more agents. Costs scale one-to-one with growth. The new model — the one Customer Central unlocks — is logarithmic. As we add more customers, our support costs barely move because we're getting massive leverage from smarter tools. This is how we change our scaling equation. Linear to logarithmic."

"And the one metric to rule them all — our true North Star — is NPS per CSO headcount dollar. This single number tells us if we're keeping customers happy while becoming more efficient. Not NPS alone. Not AHT alone. The ratio that captures leverage."

"One more thing: Justworks serves small businesses without dedicated HR. When their admin calls, CSO might be their *only* expert. That raises the bar even higher."

---

## Slide 7 — Three Phases, One Dependency Chain

"You've seen the vision. Here's the roadmap to get there — and why you can't skip a step."

"Phase 1: the Foundation. This is our MVP. In just seven weeks, we deliver that unified view and kill the old workflow. Done."

"Phase 2: Intelligence. Here we start getting smarter — layering in ML-driven health scores, proactive alerts, write-back actions."

"Phase 3: Prediction. This is the really exciting stuff — the grand vision you just saw. Churn prediction, AI summaries, agent copilot — the works."

"And what's absolutely key here is that each phase builds directly on the one before it. We have to earn our way to the next level."

"Let me be crystal clear on this: Phase 1 is all about getting the fundamentals perfect. This is the non-negotiable foundation. Because if the data isn't right, if our agents don't trust it, then nothing else we want to build on top will ever work. It's that foundation of trusted data that unlocks the magic of Phases 2 and 3."

---

## Slide 8 — The Agent Dashboard

"Now let's get real. We have seven weeks. Here's where we start."

"This is the product that actually solves the scavenger hunt. Let me introduce you to Customer Central — the Phase 1 MVP."

*(let the screenshot breathe)*

"This. This is the agent's new world. A single screen. A single pane of glass. Designed to load in under three seconds. Before our agent even finishes saying hello — they see who's calling, what company they're with, their account status, recent conversations, open tickets, and a clear health score."

"No more tab switching. No more scavenger hunt. Just instant, actionable information."

"Walk the flow strip with me: under 500 milliseconds for instant search. Under 2 seconds for the full caller card. One click to expand the health score. Everything from those 120 seconds of detective work — on one screen, in under 3 seconds."

"This one screen is going to completely change their day-to-day."

---

## Slide 9 — Context in Seconds

"Phase 1 delivers three core capabilities — the foundation everything else depends on."

"First: Instant Search. Fuzzy matching across 500,000 contacts — by name, email, phone, company. Results show up before the customer finishes their greeting. Under 500 milliseconds."

"Second: the Caller Card. Full profile loads in under 2 seconds. Identity, company, plan type, billing status, payroll countdown, open tickets. No toggling between systems. It's all right there."

"Third: Health Score. One click, expandable breakdown — billing, payroll, support, satisfaction. Rules-based and transparent. No black box."

"We are wiping out the context-switching tax and the repeat-yourself problem right from day one. This is a targeted solution to our biggest operational headaches."

"And one critical design principle: this is a read-only MVP. We validate data accuracy for 60-plus days before agents can act on it. Wrong data displayed? Fixable. Wrong data written back? That's a disaster. Read first. Write later."

---

## Slide 10 — 7-Week Roadmap

"Seven weeks, and every single week ends with a decision gate. If data accuracy or agent trust isn't there, we extend rather than push forward."

"Weeks 0 through 2: Discovery and validation. Shadow agents. Validate data access. Build the API core and search. The whole point is to de-risk before committing to scope."

"Weeks 3 through 5: Feature build sprint. All 11 features built and tested. Alpha with 5 volunteer agents. Daily feedback standups."

"Weeks 6 and 7: Beta with a full pod — 20 to 30 agents. Identify champions. Gated rollout to all of CSO."

"So what specifically goes into those 11 features?"

---

## Slide 11 — Phase 1 MVP: 11 Features

"Our MVP isn't just a grab bag of the most popular feature requests. It's the foundational layer. It's what makes every cool thing we want to do in the future — AI summaries, proactive churn alerts, all of it — even possible. We're not putting a new coat of paint on the walls. We are building the load-bearing beams for the entire house."

"Eleven features across three categories. Let me walk through the logic."

"The Foundation layer — three features — solves the first 60 seconds of every call. Instant caller recognition with fuzzy search. A unified interaction timeline — phone, email, chat in one view with open tickets pinned to the top. And the account status strip. If we build nothing else, these three eliminate the system-hopping."

"Problem panels — six features. These map to the top call drivers: paycheck discrepancies, payroll failures, tax documents, benefits enrollment, invoices, payment cascades. Only three are full builds. The other three are deep-link integrations — 80% of the coverage at 20% of the build cost."

"Health — two features. Lightweight health score and a leadership portfolio view. And here's an important note: HS-1 and HS-2 are the beginning of Phase 2, delivered here in lightweight rules-based form. The ML-driven version comes in Phase 2."

"All of it read-only. Read before write. Sixty-plus days of accuracy validation before we let agents act on this data."

---

## Slide 12 — Data Architecture: 5 Sources

"To make any of this work, we need data. Fifty-five data fields from five source systems — Salesforce, Zendesk, the production database, billing and payments, and the event stream."

"All of it flows into a separate read-optimized aggregation layer. We're not querying source systems directly. Pre-computed, cached, optimized for sub-500-millisecond page loads. Source systems remain authoritative."

"This is the plumbing that makes everything fast."

---

## Slide 13 — Loading Strategy + Integration Risks

"Four loading tiers, designed around how agents actually work."

"Instant — under 500 milliseconds. Identity and status from cache. On screen before the agent finishes saying hello."

"Fast — up to 2 seconds. Interaction timeline and recent changes. Arrives while the customer is still talking."

"Background — 2 to 5 seconds. Tax badges, benefits summary. Loads silently — the agent never sees a spinner."

"On demand — fetched on click. Pay stubs, invoices, cascade detail. Only loaded when the agent actually needs it."

"Three integration risks, all flagged for Week 1 discovery. The Zendesk-Salesforce join key — it may not exist cleanly. Real-time payroll status — unknown if queryable or batch. And payment cascade logic — the business rules might only live in someone's head. Each risk is scoped to affect individual features, not the whole MVP. That's by design."

---

## Slide 14 — Team: 5+1 Model

"Five plus one. Two full-stack engineers, a data services engineer at 75%, a product designer, me as PM full-time, and a shared QA engineer. Twenty-three engineer-weeks total."

"The key design decision: work is split by vertical, not by layer. Each engineer owns a complete slice — database to API to UI. No handoffs. Engineer 1 owns the foundation features. Engineer 2 owns the problem panels. The data engineer builds the aggregation layer. Clean ownership, clean accountability."

"Biggest staffing risk: the data services allocation. If that 75% slips, the whole timeline shifts."

---

## Slide 15 — What I Don't Know

"Look, a project this important needs more than just good plans. It needs honesty about what we don't know yet."

"Seventeen questions mapped to five stakeholders. Three of them could change the scope entirely."

"One: Caroline Crossland, Salesforce Solutions Architect. Is there a reliable join key between Salesforce accounts and Zendesk organizations? This is the single highest-risk data question. If there's no shared identifier, the interaction timeline degrades to Zendesk-only history."

"Two: Evan Lehrman, Senior Technical PM. Can we get read-replica access to the production database? This determines whether we show live data or cached snapshots."

"Three: Renee Orser, VP of Internal Tools. What signals does leadership actually use to assess account health? I have a hypothesis, but it needs validation."

"And I want to be completely transparent: I haven't spoken to a single CSO agent to validate these problems. I haven't dug into support ticket volumes. This is from the outside looking in. I've made 47 explicit assumptions, and every one is documented in the proposal. My first actions on the inside would be to shadow 5 to 10 calls and pull ticket data to validate or correct the priorities."

---

## Slide 16 — Success Metrics

"A project this important needs more than just feel-good stories. We've defined a really clear, rigorous set of metrics to measure success, keep ourselves accountable, and prove the business case."

"But above everything else: CSO agent adoption is the number one metric. They have to *want* to use this because it makes their job easier — not because they were told to. If agents don't adopt it, nothing else on this slide matters."

"Leading indicators — weeks 1 and 2: Orientation time under 10 seconds. Systems accessed per call drops from 5 to 2. Health score accuracy at 80-plus percent."

"Outcome metrics — 90 days: We're targeting a 15 to 20% drop in average handle time. 10% bump in first-contact resolution. North Star ratio trending up quarter over quarter."

"Guardrails — continuous: NPS floor stays at plus-60, data accuracy at 98%, zero increase in escalation rate. We have to make sure we're not trading quality for speed."

---

## Slide 17 — Pull-Based Rollout

"This is pull-based adoption. If agents don't prefer it, we don't force it — we fix it."

"Alpha — Week 5. Five volunteer agents, supplementing their existing tools. Daily 15-minute feedback standups. Gate to proceed: data accuracy at 95% or higher, and three out of five agents prefer it."

"Beta — Week 6. Full pod, 20 to 30 agents. Customer Central becomes their primary tool. Gate: 70% using it as primary, satisfaction at 3.5 out of 5, and 2 to 3 champions identified."

"Launch — Week 7. Champions co-facilitate training. They become peer trainers. And that's the key — agents trust other agents more than the PM telling them about a new tool."

---

## Slide 18 — How I Got to the MVP

"People sometimes ask: why these 11 features? Why not 8? Why not 15? We followed a really specific four-step process to figure out where to start."

"Step 1: We broke down the core jobs our agents actually need to do. Every feature maps back to a job."

"Step 2: Dependency stack. Foundation before operations before intelligence. You can't score data you haven't consolidated."

"Step 3: Score and rank. Twenty problems scored on impact, confidence, and ease. And this was the real aha moment — the top-scoring problems all converge on the same six data fields. That convergence gave us a super clear boundary for the MVP."

"Step 4: Trust progression. An agent isn't going to act on data they don't trust. So read-only first. Build trust. Then write-back in Phase 2."

"That convergence is why 11 features feel achievable in 7 weeks. We're not building 11 independent features — we're building a shared foundation that surfaces in 11 different ways."

---

## Slide 19 — From Reactive to Proactive

"So when you pull it all together — the product, the roadmap, the business case — you see that this entire thing is driving toward one really ambitious vision."

"On the left: reactive. Agents fighting fires. 120 seconds of context-hunting. Five systems. No unified view. A person holding back a flood."

"On the right: proactive. Agents standing on solid ground. Complete context in 3 seconds. One screen. Full picture. Not scrambling — in control."

"The MVP builds the unified workspace. That's the foundation. Phase 2 layers intelligence on top: ML scoring, proactive alerts, write-back actions. Phase 3 adds prediction: AI summaries, churn forecasting, cross-functional signals we can feed to product and sales."

"Each phase produces the data the next phase needs. This isn't a feature roadmap — it's a dependency chain. And without the clean, consolidated data from Phase 1, none of the rest is possible."

"This is how we transform CSO from a reactive cost center into a proactive strategic asset for the entire business."

---

## Slide 20 — Prototype Demo

"Let me show you what this actually feels like. This is a working prototype — built with sample data, showing the proposed interaction model."

*(interact with the prototype)*

"Cmd+K. Type 'Sarah Chen.' Results in under 2 seconds across 500,000 contacts."

"Look at what loads: Acme Corp, admin role. Billing green. Payroll countdown. Two open tickets. The entire 60 seconds of context-hunting — gone."

"Click into the interaction timeline — every phone call, email, and chat, with open tickets pinned to the top."

"Expand the health score. Transparent breakdown. No black box."

"Single screen. Complete context. Under 3 seconds. That's the MVP."

---

## Slide 21 — Aspirational Closing

*(read from the screen, slowly)*

"What if the customer never needed to call in the first place?"

*(pause — let it land)*

"Not because we want to get rid of our amazing support team, but because we want to build a system so smart, so anticipatory, that it finds and fixes problems before our customers even notice them."

"Today: 120 seconds of detective work before helping begins. With Customer Central: complete context in under 3 seconds. That's the Phase 1 win."

"But the real arc is bigger. Phase 1 builds the foundation. Phase 2 adds intelligence. Phase 3 brings prediction. Every phase earns the next. A fundamental shift from reactive problem-solving to proactive partnership. That is the future that Customer Central is going to make possible."

"All of it starts with seven weeks and 23 engineer-weeks of investment."

---

## Slide 22 — Explore the Proposal

"Everything is on this slide — all the artifacts, all live, all clickable. Strategy docs, the interactive prototype, data models, the Miro workshop board, even the original case study prompt. The prototype is fully functional — search, click through tabs, expand the health score. It's designed to be played with, not just read."

"I've made 47 explicit assumptions in this proposal. Some of them are wrong. That's expected — I built this without access to your systems, your data, or your agents. The proposal is designed to be a starting point for conversation, not the final answer."

"With that, I'd love to open it up for questions. We can talk about the proposal, the roadmap, the tech, the business impact — whatever's on your mind."

---

## THREAD TO MAINTAIN THROUGHOUT

Every section subtly reinforces one message: **"I make decisions under uncertainty, I'm transparent about what I don't know, and I sequence work so that each phase de-risks the next."** The audience is evaluating PM judgment, not whether the feature list is perfect.

---

## PACING REFERENCE

| Section | Slides | Time | Duration |
|---|---|---|---|
| Opening | 1 | 0:00 – 0:45 | 45 sec |
| The Dream | 2 | 0:45 – 1:30 | 45 sec |
| The Problem | 3–4 | 1:30 – 3:00 | 1 min 30 sec |
| The Grand Vision | 5 | 3:00 – 4:00 | 1 min |
| The Strategic Case | 6 | 4:00 – 4:45 | 45 sec |
| Three Phases | 7 | 4:45 – 5:30 | 45 sec |
| Agent Dashboard | 8 | 5:30 – 6:15 | 45 sec |
| Context in Seconds | 9 | 6:15 – 6:45 | 30 sec |
| 7-Week Roadmap | 10 | 6:45 – 7:30 | 45 sec |
| MVP Requirements | 11 | 7:30 – 9:15 | 1 min 45 sec |
| Data Requirements | 12–13 | 9:15 – 10:45 | 1 min 30 sec |
| Engineering Resources | 14 | 10:45 – 11:30 | 45 sec |
| Open Questions | 15 | 11:30 – 12:45 | 1 min 15 sec |
| Success Metrics | 16 | 12:45 – 14:30 | 1 min 45 sec |
| Rollout & Training | 17 | 14:30 – 15:30 | 1 min |
| MVP Rationale | 18 | 15:30 – 17:15 | 1 min 45 sec |
| Reactive to Proactive | 19 | 17:15 – 18:00 | 45 sec |
| Prototype Demo | 20 | 18:00 – 19:00 | 1 min |
| Closing | 21–22 | 19:00 – 20:00 | 1 min |

**Then:** 10 minutes of panel questions, followed by 45-minute workshop.
