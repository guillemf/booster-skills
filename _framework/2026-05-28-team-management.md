---
title: Team Management
author: Guillem EfeGe
date: 2026-05-12
categories: [BoosterSkills, Chapters]
layout: post
# cover: /assets/covers/booster_skills_people_onboarding.png
---

>It is amazing what you can accomplish if you do not care who gets the credit.
>
>
> --**Harry S. Truman**, 33rd President of the U.S.
{: .block-tip }

We could say that team management is somehow an art, not in the sense of artistic creation, but in the sense of imagination, intuition, and care. You could follow all the rules, and still not be able to make the team work. I started this part of the framework, LAN, with the statement that a team is more than a group of people working together, and, in this section, I am going to give you some directives that will help you with that matter, but only your real intent and gut feelings will make it a successful endeavor.

The first crucial aspect to understand is what rules apply to any team. This is very well detailed in the book "The Five Dysfunctions of a Team"[^1], which presents in the form of a story, how a new manager makes a group become a team.

Let's start with the most foundational framework for this: the five dysfunctions.

# The five dysfunctions

From bottom to top, the dysfunctions are: absence of trust, fear of conflict, lack of commitment, avoidance of accountability, and inattention to results. As Lencioni points, high performance comes from systematically removing these, starting at the base rather than jumping straight to “results” or “ownership.”

I commented several times that manners matter, and individual results never benefit team or company goals. Your feeling of belonging is essential to the team success, and you, as the team manager should be the first and most enthusiastic evangelizer.

## Absence of trust

This is about vulnerability-based trust: people are unwilling to admit mistakes, weaknesses, or ask for help, so they protect themselves instead of the team. Without that vulnerability, you get guarded conversations, politics, and low-quality collaboration, because people never really put their cards on the table.

I've seen many teams that don't get there because most of the members are scared to admit they don't know. That leads unavoidably to misinterpretations, non-expected results, and lost time. Your team members should feel comfortable asking for clarifications, or information without having the fear of losing trust or credibility just because they are not experts in everything, **nobody is expert in everything** and that is OK.

> **A simple example**:
>
> A senior engineer never admits when they’re stuck, silently burns evenings, and then quietly slips deadlines; no one else can help because the struggle is hidden.
>
{: .block-tip }

## Fear of conflict

When trust is low, people avoid honest, passionate debate and keep a surface-level “nice” atmosphere, this is what Lencioni calls **artificial harmony**. This avoidance means hard issues never get properly discussed; decisions are watered down, resentment builds, and the real conflicts move into side conversations and back channels. No one should fear conflict if the basic rules of conduct are clear. As the team leader, you should ensure that these rules are explicit, clear, and known by everyone. It is also your responsibility to act as an arbiter and guarantor of their compliance at all times.

As the saying goes, good contracts lead to good business; healthy discussion can only lead to better understanding and a stronger commitment after the necessary clarifications and agreements are reached. Therefore, you should encourage discussions within the team.

> **A simple example**:
>
> In planning meetings, everyone nods at a risky roadmap, then later complains 1:1, or “fixes” it in Slack threads, but never in the room where it matters.
>
{: .block-tip }

## Lack of commitment

If you don’t have real conflict, people don’t fully buy into decisions; they may agree publicly but remain unconvinced, creating ambiguity about direction and priorities. Lencioni distinguishes commitment from consensus: teams don’t need unanimous agreement, but they do need clarity and people willing to support a decision once it’s made.

A technique that always worked for me is the acceptance by disagree and commit. If you are not happy with the proposal, but you don't have another, sustainable and arguable, alternative, you should accept by disagree and commit. That does not mean that you are happy with it, but you recognize that you don't have a better solution, and you don't want to get stuck.

> **A simple example**:
>
> A team “agrees” on a release date, but half of them still think it’s unrealistic; later, they treat slippage as inevitable instead of something they own and defend.
>
{: .block-tip }

## Avoidance of accountability

When commitment is weak, it becomes socially unsafe to call out peers’ behavior or performance, so standards drift and underperformance becomes normalized. Lencioni emphasizes peer accountability: in strong teams, colleagues challenge each other against clear commitments and shared standards, instead of leaving everything to the boss. Freedom and accountability go hand in hand. If you expect autonomy to make decisions, you must also own the outcomes. The same applies to everyone on your team — don't hold people accountable for decisions they had no part in.

Once this is clear, you should expect the team to request this commitment from everyone in the team.

> **A simple example**:
>
> People arrive late to stand-ups or skip code reviews, and no one says anything; eventually “we’re not serious about our own rules” becomes the real norm.
>
{: .block-tip }

## Inattention to results

At the top of the pyramid, individuals focus on personal status, departmental wins, or career safety instead of the collective results of the team. When this happens, you see turf wars, vanity metrics, or “my function did its part” thinking, even if the overall business outcome is failing.

I've emphasized this concept repeatedly because I believe it's key to build a team. Here, Lencioni reiterates that individual victory, as opposed to team victory, is ineffective. This doesn't mean individual victory is inherently bad; it means it should never come at the expense of the team's success. For this to happen, the most important thing is for the team to internalize this concept. There's a saying that sums it up perfectly:

>
> "If you want to go fast, go alone. If you want to go far, go together."
{: .block-tip }

> **A simple example**:
>
> Product celebrates shipping a big feature on time while Sales quietly misses revenue targets and Support is drowning in tickets; each silo optimizes its own scoreboard.
>
{: .block-tip }

## Key takeaways for leaders

>
> * **Start with trust**: create safety for vulnerability (admitting errors, asking for help) or everything else becomes theater.
>
> * **Normalize constructive conflict**: explicitly invite challenge and debate before deciding.
>
> * **Make decisions clear and visible**: who decided what, by when, and how it’ll be communicated, so commitment is unambiguous.
>
> * **Push peer accountability**: encourage team members to hold each other to shared standards, not just upward accountability to the manager.
>
> * **Keep a shared scoreboard**: define and track collective results so everyone orients to the same outcomes
>
{: .block-tip }

Now that we know what can break a team from within, let's look at what can break it from the outside: structure.

# Team Topologies & Structure

You now understand what can break a team from the inside. But even a psychologically healthy team can fail if it is structured incorrectly. Structure is not bureaucracy — it is clarity. It defines who does what, how teams interact, and where the cognitive load falls.

The most practical framework for this is Team Topologies, by Matthew Skelton and Manuel Pais[^2]. It gives you a language to design your organization around the work, not the other way around.

## The four team types

Stream-aligned teams are the core. They are cross-functional, end-to-end responsible for a specific flow of work: a product, a user journey, or a business capability. If you only build one kind of team well, make it this one.

Platform teams exist to reduce the cognitive load of stream-aligned teams. They build and maintain internal tools, infrastructure, and shared capabilities so that other teams don't have to reinvent the wheel. A platform team's success metric is the speed and autonomy it gives to others.

Enabling teams are temporary by design. They go into a stream-aligned team, help them build a new capability or adopt a new practice, and then step back. Think of them as internal consultants — they should make themselves unnecessary.

Complicated-subsystem teams handle areas that require deep, specialized expertise — a cryptography module, a real-time engine, or a recommendation algorithm. Only create one of these when the complexity genuinely demands it. Don't use it as an excuse to silo specialists.

## The three interaction modes

How teams work together matters as much as how they are structured. Skelton and Pais define three modes:

Collaboration — Two teams work closely together for a defined period to explore or solve something complex. It is high-bandwidth and expensive; use it sparingly and with a clear end date.

X-as-a-Service — One team consumes what another provides, with minimal back-and-forth. Clear APIs, clear contracts. This is the default interaction for a mature platform team.

Facilitation — An enabling team coaches another without taking over. They are present, but the stream-aligned team does the work.

Misusing these modes is one of the most common structural mistakes. A platform team forced into constant collaboration loses its leverage. An enabling team that never steps back creates dependency.

> **Conway's Law — the hidden constraint**
>
> "Any organization that designs a system will produce a design whose structure is a copy of the organization's communication structure."
>
> --**Melvin Conway**
{: .block-tip }

This is not a metaphor. It is a law. Your software architecture will reflect your team structure whether you plan it or not. If your teams are siloed, your system will be too. If ownership is blurry, your codebase will show it.

The practical implication: design your teams around the architecture you want, not the one you have. This is called the Inverse Conway Maneuver — deliberately shaping your org to nudge the system toward the target design.

## What this means for you as a leader

Before adding headcount, ask: what team type do we actually need?

Protect your stream-aligned teams from being pulled into platform work, and vice versa.

Regularly review your interaction modes — collaboration that was necessary six months ago may now be creating unhealthy dependency.

If your best engineers are buried in a complicated-subsystem team that nobody talks to, you have a structure problem, not a people problem.

## Key takeaways for leaders

>
> * Structure your teams around the work, not the org chart history
>
> * Default to stream-aligned; add other types only when there is a clear need
>
> * Define interaction modes explicitly — ambiguity here costs time and trust
>
> * Let Conway's Law work for you by designing teams around your target architecture
>
> * Review structure regularly; what works at 5 engineers breaks at 20
>
{: .block-tip }

# 1-on-1s & Feedback Loops

## How to Run Effective 1-on-1s

Structure beats spontaneity. Becoming predictable is the best way to ensure that the meeting will be happening in a distressed environment, and all the topics will be covered. Prepare a template you can use to keep track of previous meetings while listing what both want to talk about.

Regular 1-on-1s are your single best tool to catch small problems before they become dysfunctions. It is always the best approach to raise the problems before they become unmanageable, and the day-to-day activity occupies most of our time, and talking about our concerns seems never to be a priority, this is the forum to concentrate in these aspects of your professional life.

Weekly or bi-weekly is ideal—consistency builds psychological safety and prevents the meeting from becoming a status update. As repeatedly commented before, 1-on-1s should never be a status check, there are other tools for that. 1-on-1s are the moment you take to openly speak about past, present, and future in a more global way. It is the perfect tool to connect with your people.

### Agenda Framework

A strong 1-on-1 balances employee priorities with manager support. Create a shared agenda where both of you contribute topics before the meeting. Here's a proven structure:

* **Personal check-in (5-10 min)**: Build trust with genuine conversation beyond work. How are they really doing?
* **Progress & blockers (10 min)**: Review current work—but focus on removing obstacles, not micromanaging details
* **Feedback exchange (10 min)**: Two-way street. Give specific feedback and invite theirs on your leadership
* **Career development (5-10 min)**: Long-term goals, skill gaps, learning opportunities. This separates great managers from task managers
* **Open topics (5-10 min)**: Their space to raise anything. Listen 80% of the time

### What NOT to Make It

* Don't turn 1-on-1s into project status meetings—that's what stand-ups are for.
* Don't cancel them when things get busy; that signals your team isn't the priority.
* Don't dominate the conversation; if you're talking more than 20%, you're doing it wrong.

Document action items at the end of every session and review them next time—accountability flows both ways. Always remember that this will also be a great tool for both parties to go through the year, and keep a good log on the progress of the job done.

### Choosing Your Feedback Model

#### Radical Candor

Kim Scott's[^3] framework balances two dimensions: Care Personally and Challenge Directly. The goal is the upper-right quadrant—radical candor—where you're both kind and brutally clear.

> ⚠️ The traps:
>
> **Ruinous empathy**: You care but won't give hard feedback. It feels safe short-term but hurts people long-term
>
> **Obnoxious aggression**: Direct but cold. Gets results temporarily, destroys trust permanently
>
> **Manipulative insincerity**: Neither caring nor direct. Pure politics
>
{: .block-warning }

**To practice it**:

* Build the relationship first, then be extremely specific with critical feedback
  * Always start with a gentle conversation, entering directly to the point will put the other part in defensive mode. You can even introduce what you are going to talk about in the most neutral way possible to prepare for what is about to come.
* Don't sugarcoat, but don't get personal.
  * People, in general, don't expect paternity on feedbacks, so don't try to downplay it, you are there because there is something that needs attention, but at the same time, keep it as professional as possible not entering in personal evaluations, you are not talking about personal view, you are talking about work. As the sentence states "It's not personal, it's business".
* Say "In yesterday's demo, the second half felt rushed, and key features weren't explained," not "You're bad at demos."
  * Always point to specifics, never to general. Bring examples and suggestions to correct the problem.

#### SBI Model (Situation-Behavior-Impact)

If Radical Candor is the philosophy, SBI is the tactical script. It's a three-step formula that keeps feedback factual and reduces defensiveness:

* **Situation**: Set the context—when and where specifically. "This morning at the 11 a.m. team meeting…"
* **Behavior**: Describe observable actions, no interpretation. "You interrupted Sarah twice while she was presenting the design."
* **Impact**: Explain the consequence on you, the team, or the work. "It made her hesitant to finish her point, and we didn't get full clarity on the timeline."
* Add the "I" for inquiry: After delivering SBI, ask about their intent. "What was going through your mind at that moment?" This turns feedback into dialogue and reveals assumptions you might have wrong.

### 1-on-1 Template

You can use the example template I prepared for you as a starting point. Review it, tune it to fit your needs, and send me any suggestion for improvement.

* Markdown [1-on-1 Template](/assets/documents/one-on-one-template.md 'Markdown Document'){:target="_blank"}
* DocX [1-on-1 Template](/assets/documents/one-on-one-template.docx 'DocX Document'){:target="_blank"}
* PDF [1-on-1 Template](/assets/documents/one-on-one-template.pdf 'PDF Document'){:target="_blank"}

# Hiring & Onboarding

Skills can be taught. Values can't. The balance between hiring for technical competence and cultural alignment shapes your team's long-term performance. Hire purely for skills, and you risk someone who clashes with your team dynamics; hire purely for fit, and you might lack the technical depth to execute.

## The Two-Step Evaluation

Use a structured approach that separates but balances both dimensions:

* **Step 1 - Technical assessment**: Skills tests, coding challenges, or architecture discussions to measure hard and soft skills. Don't lower the bar here—gaps in foundational skills compound over time.
* **Step 2 - Behavioral interviews**: Situational questions that reveal values alignment, collaboration style, and how someone responds to conflict or ambiguity. Ask "Tell me about a time when you disagreed with your team's direction and how you handled it," not "Do you work well with others?"

## Belbin Roles in Hiring

The existing People section already introduces Belbin, now let's apply it tactically. Before opening a role, ask: what team role gap are we filling? This innocent question has more importance than you might think. The final goal of the team is to fulfill all needs, not just to add more workforce, remember the quote by Warren Buffet, "_You can't produce a baby in one month by getting nine women pregnant_", same happens here, team work won't improve just by adding more people, but the right people in the right place.

If your team is heavy on Plants (creative thinkers) but lacks a Completer Finisher, hiring another visionary will amplify chaos, not productivity. Use Belbin profiles during interviews to understand not just what someone can do, but how they naturally work and where they'll add diversity to your team's cognitive balance.

Warning: "Culture fit" is not "hire people like us". Focus on values alignment and culture add—bring people who share core principles but challenge groupthink and enrich perspective.

## Common Hiring Anti-Patterns

As with any other aspect, hiring has some aspects that can be considered antipatterns, practices you need to avoid in order to succeed.

* **Overvaluing pedigree**: A senior title elsewhere doesn't mean they fit your team's stage or structure
* **Interview theater**: Six-hour onsite loops that test endurance, not ability
* **Skill tunnel vision**: Ignoring red flags in collaboration or communication because the candidate "crushed the coding test"
* **Homogeneous teams**: Prioritizing comfort over complementary strengths, which breeds blind spots

In summary, we should pay attention to what we see, what we need, and don't pretend to be what we are not.

## The First 90 Days Onboarding Framework

A structured onboarding plan is your highest-leverage retention tool. Break it into three phases: orientation, contribution, and independence. Let's see a more specific onboarding plan.

### Days 1-30: Orientation

**Goal**: Understand the team, codebase, product, and development workflow.

Technical setup (complete 48 hours before start):

* GitHub/GitLab access tested, can clone main repo
* Slack channels configured, Jira/Linear visible, CI/CD pipeline accessible
* Cloud provider permissions, Confluence/Notion wiki access

#### Day 1 actions

**30-minute manager welcome**: role expectations, success metrics at 30/60/90 days.

**Team intro call**: names, roles, communication norms

* **Architecture walkthrough** (45-60 min, recorded): high-level system tour, key dependencies
* **Early wins**: Assign a starter ticket—small, well-scoped task (bug fix, documentation improvement) that requires navigating the codebase and deployment process. First PR submitted by end of week 1, even if small. The goal is psychological momentum, not heroics.
* **Buddy system**: Assign a peer (not the manager) as the first point of contact for "too basic" questions. This is the single practice most strongly associated with onboarding success. Define the buddy's responsibilities clearly: daily check-ins first week, pairing sessions, social integration support.

#### Social integration

1:1s with every team member in first two weeks. We often forget that new environment, new context, and new people are big changes and challenges for people, and an important part of the onboarding is to get this new joiners comfortable with it as soon as possible.

Virtual coffee chats with 3-4 people they wouldn't naturally interact with (schedule these; they won't happen organically remote). I've tried many approaches like the '_Slack Virtual Coffee_' that schedules 30 minutes informal meetings early in the morning between random people in the team, or the '_Get to Know Each Other Sessions_' that ensures that everyone in the team had at least one face to face session in the cafeteria or any social space with the new joiners in their first month as part of the job dutties.

There are many techniques that work, you choose the one that best suits your needs, but be sure you have one.

This actions will open the space to get better feedback from the team and for the new joiners in the subsequent 1-on-1 sessions.

### Days 31-60: Contribution

**Goal**: Take on increasingly complex tasks with decreasing support.

* Ship at least one meaningful feature or fix per week to production
* Participate in code review as both author and reviewer—reviewing others' PRs is one of the fastest ways to build codebase familiarity
* Attend all sprint ceremonies with the expectation of contributing opinions, not just listening
* Weekly 1:1 with manager structured around: what went well, what's blocking you, what do you need from me. This weekly cadence is the strongest predictor of remote onboarding success

This is an example that you should adjust to the role and level of the new joiner, but you get the essence of the action.

### Days 61-90: Independence

**Goal**: Operate as a self-sufficient team member who can identify, scope, and complete work with minimal guidance.

Success checkpoints:

* Can the person navigate the codebase independently without asking?
* Have they shipped at least two meaningful contributions to production?
* Do they know who to ask for what across the team?
* Have they identified at least one thing that could be improved (process, documentation, code)?
* Shift cadence: Move 1:1s from weekly to bi-weekly as confidence and trust grow.

If any of these checkpoints are not met, this is a great time to start addressing the issues. Get good information about what is happening and what is preventing the new joiner from succeeding in that aspect. Don't lose this opportunity as a checkpoint of the status, you are in the last part of the onboarding and having a checkpoint at the beginning could save from a bad situation at the end of the 90 days.

## ⚠️ What NOT to Do

* Don't leave onboarding to chance or "just shadow someone"
* Don't overload week 1 with HR paperwork and compliance videos before any real context
* Don't assign make-work tasks—early wins must be genuinely useful, or credibility suffers
* Don't skip social integration for remote hires; relationships drive retention and collaboration
* Don't wait for the new hire to ask for help; structure daily async check-ins during month 1

**Gather feedback**: Ask the new hire during and after onboarding what worked and what didn't, then iterate your process. This information is pure gold to refine your onboarding process, improve it, and try to not repeat the same errors once and again.

# Team Health Checks

Most teams only get a real “health signal” when something already hurts: burnout, missed deadlines, conflict, or people leaving. A team health check is a simple, recurring way to see those signals early, when a small adjustment can still fix them. Health checks are the early-warning system for the five dysfunctions and for structural issues described in Team Topologies. Think of it as a regular “team retro, but zoomed out”: not just “how was this sprint?” but “how are we doing as a team in general?” Done well, it becomes a shared language to talk about trust, collaboration, focus, and results without turning it into blame.

The ideal cadence for stable teams is to run a health check every 1–3 months per team, and after major change events (reorg, big incident, new manager), this will give you a traceable and improved version with time. For new or stressed teams, the attention should be higher, so a monthly check can help you mitigate unwanted situations. In the case of ad-hoc or project teams, at kickoff and mid-point are good timings for a health check.

When you are if front of a very fragile team, an anonymous pre-check (e.g., quick anonymous form, then discuss aggregated results), can be a starting point, but bear in mind that the goal is to move toward open conversation, hiding the problems never fix them.

> Best for: cross‑functional product/engineering teams of 4–10 people, with at least 2–3 months working together. Not ideal for: brand‑new teams, crisis situations, or performance management.
{: .block-tip }

## Goal & Success Criteria

Success = we end with 1–3 concrete experiments, owners, and check-in dates, not a perfect score.

## Spotify Squad Health Check (Adapted)

The Spotify Squad Health Check is one of the most popular models to do this in a light, visual way. The original idea is simple:

1. Pick around 10 themes.
2. For each theme, everyone rates how they feel using a traffic light:
    * 🟢 Green – “We’re happy here, no big need for change.”
    * 🟡 Yellow – “Meh, could be better.”
    * 🔴 Red – “Not good, we need to improve this.”
3. Discuss the results together and agree on a few concrete actions.

As an example a default pack of themes can be:

1. Delivering value
2. Code Review Quality
3. Tech quality
4. Technical Debt
5. Fun
6. Teamwork
7. Career Progression
8. Transparency
9. Training received
10. Future

> If ‘Technical health’ is mostly red, a typical first experiment is: ‘We will add a 30-minute weekly refactoring slot for the next 4 weeks and track what we improve.’
{: .block-tip }

Spotify stresses a few key principles:

* It’s about improvement, not judgement. If people fear being evaluated, the data becomes useless.
* Keep it fun and face‑to‑face, not just an anonymous form. The conversation is the real value.
* Teams can adapt the questions so they feel relevant. Team acceptance matters more than strict consistency.
* Avoid comparing teams or creating incentives to “look good”. If one team is more “red”, they might just be more honest.

> Sample Health Dimensions:
>
> You can propose 8–10 lenses that align with your framework (Lencioni + Team Topologies + leadership):
>
> * **Trust & psychological safety** – People feel safe admitting mistakes and asking for help.
>
> * **Healthy conflict** – We can disagree openly without drama.
>
> * **Clarity & commitment** – We know the priorities and genuinely support the decisions.
>
> * **Peer accountability** – We hold each other to our standards, not just the manager.
>
> * **Focus on results** – We care more about team outcomes than individual heroics.
>
> * **Flow & delivery** – Work moves through the system with reasonable speed and predictability. ex. “Lead time, WIP, or % of work unplanned in the sprint.”
>
> * **Technical health** – Code quality, automation, and technical debt feel under control. ex. “Build failure rate, deployment frequency, or error budget.”
>
> * **Team structure** – Responsibilities and interactions with other teams are clear.
>
> For each one, you can use a one-line description and the 🟢🟡🔴 voting.
>
{: .block-tip }

## Adapting Lencioni into a Checklist

We already explained the five dysfunctions. Now, let's translate them into a simple checklist you can run as a quick diagnostic.

Below is a quick self-assessment based on Lencioni. Take 5–10 minutes with your team. For each statement, everyone scores from 1 (strongly disagree) to 5 (strongly agree). Then talk about the biggest gaps.

As a rule of thumb, if a dysfunction averages below 3, treat it as a focus area for the next quarter.

### 1. Absence of Trust (Vulnerability)

* People openly admit when they don’t know something.
* We can say “I made a mistake” without fear of being attacked.
* Asking for help is seen as a strength, not a weakness.
{: .check-list }

If the average is low, you explain: “Start here. Without vulnerability-based trust, everything else is theater.”

### 2. Fear of Conflict

* We can disagree in meetings without it turning personal.
* Important topics get discussed in the room, not in side chats later.
* People feel safe to challenge ideas from seniors or managers.
{: .check-list }

If a given area scores low, revisit the corresponding subsection above for deeper context and practices in the Five Dysfunctions.

Low scores → you suggest: “Define clear rules for respectful debate and actively invite challenge.” f.e. "For the next 4 weeks, we’ll reserve 10 minutes per planning session for ‘devil’s advocate’: someone’s job is to challenge the current plan."

### 3. Lack of Commitment

* At the end of discussions, decisions are clearly stated and written down.
* Even when people disagree, they still support the final decision.
* Priorities are clear; there is little confusion about what matters now.
{: .check-list }

Low scores → encourage “disagree and commit” and visible decision logs.

### 4. Avoidance of Accountability

* Team members call out missed commitments or broken agreements.
* We talk about performance and behavior issues early, not months later.
* Standards (quality, communication, ways of working) are explicit and shared.
{: .check-list }

Low scores → push peer accountability, not just top‑down.

### 5. Inattention to Results

* The team has a small set of shared outcome metrics everyone cares about.
* People celebrate team wins more than individual wins.
* Decisions are driven by what’s best for the overall team or product, not for one function.
{: .check-list }

Low scores → revisit your shared scoreboard and incentives.

### ⚠️ What NOT to Do

* Don’t use this to rank teams
* Don’t use this as performance evaluation
* Don’t overstuff the session
* Don’t try to ‘solution’ everything in one go

### 🛟 For busy Managers (light version)

#### When to use it

Use this quick checklist to sense how your team is doing on the five dysfunctions, without a long workshop.

#### How it works

Everyone answers 10 statements from 1–5 (1 = strongly disagree, 5 = strongly agree). Then you look for low scores and pick one area to improve.

#### Step 1 – Explain the purpose (2 minutes)

You can say:

> “This is not a test, and it’s not about judging people. It’s a quick way to see where our teamwork feels strong or weak, so we can agree on one small improvement.”

#### Step 2 – Answer the 10 statements (5–7 minutes)

Ask everyone to score each statement 1–5.

1. **Trust**
    * People in this team can say “I don’t know” or “I made a mistake” without fear.
    * It feels normal to ask for help when we’re stuck.

2. **Conflict**
    * We can disagree openly in meetings without it becoming personal.
    * Important concerns are raised in the room, not just in side chats later.

3. **Commitment**
    * At the end of discussions, decisions are clear and written down somewhere visible.
    * Even if we don’t fully agree, we support the final decision once it’s made.

4. **Accountability**
    * We respectfully call out missed commitments or broken agreements in the team.
    * Our expectations (quality, communication, ways of working) are explicit and shared.

5. **Results**
    * We care more about shared team outcomes than individual heroics or credit.
    * We have a small set of team metrics or goals that everyone actually pays attention to.

#### Step 3 – Look at patterns (8–10 minutes)

Quickly average each statement or just spot where many people scored 1–3.

Identify one dysfunction to focus on (trust, conflict, commitment, accountability, results).

Ask: “Which of these low statements, if improved, would help us the most right now?”

#### Step 4 – Pick one concrete move (8–10 minutes)

Based on the chosen area, define a small, specific change for the next 2–4 weeks.

>
> Example (Trust): “For the next month, we’ll start retros with one small ‘I messed up and what I learned’ story from anyone who feels comfortable.”
>
> Example (Commitment): “We will end every planning meeting by writing down decisions and owners in a single shared document.”
>

Assign an owner and a date to revisit the statement scores.

#### Step 5 – Close (2 minutes)

Close with:

“_Thanks for the honesty. We’re not trying to fix everything at once. Let’s try this one change and see if our scores improve next time._”

## How to Run a Team Health Session (Step-by-Step)

> **Role of the facilitator**
> Ideally it’s the team’s manager, but in low-trust environments it might be better to have a neutral facilitator.
{: .block-tip }

> **Initial Clarifications**
> We’re not here to grade people; we’re here to find one or two things we can improve as a team over the next month.
{: .block-tip }

1. Prepare (20 minutes)
    * Choose 8–10 health dimensions (Spotify-style + your Lencioni checklist).
    * Book 60–90 minutes with the team, in a safe, closed space.
2. Individual scoring (10–15 minutes)
    * Each person scores the Lencioni statements (1–5).
    * For each health dimension, they pick 🟢 / 🟡 / 🔴.
3. Visualize (10 minutes)
    * On a whiteboard or Miro, list the dimensions and mark the colors (e.g. one dot per person).
    * For the Lencioni checklist, average the scores per dysfunction and note them at the side.
4. Discuss extremes (20–30 minutes)
    * Start with the most “red” or “mixed” areas: “What’s behind this?” “Can you share a recent example?”
    * Stay curious, avoid blame, capture patterns and concrete stories.
5. Agree on 1–3 actions (10–15 minutes)
    * For each focus area, define one small experiment for the next 2–4 weeks (e.g. “We will write decisions at the end of each meeting”).
    * Assign an owner and a check-in date.
6. Repeat
    * Do a light version every 1–3 months and track trends, not perfection.

> Keep photos or snapshots of each session’s board; over time, patterns matter more than absolute colors.
>
> Thank everybody for the honesty; we’re not fixing everything today. Let’s focus on these 1–2 experiments and check back in our next health check.
>
> This step by step guide is presented for a first full session takes 60–90 minutes, but follow-ups can be 30–45 minutes using the same board.
{: .block-tip }

If you want to run this with your team, I’ve created a three-page Team Health Check Toolkit (PDF + editable template). You can download it here or contact me if you’d like me to facilitate the first session with your team. This template is fully aligned with the Five Dysfunctions and Team Topologies methodologies we explained before.

* Markdown [Team Health Check Template](/assets/documents/team-health-check-template.md 'Markdown Document'){:target="_blank"}
* DocX [Team Health Check Template](/assets/documents/team-health-check-template.docx 'DocX Document'){:target="_blank"}
* PDF [Team Health Check Template](/assets/documents/team-health-check-template.pdf 'PDF Document'){:target="_blank"}

### 🛟 For busy Managers (light version)

If you are in a complicated situation, but still want to run a health check, you can use this "_light version_" of the check-list.

Here’s a “light version” you can paste as a sidebar/box: a 30‑minute, 5‑dimension health check designed for a single squad in a busy week. [127.0.0](http://127.0.0.1:4000/framework/2026-05-28-team-management/)

### 30-Minute Team Health Check (Light Version)

**When to use it**  
Use this when you only have 30 minutes but want a quick “how are we doing as a team?” signal without a full workshop.

**Goal**  
Get a shared picture of team health and choose 1 small experiment for the next 2–4 weeks.

#### Step 1 – Explain the intent (3 minutes)

You can say:

> “This is a quick team health check. It’s not a performance review, it’s a way for us to see where things feel good or off, and pick one small improvement to try together. Honesty matters more than looking good.” [127.0.0](http://127.0.0.1:4000/framework/2026-05-28-team-management/)

#### Step 2 – Rate 5 dimensions (7 minutes)

Ask everyone to rate these 5 dimensions using 🟢 🟡 🔴 (green / yellow / red), either on a board or shared doc.

* **Trust & safety** – People feel safe admitting mistakes and asking for help.
* **Healthy conflict** – We can disagree openly without drama.
* **Clarity & commitment** – We know priorities and genuinely support decisions.
* **Flow & delivery** – Work moves with reasonable speed and predictability.
* **Technical health** – Code quality, automation, and debt feel under control.

Everyone picks a color per dimension, no discussion yet.

#### Step 3 – Look for the “reds” and “mixes” (10 minutes)

As a group, look at the board:

* Start with any dimension that has reds or a mix of colors.
* Ask: “What’s one recent example that made you choose this color?”
* Capture short notes, not long stories.

Keep the tone curious, not blaming.

#### Step 4 – Pick one experiment (7 minutes)

From what you heard, choose **one** focus area for the next 2–4 weeks.

* Define a concrete experiment, e.g.:  
  * “We will write down decisions at the end of each meeting.”  
  * “We will add a 15‑minute weekly slot to tackle small tech debt items.”
* Assign an owner and a date when you’ll check if it helped.

Write it down where the team will see it (board, doc, Slack).

#### Step 5 – Close the loop (3 minutes)

End with something like:

> “Thank you for the honesty. We’re not trying to fix everything at once. Let’s try this one experiment, see if it helps, and we’ll do another light check in a month.”

### Mapping between Lencioni and Spotify Health Checks

| Health lens                  | Related dysfunction(s)      |
| ---------------------------- | --------------------------- |
| Trust & psychological safety | Absence of trust            |
| Healthy conflict             | Fear of conflict            |
| Clarity & commitment         | Lack of commitmen           |
| Peer accountability          | Avoidance of accountability |
| Focus on results             | Inattention to results      |

### What to do after the session

#### Communicate results to stakeholders without exposing individuals

Always keep in mind that this is a team exercise, and you are not looking for guilty individuals. As reiterated, the team is a unity that needs to work beside the individuals, and it is your duties to identify the causes and apply the solutions. So be sure to present it as a whole and don't point to specific behaviors or individuals.

#### Avoid “we did it once and forgot”

It is not uncommon to find this situation, once is done, we add a checkmark and forget it, it is done, right? No, this should be a living exercise, specially if results are not optimal. Add a 5‑minute “check last experiment” slot to the next retro to keep track and evolution, so you can ensure the progress is in the right direction and not back to the previous.

#### When to escalate

Obviously not always you can fix it. Give it some time and if there are indicators that don't progress (e.g., persistent red on “trust” for 2–3 sessions), it's time to escalate the situation and propose more serious actions.

[^1]: [The Five Dysfunctions of a Team](/others/bibliography/)
[^2]: [Team Topologies](/others/bibliography/)
[^3]: [Radical Candor](/others/bibliography/)
