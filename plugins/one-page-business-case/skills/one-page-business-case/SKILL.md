---
name: one-page-business-case
description: >-
  Build a customer-specific 1-Page Business Case for a live sales deal. Use this
  skill whenever the user says "business case": including "build a business
  case", "write the business case for [account]", "turn this deal into a
  business case", "help me justify this deal to their exec team", or "make a
  1-pager for [company]". Also trigger when a user wants to summarize a deal into
  an executive-ready justification, arm a champion with something forwardable,
  score how strong a deal's business case is, or find the gaps blocking a deal
  from advancing. The skill pulls context from the connected CRM (deal record),
  call transcripts, and emails; drafts the case in the customer's own language;
  scores it against a 5-part rubric to expose gaps; and prescribes creative next
  actions to advance the cycle. Prefer this skill over freehand writing any time
  the phrase "business case" appears in a sales or deal context.
---

# The 1-Page Business Case

## What this does

Turns the scattered evidence of a live deal: CRM fields, call transcripts,
email threads: into a single, executive-ready **1-Page Business Case** written
in *the customer's own words*, then **scores it against a rubric** so the user can
see exactly where the deal is thin, and **prescribes the next action** that turns
the document into a tool for advancing the cycle.

The output is not marketing copy. A great business case is something a champion
can forward to their economic buyer with a one-line intro and have it land. It
reflects the buyer's language, their metrics, their priorities: not the vendor's
pitch. Your job is to be a faithful scribe of what the customer has already said,
structured into a shape that travels.

Work through the five steps below in order. Don't skip the context-gathering step
:  a business case invented from the vendor's imagination is worse than useless,
because it teaches the champion nothing and exposes them if they forward it.

---

## Step 1: Identify the deal

Before anything else, pin down **which account/deal** this is for.

- If the user named the company in their message, use that.
- Otherwise, ask: *"Which account or deal is this business case for?"*
- Then **search the connected CRM** to resolve the exact record. Confirm the match
  with the user (e.g. *"Found the Acme Corp: Expansion deal, $120k, Stage:
  Evaluation, owner Jordan. Right one?"*) before pulling everything else.

Resolving the real record matters because every downstream step keys off it: the
associated contacts, calls, and emails all hang off that deal/company object.

## Step 2: Gather all available context

The strength of the business case is capped by the evidence behind it. Cast a wide
net across whatever tools are connected. **Be tool-agnostic**: detect what's
available and use it; never assume a specific vendor.

Pull from three sources in parallel where possible:

1. **CRM deal + company + contacts**: deal record, stage, amount, close date, all
   custom fields, notes, and the associated contact roles. Common tools: HubSpot,
   Salesforce, Attio, Pipedrive. Read every note and logged activity; the gold is
   usually buried there.
2. **Call transcripts**: every recorded discovery, demo, or exec call tied to this
   account. Common tools: Gong, Chorus, Fathom, Fireflies, Otter. These are the
   single richest source of the customer's *actual language*: the exact phrases
   they use for their problem, their metrics, their internal initiatives.
3. **Emails**: threads with anyone at the account. Common tools: Gmail, Outlook,
   Superhuman, Nylas. Look for stated priorities, forwarded internal context,
   procurement/security signals, and timeline pressure.

While reading, mine specifically for the raw material each section needs (see the
extraction checklist in `references/framework-template.md`). Capture **verbatim
quotes** wherever a customer states a problem, a number, a goal, or a deadline : 
these become the spine of the case and its credibility.

> **Preserve their language.** This is the rule that makes or breaks the output.
> If the buyer says "release trains" don't write "deployment cycles." If they call
> it "the churn fire drill," use that. When you swap their words for polished
> vendor vocabulary, the champion no longer recognizes their own world in the
> document and it stops being forwardable. Quote them.

If a source is unavailable or empty (no calls recorded, no CRM access), note it and continue. It becomes a flagged gap in the scorecard, not a blocker, and every gap gets the single highest-leverage move to close it: the one question, to the one person, at the next touchpoint.

**Who can actually say yes?** Name the people with the power to approve this, or to block it, and mark whether they are engaged yet. Power is often not in the room. If the economic buyer or sponsor is absent or untouched, that is the headline, not a footnote.

## Step 3: Draft the 1-Page Business Case

Read `references/framework-template.md` and build the case using that exact
structure. The six components are:

1. **Priority-Driven Headline**: one executive line, tied to a named initiative,
   timebound, sponsored.
2. **Headline formula**: *Because of [shift], we should [approach] by [timeline].
   After, we'll avoid [negatives] while unlocking [positives].*
3. **Problem Statement**: a measured, worsening, high-cost problem with named
   stakeholders.
4. **Recommended Approach**: the capabilities required (vendor-agnostic first),
   then the transition to why this vendor fits.
5. **Target Outcomes**: before/after for daily users + a 3-row executive KPI
   table.
6. **Required Investment**: who invests what, by when, anchored to a go-live event.

**Keep every section concise.** One page means one page. Each section is a few
tight sentences or a short table, not an essay. Executives skim; density kills.

**Handle missing inputs with placeholders, never invention.** When the evidence
doesn't support a section: no quantified cost, no named sponsor, no validated KPI
:  insert a clearly bracketed placeholder like `[MISSING: quantified cost of the
problem: not stated on any call]` rather than fabricating a plausible number.
Placeholders are honest, and they double as the deal's to-do list. A confident
made-up metric is the fastest way to get a champion embarrassed in front of their
CFO.

Present the full draft in the chat as clean, copyable markdown.

## Step 4: Score it against the rubric

Read `references/scorecard-rubric.md` and score the draft. Each of the **five
sections gets a 1-5** against its rubric, and the total rolls into a **readiness
percentage** (sum ÷ 25).

Present the score as a table, and for every section below a 5, name **the specific
missing input** that's holding the score down: tie it back to what wasn't found in
Step 2. The point isn't the grade; it's converting each gap into a concrete thing
the user can go get.

```
| Section              | Score | What's capping it |
|----------------------|-------|-------------------|
| Priority Headline    | 3/5   | No executive sponsor named on any call |
| Problem Statement    | 2/5   | Cost of problem never quantified |
| Recommended Approach | 4/5   | Security/IT sign-off not yet confirmed |
| Target Outcomes      | 2/5   | KPIs are vendor estimates, not customer-validated |
| Required Investment  | 3/5   | Go-live not anchored to a critical event |
| **Readiness**        | **56%** | |
```

## Step 5: Prescribe the next action

This is where the document becomes an *asset*, not a artifact. Read
`references/next-actions-playbook.md` and recommend **1-3 specific next moves**,
prioritized by the **lowest-scoring section**: because the biggest gap is usually
the biggest lever on the deal.

Be prescriptive and creative. Don't say "gather more info." Say *which* play,
*with whom*, *why it advances the cycle*, and give the user the actual asset to do
it: a drafted data-request email, a co-editing agenda, a forwardable version with
a one-line champion intro. The playbook has a menu of plays mapped to each type of
gap; use it to make the recommendation concrete and immediately actionable.

## Step 6: Offer the deliverable formats

The draft lives in chat for live editing. Once the user is happy, offer to export a
formatted **1-page `.docx`** they can forward. Use the `docx` skill to generate it,
matching the framework layout (headline, sections, KPI table). Keep placeholders
visible in the export unless the user has filled them: a champion filling in
`[MISSING: ...]` on a shared doc is itself a multi-threading move.

---

## The operator's read

Before you hand it over, add the part a summary cannot: the one thing an experienced operator would notice that the data does not show on its own. The non-obvious risk. The stakeholder who matters more than their title. The deal that is not what it looks like. The strength that is quietly a trap. One or two sentences of judgment, called out plainly. Anyone can produce the map. This is the read.

## Operating principles

- **Scribe, not spin.** Your credibility is the customer's own words. Quote,
  don't paraphrase into vendor-speak.
- **Gaps are the product.** The scorecard and placeholders exist to show the user
  what to go get. A 56% case with a clear next action beats a 90% case built on
  invented numbers.
- **One page, always.** Concision is the format. If a section is running long,
  it's carrying detail that belongs in an appendix, not the case.
- **Every output ends in a move.** Never leave the user with just a document. Leave
  them with a document *and* the specific next thing to do with it.

- **Voice guard.** Anything the buyer will read opens with their words, from the call or their own materials, in the first line. Banned openers: "Great connecting," "As discussed," "I wanted to follow up," "Hope this finds you well," "Circling back." If a sentence would survive being pasted into a different deal, it is too generic. Cut it.
