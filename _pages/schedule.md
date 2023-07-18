---
layout: page
permalink: /schedule/
title: Schedule
description: This workshop will be held in-person at ICML 2023 at the Hawaii Convention Center on July 28th 2023. The session will cover a tutorial, invited talks, contributed talks, posters, and a panel discussion. The schedule in Hawaii Standard Time (GMT-10) can be found below. <b>(Click the talks to see their abstracts)</b>
nav: true
nav_order: 2
---

<br>

<div>
<table class="table" id="standings" style="border-collapse:collapse">
<tr class="header" style="background-color:rgb(215, 215, 215); border-top: 1pt solid white; border-bottom: 1pt solid black;">
        <th style="border-top-left-radius: 10px; width: 15%">Hawaii Time</th>
        <!-- <th>Virtual link</th> -->
        <th style="width: 15%">Type</th>
        <th style="width: 70% border-top-right-radius: 10px;">Title & Speakers</th>
        <!-- <th style="width: 25% border-top-right-radius: 10px;">Speakers (Affiliations)</th> -->
      </tr>
      <tr>
  <tr class="header" style="cursor: pointer">
    <td>9:00 - 9:45</td>
    <td>Tutorial</td>
    <td><b>On Optimal Control and Machine Learning</b><br>
    Brandon Amos <i>(Meta AI)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
      This talk tours the optimal control and machine learning methodologies behind recent breakthroughs in the field. These are crucial components for building agents capable of computationally modeling and interacting with our world via planning and reasoning, e.g. for robotics, aircrafts, autonomous vehicles, games, economics, finance, and language, as well as agricultural, biomedical,chemical, industrial, and mechanical systems. We will start with 1) a lightweight introduction to optimal control, and then cover 2) machine learning for optimal control --- this includes reinforcement learning and overviews how the powerful abstractive and predictive capabilities of machine learning can drastically improve every part of a control system; and 3) optimal control for machine learning --- surprisingly in this opposite direction, some machine learning problems are able to be formulated as control problems and solved with optimal control methods, e.g. parts of diffusion models, optimal transport,and optimizing the parameters of models such as large language models with reinforcement learning.</td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>9:45 - 10:30</td>
    <td>Invited Talk</td>
    <td><b>Two-for-one: Diffusion Models and Force Fields for Coarse-Grained Molecular Dynamics</b><br>Rianne van den Berg <i>(Microsoft Research)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
      In this work I will cover work from the Microsoft Research AI4Science team on the use of score-based generative modeling for coarse-graining (CG) molecular dynamics simulations. By training a diffusion model on protein structures from molecular dynamics simulations we show that its score function approximates a force field that can directly be used to simulate CG molecular dynamics. While having a vastly simplified training setup compared to previous work, we demonstrate that our approach leads to improved performance across several small- to medium-sized protein simulations, reproducing the CG equilibrium distribution, and preserving dynamics of all-atom simulations such as protein folding events.
    </td>
  </tr>

  <tr class="header">
    <td>10:30 - 10:45</td>
    <td>Contributed Talk</td>
    <td><b>Transport, Variational Inference and Diffusions</b>
      <br>Francisco Vargas <i>(Cambrdige)</i>, Nikolas Nusken <i>(King’s College London)</i></td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>10:45 - 11:30</td>
    <td>Invited Talk</td>
    <td><b>Imposing and Learning Structure in OT Displacements through Cost Engineering</b>
      <br>Marco Cuturi <i>(Apple & ENSAE CREST)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
      I will highlight in this work the flexibility provided by the Gangbo-McCann theorem, which provides a generic way to tie kantorovich dual potential solutions to optimal maps for the Monge problem.  We show in particular how setting the ground cost to the squared-Euclidean distance + a regularizer induces displacements that have a structure that is well suited to that regularizer (e.g. sparse if that regularizer is the L1 norm). We propose an approach, in more recent work, to learn parameters of that regularizer.
    </td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>11:30 - 12:15</td>
    <td>Invited Talk</td>
    <td><b>Designing High-Dimensional Closed-Loop Optimal Control Using Deep Neural Networks</b>
      <br>Jiequn Han <i>(Flatiron Institute)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
      Designing closed-loop optimal control for high-dimensional nonlinear systems remains a persistent challenge. Traditional methods, such as solving the Hamilton-Jacobi-Bellman equation, suffer from the curse of dimensionality. Recent studies introduced a promising supervised learning approach, akin to imitation learning, that uses deep neural networks to learn from open-loop optimal control solutions.
    </td>
  </tr>

  <tr class="header" style="background-color:rgb(240, 240, 240);">
      <!-- <tr> -->
        <td>12:15 - 13:15</td>
        <td></td>
        <td>Poster Session &amp; Lunch</td>
  </tr>

  <tr class="header">
    <td>13:15 - 13:45</td>
    <td>Panel Session</td>
    <td>
      Daniela Rus <i>(MIT)</i> <br>
      Arnaud Doucet <i>(University of Oxford &amp; DeepMind)</i> <br>
      Evangelos Theodorou <i>(Georgia Tech &amp; Amazon)</i> <br>
      Jeannette Bohg <i>(Stanford)</i> <br>
      Sarah Dean <i>(Cornell)</i> <br>
    </td>
  </tr>

  <tr class="header">
    <td>13:45 - 14:30</td>
    <td>Invited Talk</td>
    <td><b></b>
      <!-- <br> -->
      Claire Tomlin <i>(UC Berkeley)</i></td>
  </tr>

  <tr class="header">
    <td>14:30 - 14:45</td>
    <td>Contributed Talk</td>
    <td><b>Bridging Reinforcement Learning Theory and Practice with the Effective Horizon</b>
      <br>Cassidy Laidlaw, Stuart Russell, Anca Dragan <i>(UC Berkeley)</i></td>
  </tr>

  <tr class="header" style="background-color:rgb(240, 240, 240);">
      <!-- <tr> -->
        <td>14:45 - 15:00</td>
        <td></td>
        <td>Coffee Break</td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>15:00 - 15:45</td>
    <td>Invited Talk</td>
    <td><b>Reinforcement Learning and Multi-Agent Reinforcement Learning</b>
      <br>Giorgia Ramponi <i>(ETH Zurich)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
      Reinforcement learning (RL) has emerged as a powerful paradigm for enabling intelligent agents to solve sequential decision-making problems under uncertainties. It has witnessed remarkable successes in various domains, ranging from game-playing agents to autonomous systems. However, as real-world challenges become increasingly intricate and interconnected, there is a need to go beyond the single-agent framework. Multi-agent reinforcement learning (MARL), is an extension of RL that enables multiple agents to learn and interact, introducing a new dimension of complexity and sophistication.
      <br><br>This talk delves into the exciting realm of RL and MARL, exploring the foundational principles, recent advancements, and promising applications of these techniques. We begin by introducing the core concepts of RL. Building upon this foundation, we shift our focus to MARL, where multiple agents learn simultaneously, either cooperating or competing with each other. Then, we examine the challenges posed by MARL, including coordination, communication, and the exploration-exploitation dilemma.
    </td>
  </tr>

  <tr class="header">
    <td>15:45 - 16:00</td>
    <td>Contributed Talk</td>
    <td><b>Modeling Accurate Long Rollouts with Temporal Neural PDE Solvers</b>
      <br>Phillip Lippe<sup>1</sup>, Bastiaan S. Veeling<sup>2</sup>, Paris Perdikaris<sup>2</sup>, Richard E Turner<sup>2</sup>, Johannes Brandstetter<sup>2</sup>
      <i>(<sup>1</sup>University of Amsterdam, <sup>2</sup>Microsoft Research AI4Science)</i></td>
  </tr>

  <tr class="header" style="background-color:rgb(240, 240, 240);">
      <!-- <tr> -->
        <td>16:00 - 17:00</td>
        <td></td>
        <td>Poster Session</td>
  </tr>

<!-- </table> -->
<!-- </div> -->