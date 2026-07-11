# Seven Years in Crypto. Now I'm Fixing How AI Agents Remember.

---

## The short version

I spent seven years deep in crypto infrastructure — at Bitfinex, Tether, Ankr, and Biconomy — building systems where state wasn't optional. In those environments, a missed transaction isn't just a bug. It can have legal consequences. So you learn, fast, that systems need to remember.

Then the AI agent wave hit. And I noticed something strange: most of these agents ship with amnesia.

---

## What I kept seeing

Production coding agents with no memory of what they tried last session. Support agents that rediscover the same solution every single time a ticket comes in. Teams patching this by stuffing more context into the prompt — until they hit the context window. Or paying to re-explain the entire codebase. Every. Single. Session.

The standard fix is RAG — retrieval-augmented generation. Which is a great technology. For documents. But agents aren't documents.

And vector search? Here's how I think about it: a pile of emails versus a CRM. A pile of emails can surface things that look similar. A CRM tells you what actually happened, what worked, and why. Those are not the same thing.

---

## What I'm building

I founded [Effortless Labs](https://effortlesslabs.xyz) — a small, opinionated team based in Singapore — to work on this exact problem.

We're building two things:

**LocusGraph** (https://locusgraph.com) — a structured knowledge layer for AI agents. Not a transcript log. Not a vector store. A typed, temporal, relational record of what happened, what worked, what didn't, and why. It's model-agnostic (works across GPT-4, Claude, whatever comes next) and owner-controlled — so you're not dependent on a vendor memory API that can reprice or pivot on you tomorrow. Your knowledge graph persists independently of the model underneath it.

It's built for teams running coding agents, support agents, and SaaS copilots in production. Not in demos. In production.

**Dobby** — a workflow automation agent. More on this soon.

---

## A small but important distinction

LocusGraph isn't trying to help agents retrieve better. It's trying to help agents reason over structured knowledge. There's a difference between pulling up something that looks relevant and actually knowing what resolution applies to this specific situation.

That distinction matters a lot when you've spent seven years in systems where getting it wrong has consequences.

---

## Let's talk

If you're building with agents in production and you're tired of watching them make the same mistake twice — I'd genuinely love to compare notes.

Find me here, or reach out directly. Strong opinions and reasonable caffeine intake included at no extra charge.
