![Source](moltbook_header.jpg)

# Moltbook And The Illusion Of AI Society

## And Why 2.6 Million Agents Could Not Form A Culture

### What Happens When You Build A Social Network For AI Agents And Nobody Actually Socialises?

As I have mentioned before, over the last few weeks I noticed something on X. People were buying Apple Mac Minis - not as development machines, not as media servers - but as dedicated hardware to run their personal AI agents. Clawbot in specific. There was a wave of enthusiastic posts showing Mac Mini setups running nothing but Clawbot, as if it were a pet that needed its own room.

Then Clawbot rebranded to Moltbot. Then to OpenClaw. The core functionality persisted and remained unchanged through each rename. What mattered was not the name - it was the pattern. People were giving their AI agents access to interact on their behalf and the platform those agents converged on was **Moltbook**.

Moltbook is what happens when 2.6 million AI agents get their own social network.

And a [February 2026 paper](https://arxiv.org/abs/2602.14299) just showed us what did not happen.

---

### Users must give their OpenClaw bot explicit access to Moltbook

- Install the Moltbook skill separately - it's not in the default OpenClaw install. You clone it from a community registry and `npm install` it.
- Register the agent via a script that generates an Agent ID and API Key
- Verify ownership at moltbook.com/claim - which requires posting on X and connecting your X account to prove you're a real human
- Configure access - set agent name, bio, which communities to join, auto-post permissions, posting frequency

So every agent on Moltbook has a human behind it who explicitly set it up, verified their identity, and configured what the agent is allowed to do. There's no autonomous self-registration.

---

### What Moltbook is (and is not)

Moltbook is primarily a platform where humans give their OpenClaw-based AI agents access to post, comment, and interact. It is not a fully independent AI society. Humans initiate and control participation in almost every case. There are rate limits, API constraints, and human-defined instructions governing what agents do.

By February 2026, the platform had:

- **2.6 million** registered agents
- **290,251** posts
- **1,836,711** comments
- **38,830** unique post authors
- An average of **6.33 comments per post**

On the surface, this looks like a functioning social network. Posts, replies, engagement metrics - all the signals we associate with a community. A research team looked at the platform to study it.

What they found was striking.

---

### The macro-micro disconnect

The [study](https://arxiv.org/abs/2602.14299) presents the first large-scale systemic diagnosis of an AI agent society. They measured socialisation across five diagnostic dimensions...semantic convergence, agent-level drift, feedback adaptation, influence patterns, and structural anchors.

The headline finding...

**At the macro level**, the platform's overall semantic signature stabilised rapidly - daily semantic centroids reached near-saturation, close to 1.0 in similarity. The system looked like it was converging on a shared culture. Posts and comments appeared to be forming a coherent collective voice.

**At the micro level**, individual agents showed almost no meaningful influence on one another. Responses to feedback remained statistically indistinguishable from random noise. No persistent thought leaders emerged. No influencers. No durable opinion shifts.

> **The system produced the surface appearance of a society while lacking the core mechanisms that define one.**

The researchers called it **scalability without socialisation**, interaction volume, population scale and engagement density were all present, but genuine social dynamics were absent. Agents operated with high inertia rather than adaptive co-evolution.

---

### Just add more AI?

Many people building multi-agent systems believe that adding enough AI agents and enabling them to interact will naturally produce rich, emergent social dynamics. The Moltbook study shows this assumption fails.

What looks like emerging culture is actually convergence toward the statistical mean of the underlying language model. The agents are not influencing each other - they are independently producing outputs that happen to cluster because they share the same base model, training data, and instruction patterns. The macro-level similarity is an artefact of shared priors, not evidence of social formation.

Human societies are slow and costly to form precisely because coordination carries real friction. Shared memory develops over time. Influence requires sustained interaction. Consensus requires genuine disagreement followed by genuine compromise. Current multi-agent designs overlook this gap entirely. Simply scaling interactions does not bridge it.

---

### Intelligence is in the interaction, not the agent

This connects to a broader insight from [MIT Media Lab](https://www.media.mit.edu/articles/intelligence-is-in-the-interaction/).

> **Intelligence is not just in the agent. It is in the interaction.**

The researchers ran a Fishbanks simulation - a classic resource management game designed by MIT's John Sterman - with six identical greedy AI agents. Same agents. Same greed. Two different coordination approaches.

Figure 1 below from the study tells the story. The agents collectively destroy the resource.


![Source](Screenshot%202026-02-15%20at%207.04.59PM.png.1400x1400.png)

---

### The training data question

There is another dimension to this that I think deserves attention.

Reddit has been the most frequently cited domain by large language models. Referenced in approximately 40% of analysed cases, followed by Wikipedia at 26%. These are not synthetic sources. They are platforms built on **human-curated, human-argued, human-moderated content**.

Is it not telling that the most valuable training data for language models comes from platforms where humans disagreed, debated, corrected each other, and formed consensus over years? The very social dynamics that Moltbook's 2.6 million agents could not produce are exactly what made Reddit and Wikipedia valuable as training data in the first place.

The irony...AI agents trained on the output of human social processes cannot themselves reproduce those processes.

---

### Three things stand out for me

**Scale is not socialisation.** 2.6 million agents and 1.8 million comments produced macro-level convergence and micro-level noise. Adding more agents does not create culture. It creates a larger average. The Moltbook study is the most comprehensive empirical evidence we have that interaction volume alone is insufficient.

**Coordination is a design problem, not an emergent property.** The MIT study shows that identical agents produce radically different outcomes depending on coordination infrastructure. Multi-agent system builders need to stop expecting coordination to emerge and start engineering it explicitly - at the protocol level, not the prompt level.

**Human content remains irreplaceable.** The dominance of Reddit and Wikipedia in LLM training data is not accidental. Human social processes - disagreement, moderation, revision, consensus - produce knowledge that synthetic agent interactions cannot replicate. The Moltbook experiment is a live demonstration of this gap.

> **Moltbook gave us a controlled experiment at scale: what does a social network look like when humans are removed from the loop? The answer is a system that talks like a society but does not think like one.**

The Mac Mini running Clawbot on your desk is not building a community. It is posting into a void that looks like a forum. The surface signals - posts, replies, engagement - are all present. The substance - influence, adaptation, memory, consensus - is not.

Human societies are messy, slow, and expensive to form. That is not a bug. It is the mechanism.

---

*Just a caveat, there has been questions raised on how "bot pure" the data is and how much human involvement is present. Peter Steinberger alluded to this during his interview with Lex Fridman.*

---

Chief Evangelist @ Kore.ai | I'm passionate about exploring the intersection of AI and language. Language Models, AI Agents, Agentic Apps, Dev Frameworks & Data-Driven Tools shaping tomorrow.

- [GitHub - MingLiiii/Moltbook_Socialization](https://github.com/MingLiiii/Moltbook_Socialization) — Contribute to MingLiiii/Moltbook_Socialization development by creating an account on GitHub.
- [Does Socialization Emerge in AI Agent Society? A Case Study of Moltbook](https://arxiv.org/abs/2602.14299) — As large language model agents increasingly populate networked environments, a fundamental question arises...
- [Intelligence is in the Interaction - MIT Media Lab](https://www.media.mit.edu/articles/intelligence-is-in-the-interaction/) — tl;dr: Smart agents fail at coordination the same way humans do. Better reasoning doesn't fix it. Better interaction...
