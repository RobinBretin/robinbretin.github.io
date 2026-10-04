---
layout: page
title: "VR as a Research Method"
description: "Using virtual and hybrid environments to study Human–Robot Interaction rigorously."
img: assets/img/projects/vr.png
importance: 4
category: work
related_publications: true
---


{% include figure.liquid
  path="assets/img/projects/vr.png"
  title="Ecological Robotics"
  class="img-fluid rounded z-depth-1"
%}

<p class="caption">
  From physical to hybrid to virtual: different ways of composing HRI experiments around the phenomenon being studied.
</p>

## Overview

<div class="row row-cols-1 row-cols-md-2 g-4">

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">Research focus</h4>
        <p class="card-text">
          Understanding how Virtual Reality can be used as a rigorous research instrument
          for Human–Robot Interaction without overlooking how the medium itself may affect
          the phenomena being studied.
        </p>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">Current stage</h4>
        <p class="card-text">
          A methodological approach has been developed and applied across several
          Human–Drone Interaction studies. I am now extending it toward hybrid
          physical–virtual environments and exploring how well this reasoning transfers
          to other HRI phenomena.
        </p>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">Work so far</h4>
        <p class="card-text">
          A methodological protocol developed during my PhD, multiple VR-based
          Human–Drone Interaction studies, real–virtual comparisons, and recent work
          combining physical and virtual drones within the same experiment.
        </p>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">Collaboration opportunities</h4>
        <p class="card-text">
          I am interested in working with HRI and XR researchers facing experiments
          that are difficult, risky, expensive, or technologically constrained in the
          physical world, and in jointly developing and evaluating virtual or hybrid
          approaches suited to those research questions.
        </p>
      </div>
    </div>
  </div>

</div>


## The idea

Robots are not always easy to study in the real world.

Hardware constrains what can be built and tested. Safety requirements may limit how closely people and robots can interact. Outdoor experiments introduce legal, logistical, and environmental difficulties. And some scenarios—from dangerous encounters to large groups of robots—may simply be impractical to reproduce physically.

Virtual Reality offers a powerful alternative. It allows researchers to precisely control robot appearance and behavior, create situations that would otherwise be unsafe, and investigate technologies that do not yet physically exist.

But this flexibility comes with a methodological challenge.

A virtual robot is not experienced exactly like a physical one. Its sensory cues, physical consequences, perceived presence, and the actions available around it may all differ.

So rather than asking only:

**“Is VR ecologically valid?”**

I am interested in a more useful question:

**How might VR affect the particular phenomenon we are trying to study?**

This question became an important methodological thread throughout my PhD on Human–Drone Interaction.


## Reasoning about VR, rather than assuming it works

During my PhD, I developed a methodological protocol for reasoning about the use of VR in Human–Drone Interaction.

The central idea is that the suitability of a virtual experiment depends on **what produces the phenomenon being studied and how the experimental medium may affect those mechanisms**.

The protocol works through three steps:

<div class="row row-cols-1 row-cols-md-3 g-4">

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">1. Identify the mechanisms</h4>
        <p class="card-text">
          Start by identifying what the phenomenon under study actually depends on:
          for example visual perception, threat appraisal, sound, physical risk,
          situational awareness, or movement.
        </p>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">2. Assess VR's influence</h4>
        <p class="card-text">
          Examine how the virtual environment may affect those mechanisms.
          Differences in sensory cues, distance perception, movement, presence,
          or physical consequences may matter differently depending on the phenomenon.
        </p>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="card h-100">
      <div class="card-body">
        <h4 class="card-title">3. Minimize or account for it</h4>
        <p class="card-text">
          Adapt the experimental setup where possible, and explicitly document
          the remaining differences and assumptions so that their implications
          for the findings can be evaluated.
        </p>
      </div>
    </div>
  </div>

</div>

Not every difference can—or needs to—be removed. Making the remaining assumptions and limitations explicit is equally important, because it allows others to judge where the findings are likely to apply.


## Putting the method to work

This methodological approach developed alongside my empirical work on <a href="/_projects/1_project.md">Human–Drone Proxemics</a>.

Across several studies, VR allowed me to investigate situations that would have been difficult or unsafe to reproduce with physical drones while retaining precise experimental control.

I used virtual environments to manipulate factors such as drone height, social context, potentially dangerous payloads, and task constraints while allowing participants to move naturally around the drones.

I also directly compared defensive responses around real and virtual drones {% cite bretin_i_2023 %}.

These studies provided a practical testbed for understanding not only what VR makes possible, but also where its influence needs to be considered when interpreting HRI findings.


## Between virtual and physical

The choice does not have to be between a completely physical experiment and a completely virtual one.

More recently, I have been exploring **hybrid experimental environments** that selectively reintroduce physical elements into virtual interactions.

A useful example comes from *One for All*, a master thesis by Alexander Melem which I supervised (under review at IEEE VR 27).

The project asked:

**Could one real drone make an entire virtual group of drones feel more physically present?**

We developed a setup in which participants saw a group of visually identical drones in VR, while one member of the group was paired with an actual motion-tracked drone flying in the physical room.

In a study with **25 participants**, virtual drones were **2.77 times more likely to be judged physically present** when one real drone was included. The hybrid setup also increased perceived interaction realism and concern about collisions.

Effects on spatial behavior were more context-dependent, appearing most clearly in one demanding moving-group condition.

This points toward a broader experimental design space between fully virtual and fully physical studies: researchers may be able to selectively preserve the physical aspects of an interaction that matter for their research question without physically instantiating the entire scenario.


## Where is this going?

I want to understand how virtual and hybrid environments can best be used to study different HRI phenomena.

A key challenge is to develop methodological approaches that help researchers support the validity and interpretability of their findings, while making the assumptions and limitations of virtual studies explicit enough for others to judge where those findings apply.

This is particularly important because VR is a moving target. Limitations that matter today may disappear as sensing, rendering, haptics, tracking, and physical–virtual integration improve. Rather than relying on fixed conclusions about what VR can or cannot reproduce, I am interested in approaches that remain useful as the technology evolves.

I also want to bring this methodological perspective into other parts of my research. For example: **can territorial dynamics be meaningfully studied in VR?** Under what conditions can a virtual space generate expectations about access, control, intrusion, or appropriate robot behavior?