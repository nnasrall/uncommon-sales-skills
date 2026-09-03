# Getting Started

## Requirements

- **A paid Claude plan** (Pro, Max, Team, or Enterprise) to install plugins.
- **Deal data**, ideally connected. The skills work best with [Fluint](https://www.fluint.io) connected, and fall back to any CRM, call recorder, or email tool you have linked. They still work with nothing connected, leaning on what you paste in.

## Install the marketplace

1. In Claude, open **Customize → Plugins** (or **Settings → Capabilities → Plugins**).
2. Choose **Add marketplace** and paste the repository:
   ```
   nnasrall/uncommon-sales-skills
   ```
3. Install all ten skills, or pick the ones you want.
4. Turn on **Sync automatically** so installs update themselves when the repo changes.

### Single-skill option

Each skill is also a standalone `.skill` file. To test just one, download it and use **Settings → Capabilities → Upload skill**.

## Connect your data (recommended)

The skills gather deal context on their own from whatever is connected. To get the richest results:

- **Fluint** — the primary source. Connect the Fluint MCP so the skills can pull your deal, account, and meeting objects directly. This is the fastest path to the real language of a deal.
- **CRM** — HubSpot, Salesforce, Attio, Pipedrive. The record, stage, contacts, and notes.
- **Call transcripts** — Gong, Chorus, Fathom, Fireflies. The buyer's actual words.
- **Email** — Gmail, Outlook, Superhuman. Stated priorities, timing, who is cc'd.

If none are connected, paste the relevant call notes or email thread into the chat and the skill will work from that.

## Run your first skill

You do not type a command. You describe the situation, and Claude picks the right skill.

Try one of these:

- *"Prep me for my call tomorrow with the VP of Ops at Acme."*
- *"Help me follow up after today's demo, there were four people on it."*
- *"Why is the Acme deal stuck?"*
- *"Build the business case for Acme."*

The skill will:

1. **Gather context** from your connected sources (or ask you for it).
2. **Apply the framework** for that play.
3. **Hand you the deliverable**: a brief, a set of follow-ups, a plan, a business case.
4. **Flag any gaps** and tell you the one question to ask next.

## Next

- Read [[The Philosophy]] to understand what the skills are doing and why.
- Skim the [[Skill Reference]] to see all ten and when each fires.
