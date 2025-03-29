---
layout: page
permalink: /2023/contributed-talks-II/
title: "IICCSSS 2023: Contributed talks on Wednesday, Sep 13"
description:
nav: false
---

### Deep learning (Room HS001)

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
<td markdown="span">13:30–13:50</td>
<td markdown="span">_Nina Ma_

**Mastering prompt engineering: Unleashing the potential of language models**

Prompt engineering is a crucial aspect of harnessing the power of language models, enabling tailored and effective interactions. This talk delves into the art of creating prompts that yield desired outputs from language models like GPT-3.5. Prompt engineering involves using instructional completion prompts and fine-tuning techniques to enhance model performance. Completion prompts guide the model's responses, while fine-tuning optimizes its behavior. By leveraging fine-tuning, you can expose the model to a broader range of training data than can fit in a prompt, thereby achieving token savings and lower latency rates. Various strategies make prompt engineering more effective. Initiating with clear instructions, specificity, and tone-setting helps frame the context. Breaking tasks into sub-tasks and using probing questions elaborates outcomes effectively. Refining the prompt iteratively and employing additional tactics like delimiters, structured output requests, and temperature parameter modifications further enhance results. Prompt engineering also encompasses zero-shot, one-shot, and few-shot approaches. These methods leverage task descriptions, examples, and fine-tuning, respectively, to make language models more adaptable to specific tasks. However, prompt engineering isn't without challenges. Concepts like prompt leaking, prompt injection, and jailbreaking highlight potential risks associated with unintended model behavior and data privacy. In a world where language models play an increasingly significant role, mastering prompt engineering empowers us to extract meaningful and tailored insights, responses, and content from these powerful AI tools.

</td>
</tr>
<tr>
<td markdown="span">13:50–14:10</td>
<td markdown="span"> _Emanuele Sansone_

**GEDI: GEnerative and DIscriminative training for self-supervised learning**  
Self-supervised learning is a popular and powerful method for utilizing large amounts of unlabeled data, for which a wide variety of training objectives have been proposed in the literature. In this talk, we provide a Bayesian analysis of state-of-the-art self-supervised learning objectives and propose a unified formulation based on likelihood learning. Our analysis suggests a simple method for integrating self-supervised learning with generative models, allowing for the joint training of these two seemingly distinct approaches. We refer to this combined framework as GEDI, which stands for GEnerative and DIscriminative training. Additionally, we demonstrate an instantiation of the GEDI framework by integrating an energy-based model with a cluster-based self-supervised learning model. Through experiments on synthetic and real-world data, including SVHN, CIFAR10, and CIFAR100, we show that GEDI outperforms existing self-supervised learning strategies in terms of clustering performance by a wide margin. We also showcase an application to the neuro-symbolic setting, where GEDI can learn symbolic representations supporting learning and reasoning in the small data regime without the need for additional supervision or costly pre-training steps.

</td>
</tr>
<tr>
<td markdown="span">14:10–14:30</td>
<td markdown="span">_Tobias Hoffmann_

**Local syntactic coherence effects in GPT3 surprisals**

Local syntactic coherence (LSC) effects have shown that the human sentence processor (HSP) can be misguided by a locally embedded sequence of words that could form a sentence in isolation, but must be analyzed differently in the left context of the sentence. These effects have been attributed to temporal local affixes (SOPARS, Tabor_et_al. 2004) and word-wise prediction in recurrent networks (Konieczny_et_al. 2005), among others. Large language models, such as GPT-3+, have impressive capabilities in language comprehension and production. Due to their transformer-based architecture, they should be immune to LSCs. We used the OpenAI API to retrieve the surprisal values for our test items word by word. We then reanalyzed our eye-tracking reading data on sentences with local syntactic coherence embedded in short contexts (citation omitted). Contexts were constructed to draw attention to either the local coherence meaning or the global meaning of the target sentence. While the context manipulation affected the size of the LSC effect, it did not alter GPT-3 surprises in the critical region. While GPT-3 surprise scores were good predictors of total reading time, they did not eliminate LSC effects. We conclude that HSP, unlike transformer-based LLMs, employs mechanisms of local attention.

</td>
</tr>
<tr>
<td markdown="span">14:30–14:50</td>
<td markdown="span">_Sabine Scholle_

**Can we deepfake fMRI data? Unpaired functional alignment for group level neural decoding**

This presentation focuses on the functional alignment of fMRI data, drawing inspiration from Daniel Anthes' thesis titled "BOLD Deepfakes: Functional Alignment for Unpaired Data using Deep Neural Networks" and delving into the foundational work of J.V. Haxby, a renowned researcher in the field of fMRI data analysis (Haxby et al., 2010).

A core challenge for cognitive neuroscience is to find similarity across neural diversity (Churchland, 1998); that is, to find shared or similar neural processes supporting the diversity of individual cognitive experience. Anatomical variability and limited structure-function correspondence across cortex (Paquola et al., 2019) make this goal challenging. To address this challenge, functional alignment is an increasingly popular family of methods for functional magnetic resonance imaging (fMRI) analysis: from the initial introduction of hyperalignment in Haxby et al. 2011, the range of associated methods has grown to include several other linear methods. The presentation explores the innovative approach proposed by Daniel Anthes of "BOLD Deepfakes," leveraging nonlinear deep neural networks to achieve one-shot functional alignment for unpaired data.

Lastly, the presentation outlines potential avenues for further improvement and regularised enhancements in the context of my bachelor thesis. These ideas include exploring novel regularisation techniques to improve the robustness and generalisation of the deep neural network models.

</td>
</tr>
</tbody>
</table>

<br>

### Perception (Room SR003)

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
<td markdown="span">13:30–13:50</td>
<td markdown="span">_Tin Mišić_

**Object tracking using an active stereo visual system**

Object tracking has many applications in robotics, autonomous vehicles, and surveillance. Among all methods, those that use active stereo systems with moving cameras stand out the most. Special emphasis in this paper is given to approaches of active stereo systems that use virtual horopters and log-polar image mapping. An active stereo system is designed that uses ordinary web cameras and servo motors. The cameras and motors are connected with plastic parts printed on a 3D printer, and the entire system runs on a personal computer. The system's real-time performance, ability to track a moving object against various backgrounds, consistency of focus on the object, and accuracy of the estimated object position were tested. Approaches using Cartesian image mapping and those using log-polar mapping were compared. Based on the obtained results, some advantages of log-polar mapping over Cartesian mapping were shown, as well as the drawbacks of the specific implementation.

</td>
</tr>
<tr>
<td markdown="span">13:50–14:10</td>
<td markdown="span">_Niranjan Rajesh_

**Investigating brain-like CNNs and their consequences**

​​Recent research in Neuro-inspired Machine Learning in the visual domain has resulted in CNNs that are modelled after the primate visual systems. These are usually done through structural or representational alignment of the CNNs with their primate brain counterparts. These models claim to be behaviourally comparable to human visual intelligence and correlations were found in areas like robustness to visual adversarial attacks. My work will further investigate this consequence of primate visual system alignment in CNN i.e. the connection between brain likeness and adversarial robustness.

</td>
</tr>
<tr>
<td markdown="span">14:10–14:30</td>
<td markdown="span">_Viktor Bublitz_

**Monitoring nociception in the frontal EEG**

Monitoring pain and nociception in critical care patients who cannot self-report presents a substantial challenge. Clinical signs frequently lack both sensitivity and specificity, and existing technical methodologies come with inherent limitations. Accurate predictions of nociception could optimize the administration of analgesia ahead of procedures like endotracheal suctioning. In my doctoral research, I explored strategies to quantify nociception and anticipate reactions to painful interventions in intensive care settings. We particularly examined electroencephalogram (EEG) correlates that either precede or occur simultaneously with behavioral responses to noxious stimuli, such as endotracheal suctioning. Our results showed an elevation in power within the 2-5Hz band that both anticipated and matched these responses, coupled with a decrease in the alpha-band power during these events. Such patterns could be associated with the processing of noxious stimuli and might pave the way for refining and individualizing analgesia in patients unable to articulate their pain. Notably, other power bands and ratios did precede the responses in our study, but these could be attributed more to the concurrent sedation level and arousal than to nociception. Deciphering these intertwined effects is the motivation behind the research that I am currently conceptualizing for subsequent investigations.

</td>
</tr>
<tr>
<td markdown="span">14:30–14:50</td>
<td markdown="span">_Revan Rangotis_

**Drift-diffusion modelling reveals distinct decision processes for 3D and global motion stimuli in humans and macaques**

Neurophysiology localised perceptual decision signals for binocular 3D depth and motion stimuli to visual area V5/MT. Drift diffusion modelling (DDM) is widely used to investigate the underlying decision-making processes by simulating decisions as noisy evidence-accumulation which terminates once a threshold is crossed. Two key questions remain unexplored: 1. To what extent are modelled decision processes affected by the visual stimulus (here 3D depth vs. motion) and by the effector for the response (hand vs. saccades)? 2. Are the modelling parameters comparable between monkeys and humans? To answer these questions, we tested 2 male monkeys (Macaca mulatta) and 20 humans on different stimulus/effector combinations in a 2-alternative forced-choice task (2AFC). Stimuli were a 3D structure-from-motion cylinder or a random dot kinematogram (RDK), requiring perceptual decisions about binocular depth or direction of motion, respectively. Effectors comprised hand and saccadic eye movements. Linear discriminant analysis (LDA) revealed a strong separation by stimulus type but not for the effector for the human data (p<0.001, ROC analysis). Nearly identical clustering was observed for the monkey data when it was projected onto the same space with almost complete overlap. We conclude that DDM reveals distinct brain processes for perceptual decisions about visual motion and binocular 3D stimuli in humans and macaques, although perceptual signals for both have been localised to the same brain area. We found no distinction between hand and eye movement responses in either species.

</td>
</tr>
</tbody>
</table>
