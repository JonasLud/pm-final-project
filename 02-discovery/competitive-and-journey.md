# Competitive Analysis & Journey Map (Module 2)

## Responses
- **Role, who are you solving for? (the specific user segment or profile):** Mara is a consumer in the Germany pilot with two or more open claims and variable or shift income, who starts the instalment journey on her phone after a digital reminder.

This defines her by the three traits the research links to the weakest outcomes:

Two or more claims: About 35% of starters (roughly 2,970 a month). Agreement drops from 52.1% with one claim to 37.7% with two and 27.6% with three or more.
Variable or shift income: About 34% of starters. This group misses the most payments, at 22.5%.
Mobile, after a reminder: About 78% of starters are on mobile, where agreement is lower than on desktop (43.8% vs 54.0%) and where the upload defect hits (T-201).

One caveat for your slide: the research gives each trait’s share separately but not how many consumers have all three. The combined segment is smaller than any single figure, so don’t present 35% or 2,970 as Mara’s segment size. Say “Mara sits where these three groups overlap” instead, and flag the overlap size as something to pull from the row-level data.
- **Goal, what is this user ultimately trying to achieve?:** Goal: Mara wants to get her debts settled and stop the collection pressure with a single plan that fits her pay days, without risking a missed payment or her financial stability.

This goes one level deeper than “set up an instalment plan,” because the plan is only her means. What she’s ultimately after shows up in the research as her open questions:

Stopping the pressure on all claims, not just one. She can’t tell whether settling one claim stops action on the other (N-03). Her goal is to be done with collection entirely.
A plan that survives a bad month. With shift income, her real fear is the month her pay drops. Variable-income consumers miss the most payments (22.5%), and she doesn’t know what a missed payment would cost her (T-208, N-05).
Sharing her situation without it being used against her. The research shows financially stretched consumers fear self-incrimination when asked about income (T-206, N-06).

This framing also lines up with your business risk. Riverty’s metric counts a plan as success when it’s created, but Mara counts it as success only when it holds. That’s the same gap your hook describes between SSR and broken agreements.
- **Friction, the main barrier (moment of misery) stopping them from succeeding:** Friction: Mara is asked to commit to a plan she can’t fully understand. On her phone, right after the reminder, she can’t tell whether “income” means this month or a normal month (N-01), whether settling one claim stops action on the other (T-202, N-03), or what happens if she misses a payment (T-208, N-05). So she either stops and calls an agent, or agrees to a plan she may not be able to keep.

This is the main barrier because it matches the Executive Summary’s central finding: the portal makes agreeing to a plan easy but understanding it hard. It’s also the barrier with the most evidence behind it:

It’s why people call. Missed-payment consequences (18.6%) and combining claims (17.3%) are the top two contact reasons. Together with why income is asked, the top three make up about 52% of contacts, and all of them are comprehension questions.
It hits Mara’s segment hardest. Agreement falls from 52.1% with one claim to 27.6% with three or more, and variable-income consumers miss the most payments (22.5%).
It connects both bad outcomes in your hook: the 31% who call and the 19% who miss a payment within 60 days.

The mobile upload timeout (T-201) is a real barrier too, but it’s a separate, technical one: it blocks 853 journeys whether or not Mara understands her plan. I’d keep it out of the Friction statement and list it in your backlog as a must-fix (B5), so the moment of misery stays focused on a single human struggle.
- **External tools, the outside platforms or tools the user is forced to use:** Here are the outside tools Mara turns to, based on your hook and the Executive Summary. One honest caveat up front: the research confirms that she leaves the portal, but it only measures one destination. Most of the tools below come from your hook’s inference, so I’ve marked the evidence for each.

Tool	What Mara uses it for	Evidence
Phone line to a Riverty agent	Getting answers on missed payments, combining claims and why income is asked	Confirmed: 31% of starters call within 7 days; top three reasons make up about 52% of contacts
Paper letters + phone camera	Photographing letters to cross-check amounts and claim references against the portal	Supported: amount mismatch in 531 journeys (T-203, N-07); separate claims (T-202). Photographing is inferred
Banking app	Scrolling through past months to work out what “income” means for her	Inferred from the ambiguous income question (N-01)
Calculator or notes app	Estimating a “safe” monthly instalment herself	Inferred from N-01 and her variable income
Google search	Looking up what happens if she misses an instalment, whether a plan affects her credit record, and whether Riverty is legitimate	Inferred from the missing consequence explanation (T-208, N-05)
Forums, consumer advice centres, debt counselling	Getting reassurance her case-specific questions can’t get in the portal	Inferred as where Google sends her
Other creditors’ apps, overdraft, family	Paying simpler bills first, or covering a gap after a missed payment	Inferred from your hook

Two notes for your deliverable:

The agent line isn’t technically “external.” It’s Riverty’s own channel, but it’s outside the product, and it’s the only workaround the data quantifies. I’d keep it in the list and label it as “outside the digital journey” rather than as an external platform.

Don’t present the inferred tools as findings. The Executive Summary’s self-review already flags treating inference as evidence as a logic leak. On your slide, show the agent line as the confirmed workaround and present the others as “likely workarounds to validate.” You could check them cheaply by adding a question to future interviews (“Where did you look for answers before calling?”) or by reviewing agent notes for mentions of Google, debt counselling or letters.
- **The process, the 3 to 5 manual steps the user takes to get the job done:** Here’s Mara’s workaround as a single process in five steps, from the moment she gets stuck to the moment her plan is set up. It follows the path most supported by the research: she tries to work it out herself, then calls an agent.

She gets stuck and leaves the portal. At the income question or the plan screen, she can’t tell what “income” means, whether her claims can be settled together, or what a missed payment would cost (N-01, T-202, N-03, T-208). She closes the portal, meaning to come back. (Supported)
She works out her own numbers. She opens her banking app, scrolls through recent months of shift pay, and uses a calculator or notes app to guess a safe monthly amount. (Inferred)
She checks her letters against the portal. She gathers the paper letters for each claim and compares the amounts and references with what the portal shows, which can differ (T-203, N-07). (Supported; the comparison itself is inferred)
She calls an agent. Often days later, she phones Riverty with her open questions. 31% of starters do this within seven days, and about 52% of those calls are comprehension questions. (Confirmed)
She repeats everything she already entered. The agent can’t see her online answers, so she goes through identity, affordability and case checks again before a plan is set up (T-205, N-08). (Supported)

Why this process is inefficient: Mara does the portal’s job twice. First she does it alone, with guesswork, in steps 2 and 3. Then she does it again with an agent, in step 5. The task takes days instead of minutes, moves from her phone to a phone call, and costs Riverty 11–13 minutes of agent time for questions one line of explanation could answer. If she skips step 4 and agrees in the portal based on her own guess, the process is shorter, but the plan is more likely to break.
- **Core frustration, the exact moment the process feels most “broken”:** Core frustration: The moment Mara looks at the plan screen and has to tap “confirm” without knowing what she’s agreeing to. The shortest plan is shown first as if it were the right answer (N-02), nothing tells her what happens if she misses a payment (T-208, N-05), and she can’t tell whether this plan stops action on her other claim (T-202, N-03). She’s asked to make a commitment about her money with three open questions, and the only way to answer them is to leave the portal and call.

Why this is the most broken moment: It’s the point where every earlier problem lands at once. The income she guessed, the claims she can’t see together and the consequences no one explained all come down to one button. It’s also where Mara’s process splits into the two outcomes that drive your business crisis: she either stops and calls an agent (missed-payment consequences and combining claims are the top two contact reasons, at 18.6% and 17.3%), or she confirms anyway and the plan is more likely to break. And it’s the moment where the process looks most successful to Riverty, because a confirmed plan counts toward SSR immediately, whether or not it will hold.

One honest caveat: this isn’t where the most people drop out. The largest drops come earlier, at the affordability question and the document upload. Those are where Mara gives up. The confirm screen is where the process breaks for the people who keep going, which is why it best captures the frustration in your hook.
- **The evidence, a specific quote or behavior from the research that proves this:** Mara’s process feels most broken at the plan screen, where she has to confirm a plan without knowing what a missed payment costs or whether it stops action on her other claim, as one multi-claim consumer put it: “I did not know if paying one would stop the letters about the other” (N-03). Another participant shows what happens when consumers confirm anyway: “I picked the plan with the lowest number of months because it looked like the right answer. The amount was too high and I missed the second payment” (N-02). The data confirms this is systemic, not anecdotal: after the shortest plan was shown first in Month 4, missed payments within 60 days rose from 15.6% to 19.0%.
- **Your journey map file name (e.g. journey-map.html):** <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Mara’s future-state journey</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Literata:opsz,wght@7..72,500;7..72,600&family=Public+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --ink: #1c2b3a;
    --muted: #55657a;
    --line: #c9d3de;
    --surface: #ffffff;
    --page: #eef2f6;
    --calm: #0f7a6c;
    --calm-soft: #dcefeb;
    --tag: #e3e8f4;
    --tag-ink: #2d3f73;
    color-scheme: light;
  }
  @media (prefers-color-scheme: dark) {
    :root:not([data-theme="light"]) {
      --ink: #e6edf4; --muted: #a3b1c2; --line: #34465a; --surface: #17222e;
      --page: #0f1821; --calm: #5fcbb7; --calm-soft: #173a36; --tag: #23304d; --tag-ink: #c3cff3;
      color-scheme: dark;
    }
  }
  :root[data-theme="dark"] {
    --ink: #e6edf4; --muted: #a3b1c2; --line: #34465a; --surface: #17222e;
    --page: #0f1821; --calm: #5fcbb7; --calm-soft: #173a36; --tag: #23304d; --tag-ink: #c3cff3;
    color-scheme: dark;
  }
  * { box-sizing: border-box; }
  body {
    margin: 0; background: var(--page); color: var(--ink);
    font-family: "Public Sans", system-ui, -apple-system, "Segoe UI", sans-serif;
    font-size: 15px; line-height: 1.5;
    padding: max(2rem, env(safe-area-inset-top)) 1.25rem max(2rem, env(safe-area-inset-bottom));
  }
  main { max-width: 1120px; margin: 0 auto; }
  h1, h2, h3 { font-family: "Literata", Georgia, "Times New Roman", serif; font-weight: 600; margin: 0; }
  h1 { font-size: clamp(1.6rem, 3vw, 2.2rem); line-height: 1.2; max-width: 28ch; }
  .lede { color: var(--muted); max-width: 70ch; margin: .6rem 0 2.2rem; }
  .timeline { list-style: none; margin: 0; padding: 0; display: grid; grid-template-columns: repeat(4, 1fr); gap: 1rem; position: relative; }
  .timeline::before { content: ""; position: absolute; top: 18px; left: 18px; right: 18px; height: 2px; background: var(--calm); opacity: .5; }
  .stage { position: relative; }
  .node {
    width: 36px; height: 36px; border-radius: 50%; background: var(--calm); color: var(--surface);
    display: grid; place-items: center; font-weight: 600; position: relative; margin-bottom: 1rem;
  }
  .card { background: var(--surface); border: 1px solid var(--line); border-radius: 10px; padding: 1.1rem; height: calc(100% - 52px); }
  .card h2 { font-size: 1.15rem; margin-bottom: .4rem; }
  .tag { display: inline-block; background: var(--tag); color: var(--tag-ink); font-size: .8rem; font-weight: 500; padding: .1rem .5rem; border-radius: 4px; margin-bottom: .9rem; }
  dl { margin: 0; }
  dt { font-size: .8rem; font-weight: 600; color: var(--muted); margin-top: .8rem; }
  dd { margin: .15rem 0 0; }
  .outcome {
    margin: 1.6rem 0 2.4rem; background: var(--calm-soft); border-left: 4px solid var(--calm); border-radius: 0;
    padding: 1rem 1.25rem;
  }
  .outcome h3 { font-size: 1.25rem; }
  .outcome p { margin: .3rem 0 0; color: var(--muted); }
  .advantages h2 { font-size: 1.3rem; margin-bottom: .8rem; }
  .advantages ol { margin: 0; padding-left: 1.3rem; display: grid; gap: .5rem; max-width: 80ch; }
  .note { margin-top: 2rem; padding-top: 1rem; border-top: 1px solid var(--line); color: var(--muted); font-size: .85rem; max-width: 80ch; }
  @media (max-width: 860px) {
    .timeline { grid-template-columns: 1fr; gap: 1.2rem; }
    .timeline::before { top: 18px; bottom: 18px; left: 17px; right: auto; width: 2px; height: auto; }
    .stage { display: grid; grid-template-columns: 36px 1fr; gap: .9rem; }
    .node { margin-bottom: 0; }
    .card { height: auto; }
  }
</style>
</head>
<body>
<main>
  <h1>Mara settles all her claims in one break, on her phone</h1>
  <p class="lede">Future-state journey for a multi-claim, shift-income consumer in the Germany pilot. Each stage replaces a manual workaround from the research with one step inside the portal.</p>

  <ol class="timeline">
    <li class="stage">
      <div class="node" aria-hidden="true">1</div>
      <div class="card">
        <h2>See all claims</h2>
        <span class="tag">B1, combined plan</span>
        <dl>
          <dt>User action</dt>
          <dd>Taps reminder, sees all claims in one plan → no letter cross-checking.</dd>
          <dt>Internal state</dt>
          <dd>Knows her full debt upfront → feels in control instead of anxious.</dd>
          <dt>Pain point addressed</dt>
          <dd>Shows whether paying one claim stops other letters → resolves N-03.</dd>
        </dl>
      </div>
    </li>
    <li class="stage">
      <div class="node" aria-hidden="true">2</div>
      <div class="card">
        <h2>Share income safely</h2>
        <span class="tag">B3, B5, B6</span>
        <dl>
          <dt>User action</dt>
          <dd>Answers guided income question, uploads payslip → no banking-app guesswork.</dd>
          <dt>Internal state</dt>
          <dd>Sees why income is asked and kept → stops fearing self-incrimination.</dd>
          <dt>Pain point addressed</dt>
          <dd>Defines income month, explains data use, fixes upload → resolves N-01, N-06, T-201.</dd>
        </dl>
      </div>
    </li>
    <li class="stage">
      <div class="node" aria-hidden="true">3</div>
      <div class="card">
        <h2>Confirm with clarity</h2>
        <span class="tag">B2, pay-day date</span>
        <dl>
          <dt>User action</dt>
          <dd>Reviews one plan dated to her pay day → picks an amount she can keep.</dd>
          <dt>Internal state</dt>
          <dd>Sees missed-payment consequences before confirming → commits knowingly, not hopefully.</dd>
          <dt>Pain point addressed</dt>
          <dd>Replaces “lowest months looked right” guessing → resolves N-02, N-05, T-208.</dd>
        </dl>
      </div>
    </li>
    <li class="stage">
      <div class="node" aria-hidden="true">4</div>
      <div class="card">
        <h2>Help with context</h2>
        <span class="tag">B4, agent handoff</span>
        <dl>
          <dt>User action</dt>
          <dd>Calls only if needed; agent sees her inputs → no repeated checks.</dd>
          <dt>Internal state</dt>
          <dd>Trusts the plan will hold → no Google searches or anxious callbacks.</dd>
          <dt>Pain point addressed</dt>
          <dd>Agent sees why the plan was offered → resolves N-08, N-09.</dd>
        </dl>
      </div>
    </li>
  </ol>

  <section class="outcome">
    <h3>Outcome: a plan kept at 60 days, not just created</h3>
    <p>Success is measured on agreements that hold, which makes the Self-Service Rate trustworthy.</p>
  </section>

  <section class="advantages">
    <h2>Competitive advantages over the manual workaround</h2>
    <ol>
      <li><strong>Speed:</strong> one phone session during a break replaces days spent across letters, apps and calls.</li>
      <li><strong>Reliability:</strong> plans built on guided inputs and known consequences hold better than guessed ones.</li>
      <li><strong>Visibility:</strong> every plan is explainable to Mara, agents and compliance, making SSR trustworthy (N-12).</li>
    </ol>
  </section>

  <p class="note">Open gaps: late reminders before the first instalment (T-207) and the shortest-plan-first default (N-02) have no backlog item yet. All figures and interview notes come from fictional practice data.</p>
</main>
</body>
</html>
