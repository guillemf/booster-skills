---
title: Stakeholder Map & Expectations (inside + outside)
author: Guillem EfeGe
date: 2026-06-05
categories: [BoosterSkills, Chapters]
cover: /assets/covers/booster_skills_wan_stakeholders.png
layout: post
---

# Who Are Your Stakeholders, Really?

Most people think of stakeholders as "the people you report to." In practice, your stakeholder landscape is much wider and more varied than that. A stakeholder is anyone whose goals, decisions, or wellbeing are directly connected to what your team does — and that includes people who never attend your sprint reviews, never read your roadmap, and may not even know your team exists by name.

Mapping them starts with a simple question: *who can make this work easier, harder, or irrelevant?* The answer will cover your direct manager, sure, but also the PM whose roadmap depends on your delivery, the platform team whose infrastructure you sit on, the compliance officer who can block your release, the sales team who's already promised a feature to a customer, and the end user who will simply stop using the product if you get it wrong.

Until you make this map explicit, you are navigating a dark network. You'll be surprised by requests, blindsided by objections, and confused about why "obviously good" work keeps getting delayed or cancelled. The map doesn't need to be complicated — it needs to be honest and current.

> **A real example:** 
>
> _A backend team spent two sprints building a new data export API they were proud of. It was well-designed, well-documented, and shipped on time. The problem? The compliance team had been sitting on a new data residency regulation for three weeks and assumed someone would loop them in. Nobody had mapped compliance as a stakeholder. The feature was frozen the week after it shipped. Two months and a significant redesign later, it finally reached production. The technical work was never the issue — the routing table was broken._
{: .block-tip }

# Inside vs Outside: Two Types of Stakeholders

A useful first cut is separating your stakeholders into two groups, each with a different type of influence and a different communication style.

**Internal stakeholders (inside)** are people employed in or directly working with your organization. They typically have formal authority or direct influence over your work: your engineering manager, product managers, adjacent team leads, tech leads, senior engineers, executives, and support or operations teams. These are the people who shape your priorities, approve your decisions, and depend on you to deliver on shared organizational goals. They speak your internal language: sprints, OKRs, roadmaps, incidents.

**External stakeholders (outside)** are customers, end users, vendors, partners, regulators, and the broader community that interacts with your product or is affected by it. They don't care about your internal processes; they care about outcomes: does the product solve their problem, reliably, without making them feel ignored? Their feedback often reaches you indirectly — through support tickets, NPS scores, contract renewals, or public reviews — but it carries enormous weight.

Every non-trivial project has both types. The teams that ignore external stakeholders build products with great internal alignment and zero real-world adoption. The teams that ignore internal stakeholders move fast and get blocked by politics, compliance, or budget decisions they never saw coming. A healthy WAN keeps both sides on the map.

> **A pattern you'll recognize:** 
>
> _The team that ships a feature perfectly aligned with its internal roadmap, only to discover that the three largest enterprise customers needed something slightly different and have already started evaluating competitors. Internal alignment without external signal is just well-organized wishful thinking._
{: .block-tip }

Find this table to identify internal/external stakeholders.

| Side     | Stakeholder group       | Typical expectations from you                                | What you should ask from them                                           |
| -------- | ----------------------- | ------------------------------------------------------------ | ----------------------------------------------------------------------- |
| Internal | Your direct team        | Clear priorities, support, feedback, no surprises em-tools+1 | Honest status, constraint signals, ownership em-tools                   |
| Internal | Product manager / PO    | Delivery predictability, trade-off clarity em-tools+1        | Clear product goals, scope, and success metrics linkedin                |
| Internal | Design / UX             | Early involvement, context on constraints uxpressia          | Testable designs, user insight, design decisions uxpressia              |
| Internal | Other engineering teams | Stable APIs, predictable integration points asana            | Shared roadmaps, integration timelines asana                            |
| Internal | Leadership / execs      | Progress towards business goals, risk visibility icaew+1     | Strategy, priorities, resourcing, air cover icaew                       |
| External | Customers / end users   | Reliable product, honest communication, support miro+1       | Feedback, usage signals, reasonable change expectations dovetail        |
| External | Client org stakeholders | Business outcomes, timelines, transparency dovetail+1        | Clear requirements, decision-making, access to people projectmanagement |
| External | Vendors / partners      | Clear interfaces, timely info, fair collaboration icaew      | SLAs, roadmap alignment, integration support icaew                      |
| External | Regulators / compliance | Compliance, documentation, auditability icaew                | Clear rules, guidance, reasonable timelines icaew                       |


# Mapping Your Stakeholders: A Practical Approach

You don't need a sophisticated tool to build a useful stakeholder map. You need clarity, honesty, and a habit of keeping it updated. A simple but effective approach is to plot stakeholders on two dimensions:

- **Influence**: how much power do they have to enable or block your work?
- **Interest**: how closely connected are they to the outcomes your team produces?

This gives you four practical groups:

| | High Interest | Low Interest |
|---|---|---|
| **High Influence** | Manage closely — align actively, communicate frequently, involve in key decisions | Keep satisfied — give them what they need without overwhelming them |
| **Low Influence** | Keep informed — they care and their signal is valuable, but they don't steer the ship | Monitor — light touch, no frequent communication needed |

The goal isn't to "manage" people as objects; it's to invest your limited communication and relationship energy where it has the most impact. Stakeholders in the top-left quadrant need regular, intentional engagement. Stakeholders in the bottom-right need periodic visibility. Treating all stakeholders the same way — either ignoring most of them or involving everyone in everything — is a fast path to noise, friction, and missed expectations.

Once you have a draft map, ask yourself: *Are there people here whose expectations I have never explicitly discussed with them?* Those are your biggest risks.

> **Try this:** 
> 
> _At the start of your next initiative, take 30 minutes with your team and write down every person or group that could affect or be affected by the work. Then place them on the grid together. You'll almost always find at least one stakeholder that nobody owns, and at least one person in the "manage closely" quadrant who's been receiving the same low-touch update as everyone else. That conversation alone is worth the half-hour._
{: .block-tip }

# Understanding and Managing Expectations

Having a stakeholder map is the first step. Understanding what each stakeholder actually expects from you is the harder, more important second step. Expectations are not always what people say out loud — they are also what they assume you already know.

Unspoken expectations are the most dangerous. A senior executive might expect weekly updates on a critical project without ever asking for them, and interpret your silence as a lack of urgency. A customer might expect that a promised feature means "shipped by next quarter," while your team thinks it means "on the backlog somewhere." These gaps don't get resolved by better intentions; they get resolved by explicit, documented conversations.

A few practical habits for managing expectations at the WAN level:

- **At the start of any significant initiative**, hold a lightweight "expectation alignment" conversation with your key stakeholders: what does success look like to them, by when, and how do they want to stay informed?
- **Don't confuse preference with requirement**. It is fine — and often valuable — to challenge a stakeholder's stated expectation when you have data and an alternative proposal. What is never acceptable is ignoring it entirely or replacing it with your own assumptions.
- **Write down what was agreed**. A shared document, a Confluence page, even a follow-up email. Verbal alignment evaporates under pressure. Written alignment holds.
- **Revisit the map regularly**. Projects change scope, organizations restructure, people move. A stakeholder map that was accurate three months ago may be dangerously out of date today.

> **A story worth telling:** 
> 
> An engineering lead inherited a project mid-flight. The previous lead had done good verbal alignment with the VP sponsor but nothing was written down. Three months in, the VP remembered the delivery date as "end of Q2." The team had understood "Q3 at the latest." Same conversation, same people, completely different mental models. The project wasn't late — but it took two difficult meetings and a lot of goodwill to close that gap. A one-paragraph follow-up email after the original alignment meeting would have prevented the entire thing.
{: .block-tip }

# Communication Patterns: Routing the Right Signal to the Right Node

Once you know who your stakeholders are and what they expect, the practical question becomes: how do you communicate with each of them without drowning in meetings or leaving people in the dark?

Think of this as designing the communication architecture of your WAN. Different stakeholders need different signal types, different frequencies, and different levels of detail:

- **Executives and senior leadership**: infrequent, high-signal updates focused on outcomes, risks, and decisions needed. They don't need the details; they need to know whether things are on track, what's at risk, and what you need from them. A concise written summary or a brief synchronous check-in works better than a full status meeting.
- **Peer teams and adjacent leads**: regular, structured touchpoints around shared work, dependencies, and blockers. The goal is predictability: they should never be surprised by something your team is doing that affects them.
- **End users and customers**: feedback loops rather than broadcasts. You're not sending them status reports; you're creating channels where their signal reaches your team reliably — support reviews, user sessions, usage analytics, periodic surveys.
- **Vendors and external partners**: periodic formal check-ins anchored to contract milestones, roadmap updates, or shared service reviews. These relationships need less frequency but more structure.

The common mistake is applying one communication model to everyone: either sending long updates to all stakeholders or holding large group meetings that serve no one particularly well. Segment your communication like you'd segment network traffic — right content, right format, right frequency, right audience.

> **A concrete pattern that works:** 
> 
> _One engineering manager introduced a simple "stakeholder digest" — a short weekly message structured in three lines: **what shipped, what's at risk, what decision is needed from you.** Senior stakeholders started reading it because it respected their time. Adjacent teams stopped asking for status meetings because they already had the signal they needed. The manager spent less time in reactive conversations and more time doing actual work. The format took 15 minutes to write and saved roughly 3 hours of meetings per week._
{: .block-tip }

# When Expectations Break: Recovering Stakeholder Trust

Even with a solid map and good communication habits, expectations will occasionally break. A deadline slips, a promised feature gets deprioritized, a vendor fails, or a business decision makes a customer unhappy. How you handle these moments matters far more than the fact that they happened.

The pattern that works is simple but requires discipline: **be proactive, be specific, and come with options**.

- **Proactive** means telling stakeholders about a problem before they find out on their own. The moment you know something is at risk, communicate it. A stakeholder who hears bad news early can adapt. A stakeholder who hears it after the fact loses trust that is very hard to rebuild.
- **Specific** means describing clearly what happened, what the impact is, and what you know versus what you don't yet know. Vague apologies and generic reassurances don't help; they signal that you don't fully understand the situation.
- **Options** means coming to the conversation with at least one alternative path: a revised timeline, a reduced scope, a mitigation plan, a trade-off for them to choose from. Don't just present the problem — bring your thinking about what comes next.

Trust with stakeholders is a long-term asset. It compounds when you communicate honestly and consistently, and it erodes quickly when people feel surprised, ignored, or managed with spin rather than substance.

> **The moment that defines you:** 
> 
> _A team was three days away from a major release when a critical integration with a third-party payment provider failed in staging. The engineering lead had two options: push the release anyway and hope it held in production, or tell the business stakeholders immediately and propose a two-week delay with a clear mitigation plan. She chose transparency. The stakeholders were unhappy for about 48 hours. Two weeks later, the release went out cleanly. A year later, the same stakeholders specifically mentioned that moment in her performance review — not as a failure, but as an example of mature, trustworthy leadership. The technical problem was forgotten. The honesty wasn't._
{: .block-tip }

# Key Ideas

> *  Your stakeholder landscape is always wider than your org chart. Map it explicitly, and keep it current.
> *  Internal and external stakeholders have different types of influence and different communication needs — both matter.
> *  A power/interest grid is a simple, effective tool for prioritizing where to invest your relationship energy.
> *  Unspoken expectations are your biggest risk. Make them explicit, write them down, and revisit them regularly.
> *  Design your communication architecture like your network architecture: right signal, right format, right frequency, right audience.
> *  When expectations break, recover with proactivity, specificity, and options — not silence or generic reassurance.
{: .block-tip }