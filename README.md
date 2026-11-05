<!--
public-header:
  originator: "Jonas Maandi Wallin"
  editor: "Jonas Maandi Wallin"
  contact: "https://www.linkedin.com/in/jonasmaandiwallin"
  license: "CC-BY-4.0"
  repository: "https://github.com/jonasmaandiwallin/jonasmaandiwallin"
  path: "README.md"
-->
# Kebab and strategy by day, kebab-case by night.

I make my living in FMCG market strategy. The repositories here are what happens when I spend my spare time exploring how far agentic engineering can go – without writing code myself.

It started with a question from my wife, looking at my running gear, watches and data: "What are you actually going to do with all that?"

Well, call it my "hold my beer" moment.

Late 2025. AI hype was in full swing. Everyone seemed convinced you could build just about anything with AI. I was more sceptical. I'd done some vibe coding before. It was exciting, until things started falling apart. The AI would fix one bug and quietly break three features, all while remaining perfectly polite and cheerful.

But I had a thought: what if AI-generated software could be made traceable, verifiable and structured in a way that language models could reliably work with? I don't read code, so I needed a way to understand what had actually been built, whether it matched the specification, and whether the intended logic was really there. Not by taking the AI's word for it, or trusting a green checkmark. I needed a verification harness that made the implementation's behaviour visible and testable.

That led me to contract-driven design: define what something must do, how it should be verified, and what must never be compromised, before letting agents build it.

I decided to put that idea to the test by building something I genuinely wanted: an adaptive, evidence-based running coach that could make smarter use of all the data runners already collect, and get the most out of the fewest sessions a week without breaking them. Every previous attempt at a sub-40 10K had ended the same way: overuse injury, forced rest, start over.

Building Runapp was anything but straightforward. Things broke. Agents lost context. Fixes created new problems. But rather than patching things up and moving on, I treated every failure as a design problem. Each incident led to a new architectural constraint, a better contract, a stronger verification mechanism or a more reliable way of coordinating agents.

But verifying that the software did what it was specified to do wasn't enough. I also wanted to know whether the underlying engine could actually deliver better training plans than existing approaches. Correct implementation doesn't guarantee better outcomes. That led to Runapp Validation: a simulation environment built to challenge the engine, test its assumptions and evaluate its performance before real runners would have to trust it.

Gradually, the solutions developed across both projects started forming a coherent system. What emerged from building and validating Runapp became Governed Agentic Engineering (GAE): a set of standards and practices for making agentic software development traceable, verifiable and governed. Not a framework I designed first and applied afterwards, but one that grew organically from solving real problems while building and testing a real product.

Trying to solve one problem produced three things, published here in the order they are best read: the method, the product, and the proof.

Grab a kebab and take a look.

| | Repository | What it is |
|---|---|---|
| **Method** | [governed-agentic-engineering](https://github.com/jonasmaandiwallin/governed-agentic-engineering) | GAE: standards and a starter kit for governed agentic software development, where the agents that write the specification are governed as strictly as the ones that write the code. |
| **Product** | [runapp-platform](https://github.com/jonasmaandiwallin/runapp-platform) | Runapp, an evidence-based running coach built with GAE. Deterministic at runtime, governed in evolution. |
| **Proof** | [runapp-validation](https://github.com/jonasmaandiwallin/runapp-validation) | How Runapp measures its plans before a runner follows them: a simulator, QDOT, and the strongest case against the results. |

### What this is not

It is one person's work, with agents in governed roles doing the drafting and building under my direction. GAE was developed in one installation and tried in a second; no outside adopter has installed it yet. This is an ongoing exploration, not a claim of an established industry standard.

### Elsewhere

*Explorations in agentic engineering* on X: [@j_wallin](https://x.com/j_wallin). Contact: [LinkedIn](https://www.linkedin.com/in/jonasmaandiwallin).
