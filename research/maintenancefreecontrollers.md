---
layout: basic
title: Research > Maintenance-free Controllers
permalink: /research/maintenancefreecontrollers
papers: ["Almost Surely Stable Deep Dynamics", "Deep Neural Network Approximation of Nonlinear Model Predictive Control", "Optimal PID and Antiwindup Control Design as a Reinforcement Learning Problem", "Reinforcement Learning based Design of Linear Fixed Structure Controllers", "Towards Self-Driving Processes: A Deep Reinforcement Learning Approach to Control"]
---

# Deep Learning for Process Control

Traditional controllers used in the process industries, such as PID loops or MPC, require constant attention and upkeep for its entire lifecycle including modeling, design, tuning and maintenance. These controllers are typically designed for a narrow operating range by assuming linear process behavior, and are not resilient to changes in plant equipment or operating conditions. In complex industrial systems, there often exists a trade-off between high performance controllers and the development of complex models that are computationally intensive and difficult to interpret or maintain.

<div class="columns">
  <div class="column is-one-quarter is-hidden-mobile"></div>
  <div class="column">
    <figure class="image">
      <img src="{{ site.baseurl }}/assets/img/pexels-magda-ehlers-2569842.jpg" alt="Photo of industrial plant and piping" title="Photo of industrial plant and piping. Royalty-free image from Pexel">
    </figure>
  </div>
  <div class="column is-one-quarter is-hidden-mobile"></div>
</div>

Inspired by the recent successes of deep learning in computer vision and natural language processing, our group is exploring deep reinforcement learning (DRL) as a model-free and maintenance-free framework for process control in industrial settings. Recent work that we've published shows promising results for DRL in terms of setpoint tracking performance and adaptability, but there are still many fundamental questions left to explore, including sample efficiency (big data is not always good data), stability guarantees, interpretability and computational challenges.

Ultimately, we are interested in the development of smart plants and advanced controllers that can provide a high level of safety and reliability for the industry.

<div class="columns">
  <div class="column">
    <figure class="image">
      <img src="{{ site.baseurl }}/assets/img/deeprl.png" alt="Reinforcement Learning based Design of Linear Fixed Structure Controllers" title="Reinforcement Learning based Design of Linear Fixed Structure Controllers">
    </figure>
    <figcaption><b>Reinforcement Learning based Design of Linear Fixed Structure Controllers - Lawrence et al. (2020): </b>A standard closed-loop structure is shown inside the dashed box. Arrows passing the dashed line indicate the passing of some time-horizon [0, T]. Outside the dashed box, we store cumulative rewards based on slightly perturbed policies, which are used to update the policy with a finite-difference scheme described in section 4.2 in the manuscript.</figcaption>
  </div>
  <div class="column">
    <figure class="image">
      <img src="{{ site.baseurl }}/assets/img/deeprl_pid.png" alt="Optimal PID and Antiwindup Control Design as a Reinforcement Learning Problem" title="Optimal PID and Antiwindup Control Design as a Reinforcement Learning Problem">
    </figure>
    <figcaption><b>Optimal PID and Antiwindup Control Design as a Reinforcement Learning Problem - Lawrence et al. (2020): </b>A standard closed-loop structure is shown inside the dashed box. Arrows passing the dashed line indicate the passing of some time-horizon [0, T]. Outside the dashed box, we store cumulative rewards based on slightly perturbed policies, which are used to update the policy with a finite-difference scheme described in section 4.2 in the manuscript.</figcaption>
  </div>
</div>

## Selected Publications

See below for a selection of our papers related to deep (reinforcement) learning.

{% include selected_pubs.html %}
