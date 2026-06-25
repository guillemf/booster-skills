---
title: Cross‑Team Collaboration & Dependencies
author: Guillem EfeGe
date: 2026-06-25
categories: [BoosterSkills, Chapters]
layout: post
published: false
---

### Why Cross-Team Collaboration Matters

In a multi-team environment, no team ships meaningful product alone; value always crosses team boundaries.

Dependencies aren’t inherently bad – they’re like passing the ball in a team sport: essential, but costly if done badly.

A simple example: Feature team needs a platform change and a data model update. Done well, this is smooth passing; done badly, it’s three teams blocking each other for weeks

### CPU / LAN / WAN View On Dependencies

#### CPU (You / Core Leadership)

You define the architecture of collaboration: who owns what, how work flows, and which dependencies are acceptable versus harmful.

#### LAN (Inside Your Circle)

These are high-bandwidth, high-trust relationships: teams you work with weekly, shared rituals, and quick decisions.

Dependencies here should be explicit in backlogs, discussed in planning, and resolved quickly in short feedback loops.

#### WAN (Outside Your Circle)

These are slower links: other orgs, distant teams, external vendors. Hand-offs need clearer contracts: APIs, SLAs, and timelines.

Here you minimize “chattiness” and design stable interfaces so your teams can move without constant renegotiation.

### Healthy vs Unhealthy Dependencies

#### Healthy (valuable) dependencies

They give access to shared platforms, expertise, or standards that let teams move faster with less duplication.

They are visible, owned, and planned: people know who they depend on, for what, and by when.

#### Unhealthy (disruptive) dependencies

These show up as constant blocking, unclear ownership, approvals for everything, and endless cross-team meetings.

They usually come from fuzzy architecture, overlapping responsibilities, or “hero-based” collaboration instead of clear workflows.

WAN-wise: healthy WAN dependencies feel like well-designed APIs; unhealthy ones feel like calling random people for favors.

### Core Practices For Cross-Team Collaboration

You can present this as “how to keep the network flowing”:

#### Make dependencies visible

Tag and link cross-team dependencies in your issue tracker and project kickoffs.

Use simple visuals (dependency boards, value stream maps) to show where work regularly crosses teams and where it gets stuck.

### Align goals, then plans

Ensure teams optimize for the same company-level outcomes, not local metrics.

When starting an initiative, include dependent teams in the kickoff and agree on shared goals, key milestones, and risks.

#### Define clear interfaces between teams

For recurrent collaboration (e.g., platform vs feature teams), define stable “contracts”: what each team provides, how to request changes, and expected lead times.

Treat these like API definitions for human teams: minimal, explicit, and versioned rather than re-negotiated every sprint.

#### Build lightweight collaboration routines

Keep one regular cross-team sync focused purely on dependencies, decisions, and risks—not status you already see in tools.

Encourage direct escalation and asking for help instead of silent waiting; this is a skill you can explicitly coach.

### Reducing Pain Without Owning The Org Chart

Most engineers don’t control the org structure, but they can reduce dependency pain inside whatever structure they have.

#### Map dependencies around the real complexity

Focus on the few cross-team dependencies that touch the most complex parts of the work; resolve those collaboratively in short iterations.

Temporarily behave like “one big team” to crack the complex piece, then go back to normal with clearer hand-off rules.

#### Standardize how work is described

Use a simple story template that always includes dependencies, and make it mandatory for cross-team work.

This reduces coordination overhead: people know exactly what’s needed without long back-and-forth.

#### Continuously redesign dependencies

As you scale, regularly review which dependencies are valuable and which are disruptive, then adjust ownership and boundaries.

Aim for end-to-end ownership of critical flows by as few teams as possible, and simplify wherever work crosses your LAN/WAN links.