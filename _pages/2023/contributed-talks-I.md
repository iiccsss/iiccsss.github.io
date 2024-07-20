---
layout: page
permalink: /2023/contributed-talks-I/
title: 'IICCSSS 2023: Contributed talks on Tuesday, Sep 12'
description: 
nav: false
---

### Computational modeling of cognition (Room HS001)

<table class="table table-bordered table-striped">
<colgroup>
<col width="15%" />
<col width="85%" />
</colgroup>
<thead>
<tr class="header">
<th>Time</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td markdown="span">13:50–14:10</td>
<td markdown="span">_Surabhi S Nath_   

**Inside the grid, yet outside the box: Computational investigations of human creativity using pixel patterns**   

Creativity is an important, yet elusive, human characteristic. Despite strides in understanding creativity as a cognitive ability, there is a paucity of computational studies associated with it. Our work aims to fill this gap with a computational investigation of the mechanisms underlying little-c creative artistic work, from a reward learning perspective. We define tractably constrained experimental settings involving binary 5x5 pixel patterns. We develop a taxonomy with two types of creativity – static and dynamic, crossed with two modes of creativity – evaluation and production, resulting in four experimental conditions for investigation. We outline various possible underlying computational mechanisms such as (1) an immediate value function for static creativity, (2) a long-run value function for dynamic creativity, (3) the history-dependent nature of evaluation and (4) a search process guiding the production. We design a series of behavioural experiments based on our taxonomy and propose directions for data analyses. Through this we aim to enrich the computational understanding of product and process creativity.
</td>
</tr>
<tr>
<td markdown="span">14:10–14:30</td>
<td markdown="span">_Yuki Tsukamura_   

**Cognitive modeling of the latent scope bias in causal explanations**   

Latent scope bias refers to the tendency to prefer explanations that do not predict unobservable events over those that do in causal explanations. The occurrence of latent scope bias is believed to be due to an underestimation of the occurrence probability of unobservable events and Bayesian probability calculations using it. However, it remains unclear whether it is based on Bayesian probability calculations. Therefore, we employed subjective probability response data and compared this process with alternative models through Bayesian modeling. As a result, a cognitive model based on "subjective utility" was favored over Bayesian probability calculations, suggesting that the process of evaluating explanations leading to the latent scope bias is not based on Bayesian probability calculations.   
Furthermore, while latent scope bias was observed in the aggregated data from all participants, it was not necessarily a large effect, and it was shown that it did not occur in a certain number of the participants when looked at individually. In other words, a certain number of normative respondents answered values corresponding to the normative solution with relatively small variance. From these findings, it is also suggested that the latent scope bias may appear to arise in the entire group due to a certain number of people with bias.
</td>
</tr>
<tr>
<td markdown="span">14:30–14:50</td>
<td markdown="span">_Ryutaro Mori_   

**How real-time interaction aids collaboration under the temptations to free ride**  

Understanding how human groups collaborate successfully, even when individuals may be tempted to free ride, is a fundamental question in the social sciences. While conventional models such as game theory often distill socially dependent situations into simplified "staged settings" in which agents choose actions only at fixed timings, real-world collaborations are typically marked by real-time interactions in which decisions are made instantaneously and communicated immediately. Our research posits that such real-time interactions facilitate collaboration by naturally creating a sequence of cooperative actions and reactions. Specifically, when decision timings are sequential rather than simultaneous, each decision becomes a response to prior ones, mitigating much of the social unpredictability and aiding coordination. Moreover, if agents themselves can decide when to act, the earlier/precedent decisions could lean more towards cooperation than if they were random; cooperative agents might decide early to encourage reciprocation, while competitive agents might delay revealing their intentions. We formulate these ideas using a classic prisoner’s dilemma game and experimentally verify several key behavioral regularities. In the talk, I would particularly love to discuss how computational modeling can be employed to decipher real-time strategic interactions.
</td>
</tr>
</tbody>
</table>
<br>

### Neuroscience (Room SR003)

<table class="table table-bordered table-striped">
<colgroup>
<col width="15%" />
<col width="85%" />
</colgroup>
<thead>
<tr class="header">
<th>Time</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td markdown="span">13:50–14:10</td>
<td markdown="span">_Jonas Elpelt_   

**The interplay of synaptic remodeling, forgetting and creativity**   

Why do we forget? The fascinating phenomenon of forgetting is often associated with pathologies such as dementia, but forgetting can have crucial positive effects for behavioral flexibility and can enforce more creative abilities. Recently, it has been shown that forgetting involves biological mechanisms that actively and selectively ‘erase’ memory information and can lead to changes on different organizational levels (synapses, neurons, networks, behavior). In a joint German-Israeli project we want to study the change of representations under continuous synaptic reconfiguration in vitro, in vivo and in silico models. By investigating spontaneous dynamics in network configurations we want to explore the possibility that spontaneous changes in synaptic connection might drive forgetting. For this purpose we use the behavioral readout of forgetting and adaptive learning to construct a theoretical framework to link forgetting and intrinsic synaptic dynamics. Finally we want to establish a possible relationship of forgetting, increased synaptic plasticity and creativity in both biological and artificial neural networks.
</td>
</tr>
<tr>
<td markdown="span">14:10–14:30</td>
<td markdown="span">_Ralf Krüger_   

**Comparison of preprocessing of EEG hyperscanning data with different automated algorithms**   

In the context of naturalistic, out-of-lab brain imaging situations, the data quality is often not optimal. I am currently comparing several preprocessing algorithms (Artificial Subspace Reconstruction, global and local Autoreject and Automated ICA) on their ability to clean data obtained in an neurofeedback art exhibit. Two participants were shown a sculpture while simultaneously measuring inter-brain synchronisation with an 8-channel EEG system as part of the exhibit Brain Palace in the STATE Studio Berlin. I will present the results of this experiment as well as standard preprocessing methods on the power spectrum density of the subjects and several connectivity metrics. Since the connectivity metrics are very sensitive to changes in the frequency domain of the signals, care has to be taken that within subject pairs the signal is processed in similar ways, which needs to be accounted for in artifact removal. I used the Hyperscanning Pipeline for Python HyPyP to perform most of the analysis, but implemented some additional functionality to visualize the intermediate results and measure connectivity metrics not yet specified in the pipeline. I will also present a signal-to-noise ratio and its limitations for determining signal quality in this context.
</td>
</tr>
<tr>
<td markdown="span">14:30–14:50</td>
<td markdown="span">_Guillaume Pourcel_   

**Skill homeostasis: Toward a model of ultra-robust behavior**   

In this talk, I'll present my current research directions in modeling the impressive phenomenon of ultra-robust behavior in humans, focusing on two intriguing cases: sensory substitution and inverted vision. Sensory substitution demonstrates the brain's rapid adaptation to distorted sensory inputs, such as retranslating visual information into tactile sensations through an array of vibrators. Inverted vision studies are concerned with our abilities to adapt to the disruption of our visual processing by presenting the world upside-down. Both cases showcase remarkable resilience in the face of diverse perturbations.   

Conventionally, explanations for robust behavior have rested upon the premise of a meta-learning framework, wherein evolution optimizes learning rules capable of coping with the variability of environments experienced during phylogeny. We propose an alternative hypothesis that suggests that the brain employs a homeostatic mechanism to regulate skills when faced with unprecedented disturbances. Drawing inspiration from computational neuroscience and population dynamics, we view the brain as a nonlinear dynamical system with distinct skill-related patterns encoded in the activity of neural populations.   

Central to our model is the identification of skill-specific linear subspaces, acting as references for regulation. When significant perturbations occur, the brain seeks equilibrium by readjusting its internal dynamics. This novel perspective not only addresses robustness in a volatile environment but also unveils a mechanism for the brain to restore stability amidst unforeseen challenges.
</td>
</tr>
</tbody>
</table>


