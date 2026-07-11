## I've watched a lot of expensive software forget things.

Seven years in crypto infrastructure — Bitfinex, Tether, Ankr, Biconomy — building systems where state isn't optional and a missed transaction is a lawsuit. Systems that couldn't afford amnesia.

Then the AI wave hit, and the industry shipped agents that forget everything between sessions and called it a product.

Ask a production coding agent what it tried last Tuesday. You get nothing. Not "I tried X and it failed because Y." Nothing. Every session starts from scratch. Every mistake gets made twice. Every solution gets rediscovered like it's the first time. We built recall for the model and forgot to build memory for the system running it.

That's the problem I work on.

---

## LocusGraph

**Agents don't have bad memory. They have no memory architecture.**

The usual fix — vector search over old conversations — sounds right for about ten minutes. Similarity search finds things that *look like* what you asked. What you need is things that are *relevant* to what you asked. Those aren't the same operation. A support agent pulling "conversations about billing" hands you the ten most similar complaints, not the one fix that actually worked.

LocusGraph is a structured knowledge layer. When an agent handles something, it doesn't dump a transcript — it writes a typed, temporal, relational record: what happened, what worked, what didn't, and why. A vector store is a pile of emails. LocusGraph is a CRM. One is searchable. The other is usable.

Model-agnostic and owner-controlled. Trade GPT-4 for Claude for whatever ships next quarter — the graph stays. You own the data. No vendor memory API that can hike pricing, pivot, or decide your use case is out of scope.

**Who it's for:** teams running coding agents, support agents, and SaaS copilots in production. Not demos. Production.

---

## The Seven-Year Interlude

Crypto infrastructure is a masterclass in what happens when a system can't afford ambiguity. At Bitfinex you learn that unstructured state kills you. At Tether you learn that auditability isn't optional. At Ankr and Biconomy you learn that developer tools live or die on whether they work in production — not on how clean they look in a blog post.

The common thread: when the mistakes are denominated in real money, you get serious about data structures fast.

I brought that habit to AI agents. Everyone else was excited about what LLMs could generate. I kept asking what they were being built on top of. Too often the answer was vibes.

---

## What I'm Building

**LocusGraph** — structured knowledge infrastructure that lets AI agents learn from experience. For teams running coding agents, support agents, and SaaS copilots in production.

**Dobby** — the workflow automation agent. The thing that actually runs.

**Effortless Labs** — the company. Singapore. Small team, strong opinions, reasonable caffeine intake.

---

## The Actual Pitch

If you're running AI agents in production and your engineers are debugging failures the agent hit last week, you don't have a model problem. You have a knowledge infrastructure problem.

Most teams answer this by cramming more into the prompt. That works right up until the context window fills, the model loses the thread, or you're paying to re-explain your whole codebase every session.

The other answer is RAG — a fine technology, built for documents. Agents aren't documents.

LocusGraph is what you get when you take the real problem seriously: structured, typed, temporal knowledge an agent can reason over, not just retrieve. That's a different thing.

---

**LocusGraph** · [locusgraph.com](https://locusgraph.com) · **X** · [x.com/exportpng](https://x.com/exportpng) · Singapore
