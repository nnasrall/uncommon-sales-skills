# FAQ

## Do I need a paid Claude plan?

Yes, to install a plugin marketplace. Pro, Max, Team, or Enterprise. Individual `.skill` files can be uploaded for testing under Settings → Capabilities → Upload skill.

## Do I need Fluint to use these?

No. Fluint is the primary and richest data source, but every skill falls back to your CRM, call recorder, and email, and works even with nothing connected by leaning on what you paste in. Fluint just makes it faster and more complete. Learn more at [fluint.io](https://www.fluint.io).

## What CRMs and call tools work?

The skills are tool-agnostic. They recognize the common ones (HubSpot, Salesforce, Attio, Pipedrive for CRM; Gong, Chorus, Fathom, Fireflies for calls; Gmail, Outlook, Superhuman for email) and use whatever you have connected in Claude.

## How do I actually run a skill?

You do not type a command. You describe the situation in plain language ("prep me for my call with Acme," "why is this deal stuck," "build the business case for Acme") and Claude reaches for the right skill. See [[Getting Started]].

## Will these send emails or take actions on my behalf?

No. The skills produce drafts and plans in your chat. You review and send. They are built to hand you a finished, forwardable asset, not to act for you.

## What makes these different from a generic prompt library?

Three things: they run a real methodology from *Selling With* and *Brief & Brilliant* rather than generic tips; they write in the buyer's own language sourced from your actual deal data; and every one ends in a deliverable plus an operator's read, the judgment a summary hides. See [[The Philosophy]].

## Can I customize a skill for my team?

Yes. Each skill is plain Markdown (a `SKILL.md` plus reference files). Fork the repo, edit the frameworks or output templates to match your motion, and point your own marketplace at your fork. The skills are designed to be adapted.

## How do updates work?

If you turned on **Sync automatically** when adding the marketplace, installed skills update themselves when the repo changes. Otherwise, re-sync the marketplace in Customize → Plugins.

## Who built this?

[Nate Nasralla](https://www.fluint.io), author of *Selling With* and *Brief & Brilliant*, and founder of Fluint. The skills are the productized version of the system in both books.

## How do I report a bug or suggest a play?

Open an issue on the repository. These are living skills, tuned from real deals, and feedback shapes them.
