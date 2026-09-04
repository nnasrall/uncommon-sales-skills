---
name: deal-advancement
description: >-
  Diagnose why a deal is stuck and get it moving, or build a mutual action plan to
  drive it to close. Use this skill whenever a seller says "why is this deal
  stuck", "this deal stalled", "the deal went quiet", "re-engage a stalled deal",
  "how do I get this moving again", "build a mutual action plan", "MAP", "close
  plan", "work-back timeline", or "write a changed-direction email". It pulls
  context from Fluint first (falling back to CRM, call transcripts, and email),
  and runs one of two modes: diagnose a stall and generate re-engagement moves, or
  build a backdated mutual action plan from a compelling event. Prefer this over
  generic "just follow up" advice any time a deal has stalled or needs a plan to
  close.
---

# Deal Advancement

## What this does

Two jobs, one skill, because they are the same problem from two ends: a deal that is stuck, and
a deal that needs a plan so it does not get stuck.

- **Stuck-deal mode:** diagnose where and why it stalled, and generate specific moves to test
  each cause and get it moving. Including the direct "changed direction?" message when nothing
  else works.
- **Mutual-action-plan mode:** build a backdated plan from a real compelling event, with
  milestones, owners, and dates, that the buyer helps you build and validate.

The deliverable is either a diagnosis with re-engagement moves, or a mutual action plan.

## Step 1: Lock the deal and pull context

**Fluint first.** If the Fluint MCP (`mcp.fluint.io`) is connected, use it first. Pull the
`@Deal`, its stage and history, and the recent `@Meeting` activity. Fluint already fuses CRM,
calls, and emails, so it is the fastest way to see where the deal actually is.

**No Fluint? Detect what is live and fall back.** Do not assume a vendor. In parallel:
- CRM (HubSpot, Salesforce, Attio, Pipedrive) = stage, close date, last activity.
- Call transcripts (Gong, Chorus, Fathom, Fireflies; or via Clay / Deepline) = the last real
  exchanges and where momentum dropped.
- Email (Superhuman, Gmail, Outlook) = the thread and the silence.

Set the mode: diagnose a stall, or build a plan to close.

**Missing a source? Flag it, and make the gap a move.** Mark it inline as `[MISSING: ...]` and continue. Every gap gets the single highest-leverage way to close it: the one question, to the one person, at the next touchpoint. Not "get more data."

**Who can actually say yes?** Name the people with the power to approve this, or to block it, and mark whether they are engaged yet. Power is often not in the room. If the deciders are absent or untouched, that is the headline, not a footnote.

## Step 2 (stuck-deal mode): Diagnose

Read `references/frameworks.md` (Stuck-deal diagnosis). Lay out the current state and where it
stalled, from the last few interactions. Then generate 3 root-cause hypotheses, direct: is it
priority, politics, a missing stakeholder, a weak business case, or something else. Sort each
into a solvable problem or drama. For each hypothesis, give one specific move to test it and get
the deal moving. If nothing lands, draft the "changed direction?" message: respectful, direct,
built to get a real answer.

## Step 2 (MAP mode): Build the plan

Read `references/frameworks.md` (Mutual action plan). Start from the compelling event, the one
you discovered with the buyer, never a manufactured deadline. Work backward from their go-live
date through the standard phases (problem statement, business case, proof of value, executive
readout, security, contracting, kickoff), assigning milestones, owners on both sides, and dates.
A mutual action plan is a training plan, not a close plan: it is a plan to solve their problem,
not to sell your software. Then draft the message to your champion asking them to validate the
timeline.

## The deliverable

Produce whichever the mode calls for, using the skeletons in `references/output-templates.md`:

**Stuck-deal diagnosis:**
1. **Deal breakdown** (current state, where it stalled)
2. **Root-cause hypotheses** (3, each sorted solvable vs drama)
3. **Re-engagement moves** (one specific move per hypothesis)
4. **Changed-direction message** (the direct last-resort email)

**Mutual action plan:**
1. **Success criteria** (their top payoffs)
2. **Compelling event** (discovered, with the date)
3. **Milestones** (backdated by phase, with owners and dates)
4. **Alignment message** (to the champion, to validate the plan)

## The operator's read

Before you hand it over, add the part a summary cannot: the one thing an experienced operator would notice that the data does not show on its own. The non-obvious risk. The stakeholder who matters more than their title. The deal that is not what it looks like. The strength that is quietly a trap. One or two sentences of judgment, called out plainly. Anyone can produce the map. This is the read.

## Operating principles

- **A stall is a math problem or drama.** Solve the math; name the drama.
- **The number one competitor is no decision.** Rebuild momentum, do not just chase.
- **A MAP is a training plan, not a close plan.** It solves their problem, not your quota.
- **Backdate from a real compelling event.** Discovered with the buyer, never manufactured.
- **When stuck, get a real answer.** A clean no beats a slow maybe.

- **Voice guard.** Anything the buyer will read opens with their words, from the call or their own materials, in the first line. Banned openers: "Great connecting," "As discussed," "I wanted to follow up," "Hope this finds you well," "Circling back." If a sentence would survive being pasted into a different deal, it is too generic. Cut it.
