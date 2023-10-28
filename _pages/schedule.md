---
layout: page
permalink: /schedule/
title: Schedule
description: This workshop will be held in-person at Neurips 2023 at the New Orleans Ernest N. Morial Convention Center on December 16th 2023. The session will cover invited talks, contributed talks, and posters. The schedule will be announced here soon. The schedule in Eastern Standard Time (GMT-5) can be found below. <b>(Click the talks to see their abstracts)</b>
nav: true
nav_order: 2
---

<br>

<div>
<table class="table" id="standings" style="border-collapse:collapse">
<tr class="header" style="background-color:rgb(215, 215, 215); border-top: 1pt solid white; border-bottom: 1pt solid black;">
        <th style="border-top-left-radius: 10px; width: 15%">EST</th>
        
        <th style="width: 15%">Type</th>
        <th style="width: 70% border-top-right-radius: 10px;">Title & Speakers</th>
        
      </tr>
      <tr>
  <tr class="header" style="cursor: pointer">
    <td>9:00 - 10:00</td>
    <td>Plenary Talk</td>
    <td><b>TBC</b><br>
    Felix Otto<i> (Max Planck Institute)</i></td>
  </tr>
    <td></td>
    <td></td>
    <td>TBC
    </td>
  </tr>

  <tr class="header" style="background-color:rgb(240, 240, 240);">
      
        <td>10:00 - 10:30</td>
        <td></td>
        <td>Coffee break</td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>9:45 - 10:30</td>
    <td>Invited Talk</td>
    <td><b>Unbalanced Optimal Transport: Efficient solutions for outlier-robust machine learning</b><br>Laetitia Chapel<i> (Institute Agro Rennes-Angers)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
      Optimal transport (OT) has become a powerful tool for calculating distances (a.k.a. Wasserstein or earth mover's distances) between empirical distribution of data thanks to efficient computational schemes that make the transport computation tractable. The OT problem aims to find a transportation map that preserves the total mass between two probability distributions, requiring their mass to be equal. However, this requirement can be overly restrictive in certain applications such as color or shape matching, where distributions may have arbitrary masses and/or when only a fraction of the total mass has to be transported. This also happens when the source and/or target distributions are contaminated by outliers; in such cases, one might want to exclude these outliers from the transportation plan.  Unbalanced Optimal Transport adresses the problem of removing some mass from the problem by relaxing marginal conditions (using weighted penalties in lieu of equality). In this talk, we will review efficient algorithms that can be devised in this context, particularly focusing on formulations where no additional regularization is imposed on the OT plan. 
    </td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>15:00 - 15:15</td>
    <td>Contributed Talk</td>
    <td><b>TBC</b>
      <br>Zoe Piran<i> (Hebrew University of Jerusalem) </i></td>
  </tr>
    <td></td>
    <td></td>
    <td>
    TBC
    </td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>10:45 - 11:00</td>
    <td>Contributed Talk</td>
    <td><b>Accelerating Motion Planning via Optimal Transport</b>  <br>An Le, Georgia Chalvatzaki, Armin Biess, Jan Peters<i> (TU Darmstadt and Ben-Gurion University of the Negev) </i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
      Motion planning is still an open problem for many disciplines, e.g., robotics, autonomous driving, due to issues like high planning times that hinder real-time, efficient decision-making. A class of methods striving to provide smooth solutions is gradient-based trajectory optimization. However, those methods might suffer from bad local minima, while for many settings, they may be inapplicable due to the absence of easy access to objectives-gradients. In response to these issues, we introduce Motion Planning via Optimal Transport (MPOT) - a \textit{gradient-free} method that optimizes a batch of smooth trajectories over highly nonlinear costs, even for high-dimensional tasks, while imposing smoothness through a Gaussian Process dynamics prior via planning-as-inference perspective. To facilitate batch trajectory optimization, we introduce an original zero-order and highly-parallelizable update rule -- the Sinkhorn Step, which uses the regular polytope family for its search directions; each regular polytope, centered on trajectory waypoints, serves as a local neighborhood, effectively acting as a trust region, where the Sinkhorn Step ``transports'' local waypoints toward low-cost regions. We theoretically show that Sinkhorn Step guides the optimizing parameters toward local minima regions on non-convex objective functions. We then show the efficiency of MPOT in a range of problems from low-dimensional point-mass navigation to high-dimensional whole-body robot motion planning, evincing its superiority compared with popular motion planners and paving the way for new applications of optimal transport in motion planning.
    </td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>11:00 - 11:30</td>
    <td>Invited Talk</td>
    <td><b>Learning on graphs with Gromov-Wasserstein: from unsupervised learning to GNN</b><br> Rémi Flamary<i> (École Polytechnique)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
      In recent years the Optimal Transport (OT) based Gromov-Wasserstein (GW) divergence has been investigated as a similarity measure between structured data expressed as distributions typically lying in different metric spaces, such as graphs with arbitrary sizes. In this talk, we will address the optimization problem inherent in the computation of GW and some of its recent extensions, such as Entropic, Fused and semi-relaxed GW divergences. Next we will illustrate how these OT problems can be used to model graph data in learning scenarios such as graph compression, clustering, classification and structured prediction. Finally we will present a recent application of GW distance as a novel pooling layer in Graph Neural Networks.
    </td>
  </tr>

  <tr class="header" style="background-color:rgb(240, 240, 240);">
      
        <td>12:00 - 13:30</td>
        <td></td>
        <td>Poster Session &amp; Lunch</td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>13:30 - 14:00</td>
    <td>Invited Talk</td>
    <td><b>Neural Optimal Transport</b>
      <br>Brandon Amos<i> (Meta AI)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
    TBC
    </td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>14:00 - 14:30</td>
    <td>Invited Talk</td>
    <td><b>TBC</b>
      <br>Arnaud Doucet<i> (University of Oxford)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
      TBC
    </td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>14:30 - 15:00</td>
    <td>Invited Talk</td>
    <td><b>Sketched Wasserstein Distances</b>
      <br> Florentina Bunea<i> (Cornell University)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
      The Wasserstein distance between mixing measures has come to occupy a central place in the statistical analysis of mixture models. We give the first axiomatic justification of its usage as a canonical measure of discrepancy between any mixture distributions. Inference for the Wasserstein distance between mixing measures is generally difficult in high dimensions. Specializing to discrete mixtures arising from topic models, we offer the first minimax lower bound on estimating the distance between pairs of mixing measures in this model class. This reveals regimes under which fast estimation of the distance between mixing measures can be expected, even if the ambient dimension of the mixture distributions is large. In such regimes, we develop fully data-driven inferential tools that allow us to obtain the first asymptotically valid confidence intervals for the Wasserstein distance between mixing measures, in topic models. Our results apply to potentially sparse mixtures of potentially sparse high-dimensional discrete probability distributions, and are illustrated via an example on movie reviews from the IMDb data set.
    </td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>15:00 - 15:15</td>
    <td>Contributed Talk</td>
    <td><b>Provably Fast Finite Particle Variants of SVGD via Virtual Particle Stochastic Approximation</b>
      <br>Aniket Das, Dheeraj Nagaraj<i> (Google)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
  SVGD is a popular particle-based variational inference algorithm with well studied mean-field dynamics. However, its finite-particle behavior is far less understood. Our work introduces the notion of virtual particles to develop novel stochastic approximations of mean-field SVGD dynamics in the space of probability measures, that are exactly realizable using finite particles. As a result, we design two computationally efficient variants of SVGD (VP-SVGD and GB-SVGD) with provably fast finite-particle convergence rates. Our algorithms are specific random-batch approximations of SVGD which are computationally more efficient than ordinary SVGD. We show that the $n$ output particles of VP-SVGD and GB-SVGD, run for $T$ steps with batchsize $K$, are as good as i.i.d samples from a measure whose Kernel Stein Discrepancy to the target is at most $O(\frac{d^1/3}{(KT)^{1/6}})$ under standard assumptions. We prove similar results under a mild growth condition on the score function, which is weaker than the assumptions of prior works. Our convergence rates for the empirical measure (of the particles output by VP-SVGD and GB-SVGD) to the target distribution enjoys a **double exponential improvement** over the best known finite-particle analysis of SVGD. Furthermore, our results give the **first known polynomial oracle complexity in dimension**, completely eliminating the curse of dimensionality exhibited by previously known finite-particle rates.
    </td>
  </tr>


  <tr class="header" style="cursor: pointer">
    <td>15:15 - 15:30</td>
    <td>Contributed Talk </td>
    <td><b>Towards a Statistical Theory of Learning to Learn In-context with Transformers Talk</b>
      <br>Youssef Mroueh<i> (IBM)</i> </td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
Classical learning theory focuses on supervised learning of functions via empirical risk minimization where labeled examples for a particular task are represented by the data distribution experienced by the model during training. Recently, in-context learning emerged as a paradigm shift in large pre-trained models. When conditioned with few labeled examples of potentially unseen tasks in the training, the model infers the task at hand and makes predictions on new points. Learning to learn in-context on the other hand, aims at training models in a meta-learning setup that generalize to new unseen tasks from only few shots of labeled examples. We present in this paper a statistical learning framework for the problem of in-context meta learning and define a function class that enables it. The meta-learner is abstracted as a function defined on the cross product of the probability space (representing context) and the data space. The data distribution is sampled from a meta distribution on tasks. Thanks to the regularity we assume on the function class in the Wasserstein geometry, we leverage tools from optimal transport in order to study the generalization of the meta learner to unseen tasks. Finally, we show that encoder transformers exhibit this type of regularity and leverage our theory to analyze their generalization properties.
    </td>
  </tr>

  <tr class="header" style="background-color:rgb(240, 240, 240);">
      
        <td>15:30 - 16:00</td>
        <td></td>
        <td>Coffee break</td>
  </tr>


  <tr class="header" style="cursor: pointer">
    <td>16:00 - 16:30</td>
    <td>Invited Talk</td>
    <td><b>TBC</b>
      <br>Smita Krishnaswamy<i> (Yale University)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
    TBC
    </td>
  </tr>

  <tr class="header" style="cursor: pointer">
    <td>16:30 - 17:00</td>
    <td>Invited Talk</td>
    <td><b>Proximal algorithms for sampling and variational inference</b>
      <br>Sinho Chewi<i> (Institute of Advanced Study)</i></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>
    Probabilistic problems which involve the non-smooth entropy functional benefit from the design of proximal algorithms over the Wasserstein space. This paradigm will be illustrated for sampling via the proximal sampler, and for Gaussian variational inference.
    </td>
  </tr>

  <tr class="header" style="background-color:rgb(240, 240, 240);">
      
        <td>17:00 - 17:15</td>
        <td></td>
        <td>Closing remarks</td>
  </tr>

  <tr class="header" style="background-color:rgb(240, 240, 240);">
      
        <td>17:15 - ...</td>
        <td></td>
        <td>Poster Session and hangout</td>
  </tr>


<!-- </table> -->
<!-- </div> -->