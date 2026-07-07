---
title: Customers & Users - Bringing the Outside In
author: Guillem EfeGe
date: 2026-06-25
description: "How to keep customer and user reality flowing into your team’s decisions through feedback, narratives, and everyday habits."
tags:
  - framework
  - wan
  - customers
  - users
  - feedback
  - product
categories: [BoosterSkills, Chapters]
layout: post
published: true
---

If WAN is how you connect your team to the outside world, customers and users are the clearest signal of whether what you’re building actually matters.

They are the people who feel your product in their day‑to‑day lives: the ones who struggle with a workflow, celebrate a feature, or quietly churn when you miss the mark. At this layer, your job is not just to “serve the business,” but to translate real‑world problems and behaviors into decisions your team can act on without guesswork.

Most teams think they’re customer‑centric because they occasionally read feedback or look at a dashboard. In practice, many operate with a blurred picture of who their users really are and what they’re trying to get done. That’s how you end up shipping features that are technically correct but emotionally wrong: they work, but they don’t solve a meaningful problem, so usage is low and frustration is high. Bringing the outside in means treating customer understanding as a continuous input into your decisions, not a one‑off research activity.

When this works, your team feels connected to reality: people can link their tasks to concrete user stories, support tickets, usage patterns, and business outcomes. You see more “we built this because…” and fewer “we built this because someone in a meeting said so.” When it doesn’t, you get local optimizations: elegant technical solutions to problems nobody asked you to solve, while the actual painful issues remain untouched.

I’ve seen teams spend weeks polishing workflows that made perfect sense internally, only to discover later that customers were still struggling with the most basic step of the journey. In one case, a team released a more powerful admin panel, with extra filters and better visibility, only to learn that the main frustration for users was still the confusing onboarding sequence they had to pass through before they could even reach those screens. The team had built something useful, but not something urgent. That is one of the clearest WAN failures: the signal from outside never really made it inside.

# Who Are Your Real Customers and Users?

Inside the company, you have plenty of internal stakeholders: managers, PMs, execs, and other teams. They all have opinions. But your customers and users live outside that bubble. They are the people who pay, adopt, recommend, ignore, or abandon your product, and they are often more diverse than your internal mental model suggests.

A simple distinction helps:

- **Customers** are the people or organizations who buy, approve, or fund the product.
- **Users** are the people who actually interact with it day after day.  

Sometimes they are the same person. Often they are not.

If you only optimize for the buyer, you risk making a product that demos well but frustrates the people who have to live with it. If you only optimize for the user, you can miss the real buying constraints: cost, compliance, reporting, integration, legal requirements, or organizational fit. WAN means understanding both sides and knowing when the signals conflict.

> **Example:**
>
> A B2B support platform invested in advanced reporting because leadership kept hearing that customers wanted “more visibility.” The feature looked strong in demos and helped in sales conversations. But daily users — support agents and team leads — were still losing time on a clumsy macro editor that made repetitive tasks painful. The buyers liked the reporting story. The users still struggled with the product. Once the team separated customer needs from user pain, their priorities became much clearer.
{: .block-tip }

# Practical Ways to Collect Ongoing Feedback

You do not need a big research department to stay connected to customers. You need a small number of reliable channels and the discipline to use them consistently. The goal is to create a steady stream of outside signals instead of relying on occasional heroic research efforts.

Useful sources include:

- Support tickets and customer success conversations.
- Product analytics and usage drop‑off points.
- Short customer interviews around specific workflows.
- Beta groups, pilots, or early access programs.
- Sales calls, onboarding calls, and implementation reviews.

Each source has limitations on its own. Support shows pain but not always priority. Analytics show behavior but not intent. Interviews show context but on a small sample. When you put them together, they start to behave like a healthier WAN: not one perfect signal, but several weaker signals that reinforce each other.

> **A simple habit that pays off:**
>
> One manager blocked 30 minutes every Friday to read support patterns and review one real customer story with the team. Not a giant report, just one issue, one quote, one workflow, and one lesson. Over a few months, that created better product instincts than many planning meetings, because the team kept hearing real language from real users.
{: .block-tip }

# Turning Raw Feedback into Actionable Narratives

Raw feedback is noisy. It arrives as complaints, feature requests, screenshots, frustration, praise, or offhand comments in calls. Teams cannot act well on a random pile of disconnected signals. They need feedback translated into narratives that explain the problem clearly enough to guide action.

A useful structure is simple:

- **Who** is experiencing the problem?
- **What** are they trying to achieve?
- **Where** does it break down?
- **Why** does it matter?

That last part matters more than many teams realize. If you cannot explain why the issue matters, it becomes easy to deprioritize or overreact to. A clear narrative helps you compare it against other work without reducing everything to “someone asked for this.”

> **Example in practice:**
>
> “Users want faster reports” is weak.  
> “Operations managers need to export shift data in under 2 minutes before daily stand‑up; current exports take 15+ minutes, which delays planning and causes manual workarounds” is much stronger.  
> The second version gives the team a role, context, time pressure, and business impact. That is something people can build around.
{: .block-tip }

These narratives become one of the most useful bridges between outside reality and inside execution. They help engineering, product, design, and leadership look at the same problem with the same frame.

# Keeping Customer Stories Visible Day to Day

Customer understanding fades quickly when it only lives in long documents, research folders, or quarterly slide decks. If you want the outside world to shape daily decisions, then customer stories need to be visible in the normal flow of work.

That does not require a big process. Small rituals are usually enough:

- Start planning or refinement with one recent customer story.
- Include a real scenario in product demos, not just a feature tour.
- Keep a lightweight wall, page, or board of recurring customer pain points.
- Ask support, sales, or customer success to share one meaningful signal each week.

These habits make the product feel less abstract. They also help teams make better trade‑offs, because people can picture who is affected instead of only thinking in tickets and deadlines.

> **A small ritual:**
>
> One team opened sprint planning with a two‑minute “customer moment.” Sometimes it was a support quote. Sometimes it was a short onboarding story. Sometimes it was a chart showing where users kept dropping off. It was small, but it changed the tone of planning. Engineers started asking, “Which kind of user is this really for?” before debating implementation details.
{: .block-tip }

# Balancing What Users Ask For with What Makes Sense

Listening to users does not mean saying yes to everything they request. Some requests are real needs. Others are workarounds disguised as solutions. Some are valuable but too narrow. Some are loud but not important. Good WAN work means listening carefully without becoming a feature factory.

A useful mindset is to treat every request as a signal about a problem, not as a final specification.

Ask questions like:

- What are they really trying to achieve?
- Is this problem recurring across segments?
- Is the requested solution the best one, or just the most visible one?
- Would solving the underlying issue create broader value?

This is one of the places where maturity matters. Customers want to feel heard, not necessarily obeyed. If you can explain that you understood the pain, investigated the context, and chose a better path, trust often grows even when the exact request is declined.

> **Concrete example:**
>
> A large customer pushed hard for a custom workflow that would have added a lot of complexity to the product. Instead of deciding too quickly, the team dug into the problem and learned that the real pain was double data entry across two systems. They ended up building a simpler export path that solved the issue for that customer and several others. The original request was rejected, but the real problem was solved more cleanly.
{: .block-tip }

# Building an Outside‑In Habit in the Team

Bringing the outside in is less about one big research effort and more about repeated habits. You want a team that naturally asks, “How does this show up for real users?” before jumping into solution mode.

That usually shows up in small behaviors:

- Rotating who joins customer or onboarding calls.
- Requiring some outside evidence for bigger initiatives.
- Reviewing key customer metrics together, not only in leadership decks.
- Connecting wins to real user outcomes, not only delivery milestones.

Over time, this changes the culture. Customer understanding stops being a specialist activity and becomes part of the team’s shared operating model. The WAN gets healthier because signals from outside do not need to fight their way in; they already have a route.

> **You can usually spot the shift when:**
>
> People start interrupting internal debates with questions like “Which users is this helping?” or “Do we know this is a real pain, or just a guess?” That is a strong sign that the outside world is no longer an occasional visitor in your process. It has become part of how the team thinks.
{: .block-tip }

# Key Ideas

> * Customers and users are not the same as internal stakeholders. You need to understand both buyers and daily users.
>
> * Outside signals become useful when they are continuous, not occasional.
>
> * Raw feedback needs translation into clear narratives: who, what, where, and why it matters.
>
> * Small rituals help customer stories stay visible in everyday work.
>
> * Listening well does not mean saying yes to every request; it means understanding the real problem underneath.
>
> * A strong WAN keeps your team grounded in real people, not only internal opinions.
>
{: .block-tip }

# Related Pages

- [WAN](../2026-06-05-part3/)
- [Stakeholder Map & Expectations (inside + outside)](../2026-06-06-stakeholder-map/)
- [Cross-Team Collaboration & Dependencies](../2026-06-25-cross-team-collab/)