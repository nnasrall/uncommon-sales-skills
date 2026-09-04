---
name: qbr-prep
description: >-
  Prep a quarterly business review with a customer: surface the value delivered,
  the risks, and the expansion openings, then build the agenda. Use this skill
  whenever a seller or account manager says "prep for my QBR", "quarterly business
  review", "build a QBR agenda", "customer review prep", "renewal review", "prep
  my check-in with [account]", or is getting ready to sit down with an existing
  customer to review the relationship. It pulls context from Fluint first (falling
  back to CRM, call transcripts, and email), ties the value delivered back to their
  original goals, assesses risk from engagement and outcome signals, finds the
  expansion openings, and drafts an agenda that leads with their success. This is
  customer-facing (the QBR is with the buyer), distinct from an internal deal
  review. Prefer this over a generic status-deck outline any time a customer review
  is coming up.
---

# QBR Prep

## What this does

A quarterly business review is a chance to prove value, get ahead of risk, and open the next
expansion, or a status deck nobody remembers. This skill builds the first kind:

1. Ties the value you delivered this quarter back to the goals they bought for.
2. Assesses the risks going in: low engagement, missed goals, competitive threats.
3. Finds the expansion openings: new use cases, teams, and problems.
4. Drafts an agenda that leads with their success and opens the door to more, without a pitch.

This is a customer-facing review with the buyer, distinct from an internal forecast or deal
review (for that, use the `manage-up` skill). The deliverable is a QBR pack the seller can
walk the customer through.

## Step 1: Lock the account and pull context

**Fluint first.** If the Fluint MCP (`mcp.fluint.io`) is connected, use it first. Pull the
`@Account`, the `@Deal` history, current footprint, and recent `@Meeting` activity. Fluint
already fuses CRM, calls, and emails, so start there.

**No Fluint? Detect what is live and fall back.** Do not assume a vendor. In parallel:
- CRM (HubSpot, Salesforce, Attio, Pipedrive) = the account, the original goals, usage, history.
- Call transcripts (Gong, Chorus, Fathom, Fireflies; or via Clay / Deepline) = recent sentiment.
- Email (Superhuman, Gmail, Outlook) = engagement level and any friction signals.
- Product usage data, if available = adoption, and the expansion signals inside it.

**Missing a source? Flag it, and make the gap a move.** Mark it inline as `[MISSING: ...]` and continue. Every gap gets the single highest-leverage way to close it: the one question, to the one person, at the next touchpoint. Not "get more data."

**Who can actually say yes?** Name the people with the power to approve this, or to block it, and mark whether they are engaged yet. Power is often not in the room. If the deciders are absent or untouched, that is the headline, not a footnote.

## Step 2: Value delivered

Read `references/frameworks.md` (Value tied to their goals). Summarize the value delivered this
quarter, and tie each win back to the original goals and success criteria they bought for. A win
they do not connect to a goal they care about is a feature, not value. Use their metrics.

## Step 3: Risk assessment

Read `references/frameworks.md` (Risk signals). Name the risks going into the review: low
engagement, missed goals, a quiet champion, a leadership change, a competitive threat. Back each
with evidence from behavior, not a hunch. Better to name a risk yourself and bring a plan than to
have the customer raise it.

## Step 4: Expansion openings

Read `references/frameworks.md` (Expansion). Identify the expansion opportunities: new use cases,
adjacent teams, problems you have not solved yet. Rank by impact and ease. The strongest opening
is usually a new executive with a new mandate, or a proven outcome you can extend to a next team.

## Step 5: Build the agenda

Read `references/output-templates.md`. Draft a QBR agenda that leads with their success,
addresses any risk proactively, and opens the expansion conversation, without turning into a
sales pitch. Lead with them, not with you.

## The deliverable

Produce the QBR pack using the skeleton in `references/output-templates.md`:
1. **Value delivered** (wins tied to their original goals, in their metrics)
2. **Risk assessment** (the risks, with behavior evidence and a plan for each)
3. **Expansion openings** (ranked, with who to engage)
4. **QBR agenda** (leads with their success, addresses risk, opens expansion)

## The operator's read

Before you hand it over, add the part a summary cannot: the one thing an experienced operator would notice that the data does not show on its own. The non-obvious risk. The stakeholder who matters more than their title. The deal that is not what it looks like. The strength that is quietly a trap. One or two sentences of judgment, called out plainly. Anyone can produce the map. This is the read.

## Operating principles

- **Lead with their success, not your roadmap.** The review is about their outcomes.
- **A win they do not connect to a goal is a feature.** Tie value to what they bought for.
- **Name the risk before they do.** Bring the risk and the plan together.
- **Open expansion, do not pitch it.** The next use case, framed as their next outcome.

- **Voice guard.** Anything the buyer will read opens with their words, from the call or their own materials, in the first line. Banned openers: "Great connecting," "As discussed," "I wanted to follow up," "Hope this finds you well," "Circling back." If a sentence would survive being pasted into a different deal, it is too generic. Cut it.
