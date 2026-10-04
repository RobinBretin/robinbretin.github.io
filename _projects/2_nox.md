---
layout: page
title: "Human–Robot Territoriality"
description: How do robots enter, occupy, and leave socially meaningful spaces?
img: assets/img/projects/territoriality.png
importance: 2
category: work
related_publications: true
---

{% include figure.liquid
  path="assets/img/projects/territoriality.png"
  title="Human–Robot Territoriality"
  class="img-fluid rounded z-depth-1"
%}

<p class="caption">
  Conceptual illustration of how a robot enters, occupies, and leaves a human territory.
</p>

## Overview
<div class="row row-cols-1 row-cols-md-2 g-4">

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">Research focus</h4>
        <p class="card-text">
          Understanding how robots enter, occupy, and leave socially meaningful spaces,
          and how their behavior interacts with the expectations attached to those spaces.
        </p>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">Current stage</h4>
        <p class="card-text">
          The initial framework and NOX model have received empirical support in a
          domestic primary territory. The research is now moving toward testing and
          refining these ideas across more complex territories, stakeholders, and robot
          forms, while developing ways to operationalize them in design and robotic systems.
        </p>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">Work so far</h4>
        <p class="card-text">
          A conceptual framework and vocabulary for Human–Robot Territoriality, the NOX
          Entry–Occupancy–Exit model, and an empirical vignette study with 290 participants.
        </p>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">Collaboration opportunities</h4>
        <p class="card-text">
          I am keen to collaborate with researchers running real-world robot deployments,
          studying social navigation or territorial behavior, or developing robot autonomy,
          to test territorial dynamics in new settings and translate them into design and
          robotic behavior.
        </p>
      </div>
    </div>
  </div>

</div>

## The idea

Spaces are not socially neutral.

A bedroom, a workplace, a classroom, a garden, or even a temporary gathering each comes with expectations about how that space should be used and experienced. We develop a sense of who belongs there, who may enter, what kinds of actions are appropriate, how long someone may stay, and what qualities of the space should be preserved.

These expectations are not necessarily explicit. Much like proxemic behavior, we often navigate them intuitively as part of everyday life.

What happens when robots begin to enter these spaces?

A robot may be physically capable of crossing a doorway, moving through a room, manipulating an object, or leaving whenever it chooses. But technical possibility does not automatically make these behaviors socially appropriate.

This is where I became interested in **Human–Robot Territoriality**: how people's relationships with spaces shape what they expect from robots entering, occupying, and leaving them.

Rather than treating space as an empty environment through which a robot simply navigates, this perspective treats it as a socially meaningful setting—one already associated with people, activities, norms, expectations, and particular ways of being used.

## A framework for thinking about territories

Before asking how a robot should behave in a territory, we need a way to describe what makes that space meaningful to the people connected to it.

Our framework {% cite bretin_nox_2026 %} brings together several concepts from territoriality research and adapts them to Human–Robot Interaction:

| Concept | A useful question | What it captures |
| --- | --- | --- |
| **Stakeholder** | *Who is meaningfully affected by what happens here?* | An agent with a meaningful connection to the territory—not necessarily the robot's user, or even someone physically present at the time. |
| **Territorial connection** | *Why does this space matter to them?* | Practical, emotional, social, or legal ties to a space, such as living, working, owning, identifying with, or relying on it. |
| **Territorial model** | *How do they expect this space to work?* | Expectations about who may access it, what may happen there, how it should be used, and what qualities it should maintain. |
| **Territorial status** | *How can they actually experience and act within the space?* | Their current position in the territorial dynamic, including authority, freedom of access and action, self-expression, and the experienced qualities of the environment. |
| **Territorial congruence** | *Do expectations and experience align?* | The degree to which what happens in the space corresponds to what stakeholders expect. |
| **Territorial behavior** | *How are these relationships expressed?* | Ways of expressing, negotiating, maintaining, or responding to territorial relationships—from personalization and rule-setting to reactions when expectations are not met. |

Together, these concepts describe the territorial setting in which an interaction takes place.

**NOX adds the temporal dimension:** what happens when a robot approaches a territory, enters it, acts or remains within it, and eventually leaves?

## NOX: Entry, Occupancy, Exit

To make these dynamics actionable for HRI research and design, we developed **NOX (ENtry, Occupancy, EXit)**, a stage-based model of how robots engage with human territories over time {% cite bretin_nox_2026 %}.

The model follows three broad phases:

- **Entry** — how a robot approaches and gains access to a territory;
- **Occupancy** — what it does, where it moves, and how its presence affects the space;
- **Exit** — when and how it leaves, and what remains after it has gone.

Across these phases, NOX identifies places where robot behavior and stakeholder expectations can diverge. We call these **friction points**.


<div style="width: 95%; margin: 2rem auto;">

{% include figure.liquid
  path="assets/img/projects/modelTer.jpg"
  title="NOX model of Human–Robot Territorial Dynamics"
  class="img-fluid rounded z-depth-1"
%}

</div>

<p class="caption">
  The NOX framework connects robot operations across Entry, Occupancy, and Exit
  with the territorial expectations through which stakeholders experience a space.
</p>

At each phase, these potential mismatches can concern three broad dimensions:

- **Freedom** — the degree of access, exit, or action the robot is expected to have;
- **Action** — whether what the robot physically does, including where and how it acts, fits the expectations associated with the space;
- **Status** — how the robot's behavior or presence changes stakeholders' actual experience of the territory, such as their authority, freedom of action, self-expression, or the qualities of the space.

Importantly, NOX does not prescribe one universally correct behavior. A robot does not, for example, always need to ask permission before entering. What matters is whether its behavior is congruent with what relevant stakeholders expect in that particular territorial context.

We evaluated this idea in a vignette study with **290 participants**, using a domestic primary territory as a first test case {% cite bretin_nox_2026 %}. Across Entry, Occupancy, and Exit, mismatches between expected and observed robot behavior were associated with more negative emotional responses, stronger defensive intentions, and lower perceived appropriateness.

The key point is therefore not that one specific behavior is always appropriate, but that **territorial expectations matter**, and that robot behavior can become problematic when it conflicts with them.


## Beyond physical boundaries

Territories do not necessarily stop at walls, doors, or property lines.

Together with <a href="https://scholar.google.com/citations?user=MZw5Bh4AAAAJ&hl=en">Felix Tener</a> and <a href="https://scholar.google.com/citations?user=Rk1SDB8AAAAJ&hl=fr">Jessica Cauchard</a>, we are extending this work to **urban Human–Drone Interaction**, asking whether spaces that are physically outside a home can nevertheless remain socially connected to it.

For example, what does it mean for a drone to fly directly outside someone's window? Is that airspace simply part of the street, or does the social meaning of the home extend beyond its physical walls?

This ongoing work is currently under review at **CHI** and explores how territorial expectations change as drones move through urban environments.

## Why does this matter?

As robots increasingly operate in everyday environments, technical accessibility does not necessarily imply social appropriateness.

Understanding territorial expectations can help us move from asking only **"Can the robot go there?"** toward asking **"What does it mean for the robot to be there?"**

## Where is this going?

A first goal is to strengthen the empirical foundations of Human–Robot Territoriality. Territorial expectations are often implicit, context-dependent, and shaped over time, so I am interested in developing better ways to observe and measure them in real-world and longitudinal interactions.

I also want to turn the framework into practical tools for design. One direction is to develop **territorial audits** that help researchers and designers identify relevant stakeholders, expectations, and potential friction points before deployment—and diagnose breakdowns once a robot is in use.

In the longer term, the goal is to move from analyzing territorial interactions after the fact toward **territorially aware robots**. This means identifying the cues that could allow a robot to infer what kind of space it is entering, whose expectations matter, when those expectations are changing, and how it should adapt, negotiate, or recover when something goes wrong.

Ultimately, I see territoriality not only as a way to explain human–robot spatial interaction, but as a basis for designing robots that can participate more appropriately in socially meaningful spaces.

Territoriality complements my work on <a href="/_projects/1_project.md">Human–Drone Proxemics</a> by adding another facet of the social use of space. More broadly, it also connects to my work on <a href="/_projects/3_ecological.md">Ecological Robotics</a>, which explores how robots can be designed around the environments—or ecosystems—they are meant to become part of.