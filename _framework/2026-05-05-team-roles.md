---
title: Team roles
author: Guillem EfeGe
date: 2026-05-05
categories: [BoosterSkills, Chapters]
layout: post
cover: /assets/covers/booster_skills_identifying_team_header.png
---

Engineering effectiveness is not just about skills and experience; certain personality traits (especially conscientiousness and openness) strongly influence project success. Teams work best when there is personality diversity instead of everyone looking the same on a psych profile. When personalities are too homogeneous, you lose complementarity, repeat the same mistakes, and struggle to adapt to new challenges.

In this chapter, we’ll look at how roles and personality traits interact in software teams, how to avoid destructive archetypes, and how to design a team roles charter you can use for hiring, onboarding, and promotions.

> ##### TIP
>Talent wins games, but teamwork and intelligence win championships.
> 
> --**Michael Jordan**, American Athlete
{: .block-tip }

Looking into what's been written, we can find different approaches.

# Roles and Personality Traits in Engineering

## Belbin’s 9 roles into 3 clusters

Meredith Belbin [^3] was a British researcher who was key to team management. His theory of the 9 team roles helped build more effective teams by grouping personalities into three clusters and showing how a balanced mix improves performance.


**Action‑oriented**. These roles drive delivery, execution, and closure.

- Shaper: energetic, pushes the team to meet deadlines, challenges the status quo.
- Implementer: organized, turns ideas into practical plans, reliable, and disciplined.
- Completer‑Finisher: detail‑focused, ensures quality, and meets deadlines.

**People‑oriented**. These roles focus on team cohesion, communication, and alignment.

- Coordinator: chairs the team, clarifies goals, delegates, and steers the group.
- Teamworker: supportive, diplomatic, manages interpersonal friction.
- Resource Investigator: outgoing, explores ideas and contacts outside the team.

**Thought‑oriented**. These roles focus on ideas, analysis, and expertise.

- Plant: creative, ideas‑driven, generates novel solutions.
- Monitor Evaluator: logical, analytical, weighs pros and cons.
- Specialist: deep technical or domain‑specific knowledge.

This maps nicely to software: Implementer/Stabilizer types who ship, Plant/Innovator types who invent, Specialist types who go deep in a stack. The problem is that most engineers have never taken Belbin, and formal workshops feel heavy‑weight. In practice, this adds another layer of complexity to teamwork and, in line with the spirit of this framework, a more practical process is possible.

**How to use this in practice**

You don’t need formal Belbin workshops. Instead, during 1:1s and retrospectives, observe:

- Who naturally pushes for deadlines and closure (Action‑oriented)?
- Who keeps the team connected and aligned (People‑oriented)?
- Who brings the deepest analysis or most creative solutions (Thought‑oriented)?

Use these observations to balance squads, not to label people permanently.

## Personality traits (Big Five) in engineering

Higher Conscientiousness and Extraversion in software teams correlate with better performance and fewer effectiveness problems. MBTI is common in IT but controversial scientifically; many studies still use it to describe typical engineer profiles (e.g., introversion, thinking preference). You don’t need to run tests, but it’s useful to know that traits like openness, conscientiousness, and extraversion materially affect collaboration and creativity in knowledge‑work teams.

This table shows a summary of the personality traits defined in _Big Five_ [^4]

| Trait (Big Five)    | When it’s high in engineers                                                    | Risk if everyone is high                                        | Value when balanced in team                                          |
| ------------------- | ------------------------------------------------------------------------------ | --------------------------------------------------------------- | -------------------------------------------------------------------- |
| Openness            | Innovation, learning new tech fast, creative problem solving.                  | Perpetual change, unstable stack, unfinished experiments.       | Some explore, others stabilise and standardise.                      |
| Conscientiousness   | Reliability, fewer bugs, stronger ownership, predictable delivery.             | Rigidity, burnout, over‑process.                                | High‑C core plus a few flexible rule‑challengers.                    |
| Extraversion        | Easier stakeholder communication, facilitation, visible leadership.            | Meeting‑heavy, less deep work, political games.                 | Mix of “front‑stage” and “deep work” engineers.                      |
| Agreeableness       | Collaboration, trust, psychological safety.                                    | Avoided conflict, weak technical challenge.                     | High‑A glue plus a few lower‑A truth‑tellers.                        |
| Emotional Stability | Calm in outages, steady under pressure.                                        | Complacency, underestimating risks.                             | Calm ICs plus some more vigilant, risk‑sensitive members.            |

**How to use this in hiring and team design**

- For a greenfield product or heavy discovery, deliberately hire more openness and extraversion.
- For a platform or reliability‑focused team, bias toward conscientiousness and emotional stability.
- For leadership roles, look for people who can flex between traits depending on context.

### Why personality matters more than we admit in engineering teams

These classifications will help us later in the chapter to determine which types of personalities fit better in each team. Remember this is not an exact science; it’s guidance, not a strict rulebook.

Engineering teams usually work under big uncertainty and pressure to meet deadlines. These are the kind of ingredients that generate frictions, frustration, and confrontations inside the team and with other teams. We are not used to accept in first instance that we might be not fully right and, let's admit it, we are not usually the most humble and rational kind of professionals.

I've seen many times cases where the autodefined 'rock star' of the team is not willing to accept any suggestion or amendment about any contribution, clearly believes that true and knowledge is always on his side. Strong personalities of this type need to be redirected quickly; if that fails, you should actively manage them out, otherwise team morale and motivation will drop.

We should aim for team members open to help but, at the same time, aware about each other responsibilities. You cannot expect others to do your tasks or follow your instructions just because you need help, being humble and open for mentoring and directions is a better attitude inside the team. Engineers often decide alone on topics where they are not the accountable owner. This usually ends badly when they later try to justify that the decision “came from someone else” while they are still accountable for the result.

### Designing teams for personality diversity, not “culture fit”

“Culture fit” often ends up meaning “does this person think like we do?”, and that is dangerous. I’m not against cultural fit; in early‑stage startups you need people who share core values like ownership, resilience, and willingness to do unglamorous work. The problem starts when you filter for personality sameness instead of shared values. Great teams are built on personality diversity with values alignment.

**Practical tip for interviews**

When you feel “I don’t click with this person”, ask yourself:

- Are they misaligned with our values?
- Or just different in style from the rest of the team (more direct, more quiet, more questioning)?

The first is a problem; the second is often exactly what the team needs.

### Common engineering archetypes and where they thrive

High‑performing teams cannot tolerate persistent single‑player behaviour; collaboration and shared ownership are non‑negotiable.

#### The Lecturer

This attitude can emerge in people who have worked in “better” teams or who see themselves as the most experienced person in the room. They feel entitled to continuously correct the rest of the team, often using a condescending tone and presenting their opinion as absolute truth. They rarely bring concrete, collaborative solutions, and often avoid backing their claims with data or analysis.

**Early signals**

- Frequently starts sentences with “Actually…” or “The right way is…” in discussions.
- Shoots down ideas without proposing alternatives.
- References past teams or companies as the only valid benchmark (“In my previous team we always…”).

**Impact on the team**

- People stop contributing ideas to avoid being “corrected”.
- Retrospectives turn into monologues instead of collaborative learning.
- Juniors either mimic the same behaviour or disengage completely.

**If you recognise yourself in this**

- Before giving feedback, ask: “Do you want input on this?” and “What outcome are you aiming for?”.
- For every criticism, bring at least one realistic alternative and an offer to help implement it.
- Ask 1–2 trusted colleagues: “Does my feedback sometimes feel condescending? What would make it easier to work with me?” and listen without defending yourself.

**If you manage or work with a Lecturer**

- Give clear feedback on behavior and impact, not personality (“When you correct people in that tone, they stop speaking up.”).
- Redirect them into mentoring or design reviews with clear expectations: challenge ideas, not people, and always bring options.
- If patterns don’t change over time, you may have to limit their influence on key discussions or, in extreme cases, manage them out to protect the team.

#### The Climber

The Climber is obsessed with getting promoted, sometimes at any cost. They can appear very supportive and collaborative—as long as their actions are visible and rewarded—but their main focus is their own trajectory, not the team’s outcomes. Their career often illustrates Peter’s principle: they climb quickly based on perception, then get stuck at a level where they’re not truly effective.

**Early signals**

- Volunteers mainly for high‑visibility work, avoids necessary but “boring” tasks.
- Manages “up” very well but contributes less in peer‑to‑peer collaboration.
- Frequently positions themselves as the hero who “saved” a project, often downplaying others’ contributions.

**Impact on the team**

- Credit and recognition become political instead of fair.
- People feel used: supported when it benefits the Climber, ignored otherwise.
- Decisions are optimised for personal optics, not for long‑term product or technical health.

**If you recognise yourself in this**

- Ask yourself, for each quarter: “What did I do that made the team more effective, even when nobody was watching?”.
- Commit to owning at least one low‑visibility, high‑importance task (documentation, mentoring, automation, incidents follow‑up).
- In performance conversations, emphasize team outcomes and shared wins, not just your individual achievements.

**If you manage or work with a Climber**

- Make evaluation criteria explicit: reward long‑term impact, collaboration, and ownership, not just visibility.
- Give feedback quickly when they take credit unfairly or throw others under the bus.
- Pair promotions and opportunities with clear expectations about supporting others, not just performing individually; if behaviour does not evolve, they can become one of the most damaging profiles in the team.

#### The Keeper

The Keeper bases their value on exclusive knowledge of a system or process. They believe that being “indispensable” protects them from risk, so they avoid documentation and resist any attempt to share or distribute their knowledge. They see curiosity from others as a threat rather than a chance to build resilience in the team.

**Early signals**

- Often says “It’s complicated” but doesn’t explain further.
- Avoids pairing or only pairs on trivial tasks.
- Critical parts of the system can “only” be touched when they are available.

**Impact on the team**

- They become a bottleneck in the best case; in the worst case, they block progress entirely when sick, on vacation, or after leaving.
- Onboarding slows down because new people struggle to understand core flows.
- Incidents take longer to resolve because knowledge is centralised in one person.

**If you recognise yourself in this**

- Reframe your value: from “I’m the only one who knows this” to “I’m the person who made this easy for others to understand and maintain”.
- Each week, document one area you “own” and walk someone through it. Treat it as an investment in your future flexibility and career.
- Ask your manager to explicitly recognise documentation and knowledge sharing as part of your performance.

**If you manage or work with a Keeper**

- Make knowledge sharing non‑negotiable: documentation, pairing, and handover should be part of goals and expectations.
- Spread ownership deliberately: rotate people through critical components and on‑call duties.
- Explain clearly that being the only one who knows something is a risk, not job security; this profile is often the easiest to redirect when incentives and expectations are clear.

In general, building a team based on attitude more than on aptitude is a strong starting point to avoid these patterns. Leaders who value coachability, reliability, and emotional intelligence create environments where Lecturers can become mentors, Climbers can become true leaders, and Keepers can become enablers of collective strength.

# Skills and roles in cross‑functional software teams

## Product Manager/Owner

We should expect a professional with a **global vision** of stakeholder needs, the **what**, the **when**, and the **urgency**. This role needs to be a **great communicator**, able to explain _what_ is needed and _why_ with precision, while also being an effective **negotiator**, since each need often comes with caveats and trade‑offs that the engineering team will surface.

Being able to give **clear instructions** and **set the right priorities** are the two most important traits for this role. Gaining the **team’s trust** is essential because the Product Owner is the one who sees the full map and decides the next step on the path.

The biggest risk for this role is the tendency to instruct about the **how**, which is never its responsibility, but only the **what**. Another common trap is when something urgent jumps onto the board, and there’s a temptation to insert it immediately into the work‑in‑progress. This is when negotiation skills must kick in to decide what can be removed from the planned work, since effort and time were already agreed upon during planning.

**Key traits**:

- Strong communicator who explains what is needed and why, with precision.
- An effective negotiator who handles trade‑offs and prioritization without overstepping into the how.
- Prioritizes trust and clarity over micro‑management, and protects the team from constant context shifts.

**Pitfalls to avoid**:

- Instructing the team on how to implement features.
- Adding urgent items into ongoing work without re‑negotiating the scope and commitments.

## Frontend/Backend/Full‑stack Engineer

Engineers are focused on **fixing problems**. This is important because, in software teams, engineers should not be focused on _which_ problem to solve, but on _how_ to solve the one that has been chosen. This is the opposite of the Product role: here, the focus is on the how, not the what.

This role must be able to communicate **technical limitations and possibilities**, and, one of the hardest parts, **estimate the effort** required to solve a given problem. To do this, engineers can and should ask to break problems into **smaller**, **manageable pieces** that can later be integrated into the larger solution.

It is also the engineer’s responsibility to request all the **information and clarifications** needed so that both the Product Owner and the Engineering team have the **same understanding** of what must be built. We’ll come back to this idea later, in the section on communication.

**Key traits**:

- Strong problem‑solving skills and the ability to break down complex work into smaller, manageable pieces.
- Ability to communicate technical constraints, options, and effort estimates clearly.
- Proactive in asking questions to ensure shared understanding with Product and QA.

**Pitfalls to avoid**:

- Building without clarity on requirements or acceptance criteria.
- Skipping collaboration with Product and QA to avoid “waste” or “over‑engineering”.

## QA Engineer

The QA Engineer works closely with **developers**, **product managers**, and **designers** to clarify requirements, influence design, and prevent bugs early. This role helps define **quality standards**, **acceptance criteria**, and **exit criteria** for each release or sprint, and often designs and improves the QA process, including test automation, metrics, and tooling.

This implies that **quality is everybody’s responsibility** in the team, and QA Engineers exist to ensure standards are met, not to test everything developers implement. This is a very important point, because in the past I’ve seen many companies delegate the _entire testing implementation_ to QAs, which pushes the complexity of the software development process to unmanageable levels.

The ideal personality for this role is **methodical**: structured, persistent, and consistent in review and communication. They don’t necessarily need to be a charismatic communicators, but they must be **direct and clear**; quality should never be a blurry or negotiate‑on‑the‑fly concept.

**Key traits**:

- Methodical, structured, and consistent in reviewing and communicating issues.
- Direct and clear; avoids “fuzzy” definitions of quality.
- Focused on defining quality standards, acceptance criteria, and exit criteria, not on executing all tests by themselves.

**Pitfalls to avoid**:

- Becoming the sole “test gatekeeper” for the team.
- Letting testing be treated as a late‑stage activity instead of an integrated part of the workflow.

## DevOps/Cloud Engineer

This role is, in a way, an **evolution of software engineering**, requiring some of the same capabilities while complementing them with others. The DevOps/Cloud Engineer needs to stay **calm under pressure**, because incidents and late‑night outages are part of the job. They should be **curious and analytical**, always asking “why did this happen?” instead of jumping to quick guesses.

They must be **organized and reliable**, because automation, deployment, and infrastructure work depend on **consistency and repeatability**. Being **collaborative and empathetic** is also key, as DevOps involves working across development, operations, security, and product teams.

**Adaptability** is another core trait: tools, pipelines, and systems change constantly, and this role has to move with them without losing stability or clarity.

**Key traits**:

- Calm under pressure, especially during incidents and outages.
- Curious and analytical, always asking “why” rather than assuming.
- Organized and reliable, ensuring that automation, deployments, and infrastructure are consistent and repeatable.
- Collaborative and empathetic, bridging dev, ops, security, and product.

**Pitfalls to avoid**:

- Over‑optimizing for “cool tech” at the expense of stability and clarity.
- Operating in isolation instead of embedding into the development lifecycle.

## Scrum Master/Agile Coach

We are looking for **openness and motivation** in this role. The journey of improving development processes is rarely straightforward, and the Agile Coach must **motivate the team**, **remove obstacles**, and **protect it from external interference**, while also **raising the flag early** when something threatens the team’s commitments.

This role cannot be performed by a shy or purely methodical person. Instead, it suits someone who is comfortable spending a large amount of time **training**, **facilitating**, and **talking with the team**, continuously capturing the pulse, finding solutions, and escalating issues that cannot be solved immediately or that affect other teams.

**Key traits**:

- Open, motivated, and comfortable spending time coaching, facilitating, and listening.
- Proactive in raising concerns early, especially when external pressure threatens the team’s commitments.
- Skilled at balancing the protection of the team with transparency to stakeholders.

**Pitfalls to avoid**:

- Being a passive administrator of ceremonies instead of an active coach.
- Avoiding difficult conversations about process or performance issues.


# Takeovers

> ##### TIP
> * Face your team personalities issues soon and looking for the best fit, most personalities can bring value.
>
> * Avoid the archetypes that hurt your team as soon as possible.
>
> * During **onboarding**, share the _team roles charter_ with new engineers, QAs, DevOps, and product folks to help them understand expectations and boundaries.
>
> * In retrospectives, use the _team roles charter_ as a baseline to discuss how closely the team is living these roles.
>
> * When defining job descriptions or promotion rubrics, map each role’s traits and pitfalls directly into skills and behaviors.
{: .block-tip }

[^3]: [Meredith Belbin](https://en.wikipedia.org/wiki/Meredith_Belbin)
[^4]: [The Big Five at work: Engineering personalities into collective strength](https://hrzone.com/the-big-five-at-work-engineering-personalities-into-collective-strength/)