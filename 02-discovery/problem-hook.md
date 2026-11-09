# Problem Hook & Value Proposition (Module 1)

## Responses
- **Chosen path, which Riverty business-unit case are you using?:** BU Collection
- **Strategic crisis, based on the brief, if the company does nothing for 12 months, what happens to its market position?:** Without action, Riverty loses ground gradually: agent workload stays high (in the fictional practice data, 31% of journey starters contact an agent within 7 days), and pressure on SSR encourages plans that lift the metric but break more often (missed payments up from 15.6% to 19.0%). After 12 months this becomes visible outside the company: clients question complaints and broken plans at contract renewal, and weaker collection rates on purchased portfolios force more cautious bids, so more efficient competitors win both client mandates and portfolios.
- **Moment of misery, what is the user likely doing outside the product (Google, spreadsheets, a competitor) because your tool isn’t serving them?:** Mara’s moment of misery comes right after the digital reminder. She’s on her phone during a break and reaches the income question. She doesn’t know whether “income” means this month or a normal month (N-01), she can only see one claim at a time (N-03), and nothing tells her what happens if she misses a payment. When the portal leaves her stuck there, she does six things outside it. The data pack only directly shows the first one; the rest are my inference from the interviews and tickets.

She calls an agent. This is the main workaround, and the data confirms it: 31% of journey starters contact an agent within 7 days. The top three reasons are exactly her open questions: missed payments, combining claims, and why income is asked.
She searches Google. Likely searches include “what happens if I miss an instalment with a debt collector,” whether a plan affects her credit record, and whether Riverty is legitimate. N-07’s mismatch between the portal amount and the letter makes the “is this claim even right?” search especially likely. That leads her to forums, consumer advice centres and debt counselling services, which give generic answers about her specific case.
She works out her own budget. With shift income, she opens her banking app, scrolls through recent months, and uses a calculator or notes app to guess a safe monthly amount. The portal asks her for that number but doesn’t help her find it.
She compares paper letters with the screen. She photographs letters and cross-checks amounts and claim references because the portal doesn’t show both claims together or match the letter (T-202, T-203).
She pays another creditor first. Her real “competitor” isn’t another collection agency; it’s every other bill. A landlord, a phone contract or a buy-now-pay-later provider with a simpler process gets paid first. In the worst case she covers the gap with her overdraft or by borrowing from family.
She does nothing and means to come back. This is the quietest and most expensive option (N-01). Letters escalate, the case gets older, and she returns, if at all, more anxious.

Daniel has his own version of this. Because he can’t see what she entered online (T-205, N-08), he re-asks everything and probably keeps personal notes on failed plans to explain them later (N-09).

What this means for the product: the portal’s biggest competitor isn’t another company. It’s the phone line, Google and doing nothing. Each workaround points to a backlog item: B2 answers the Google searches, B1 replaces the letter comparison, B3 and B6 replace the do-it-yourself budget, and B4 ends Daniel’s re-asking. Each can also be measured as a signal, such as contact reasons, return visits and time between reminder and resolution.
- **Problem hook, summarize the business risk and user pain into one urgent sentence.:** Every month, thousands of consumers like Mara try to set up a fair instalment plan on their phone, get stuck on unclear income questions and claims they can’t combine, and either call an agent (31% of starters) or sign a plan they can’t keep (19% miss a payment within 60 days), which inflates Riverty’s Self-Service Rate while quietly eroding recoveries, client trust and the value of its purchased portfolios.
- **Value proposition, based on the initiative in your assigned Riverty case, what is the new value and why is it urgent to launch now?:** The new value

For consumers like Mara, it turns a confusing, anxious task into one she can finish on her phone during a break. She gets one plan, one date that matches pay day, and no fear that her answers will be used against her.

For agents like Daniel, it ends repeated checks. Calls start with context, and a failed plan comes with the reason it was offered.

For clients and portfolio owners, it trades plans that look good on day one for plans that hold. That means fewer broken agreements, fewer complaints and steadier lifetime recovery.

For Riverty, it makes SSR trustworthy, because success is measured on plans kept, not plans created.

Why launch now (based on the fictional practice data)

The problem is getting worse, not holding steady. Missed payments within 60 days rose from 15.2% to 19.0% over six months, and the jump began right after the Month 4 change that put the 6-month plan first.

The SSR target is already rewarding the wrong behaviour. Every month without a fix adds roughly 730 broken agreements and hundreds of avoidable agent hours, while the dashboard shows progress.

The worst outcomes hit the largest underserved groups. Multi-claim consumers (about 2,970 starters a month) and shift workers fail most often, and they are exactly who the pilot segment is meant to serve.

Finally, the Germany pilot is the template for other European markets. Getting the reusable parts right now (combined claims, explanations, agent handoff) avoids each market building its own workaround later.

## Cold-read your own hook
- **Is the business risk high enough to justify a new initiative, a high-stakes threat, or a minor inconvenience?:** The risk is high enough to justify a focused new initiative: broken plans are rising (missed payments up from 15.2% to 19.0% in six months in the fictional data), SSR hides the decline, and about half of agent time goes to questions clearer explanations could answer. It isn’t an existential threat yet, since 81% of plans still hold and the fixes use existing systems, but it would become one if broken plans start driving client complaints, lost renewals or regulatory attention.
- **Is the moment of misery a systemic problem or just an edge case?:** It’s systemic. In the fictional practice data, Mara’s moment of misery describes the typical journey, not a rare one:

Most starters don’t get a lasting result. Only about 37% of the 8,360 journey starters end up with a plan still on track after 60 days.
Her open questions are the main reasons people call. 31% of all starters contact an agent within 7 days. Over half of those contacts (52%) are about the questions Mara has: missed payments, combining claims and why income is asked.
Her situation is common, not niche. About 35% of starters have two or more claims, about 34% have variable or shift income, and about 78% are on mobile.
The causes are built into the journey. Claims shown one at a time, no help text on income, and failing mobile uploads affect everyone who reaches those steps, not a small group.

Some parts are genuine edge cases and need their own path rather than driving the core design. Portal amounts that differ from the letter affect about 6% of journeys, mostly in purchased portfolios. Disputes are about 6% of contacts. Highly vulnerable consumers like N-06 are a small group but need a protected support route under the fairness guardrail.

So the core experience needs fixing first. The edge cases need a clean handoff to an agent, not a redesign.
- **Does the value proposition actually remove the obstacle you identified, or is it a generic feature?:** The value proposition partly removes the obstacle: combining claims in one plan (B1) directly fixes a top contact reason, but the explainer (B2) only works if it shows case-specific consequences, the affordability check (B3) is unproven and may add friction, and the mobile upload fix (B5) is missing despite blocking 853 journeys. To make it a sharp fix instead of a generic bundle, lead with B1 plus a case-specific B2 for multi-claim consumers, add B5, and test B3 as a hypothesis designed for variable income.
