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

- **Personal check-in (5-10 min)**: Build trust with genuine conversation beyond work. How are they really doing?
- **Progress & blockers (10 min)**: Review current work—but focus on removing obstacles, not micromanaging details
- **Feedback exchange (10 min)**: Two-way street. Give specific feedback and invite theirs on your leadership
- **Career development (5-10 min)**: Long-term goals, skill gaps, learning opportunities. This separates great managers from task managers
- **Open topics (5-10 min)**: Their space to raise anything. Listen 80% of the time

### What NOT to Make It

- Don't turn 1-on-1s into project status meetings—that's what stand-ups are for. 
- Don't cancel them when things get busy; that signals your team isn't the priority. 
- Don't dominate the conversation; if you're talking more than 20%, you're doing it wrong.

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

- Build the relationship first, then be extremely specific with critical feedback
    * Always start with a gentle conversation, entering directly to the point will put the other part in defensive mode. You can even introduce what you are going to talk about in the most neutral way possible to prepare for what is about to come.
- Don't sugarcoat, but don't get personal.
    * People, in general, don't expect paternity on feedbacks, so don't try to downplay it, you are there because there is something that needs attention, but at the same time, keep it as professional as possible not entering in personal evaluations, you are not talking about personal view, you are talking about work. As the sentence states "It's not personal, it's business".
- Say "In yesterday's demo, the second half felt rushed, and key features weren't explained," not "You're bad at demos."
    * Always point to specifics, never to general. Bring examples and suggestions to correct the problem.

#### SBI Model (Situation-Behavior-Impact)

If Radical Candor is the philosophy, SBI is the tactical script. It's a three-step formula that keeps feedback factual and reduces defensiveness:

- **Situation**: Set the context—when and where specifically. "This morning at the 11 a.m. team meeting…"
- **Behavior**: Describe observable actions, no interpretation. "You interrupted Sarah twice while she was presenting the design."
- **Impact**: Explain the consequence on you, the team, or the work. "It made her hesitant to finish her point, and we didn't get full clarity on the timeline."
- Add the "I" for inquiry: After delivering SBI, ask about their intent. "What was going through your mind at that moment?" This turns feedback into dialogue and reveals assumptions you might have wrong.

### 1-on-1 Template

You can use the example template I prepared for you as a starting point. Review it, tune it to fit your needs, and send me any suggestion for improvement.

* Markdown [1-on-1 Template](/assets/documents/one-on-one-template.md 'Markdown Document'){:target="_blank"}
* DocX [1-on-1 Template](/assets/documents/one-on-one-template.docx 'DocX Document'){:target="_blank"}
* PDF [1-on-1 Template](/assets/documents/one-on-one-template.pdf 'PDF Document'){:target="_blank"}

# Hiring & Onboarding

Skills can be taught. Values can't. The balance between hiring for technical competence and cultural alignment shapes your team's long-term performance. Hire purely for skills, and you risk someone who clashes with your team dynamics; hire purely for fit, and you might lack the technical depth to execute.

## The Two-Step Evaluation

Use a structured approach that separates but balances both dimensions:

- **Step 1 - Technical assessment**: Skills tests, coding challenges, or architecture discussions to measure hard and soft skills. Don't lower the bar here—gaps in foundational skills compound over time.
- **Step 2 - Behavioral interviews**: Situational questions that reveal values alignment, collaboration style, and how someone responds to conflict or ambiguity. Ask "Tell me about a time when you disagreed with your team's direction and how you handled it," not "Do you work well with others?"

## Belbin Roles in Hiring

Your existing People section already introduces Belbin—now apply it tactically. Before opening a role, ask: what team role gap are we filling?

If your team is heavy on Plants (creative thinkers) but lacks a Completer Finisher, hiring another visionary will amplify chaos, not productivity. Use Belbin profiles during interviews to understand not just what someone can do, but how they naturally work and where they'll add diversity to your team's cognitive balance.

Warning: "Culture fit" is not "hire people like us". Focus on values alignment and culture add—bring people who share core principles but challenge groupthink and enrich perspective.

## Common Hiring Anti-Patterns

- **Overvaluing pedigree**: A senior title elsewhere doesn't mean they fit your team's stage or structure
- **Interview theater**: Six-hour onsite loops that test endurance, not ability
- **Skill tunnel vision**: Ignoring red flags in collaboration or communication because the candidate "crushed the coding test"
- **Homogeneous teams**: Prioritizing comfort over complementary strengths, which breeds blind spots

## The First 90 Days Onboarding Framework

A structured onboarding plan is your highest-leverage retention tool. Break it into three phases: orientation, contribution, and independence.

### Days 1-30: Orientation

Goal: Understand the team, codebase, product, and development workflow.

Technical setup (complete 48 hours before start):

- GitHub/GitLab access tested, can clone main repo
- Slack channels configured, Jira/Linear visible, CI/CD pipeline accessible
- Cloud provider permissions, Confluence/Notion wiki access

#### Day 1 actions:

30-minute manager welcome: role expectations, success metrics at 30/60/90 days

Team intro call: names, roles, communication norms

- Architecture walkthrough (45-60 min, recorded): high-level system tour, key dependencies
- Early wins: Assign a starter ticket—small, well-scoped task (bug fix, documentation improvement) that requires navigating the codebase and deployment process. First PR submitted by end of week 1, even if small. The goal is psychological momentum, not heroics.
- Buddy system: Assign a peer (not the manager) as the first point of contact for "too basic" questions. This is the single practice most strongly associated with onboarding success. Define the buddy's responsibilities clearly: daily check-ins first week, pairing sessions, social integration support.

#### Social integration:

1:1s with every team member in first two weeks

Virtual coffee chats with 3-4 people they wouldn't naturally interact with (schedule these; they won't happen organically remote)

### Days 31-60: Contribution

Goal: Take on increasingly complex tasks with decreasing support.

- Ship at least one meaningful feature or fix per week to production
- Participate in code review as both author and reviewer—reviewing others' PRs is one of the fastest ways to build codebase familiarity
- Attend all sprint ceremonies with the expectation of contributing opinions, not just listening
- Weekly 1:1 with manager structured around: what went well, what's blocking you, what do you need from me. This weekly cadence is the strongest predictor of remote onboarding success

### Days 61-90: Independence

Goal: Operate as a self-sufficient team member who can identify, scope, and complete work with minimal guidance.

Success checkpoints:

- Can the person navigate the codebase independently without asking?
- Have they shipped at least two meaningful contributions to production?
- Do they know who to ask for what across the team?
- Have they identified at least one thing that could be improved (process, documentation, code)?
- Shift cadence: Move 1:1s from weekly to bi-weekly as confidence and trust grow.

## ⚠️ What NOT to Do

- Don't leave onboarding to chance or "just shadow someone"
- Don't overload week 1 with HR paperwork and compliance videos before any real context
- Don't assign make-work tasks—early wins must be genuinely useful, or credibility suffers
- Don't skip social integration for remote hires; relationships drive retention and collaboration
- Don't wait for the new hire to ask for help; structure daily async check-ins during month 1

**Gather feedback**: Ask the new hire during and after onboarding what worked and what didn't, then iterate your process

<!-- # Team Health Checks

A practical, template-driven section that could double as a lead magnet for your coaching business:
- Spotify Squad Health Check model
- Adapted checklist for the 5 dysfunctions
- Something readers can download and apply to their own team immediately

The current section ends with a strong theoretical base (Lencioni) but leaves the reader without actionable *structural* tools. Bridging that gap is the most impactful next move.
-->

[^1]: [The Five Dysfunctions of a Team](/others/bibliography/)
[^2]: [Team Topologies](/others/bibliography/)
[^3]: [Radical Candor](/others/bibliography/)