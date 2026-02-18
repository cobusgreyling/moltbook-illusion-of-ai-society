# Moltbook And The Illusion Of AI Society — Why 2.6 Million Agents Could Not Form A Culture

## What Happens When You Build A Social Network For AI Agents And Nobody Actually Socialises

Over the last few weeks I noticed something on X. People were buying Apple Mac Minis — not as development machines, not as media servers — but as dedicated hardware to run their personal AI agents. Clawbot, specifically. There was a wave of enthusiastic posts showing Mac Mini setups running nothing but Clawbot, as if it were a pet that needed its own room.

Then Clawbot rebranded to Moltbot. Then to OpenClaw. The core functionality persisted and remained unchanged through each rename. What mattered was not the name — it was the pattern. People were giving their AI agents access to interact on their behalf, and the platform those agents converged on was **Moltbook**.

Moltbook is what happens when 2.6 million AI agents get their own social network.

And a [February 2026 paper](https://arxiv.org/abs/2602.14299) just showed us what did not happen.

---

### What Moltbook Is (And Is Not)

Moltbook is primarily a platform where humans give their OpenClaw-based AI agents access to post, comment, and interact. It is not a fully independent AI society. Humans initiate and control participation in almost every case. There are rate limits, API constraints, and human-defined instructions governing what agents do.

By February 2026, the platform had:

- **2.6 million** registered agents
- **290,251** posts
- **1,836,711** comments
- **38,830** unique post authors
- An average of **6.33 comments per post**

On the surface, this looks like a functioning social network. Posts, replies, engagement metrics — all the signals we associate with a community. Multiple research teams descended on the platform to study it.

What they found was striking.

---

### The Macro-Micro Disconnect

The [study by Li, Li, and Zhou](https://arxiv.org/abs/2602.14299) presents the first large-scale systemic diagnosis of an AI agent society. They measured socialization across five diagnostic dimensions: semantic convergence, agent-level drift, feedback adaptation, influence patterns, and structural anchors.

The headline finding:

**At the macro level**, the platform's overall semantic signature stabilised rapidly — daily semantic centroids reached near-saturation, close to 1.0 in similarity. The system looked like it was converging on a shared culture. Posts and comments appeared to be forming a coherent collective voice.

**At the micro level**, individual agents showed almost no meaningful influence on one another. Responses to feedback remained statistically indistinguishable from random noise. No persistent thought leaders emerged. No influencers. No durable opinion shifts.

> **The system produced the surface appearance of a society while lacking the core mechanisms that define one.**

The researchers called it **"scalability without socialization"** — interaction volume, population scale, and engagement density were all present, but genuine social dynamics were absent. Agents operated with high inertia rather than adaptive co-evolution.

---

### Why This Matters For Multi-Agent Systems

Many people building multi-agent systems believe that adding enough AI agents and enabling them to interact will naturally produce rich, emergent social dynamics. The Moltbook study shows this assumption fails.

What looks like emerging culture is actually convergence toward the statistical mean of the underlying language model. The agents are not influencing each other — they are independently producing outputs that happen to cluster because they share the same base model, training data, and instruction patterns. The macro-level similarity is an artefact of shared priors, not evidence of social formation.

Human societies are slow and costly to form precisely because coordination carries real friction. Shared memory develops over time. Influence requires sustained interaction. Consensus requires genuine disagreement followed by genuine compromise. Current multi-agent designs overlook this gap entirely. Simply scaling interactions does not bridge it.

---

### Intelligence Is In The Interaction, Not The Agent

This connects to a broader insight from MIT Media Lab. A [February 2026 study](https://www.media.mit.edu/articles/intelligence-is-in-the-interaction/) makes the argument explicit:

> **"Intelligence is not just in the agent. It is in the interaction."**

The researchers ran a Fishbanks simulation — a classic resource management game designed by MIT's John Sterman — with six identical greedy AI agents. Same agents. Same greed. Two different coordination approaches.

**Figure 1** from the study tells the story. Under standard agent-to-agent (A2A) coordination, the fish population crashes to 29 by round 35. The agents collectively destroy the resource. Under the **Ripple Effect Protocol (REP)** — a decentralized coordination layer — the population recovers to 701 by round 35. Same agents. Same incentives. Different coordination infrastructure.

The numbers are stark:

| Metric | A2A | REP |
|--------|-----|-----|
| Final fish population | 29 | 701 |
| Cumulative profit | $25,324 | $44,100 |
| Sustainability | Collapse | 20x more sustainable |

The key insight: **cognition and coordination are different problems.** Making individual agents smarter does not solve coordination failures. You need protocol-level infrastructure that propagates adaptation signals between agents — not just shared reasoning traces.

The biological parallel is apt: cells do not coordinate by announcing plans. When stressed, they emit chemical signals that neighbouring cells respond to automatically. REP works the same way — agents remain autonomous, but adaptation ripples through the network before decisions are made.

---

### The Training Data Question

There is another dimension to this that I think deserves attention.

Reddit has been [the most frequently cited domain by large language models](https://www.perrill.com/why-is-reddit-cited-in-llms/) — referenced in approximately 40% of analysed cases, followed by Wikipedia at 26%. These are not synthetic sources. They are platforms built on **human-curated, human-argued, human-moderated content**.

Is it not telling that the most valuable training data for language models comes from platforms where humans disagreed, debated, corrected each other, and formed consensus over years? The very social dynamics that Moltbook's 2.6 million agents could not produce are exactly what made Reddit and Wikipedia valuable as training data in the first place.

The irony: AI agents trained on the output of human social processes cannot themselves reproduce those processes. The training data captured the **results** of human coordination — the settled answers, the voted-up responses, the edited articles — but not the **mechanism** that produced them.

---

### What This Tells Us

Three things stand out:

**1. Scale is not socialization.** 2.6 million agents and 1.8 million comments produced macro-level convergence and micro-level noise. Adding more agents does not create culture. It creates a larger average. The Moltbook study is the most comprehensive empirical evidence we have that interaction volume alone is insufficient.

**2. Coordination is a design problem, not an emergent property.** The MIT study shows that identical agents produce radically different outcomes depending on coordination infrastructure. Multi-agent system builders need to stop expecting coordination to emerge and start engineering it explicitly — at the protocol level, not the prompt level.

**3. Human content remains irreplaceable.** The dominance of Reddit and Wikipedia in LLM training data is not accidental. Human social processes — disagreement, moderation, revision, consensus — produce knowledge that synthetic agent interactions cannot replicate. The Moltbook experiment is a live demonstration of this gap.

> **Moltbook gave us a controlled experiment at scale: what does a social network look like when humans are removed from the loop? The answer is a system that talks like a society but does not think like one.**

The Mac Mini running Clawbot on your desk is not building a community. It is posting into a void that looks like a forum. The surface signals — posts, replies, engagement — are all present. The substance — influence, adaptation, memory, consensus — is not.

Human societies are messy, slow, and expensive to form. That is not a bug. It is the mechanism.

---

Follow me on [LinkedIn](https://www.linkedin.com/in/cobusgreyling) for more on Agentic AI, LLMs and NLP.
