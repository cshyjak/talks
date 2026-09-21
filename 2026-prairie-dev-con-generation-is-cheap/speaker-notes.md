# Speaker notes

Concise delivery notes for **Generation Is Cheap. Judgment Isn't.** Slides without a note are intentionally omitted.

## Slide 3 — About me

I have always been drawn to the problem more than the solution: building computers, taking them apart, and then building software for more than twenty years.

I am not here as an AI evangelist. I am skeptical of the marketing, but most of my coding now begins with a prompt. My work had already moved from direct implementation toward design and partnership; agentic AI accelerated that transition dramatically.

What used to happen across a career is now happening to the whole industry in a few years.

## Slide 4 — The middle of the transition

We are not at the beginning or the end of this change. We are in the middle of it.

The technology is moving faster than the habits, systems, and careers built around the old constraint.

## Slide 5 — Four lenses

These are not four separate trends. They are four views of the same shift: how we build, how we break, how we defend, and how we grow.

The pressure comes from all four moving at once.

## Slide 6 — Core thesis

AI makes generation cheap. It does not make software cheap.

The scarce work moves downstream: judgment, review, debugging, trust, and accountability.

## Slide 8 — Conversational development

ChatGPT normalized the conversational interface. The next wave pulled developers out of the IDE and into chat-first tools. Now assistants are moving into the places where work already happens.

I work in a hybrid mode: the chat interface handles much of the generative work; the IDE is where I apply judgment. That changes the interface, the audit trail, and eventually what it means to onboard a developer.

## Slide 9 — The 10x engineer

The old “10x engineer” idea was never really about typing speed. The gap was problem framing, design judgment, and knowing what not to build.

I once compared code metrics with a junior developer and had deleted more code than either of us had created. An elegant, understandable solution is more valuable than a larger one.

When generation is cheap, the highest-leverage work is still choosing the smaller solution, reducing unnecessary surface area, and stopping the wrong project before it absorbs six sprints.

## Slide 10 — Cheap in time, not in dollars

“Generation is cheap” describes time and effort, not cost.

AI can genuinely change a team’s economics when it replaces work. But if it sits on top of the same headcount and simply accelerates an expanding backlog, it is speed without direction.

As time becomes less scarce, value becomes more important. “Can we build this?” increasingly becomes yes. “Should we build this?” is the question the token budget cannot answer.

## Slide 11 — The ecosystem shift

The platform question is becoming an ecosystem question.

The leading agentic tools increasingly treat GitHub issues, pull requests, and workflows as their native operating environment. The decision is no longer only about source-control features; it is about where the next layer of developer tooling will be built first.

## Slide 12 — Review becomes production

This is not an ethics argument. It is a capacity argument.

Agentic tools remove the effort tax that used to keep low-quality contributions relatively rare. Output can scale faster than the people and systems that can evaluate it. The review queue becomes the constraint.

## Slide 15 — Observability

Most organizations are not short on telemetry. They are short on systems that make the next action obvious.

The cost is familiar: dashboards nobody opens, alerts snoozed by reflex, and expensive logs that only become relevant during a P1. Adding AI does not fix that. Its non-deterministic paths can make the system harder to trace in the ways we already understand.

Observability is not a data problem. It is a design problem.

## Slide 16 — Finding the problem

Real debugging is holding a mental model of a complex system under pressure: forming, challenging, and falsifying hypotheses while the business is on fire.

Recent outages reinforced this for me. AI helped gather information and suggest paths, but it did not solve the problem. At times it reinforced an invalid assumption and made the investigation worse. Information is not understanding.

AI handles many easy first-pass cases well. The concern is that easy cases do not build debugging instinct. That comes from repeated production ownership and accountability.

## Slide 17 — Feeling fast, going slow

This result matters because it separates feeling faster from being faster.

Experienced developers predicted a large speedup. After the work, they still believed AI had helped. But the measured result was slower. Subjective productivity is not the same as delivered productivity.

## Slide 18 — The comprehension gap

The next question is not only whether AI speeds up a task. It is whether it changes what the developer learns while doing it.

This study connects assistance to a comprehension gap, especially in debugging. That is the long-term risk: delegating the reps that build judgment.

## Slide 19 — The receipts

This is a trend line, not a single anecdote: more AI-assisted output, more review volume, and a quality signal moving in the wrong direction.

The point is not that every AI-authored pull request is bad. It is that review capacity and understanding are not scaling at the same rate as generation.

## Slide 20 — Who investigates the investigator?

When a real incident happens, decisions are made quickly and depend on understanding how the system fits together.

Handing diagnosis to another AI does not remove the need for that understanding. It can move the answer one more layer away from the person who would recognize when it is wrong.

## Slide 22 — Defensive depth

Defensive depth is not a credential. It is pattern recognition built through years of reading other people’s code, inheriting broken systems, and learning to sense that something is wrong before it becomes an incident.

Those engineers took years to develop. We should be deliberate about whether we are still creating the conditions for the next ones to emerge.

## Slide 23 — Supply chain

The immediate failure was trust in a mutable dependency reference. A tag can be moved; an immutable commit SHA cannot.

The broader lesson is simpler: every dependency is a trust decision. Pin what you trust, understand what is in the supply chain, and keep verifying it after the build passes.

Supply-chain vigilance is not a project. It is a practice.

## Slide 24 — Two different “no” answers

There are two different reasons to say no to AI.

A quality-based refusal says, “I do not trust this output yet.” A values-based refusal says, “I do not trust the production model behind it.” Both are legitimate, but they are different conversations.

## Slide 25 — Values-based refusal

For some people, the objection is not whether the output is good enough. It is whether the social, economic, or environmental cost is worth the gain.

Better output does not resolve that concern. It is a question of values and accountability, not code quality.

## Slide 26 — Assistance and authority

The useful distinction here is between assistance and authority.

A tool that flags problems can be valuable. A tool that decides what merges changes the trust boundary. The emerging pattern is not rejection of AI; it is conditional use with human accountability remaining explicit.

## Slide 29 — POC hard and fast

My own background is architecture, where ML work used to mean connecting specialist peers: model training, pipelines, and early experimentation were clearly separate domains.

That boundary has moved. AI makes it cheaper to drive a proof of concept far enough to learn what is real, then bring specialists in with evidence rather than abstract requirements.

The judgment is knowing when to drive and when to hand off. That is a prioritization decision, not a coding decision.

## Slide 30 — The floor moved

The question is not whether people should use AI. It is whether they are still learning the underlying work.

I recently helped a student preparing for co-op applications. Using AI for a first pass on a résumé was useful. The more important conversation was about how they were being introduced to the stack: whether they were gaining enough independent practice to understand and own the work.

## Slide 31 — Satisfaction paradox

The people who gain the most from AI assistance can also be the least equipped to recognize when it is wrong.

That does not argue for withholding the tools. It argues for pairing them with deliberate practice, feedback, and real ownership.

## Slide 32 — Work accelerates

AI can reduce burnout when it removes repetitive work. It can create a different kind of exhaustion when people become constant supervisors of systems they do not fully trust.

The distinction matters. The goal is not to automate every task. It is to use automation to create better work, not simply more oversight and more throughput.

## Slide 33 — Editor, not author

There is a familiar career parallel here. Moving from implementation into leadership changed how I contributed; the craft became more about direction, review, and helping others do their best work.

AI is compressing that transition for many developers. If generation and review become routine delegation, the question is not whether we become less technical. It is whether we become better at direction, product judgment, and accountability.

## Slide 37 — Where are you now?

This is the diagnostic question for the whole talk.

AI can help us ship, review, and diagnose. The question is whether our teams still understand enough to own the result when the tools are wrong or unavailable.

## Slide 38 — Where do you want to go?

The point is not to reject AI or to pretend this transition can be paused.

It is to choose the end state deliberately: use AI to make exploration cheap, while preserving the judgment, ownership, and practice that make software trustworthy.
