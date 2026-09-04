---
name: call-follow-up
description: >-
  Turn a call or group demo into the follow-up that actually moves the deal. Use
  this skill whenever a seller says "follow up after my call", "debrief this
  call", "write a recap email", "who was on the demo and what do I send each of
  them", "post-call follow-up", "send a follow-up to each stakeholder", "help me
  after this discovery call", or wants to process what just happened on a buyer
  conversation. It pulls the meeting from Fluint first (falling back to call
  transcripts, CRM, and email), maps who cared about what, locks the confirmed
  problem in the buyer's own words, surfaces the skeptics and objections that
  showed up, drafts forwardable per-stakeholder follow-ups, and debriefs where
  discovery went thin. Prefer this over a generic recap email any time a call or
  demo just happened.
---

# Call Follow-Up

## What this does

A call just happened. Most reps send one bland recap to one person and move on. That is a
missed follow-up. This skill produces a set of forwardable assets instead:

1. A stakeholder map: who was there and what each one actually cared about.
2. The problem locked in the buyer's own words, so it survives being forwarded.
3. The skeptics and objections that showed up, spoken or not, with the opening to engage.
4. A forwardable follow-up per stakeholder, tied to what they care about.
5. A discovery debrief on where the call was thin, so the next one is sharper.

Follow-up is how you keep selling in the meetings you will not be in. Write for the person
who was in the room and for whoever they forward it to next.

## Step 1: Lock the target and pull the meeting

**Fluint first.** If the Fluint MCP (`mcp.fluint.io`) is connected, use it first. Pull the
`@Meeting` (its transcript, attendees, and what Fluint read from it) plus the `@Deal` it
belongs to. Fluint already fuses the call, CRM, and email context, so start there.

**No Fluint? Detect what is live and fall back.** Do not assume a vendor. Pull in parallel:
- Call transcripts (Gong, Chorus, Fathom, Fireflies; or via Clay / Deepline) = the source of truth for who said what.
- CRM (HubSpot, Salesforce, Attio, Pipedrive) = the deal, stage, contacts.
- Email (Superhuman, Gmail, Outlook) = the thread this call sits in.

You need the transcript or your notes to do this well. If there is no record of the call at
all, say so and ask the seller for their raw notes rather than inventing what was said.

**Missing a source? Flag it, and make the gap a move.** Mark it inline as `[MISSING: ...]` and continue. Every gap gets the single highest-leverage way to close it: the one question, to the one person, at the next touchpoint. Not "get more data."

**Who can actually say yes?** Name the people with the power to approve this, or to block it, and mark whether they are engaged yet. Power is often not in the room. If the deciders are absent or untouched, that is the headline, not a footnote.

## Step 2: Map the stakeholders

Read `references/frameworks.md` (Stakeholder mapping). For every person on the call, capture:
who they are, what they seemed to care about most, the questions they asked, and any
reaction worth noting. Then chain each person's interest to the metric they own using the
"which means" connector: this user's daily pain, which means this manager's number, which
means this exec's KPI. That chain is what lets one follow-up speak to a whole committee.

## Step 3: Lock the confirmed problem

Read `references/frameworks.md` (Problem Statement). Write the problem back in the buyer's
own words, built from the five elements: Frame, Data, Benchmark, Trajectory, Connection.
Quote them. If a number was never given, do not invent it: write `[MISSING: cost of the
problem not quantified on the call]`. A confirmed problem the buyer recognizes as theirs is
what earns the next meeting.

## Step 4: Surface the skeptics and objections

Note who pushed back and on what, spoken or unspoken, and where the opening is to engage
them. Keep this light here. If a real blocker showed up, the deep work belongs in the
`champion-enablement` skill (Targeting the Skeptic). Hand it off with a one-line pointer.

## Step 5: Draft the forwardable follow-ups

Read `references/output-templates.md` and use the two forwardable-email patterns in
`references/frameworks.md` (one for non-technical contacts, one for technical evaluators).
Draft a short follow-up per stakeholder (under 120 words each): reference something specific
they said, tie it to their metric, and give one clear next step. Then a separate champion
debrief message asking their read on how it went and what the logical next step is.

If a recap already went out, do not send another. The next message's job is to arm the people
who were on the call to sell the people who were not. Write through your attendee, to the
decider: hand your attendee the two-sentence version of the case, in the buyer's own words,
ready to forward without editing. That is how you sell the room you were not invited to.

Write these to be forwarded. That means their words, not yours. Camouflage, not a billboard.
No vendor chest-thumping, no jargon, no em dashes.

## Step 6: Debrief the call

Read `references/frameworks.md` (Discovery Lookback). Grade the call across Problem, Process,
Payoff. Name the two or three moments to go deeper next time and the exact reframe that would
have opened them. Not self-criticism, just the list of what to close on the next call.

## The deliverable

The seller walks away with a ready-to-send follow-up pack, built to the skeleton in
`references/output-templates.md`:
1. **Stakeholder map** (who, what they cared about, their metric)
2. **Confirmed problem** (in their words, five elements, gaps flagged)
3. **Skeptics / objections that showed up** (and the opening)
4. **Forwardable follow-up drafts** (one per stakeholder + the champion debrief, ready to send)
5. **Discovery debrief** (graded stages + the reframes to use next time)

## The operator's read

Before you hand it over, add the part a summary cannot: the one thing an experienced operator would notice that the data does not show on its own. The non-obvious risk. The stakeholder who matters more than their title. The deal that is not what it looks like. The strength that is quietly a trap. One or two sentences of judgment, called out plainly. Anyone can produce the map. This is the read.

## Operating principles

- **Follow-up is selling in the room you are not in.** Write to be forwarded.
- **Their words, not ours.** Camouflage, not a billboard.
- **One recap to one person leaves the committee unsold.** Map them, write to each.
- **Score the call as it went.** The missed reframe is the next call's opening.

- **Voice guard.** Anything the buyer will read opens with their words, from the call or their own materials, in the first line. Banned openers: "Great connecting," "As discussed," "I wanted to follow up," "Hope this finds you well," "Circling back." If a sentence would survive being pasted into a different deal, it is too generic. Cut it.
