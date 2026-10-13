# Elevating Case Note Quality: speaker notes

## Slide 1

Welcome everyone, and thanks for making the time.

Today is about case notes: how we write them, and how we make sure they reflect the quality of the work that goes into each investigation.

I want to be clear from the start that this isn't a session about anyone individually, and it isn't a criticism of the analysis being done. A lot of good work goes into these cases. The aim is to make sure that work is visible on the page, consistently, every time.

## Slide 2

Here's how the session will run.

We'll start with some context: why we're focusing on case notes now.

Then three main themes:
- Consistent structure: what every note should contain.
- The "so what?": linking facts to the outcome.
- RFI documentation: how we record and use RFIs.

After that we'll do a knowledge check, with a quick true or false round, then a couple of real case examples to discuss as a group. We'll finish with the key takeaways and time for questions.

Please do jump in with questions as we go. This works best as a conversation.

## Slide 3

So, why now?

First, regulators are asking. Recent regulatory requests have focused directly on our case notes and how we evidence our decisions. So this isn't an internal preference or a change for the sake of it. It's a response to external scrutiny.

Second, the note is the evidence. When an auditor, regulator or banking partner reviews a case, they don't see the work we did in the tools or the thinking in our heads. They only see what's written. If it's not documented, it can't be relied on, even if the work was done.

Third, it reduces external risk. Strong notes protect CKO, they protect the team, and they protect you as the analyst who made the decision. If a case is ever looked at again, a well-written note shows your decision was reasonable based on what you knew at the time.

And to repeat the point at the bottom of the slide: what we've seen is not concentrated in individuals. It's a team-wide pattern in how we all document, so we're all improving it together.

## Slide 4

When someone reviews our cases, there are three things they're looking for.

Complete: every part of the investigation is visibly documented, including the checks where nothing was found.

Reasoned: each finding is linked to the outcome. It's not enough to list what we found; we need to say why it supports a false positive or an escalation.

Evidenced: someone with no other context should be able to pick up the note, rebuild the case and reach the same conclusion. That's the test a regulator applies.

At the moment we're inconsistent. Some notes are really comprehensive, while others don't mention certain assessments at all, even when they've been completed. The key message is that we, and regulators, can't take it at face value that something was done just because the SOP says it should be. If it isn't in the note, a reviewer has to assume it didn't happen.

## Slide 5

This is the most common piece of feedback from recent QA reviews: notes gave a general review of the merchant or the account, but didn't clearly describe the activity that actually made the rule fire.

So every note should start with the alerted activity, and these four questions are a simple way to structure it:

- Which rule? Name the rule and explain in plain terms what it's designed to detect.
- What alerted? Itemise the transactions that triggered it: the value, volume, countries and fingerprint. Not the full transaction history, just what alerted.
- Which period? Initially, the review window should match the rule's look-back period. If older transaction data is relevant to the outcome or adds valuable context, that's fine to use and include in the note. Just make clear why you've looked at it.
- So what? Explain why this specific activity is, or isn't, a concern.

The wider generic review still has a place. It can support the investigation later in the note, for example showing a high-value payment sits within an account that normally shows genuine activity. But it supports the analysis of the alerted activity; it doesn't replace it.

## Slide 6

These are the building blocks every case note should cover. Even if a section is just one line confirming the check was done, it should be there.

As mentioned, always start with the alerted activity: the rule, the specific transactions, the timeframe, and why the rule fired.

Then:
- Merchant profile: the legal name, the stated business model, and what we expected to see from onboarding.
- Customer profile: who is transacting, card types, issuing countries, and any concentration.
- Historical behaviour: prior alerts with their cases and outcomes, and relevant transactions outside the alerted timeframe. If the merchant or cardholder has been flagged before, say whether that changes today's assessment. Is this the same pattern, a new one, or an escalating one?
- Expected vs actual: frequency, velocity, value and activity patterns, compared against what we expected for this merchant.

And finally, conclusion and rationale: always link the findings back to the outcome.

Covering these in the same order every time makes notes quicker to write, easier to review and much easier to defend.

## Slide 7

A quick win.

On the left is the weak version: OSINT isn't mentioned at all. A reviewer reading that note has no way of knowing whether OSINT was done.

The stronger version is one sentence: "OSINT was conducted on the end user; no verifiable digital footprint could be obtained to assist in verifying the activity observed." The reader now knows the check was performed and what it found, even though the result was inconclusive.

That's the key point: one line is enough. Without it, a reviewer can't tell the difference between "checked and clear" and "not checked", and they'll have to assume it wasn't done.

The same applies to any check: adverse media, geographic risk, linked cases. If you did it, write it down, even if nothing came back.

## Slide 8

We want a consistent structure, but that doesn't mean copy and paste.

This is similar to the MAS exercise from last week: a common framework, but written in your own words about the specific case in front of you.

Do:
- Use the same headings in the same order so the note is easy to follow.
- Include case-specific facts, figures and dates.
- Explain your reasoning in your own words.
- Tie all the facts together at the end with your outcome.

Avoid:
- AI-generated or templated text pasted in unchanged.
- Generic phrases like "in line with expected activity" with no evidence behind them.
- Identical wording across different cases.

Regulators notice when notes read the same across different cases. It suggests a tick-box exercise rather than an investigation, which is exactly what we want to move away from.

## Slide 9

This is the heart of today's session: answering the "so what?"

We want every alert treated as an investigation, not a checklist. The simplest way to think about it is three steps:

- Fact: what did I find?
- Significance: what risk does it raise or reduce?
- Conclusion: how does it affect the outcome? Does it support a false positive or an escalation?

Most notes stop at the fact. The significance step is where the investigation actually happens, and it's what a regulator is looking for.

A few examples:
- "The merchant is in the gaming industry." That's a good start, but what risk factors come with gaming, and how did we consider them?
- "This merchant has been flagged before." Great. Does that change our current assessment?
- "The majority of transactions are debit/credit." What's the significance of that detail to this case? Is it consistent with the business model? Does it tell us anything about the risk?

For every point you write down, ask yourself: so what?

## Slide 10

These are phrases that come up regularly in case notes. In most cases they're not wrong, but they're weak, and they need tightening.

1. "The recipient might have invested in cryptocurrencies and withdrawn his accumulated profits." This is speculation. Corroborate it with evidence: check the fingerprint's pay-in activity. Did they pay in enough for profits to be plausible?

2. The gambling version: "might have invested in sports, live casino, racing and obtained profits." Rather than "it may be" or "might have", use "plausible" or "reasonable", and tie it to what the merchant does and the account activity. For example: "Given the merchant is a licensed gambling operator and the cardholder paid in £4,800 over the period, a £5,200 withdrawal is reasonable and consistent with winnings." That's a much stronger argument. And check those pay-ins: someone who paid in thousands and withdrew thousands is a very different story to someone who paid in £5 and withdrew £10k.

3. "The velocity of transactions is spread out between months, days, minutes." This says nothing about the risk. Remove it, or say what the pattern actually shows.

4. "No evidence of structuring or smurfing was identified." Only use this where structuring or smurfing is a relevant typology for the alert. Ruling out typologies that don't apply adds length but no value.

One more point on language: remove superlatives from all write-ups. Be factual in your observations and use a neutral tone in your opinions. Words like "detailed analysis", "high-quality" or "appropriately vetted" can't be tested; replace them with the evidence behind them.

## Slide 11

Before you conclude a case, run through these four questions:

- What did I expect to see for this merchant, and does the activity match?
- What could explain the difference, and have I evidenced that explanation? This is where you can look beyond the merchant or end user. Is anything happening more widely that could explain the activity, such as a World Cup, a major sporting event or a global fuel crisis? If so, reference it with the source.
- Which risk factors have I ruled out, and which remain open? If something is still open, that needs to be reflected in the outcome.
- Could someone else read this note and reach the same conclusion?

That last one is the regulator test. If a reviewer with no other context reads your note, will they agree with your outcome? If the answer is "only if they asked me", the note needs more.

## Slide 12

Moving on to RFIs. Every RFI reference in a note should follow a clear, logical flow. These four steps:

1. Was an RFI sent? If yes, document the date, what was asked and why. If no, give the rationale for not sending one. Not sending an RFI is absolutely fine, but the reasoning needs to be in the note.

2. Was a response received? Record the date it came back, or the chaser that was sent and the impact of not getting a response.

3. Was it adequate? Did it answer each of the questions we asked? If not, what was missing and why does that matter?

4. How was it used? What risk did it rule in or out, and how did it shape the final outcome?

If a reader can follow those four steps in your note, the RFI is properly documented.

## Slide 13

Here's an example of how that looks in practice.

On the left: "Performed. An RFI was sent and the response lacked details whereby the merchant stated that they do not collect PII."

Everything in that sentence is accurate. But it states the facts and stops. We don't know when the RFI was sent, what was asked, or, most importantly, what that response means for the case.

On the right is the stronger version. It adds the date and what was requested, the date of the response and what it said, and then the crucial "so what": as a result, we were unable to verify the end user or rule out, for example, third-party or mule activity. And it finishes by linking that unresolved risk to the outcome: it supports escalation.

That "as a result, we were unable to rule out..." sentence is the piece that's most often missing.

## Slide 14

Documenting the RFI is one part. The other is making sure we actually test what comes back.

RFI handling was a clear theme in the recent QA review. Responses were often accepted with little scrutiny.

Three things to focus on:

- Target the gap. Ask for what you need to resolve the specific alerted activity, rather than just sending the standard RFI form.
- Test it against the data. Does the response match what the transactions show? Check the values, dates, customers and countries. If a merchant says their customers are mainly UK-based but the alerted activity is from elsewhere, that needs to be picked up.
- Act on what is unresolved. Where a response is inadequate or inconsistent, say what risk remains and consider escalation in line with the SOP.

An RFI response is evidence to be tested, not a box to tick.

## Slide 15

This is a checklist to keep to hand when you're writing a note. It pulls together everything we've covered today:

- Rule and alerting transaction stated first.
- Merchant and customer profile.
- Historical behaviour and prior alerts.
- Expected vs actual: frequency, velocity and value.
- Other investigation checks, including negatives.
- RFI: sent or why not, response tested, and impact.
- Every finding has a "so what".
- Explanations evidenced, for example pay-ins and OSINT.
- Factual, neutral language with no superlatives.
- Conclusion and closure reason follow the evidence.

If you can tick all of these before submitting, the note will stand up to review.

## Slide 16

Let's put this into practice.

We'll start with a quick-fire true or false round. I'll read out each statement and I'd like a show of hands, true or false.

Then we'll look at a couple of real case notes together and talk through what could make them stronger.

## Slide 17

Read each statement out and ask for a show of hands before revealing the answers.

1. If the OSINT assessment is completed and nothing was found, it doesn't need to go in the note.
2. Not sending an RFI is acceptable, as long as the rationale is documented.
3. A thorough review of the merchant's overall activity is enough to discount an alert.
4. A large gambling withdrawal can be solely explained as winnings.

Where the room is split, ask one or two people to explain their answer before moving on.

## Slide 18

Answers:

1. False. Record the check. Without it, a reviewer has to assume it wasn't done. Remember: one line is enough.

2. True. This is the only true statement. A reasoned decision not to send an RFI is fine; it just needs to be written down.

3. False. Lead with the rule and the transaction that alerted. The wider history supports the analysis, it doesn't replace it.

4. False. Check the pay-ins. Someone who paid in £5 and withdrew £10k is a very different story to someone who paid in thousands and withdrew thousands. Winnings may well be the explanation, but it needs evidence behind it.

## Slide 19

A quick caveat before we start: these are real examples of case notes written by L1 and L2. What's shown are snippets of the full note, picked out to highlight the points we've covered today. This isn't about the individuals who wrote them, and as we saw earlier, these patterns appear across the team.

This case alerted on two rules: a spike in weekly crypto transaction volume, and a single transaction over £9,000.

Give everyone a minute to read the extracts, then work through the questions on the right:
- Which transaction caused the alert?
- Why did the weekly volume rule fire?
- Does the crypto statement explain the value over £10k?
- What does the velocity sentence add?

Take a few answers from the room before moving to the feedback.

## Slide 20

Here's the QA feedback on this case.

What was missing:
- The alerting transaction isn't described. It was a single withdrawal of £10,478.96, and that's not mentioned anywhere in the note.
- There's no reason given for the weekly spike. The simple explanation is that there was no activity in the previous four weeks, which is consistent for this cardholder.
- "Might have invested" is weak and isn't backed by evidence.
- The velocity sentence doesn't tie back to the conclusion.

What a stronger note does: it leads with the £10,478.96 withdrawal. It explains that the weekly rule fired because there was no activity in the prior four weeks, which is consistent with the cardholder's pattern. It shows the value is in line with their previous withdrawals. And it supports any "profits" explanation with evidence, such as the cardholder's pay-in history.

It's worth saying that the content of the original note isn't incorrect, and the outcome wasn't necessarily wrong. But the information should inform the decision, rather than just being listed as evidence that the activity is of no concern.

## Slide 21

Case 2 is at merchant level. The rule alerts when a single cardholder makes up more than 0.5% of the merchant's pay-in volume over a 30-day period.

Again, give the room a minute to read the extracts, then discuss:
- Who is the alerted cardholder, and by how much did they exceed 0.5%?
- Which sentences actually address the alerted rule or activity?
- Is the sender review specific enough?
- Is "false positive" the right outcome?

A hint if the room needs one: count how many of these sentences are about the merchant in general, and how many are about the cardholder who triggered the alert.

## Slide 22

Here's the QA feedback.

What was missing:
- The alerted cardholder and their activity aren't described at all.
- It's mostly a general merchant review, not specific to the alert. Everything in it may be true, but none of it explains why this cardholder's share isn't a concern.
- Senders were only reviewed in aggregate, not the specific sender who alerted.
- There's no reason given for why the alerted activity isn't a concern.

What a stronger note does: it identifies the alerted fingerprint and its share of pay-ins against the 0.5% threshold. It compares the cardholder's activity in the period with their usual activity at this merchant. If they only exceeded the threshold slightly and in line with their norm, it says so. That one line of specific reasoning does more than the whole general paragraph.

On the outcome: the rule fired correctly. The cardholder did exceed the threshold, so the closure reason should reflect that, rather than describing the alert as a false positive. Check the SOP for the right closure reason in these cases.

## Slide 23

To wrap up, three things to take away:

Be specific: lead with the alerted activity and cover all the investigation points, even where the answer is "checked and nothing found".

Give reasons: answer the "so what" for every finding, with evidence behind it and neutral, factual language.

Ensure traceability: document RFIs from request through to impact, or explain why one wasn't sent.

The main message is that the analysis is often already there. We just need to make sure it's visible in the note, because the note is how regulators, auditors and our partners see the quality of our work.

## Slide 24

Thank you all for your time and engagement today.

I'll open it up for any questions now. If anything comes up later, or you'd like to talk through a specific case, please do reach out.

## Additional slide A: Case 3 walkthrough (full note)

This is a full case note from L2. Unlike the first two cases, where we looked at snippets, here is the whole note, and it's a good example of the structure we've been talking about today.

Give the room a minute to read it. Before we break it down, ask: what do you notice about how this note is put together, compared with Cases 1 and 2?

Points to draw out:
- It opens with the alerted activity: the rule (high cumulative pay-to-card gambling amount over 30 days), the alerted period (August 2026), the value and volume ($94,580.57 across 48 transactions), and the specific features that made it unusual (repeated amounts of 9,594 and 9,599 RON, and transactions within the same minute).
- It reads as an investigation, not a checklist. Each section builds towards the conclusion.
- It checks pay-ins against payouts, which is exactly the point we made about gambling withdrawals. It doesn't just say "these are probably winnings"; it shows the money going in.

On the next slide we'll break it down section by section.

## Additional slide B: Case 3 broken down

Here's the same note split into the building blocks from earlier. Walk through each one.

Alerted activity: the note starts with what alerted: $94,580.57 across 48 pay-to-card payouts in August, the repeated amounts and the near-simultaneous transactions. It says what is unusual: a significant departure from the cardholder's baseline.

Merchant profile: the merchant is identified, its platforms are named, and the note explains why pay-to-card payouts are expected for this business: they are how customers withdraw betting and casino winnings.

Customer profile: who the cardholder is, where the card is issued, the card type and its risk rating, the transaction currency, and the fact that they only transact with this one merchant.

Historical behaviour: this is the strongest section. It doesn't stop at the alerted card. It sets out pay-ins against payouts over a longer period, identifies a second associated card used mainly to fund the account, and combines the two. The result is a clear net loss position of $48,137.59. That's the evidence behind the "these are gambling winnings" explanation.

OSINT: recorded, including the negative result: no adverse media, enforcement actions, PEP matches or sanctions. One line, but it shows the check was done.

RFI documentation: it follows the logic flow. Why the RFI was sent (the payout spike and no verifiable information on the cardholder's background), what was asked (source of funds and wealth, and whether payouts fit the profile), what happened (no response), and how the case was concluded without it (using internal transactional data).

Conclusion and rationale: it addresses each red flag. The payout volume is set against the deposits. The repeated amounts are explained by the platform's per-transaction payout cap of around 10,000 RON, rather than structuring. And the outcome is clearly linked back to the evidence.

Optional stretch discussion, if time allows: even a strong note can be tightened. Ask the room if they can spot anything. Points to have ready:
- Language. "Fully supported", "substantial" and "presents no immediate AML risk" are stronger than they need to be. Describing the amounts as "structured" in the opening, then concluding it isn't structuring, could confuse a reader. "Repeated amounts" is more neutral.
- Evidence for the explanation. Where does the ~10,000 RON cap come from? Citing the source makes the explanation testable.
- Loose ends. The near-simultaneous transactions are raised in the opening but not explicitly addressed in the conclusion. Every red flag raised should be closed off.
- Timing of funds. The associated card's deposits are from August to September, while the payouts run from June to August. Is it clear that deposits came before the withdrawals they're said to support?
- The unanswered RFI. Was a chaser sent? And should the "medium risk" BIN be explained, or is it a fact without a "so what"?

The overall message: this is the standard we're aiming for. It's specific, structured, evidenced, and every section serves the conclusion.

## Additional slide C: Historical Behaviour (past indicators)

History tells us whether today's activity is new, a continuation of something we already know about, or getting worse. Structure this section around four simple questions:

- Prior alerts: has the merchant or cardholder been alerted before, and what was the outcome? Then answer the "so what": is this the same pattern, a new one, or an escalation? "Previously discounted" only helps if the circumstances are the same.
- Baseline shift: has the activity moved away from their normal behaviour, such as velocity jumps, unusual volumes or new flows of funds? If so, why? In Case 1, the history explained the alert straight away: there had been no activity in the previous four weeks.
- Timeframe scope: is there relevant activity outside the alerted window, such as small test transactions before a spike, or linked cards funding the account? If you widen the scope, say why.
- Business rationale: is there a commercial reason, such as a promotion, a seasonal peak or confirmed growth? Evidence it. "Likely seasonal" is an assumption, not a rationale.

To be clear, the QA review found prior history was checked in every case; what's often missing is what it means. Remember this rule: history should either support or weaken today's outcome, so say which.

## Customer Profile (Who is it?), revised to match slide 6

Once we've anchored the note on the alerted activity, the next step is to understand who is behind it. The merchant profile tells us who should be paying; the customer profile tells us who actually is. Comparing the two is often where an alert is explained, or where the real risk shows up. Structure this section around one question: "who is it?" In particular, four simple questions:

- Who? Identify who is behind the alerted payments. Name the cardholder and the fingerprint, and check for any linked or associated cards. Is the activity driven by one end user or many, and is one card fingerprint being used by several individuals? Note how concentrated the volume is: a merchant alert caused by a single cardholder needs that cardholder reviewed, not just the merchant in general.
  - Key context from QA: a recurring piece of feedback was that senders were reviewed "in aggregate". Regulators want to see that we have looked at the specific customers who triggered the alert, not a summary of the whole customer base.
- How? How are they making the transactions? Record the card type (debit, credit or prepaid) and whether we are looking at pay-ins, pay-to-card payouts, or both. Then ask whether the method fits the business. For example, prepaid cards can be harder to trace back to a source of funds, and money paid in and quickly paid out is a different risk from a customer simply spending.
- Where? Are the transactions to or from areas we consider high-risk? Compare the issuing countries with the merchant's target markets from onboarding and its website, check them against the current Geographic Risk Rating, and look for mismatches between the card country and the customer's location. Sometimes this alone explains the alert: if a country is an expected target market, say so.
- So what? The bottom line. What patterns or trends are you seeing? Does the customer base fit what we would expect for this merchant? Does anything point to a relevant typology, such as mule activity or one person acting on behalf of others? And does the behaviour warrant a closer look, an RFI or escalation? If not, explain why.

To be clear, stating facts such as "100% of payments were made by debit card" is a start, but on its own it doesn't tell the reader anything. Remember this rule: every customer detail you record should help explain whether the alerted activity is, or isn't, a risk.

## Expected vs Unexpected (Is this strange?), revised to match slide 6

Every alert is really asking one question: is this activity what we would expect from this merchant or customer? To answer it, we need a clear picture of what "expected" looks like, from the onboarding profile, the merchant's line of business, its own history and any wider context such as seasonality or major events, and then an honest comparison with what we actually see. Structure this section around "is this strange?" In particular, four simple measures:

- Frequency: how often do transactions happen? Compare daily, weekly or monthly counts against the baseline. Look for sudden spikes, sudden drops, or a dormant account that suddenly becomes active, and ask whether it fits how this merchant trades (e.g. "a restaurant busiest at weekends", or "a subscription business billing monthly").
- Velocity: how quickly does activity happen in a short period? Look for many transactions within minutes or hours, funds paid in and quickly paid out, or several cards or attempts in quick succession. High velocity can point to card testing, mule activity or layering, but it can also have a legitimate cause, such as a platform cap splitting one withdrawal into several payments. Either way, it needs explaining.
- Value: how much money is moving? Compare actual amounts with the merchant's average transaction value, look for large one-off payments and round or repeated amounts, and compare totals with the volumes projected at onboarding.
  - Key context from QA: one of the most common weaknesses was asserting that activity was "in line with the business" without showing the analysis. Regulators want to see the comparison, not just the conclusion.
- Activity patterns against expected activity: what is the overall shape of the activity? Look for new countries, card types or end users, unusual times of day, and volume concentrated in a small number of end users. Does it still match the stated business model?

To be clear, unexpected does not automatically mean suspicious, and expected does not automatically mean fine. What matters is whether the difference can be explained and evidenced, through pay-in history, OSINT, the merchant's website or an RFI response. Remember this rule: for each measure, the note should say what we expected, what we saw, and why the difference is, or isn't, a concern. "Activity is in line with expected behaviour" gives the conclusion; it doesn't show how we reached it.

## Merchant Profile (What do we expect to see from this merchant?)

Before we can judge whether the alerted activity is unusual, we need to know what normal looks like for this merchant. The merchant profile is that foundation: it sets the expectations that everything else in the note is measured against. Without it, "in line with the business" is just an assertion. Structure this section around one question: "what do we expect to see from this merchant?" In particular, four simple questions:

- What do we know about the merchant? Start with the basics: the legal name and entity, the industry and MCC, where they operate, and what transaction values we expected at onboarding. Keep it specific to this merchant. Someone reading the note should be able to picture the business in a sentence or two (e.g. "a UK bar and restaurant group with venues in London and Manchester, with an expected average transaction of around £60").
  - Key context from QA: the merchant's legal name and entity ID were often missing, and in a couple of cases the details were out of date or belonged to a different merchant. It sounds basic, but if a reviewer can't tell which merchant we assessed, nothing else in the note can be relied on.
- Business model risk: what inherent red flags come with this type of business? Stating that a merchant is in the gaming industry is a start, but what risk factors come with gaming, and how did we consider them? Check that the MCC matches what the merchant actually does, and whether the transactions fit what we would expect from them, including the geographies and target markets they told us about.
- Look-back window: is the review aligned to the rule logic? Your baseline should start with the rule's own look-back period, whether that is 30, 60 or 90 days. If seasonality matters, for example a retailer at Christmas or a travel merchant in summer, compare against the same period in previous years as well, and state why you widened the scope.
- The baseline anchor: what is the benchmark for "normal"? Set out the expected average transaction size, transaction volume and geography, then compare the alerted activity against it. If the activity doesn't match, ask why. Has the business grown, launched a new product, or moved into a new market? Is there evidence for that?

To be clear, the merchant profile is not the investigation in itself. A long description of the merchant, its website and its Trustpilot score doesn't explain an alert. Remember this rule: the merchant profile sets the expectation; the rest of the note tests the alerted activity against it.
