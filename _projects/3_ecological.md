---
layout: page
title: "Ecological Robotics"
description: "Designing robots around the roles they should come to occupy within their ecosystems."
img: assets/img/projects/ecological.png
importance: 3
category: work
related_publications: true
---

{% include figure.liquid
  path="assets/img/projects/ecological.png"
  title="Ecological Robotics"
  class="img-fluid rounded z-depth-1"
%}

<p class="caption">
  Conceptual illustration of an ecological perspective on robot design, where behavior, interaction, embodiment, spatial presence, materials, and lifecycle are considered in relation to the ecosystem the robot is meant to become part of.
</p>

## Overview

What if we designed robots by first asking **what they should become in the world**, rather than what technology we can build?

What if designing and introducing a robot into an environment required the same level of consideration as introducing a new species into a living ecosystem?
<div class="row row-cols-1 row-cols-md-2 g-4">

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">Research focus</h4>
        <p class="card-text">
          Exploring how an ecological perspective can reshape the way robots are designed
          for the environments and ecosystems they are meant to become part of.
        </p>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">Current stage</h4>
        <p class="card-text">
          The conceptual perspective has been articulated, but it has not yet been developed
          into a systematic design methodology. The next step is to operationalize it into
          methods and tools for ecology-centered robot design and evaluate their usefulness
          in practice.
        </p>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">Work so far</h4>
        <p class="card-text">
          An initial conceptual workshop paper introducing Ecological Robotics through
          the ideas of ecological role, niche, ecological continuity, and their implications
          for robot design.
        </p>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">Collaboration opportunities</h4>
        <p class="card-text">
          I am keen to collaborate with researchers and designers in robotics, HRI,
          ecology, and design who can bring complementary methods or domain expertise
          to co-develop and evaluate ecology-centered approaches to robot design.
        </p>
      </div>
    </div>
  </div>

</div>


## The idea

What makes a robot a robot?

We can describe one through its sensors, actuators, autonomy, intelligence, appearance, or interaction capabilities. But these descriptions mostly tell us **what the system is made of or what it can do**.

Once robots leave the laboratory, however, they become part of something larger.

They enter homes, workplaces, streets, hospitals, forests, and other environments already inhabited by people, animals, technologies, infrastructures, norms, and material conditions. Over time, a robot may become more than a technical artifact operating there: it may acquire a recognizable place within this network of relationships.

This motivated us to propose **Ecological Robotics** {% cite bretin_ecological_2026%}: a perspective that shifts attention from what a robot *is* in isolation to **what it becomes within the ecosystem in which it exists**.

Here, I use *ecosystem* in a deliberately ecological sense, while extending it beyond natural environments. An ecosystem can be a forest, but it can also be a household, a workplace, or another bounded environment composed of interacting actors, practices, resources, spaces, and material conditions.

The question then changes from:

**What robot should we build?**

to:

**What kind of entity should this robot become within this ecosystem?**

## Designing from the ecological role outward

Robot design often starts from the technology.

We develop a platform, define its capabilities, design ways of interacting with it, and eventually determine where and how it might be deployed.

Ecological Robotics proposes reversing this logic.

Before deciding what the robot should look like or how it should interact, we can first ask:

**Who or what do we want this robot to become within its target ecosystem?**

We call this intended position its **ecological role**.

A robot might be designed to become a companion, an assistant, a co-worker, a piece of infrastructure, a background agent, or something for which we do not yet have an established category.

These labels are not neutral. They imply different relationships with the other actors in the ecosystem and create different expectations about how the robot should behave, how visible it should be, what it should be allowed to do, and how others should relate to it.

Once the intended ecological role is explicit, other design decisions can follow from it:

- **Behavior** — how should the robot move, communicate, cooperate, or avoid interaction?
- **Spatial presence** — how should it share space, negotiate territories, or regulate proximity?
- **Embodiment** — what physical form best supports the role it is intended to occupy?
- **Sensory presence** — what sounds, lights, movements, data collection, or other traces does it introduce?
- **Materials and energy** — what should it be made of, how should it be powered, maintained, repaired, or eventually disposed of?
- **Lifetime** — how should its relationship with the ecosystem evolve over days, months, or years?

From this perspective, interaction design does not disappear. It becomes one expression of a broader ecological commitment: **the kind of inhabitant we are trying to design.**

## Thinking like an ecologist: the case of FRED

{% include figure.liquid
  path="assets/img/projects/fred.jpeg"
  title="FRED"
  class="img-fluid rounded z-depth-1"
%}

<p class="caption">
  A rainforest biodiversity-monitoring robot developed at Aarhus University, which inspired our speculative FRED example. Photo: Claus Melvad. Source: <a href="https://ingenioer.au.dk/en/current/news/view/artikel/smart-robot-can-help-us-learn-more-about-rainforest-biodiversity"
     target="_blank" rel="noopener noreferrer"> Kim Harel, AU Engineering, Aarhus University</a>.
</p>

Imagine introducing a small autonomous robot into a forest to collect environmental data.

A conventional design process might begin by asking which sensors it needs, how it should move through difficult terrain, or how much data it can collect.

An ecological perspective adds another question:

**What kind of presence should this robot become within the forest?**

In our workshop paper, we imagine **FRED — a FoRest Exploration Device** whose intended ecological role is closer to that of a wildlife-like inhabitant than a visible scientific instrument.

That commitment could shape the entire system.

FRED might avoid direct human approach, freeze when observed, and move in ways reminiscent of an animal. Its energy source, materials, physical traces, and eventual end of life could similarly be designed around minimizing disruption to the ecosystem it inhabits.

The point is not that robots should imitate animals.

Rather, FRED illustrates what happens when we begin with an ecological role and allow **behavioral, material, spatial, and technical design decisions to follow from it**.

## More than one body

Thinking in terms of ecological roles also challenges where we locate a robot's identity.

Artificial agents may increasingly move between physical embodiments, devices, or infrastructures. A domestic robot might inhabit a humanoid body at home, continue through a mobile device outside, and temporarily use another robotic embodiment for a particular activity.

The hardware changes—but the relationships, history, expectations, and role associated with the system may persist.

We call this **ecological continuity**: the persistence of a robot's role and niche across changing material embodiments.

From this perspective, the continuity of a robot may reside less in a particular chassis than in the stable pattern of participation it maintains within an ecosystem.

## Where is this going?

At this stage, Ecological Robotics is a **research perspective rather than a fixed framework**. Our initial workshop paper introduced the lens and some of its implications; the next challenge is to make it more systematic and actionable for robot design.

One direction I am particularly interested in is developing an **ecology-centered approach to robot design**.

Human-centered design changed the way interactive technologies are created by providing designers with principles, methods, and tools for systematically considering users throughout the design process.

I am interested in asking what an analogous shift could look like for robotics:

**How can we systematically design a robot around the ecosystem it is intended to become part of?**

This means moving beyond simply evaluating environmental or social consequences after a robot has already been designed. Instead, ecological role, niche, relationships, spatial implications, material conditions, and long-term coexistence could become considerations from the beginning of the design process.

My goal is therefore not only to develop the conceptual perspective, but eventually to turn it into **methods and tools that can support ecological reasoning throughout robot design**.

This is an emerging direction, and I am particularly interested in developing it through collaborations spanning robotics, HRI, ecology, design, and related disciplines.