# Uncommon Sales Skills

**Ten Claude skills that run enterprise-level sales plays the way top reps _actually_ win.**

Your favorite LLMs trained on the market average inputs, which creates generic outputs. These skills encode the specific, hard-earned wisdom that separates reps who close complex deals from reps who get stuck: selling in the buyer's own language, selling during the meetings you're not in the room for, and crafting forwardable, sticky messages. They'll pull from your live deal data, and give you tactical assets for each eal.

Built by [Nate Nasralla](https://www.fluint.io), author of *Selling With* and *Brief & Brilliant*, on the frameworks from both books.

---

## What to expect from the library of _uncommon_ skills

- **They sell with the buyer's language, not yours.** These skills mine your call transcripts and emails for the exact words the buyer used, override the LLMs default tendencies, and write in a way that makes it easy for champions to forward your message. Which makes all the difference.

- **They're built on what's _not_ in training data.** Every skill is anchored to a specific framework tested by 1,000's of sellers and built into *Selling With* and *Brief & Brilliant*.

- **A single system, built with judgment.** Each skill builds on top of the others to create a single, end-to-end system that mirrors what a seasoned seller has: judgment. The ability to weave together multiple skillsets into a single deal.

- **Every skill builds in a tangible asset.** Not analysis you still have to figure out how act on. A a forwardable follow-up, a champion toolkit, a leadership brief, etc... You finish with the thing, ready to ship.

- **They run on your real data.** The skills pull deal context from Fluint if you use it, or, it falls back to whatever you have connected: your CRM, call recorder, email, etc.. When a fact is missing, they flag it and tell you what to do next.

---

## The ten skills

| Skill | What it does |
|-------|--------------|
| **multithread** | Map the buying committee on a new account or a single-threaded deal, then draft the outreach to widen it. |
| **account-planning** | Build a POV and a strategic account plan, or find and rank expansion whitespace in an existing account. |
| **call-prep** | Walk into a call with a Meeting Brief: a point of view, planned discovery, an opening frame, and the ask. |
| **call-follow-up** | Turn a call or demo into a stakeholder map, a confirmed problem in the buyer's words, and forwardable per-person follow-ups. |
| **champion-enablement** | Build the internal-selling kit your champion uses in the meetings you are not in: soundbite, objection reframes, a one-pager. |
| **competitive-displacement** | Unseat an incumbent by changing the criteria, not winning a feature war. Differentiation, a switching story, and trap-setting questions. |
| **deal-advancement** | Diagnose why a deal stalled and generate moves to restart it, or build a backdated mutual action plan to close it. |
| **qbr-prep** | Prep a customer quarterly review that leads with their success, gets ahead of risk, and opens expansion without a pitch. |
| **manage-up** | Prep for a forecast call or deal review: an honest read of the territory, the big bets, and specific asks of leadership. |
| **one-page-business-case** | Build a customer-specific one-page business case from your deal data, scored against a rubric, with the next move to strengthen it. |

---

## Install

You can install this as a Claude plugin marketplace. Installing requires a paid Claude plan (Pro, Max, Team, or Enterprise).

1. In Claude, open **Customize → Plugins** (or **Settings → Capabilities → Plugins**).
2. **Add marketplace** and paste this repository:
   ```
   nnasrall/uncommon-sales-skills
   ```
3. Install the skills you want, or all ten. Turn on **Sync automatically** and installs update themselves when the repo changes.

Prefer a single skill for your own testing? Each skill is also a standalone `.skill` file you can upload under **Settings → Capabilities → Upload skill**.

---

## Using a skill

You do not run a command. You just describe what you are doing, and Claude reaches for the right skill. Every skill triggers on natural language:

- *"Prep me for my call with the VP of Ops at Acme tomorrow."* → **call-prep**
- *"Help me follow up after that demo, there were four people on it."* → **call-follow-up**
- *"This deal is single-threaded, help me multithread it."* → **multithread**
- *"Why is the Acme deal stuck?"* → **deal-advancement**
- *"Build the business case for Acme."* → **one-page-business-case**
- *"Prep me for my forecast call, I need an intro from my VP."* → **manage-up**

The skill gathers your deal context, applies the framework, and hands you the deliverable. If something it needs is missing, it tells you the one question to go ask.

---

## How the data sourcing works

Every skill follows the same order:

1. **Fluint first.** If the [Fluint](https://www.fluint.io) MCP is connected, the skill uses it. Fluint already fuses your CRM, calls, and emails into deal, account, and meeting objects, so it is the fastest path to the real language of a deal.
2. **Fall back to what you have.** No Fluint? The skill detects whatever is connected and pulls in parallel: your CRM (HubSpot, Salesforce, Attio, Pipedrive), your call transcripts (Gong, Chorus, Fathom, Fireflies), and your email (Gmail, Outlook, Superhuman).
3. **Flag the gaps.** When a source is missing or a fact was never captured, the skill marks it and names the single highest-leverage move to close it. It never invents a number.

The skills work without any of these connected too. They will just lean on what you paste in and flag the rest.

---

## Who this is for

Account executives, sales engineers, and account managers running complex, multi-stakeholder, mid-market and enterprise deals. If your deals get made in rooms you are not in, and won or lost on whether your champion can carry the message, these are built for you.

---

## The thinking behind it

These skills are the productized version of the system in two books:

- ***Selling With*** — the art of selling with champions to shape the internal buying conversations that decide enterprise deals.
- ***Brief & Brilliant*** — how to simplify complex deals and sell through the noise, in the buyer's own language.

---

## Contributing and feedback

Found a rough edge, or a play you would run differently? Open an issue. These are living skills, tuned from real deals.

## License

MIT. Use them, adapt them, run them on your own pipeline.
