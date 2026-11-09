# AI Synthesis, Product Health & Insights Summary (Module 2)

## Responses
- **Assumption to validate #1:** Multi-claim consumers abandon mainly because they can’t combine claims, not because the total is unaffordable.
- **Assumption to validate #2:** People drop at the income question because it’s ambiguous (“this month or a normal month?”), not because they refuse to share.
- **Assumption to validate #3:** Differences between the portal and the letter in purchased portfolios damage trust enough to block agreements.
- **Moment of misery / red flag #1 (e.g., “user gave up after 3 tries”):** N-03 could only see one claim at a time and didn’t know whether paying one would stop the letters about the other. T-202 confirms the portal has no way to set up one plan for two claims. Mara has two claims, so this is her journey. The red flag is that the portal structurally can’t do what multi-claim consumers came for. That fits their low agreement rates (37.7% with two claims, 27.6% with three or more) and the 17.3% of agent contacts asking whether claims can be combined.
Tests assumption: multi-claim consumers abandon because they can’t combine claims, not because the total is unaffordable.
- **Moment of misery / red flag #2:** N-01, a shift worker on her break, didn’t know whether “income” meant this month or a normal month, so she closed the portal. N-06 was afraid a wrong number would be used against her. T-206 says there’s no help text on why income is asked or how long it’s kept. Three bugs make the step worse: T-201 (mobile photo uploads time out, 853 journeys stuck), T-204 (the back button clears the affordability answers) and T-207 (the reminder sometimes arrives after the first due date). The red flag is that the most sensitive step is both unexplained and technically fragile, and it fails hardest for mobile, variable-income users.
Tests assumption: drop-off here comes from ambiguity, fear and bugs, not refusal to share.
- **Moment of misery / red flag #3:** N-02 picked the shortest plan because it “looked like the right answer,” then missed the second payment. N-05 got a yes from the chat in a minute but didn’t know what happens after a late payment. T-208 confirms the chat confirms plans without showing missed-payment consequences. The red flag is that the portal makes agreeing easy but never makes the consequences clear. It produces plans that count toward SSR and then break, the same pattern as Month 4.
Tests assumption: showing consequences before confirmation reduces broken plans and “what if I miss” contacts without lowering agreements.

These are fictional practice data, so treat them as signals to validate, not proven findings.
- **Product Health & Insights Summary (Claude's output):** # Product Health & Insights Summary: Digital Instalment Journey (German Portal)

*Based on fictional practice data (sample month = Month 6). Not Riverty research.*

## Executive Summary

The digital instalment journey works in principle but is not dependable: a mobile upload failure and mistimed reminders break the journey for a meaningful share of consumers, on a channel where roughly 78% of them start. The deeper problem is experiential, because the portal makes agreeing to a plan easy but understanding it hard, so consumers either abandon at sensitive steps or accept plans they later break. As a result, the Self-Service Rate is rising while broken agreements and comprehension-driven agent contacts stay high, which means the headline metric currently overstates product health.

## Thematic Synthesis

### 1. Technical Stability

The journey's technical failures cluster at the points where consumers are most hesitant: the document step and the first payment. One defect alone blocks hundreds of journeys a month, and it falls disproportionately on mobile users, who already agree to plans less often than desktop users (43.8% vs 54.0%). A second defect undermines plans that were successfully created, by sending the reminder only after the due date has passed.

- **Critical:** Income document upload times out on mobile for large photos, leaving 853 journeys in the sample month waiting on a document that never arrived. This coincides with the largest single drop in the funnel (about 1,300 starters lost at the document step) (T-201).
- **High:** The reminder before the first instalment sometimes arrives after the due date, setting up early missed payments that are system-caused rather than consumer-caused (T-207).

### 2. Journey Design & UX

The journey's structure does not reflect how many consumers' debt actually looks. Consumers with several claims, who make up about 35% of starters, cannot see or settle them together. Agreement rates fall steeply as claim counts rise (52.1% with one claim, 37.7% with two, 27.6% with three or more). Plan presentation also steers consumers toward options they cannot sustain, and the income question is ambiguous for people whose pay varies.

- **Critical:** No combined plan across multiple claims. Consumers cannot tell whether settling one claim stops action on another (T-202, N-03).
- **High:** The plan screen presents the shortest plan first, and consumers read it as the "right" answer. Since this default was introduced in Month 4, the share of plans missing a payment within 60 days rose from 15.6% to 19.0% (N-02).
- **High:** The income question is ambiguous ("this month or a normal month?"), which hits shift and variable-income consumers hardest. This group also misses payments most often, at 22.5% (N-01).

### 3. Trust & Clarity

Many consumers hesitate because they are uncertain, not because they are unwilling. They don't know how their data will be used, what happens if they miss a payment, or whether the amount shown is correct. Without that reassurance in the portal, consumers either leave, understate their situation, or call to have a person confirm it. The chat assistant speeds up confirmation without closing these gaps: chat users agree more often but miss payments more often too (21.6% vs 18.3%).

- **High:** Consequences of a missed or late payment are not explained before confirmation, in the portal or in chat. This is the most common reason for agent contact (18.6%) (T-208, N-05).
- **High:** No explanation of why income is requested or how long it is kept, which creates fear of self-incrimination among financially stretched consumers (T-206, N-06).
- **Medium:** The portal amount differs from the letter in 531 journeys, 343 of them in purchased portfolios. Consumers stop rather than agree to a figure they can't reconcile (T-203, N-07).
- **Medium:** Some consumers still trust a human more than the portal to tell them whether a plan will cost more (N-04).

### 4. Support Load & Agent Experience

The agent channel is absorbing questions that the digital journey could answer, and the handoff makes each contact more expensive. Around 31% of starters contact an agent within seven days. The top three reasons are all comprehension questions and make up about 52% of contacts, while only 14.7% concern wanting a lower amount. Agents also start each call with no visibility of the consumer's online input or the logic behind the plan offered.

- **High:** The agent screen does not show what the consumer entered online, so agents repeat identity, affordability and case checks (T-205, N-08).
- **High:** Agents can't see why a plan was offered, which makes failed agreements hard to diagnose or correct (T-205, N-09).
- **Medium:** Handle time is uniform across contact reasons (about 11 to 13 minutes), so the cost of simple comprehension questions is the same as that of complex cases.

### 5. Governance, Data & Stakeholder Risk

The issues above extend beyond the consumer journey into client relationships, compliance and portfolio economics. The current setup gives clients, compliance and portfolio teams a weak position to stand on. Plan logic is not visible to agents, so it is unlikely to be explainable to consumers or auditors. Broken plans show up directly in client reporting. And acquired portfolios vary in the data quality the journey depends on.

- **High:** Plan recommendations cannot currently be explained to consumers or agents, which conflicts with stated compliance expectations (N-12, N-09).
- **High:** SSR counts a plan as resolved when it is created, so the metric rises even when broken agreements rise. Of the 188 extra agreements between Month 3 and Month 6, about 160 broke within 60 days.
- **High:** Client reporting is sensitive to spikes in broken plans and complaints, which links journey quality directly to client relationships (N-10).
- **Medium:** Acquired portfolios carry inconsistent data, and some lack reliable contact history, which likely contributes to amount mismatches and weakens affordability inputs (N-11).

**Minor Technical Debt:** The back button on the plan review screen clears the affordability answers, forcing consumers to re-enter sensitive information when they try to compare options (T-204, Low).

---
- **Did the AI catch the specific moment of misery / pain point you found in Step 1?:** Partly. Partly. The summary covered the issues behind all three, but it described them as findings rather than testing them as hypotheses. In a couple of places it also leaned toward the very explanation each hypothesis still has to prove.
- **Did it smooth over a critical frustration into a generic bullet point?:** Yes. It did not focus on the three Hypothesis defined.
- **Did the AI try to suggest features or a roadmap despite the constraints?:** No.
- **Logic leak / hallucination #1 (e.g., “AI suggested a new search bar feature, roadmap leak”):** 1. I treated a hypothesis as a finding. In the Product Health summary, I rated the missing combined plan “Critical” and described it as the cause of multi-claim abandonment. At that point it was only a correlation plus one interview and one ticket.
- **Logic leak / hallucination #2:** 2. I used my own inference as evidence. In the drill-down, I guessed that plans are built per claim and that affordability logic ignores the other claims. I labelled it an inference, but then let it drive the verdict (“strongly supported”) and the recommendation (“improves agreements kept”). The conclusion rested on an assumption I had introduced myself.
