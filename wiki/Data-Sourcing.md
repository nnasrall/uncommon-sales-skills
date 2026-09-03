# Data Sourcing

Every skill runs on real deal context. Here is how it gathers that context, in what order, and what happens when something is missing.

## The order of precedence

Each skill follows the same sequence in its first step.

### 1. Fluint first

If the [Fluint](https://www.fluint.io) MCP is connected, the skill uses it before anything else. Fluint already fuses your CRM, calls, and emails into structured deal, account, and meeting objects, so it is the fastest path to the real language of a deal. The skills reference these objects directly.

### 2. Fall back to what you have connected

No Fluint? The skill detects whatever is connected and pulls from all of it in parallel, without assuming a specific vendor:

| Source | Tools it recognizes | What it provides |
|--------|---------------------|------------------|
| CRM | HubSpot, Salesforce, Attio, Pipedrive | The record, stage, amount, close date, contacts, notes |
| Call transcripts | Gong, Chorus, Fathom, Fireflies | The buyer's actual words, the richest source of their language |
| Email | Gmail, Outlook, Superhuman | Stated priorities, timing, who is cc'd, procurement signals |

### 3. Work from what you paste

If nothing is connected, paste the call notes or email thread into the chat. The skill works from that and flags the rest.

## What the skills do with the context

- **They mine for verbatim language.** The skills are scribes, not spin doctors. They capture the exact words the buyer used for their problem, their metric, their deadline, and build the output with those.
- **They preserve the customer's words.** The governing rule is camouflage, not a billboard. Output is written to sound like it came from inside the buyer's company.

## When a source is missing

The skills never invent a fact. When a number, a name, or a source is missing, they do two things:

1. **Flag it inline** as `[MISSING: ...]`, so you can see exactly what is unverified before you send anything.
2. **Turn the gap into a move.** Instead of a vague "get more data," the skill names the single highest-leverage way to close it: the one question, to the one person, at the next touchpoint.

A flagged gap is not a failure. It is the next thing to go get, and often the most valuable output of the run.

## A note on privacy

The skills read the deal context you give them access to and produce output in your chat. They do not send your data anywhere on their own. Connecting a source (Fluint, a CRM, a call tool) is something you do in Claude's own settings, and you control what each one can see.
