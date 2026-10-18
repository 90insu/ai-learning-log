# Week 1: AI Literacy (Oct 12–18, 2026)

## Completed
| Date | Course | Issuer | Result |
|---|---|---|---|
| 2026-10-14 | AI Fluency: Framework & Foundations (15 lessons) | Anthropic | Certificate |
| 2026-10-16 | Claude 101 (15 lessons) | Anthropic | Certificate |

Both finished ahead of plan (scheduled for Oct 16 and Oct 17).

## Key takeaways

1. **AI fluency is a working skill, not tool knowledge.** The 4D framework
   (Delegation, Description, Discernment, Diligence) maps onto how engineers
   already work: decide what to hand off, specify it clearly, review the
   output critically, and own the final result.

2. **Context determines output quality.** Clear, specific prompts with the
   right background (files, constraints, examples) matter more than clever
   wording. It's the same as writing a good requirement: ambiguous input
   produces ambiguous output.

3. **The features are building blocks for workflows.** Projects (persistent
   context), artifacts (shareable outputs), skills (repeatable procedures),
   connectors (live data from tools) and research (multi-source deep dives)
   combine into systems, not just chats.

## Method to reuse: simple eval loop
1. **Gather examples:** 5–10 instances of a recurring task with known good answers
2. **Create test prompts:** include the context I'd naturally have when doing the work
3. **Compare outputs:** key information captured? tone right? what's missing?
4. **Refine:** adjust prompts, add examples of "good", or mark where human review is required

This is verification against a reference, the same discipline as V&V in engineering.

## Applying it to engineering work
Candidate tasks for an eval loop, using synthetic or public data only:
- **Requirements review:** flag ambiguous, untestable or conflicting requirements
- **Design review prep:** generate checklist questions from a design description
- **Test planning:** draft test cases from a requirement set
- **Technical documentation:** summarize specs or standards into one-page briefs
- **Failure analysis:** draft FMEA/FMEDA rows for a simple component, scored against my own answers

## Reflection
- **What worked:** short daily sessions on office days, longer blocks on WFH days.
- **What to watch:** course sites are moving (Skilljar → Claude Academy), so download certificates immediately.

## Next week
- CS50P Lecture 0: Functions, Variables
- Problem Set 0 (5 problems), submitted through cs50.dev
