---
layout: post
published: true
title: Brain Computer Interfaces (BCI)
---

![_config.yml]({{ site.baseurl }}/images/bci_block.png)

BCI is a system that controls a robot, computer, etc. by brain activities. It contains four steps as shown in the block diagram; obtaining brain signals, processing signals, and filtering noise, extracting informative features to classify actions, and controlling a device. The system should be as fast as possible so that subjects immediately see the result. Therefore, BCI systems are able to do fast and accurate real-time processing, analyzing, and classifying. There are three types of BCIs based on stimuli types and tasks given to the participant; active, reactive, and passive.

Active BCI is a system that modifies brain responses while a participant performs an explicit task without any stimulus. For instance, in the motor imagery BCI systems, brain activities collected when the participant imagine to perform a motor task. Differently, in reactive BCI the participant exposed to an stimuli and brain activities are collected while the participant performs the task with given stimuli. P300 speller can be example of reactive BCIs. Finally in the passive BCI, participant doesn’t perform any specific task but their mental states, emotional states are detected from brain activities. 

![_config.yml]({{ site.baseurl }}/images/bci_types.png){width=250}

### Recording Brain Activities:

Brain activities can be recorded in an invasive and non-invasive ways. Invasive and semi-invasive technologies such as ECoG, implant, etc. give better resolutions compared to non-invasive methods but they are required an operation to place the technology in or on the cortex. 

There are various ways to record brain activities non-invasively. Functional imagining techniques such as fMRI, SPECT, PET has good spatial resolutions and time resolution is acceptable. However, these techniques are expensive in terms of logistic and price. Similarly, MEG which measures the magnetic field of the brain is an expensive technique. On the other hand, Near-Infrared Spectroscopy (NIRS, fNIR) technologies are cheaper in comparison to previously mentioned techniques, and additionally, it is good to avoid artifacts in measurements but time resolution is too slow. In comparison to these technologies, EEG is a cheap technology and easy to use. Moreover, wireless EEG device solutions have been developed in order to increase the applicability area with developing technologies.

### Generators of EEG:

Neurons communicate each other using electrical and chemical signals. Messages travel through neuron as electrical signal which is known as action potential. When it reaches to the dentrits of neuron the message is transformed from action potential to chemical signals by releasing neurotransmitters. The release of these chemicals trigger an action potential in the following neuron. So that the message is conveyed to the next neuron. 

When the information flow through the axon, a current is occurred and accordingly potential and electrical field arise. 

![_config.yml]({{ site.baseurl }}/images/generator_eeg.png){width=250}

One neuron generate small amount of electrical activity. However when a group of neurons are simultaneously active the electrical activity will be enough to be measured. Electroencephalogram (EEG) which is discovered by the German psychiatrist Hans Berger in 1929, is a technology to measure the potential using the electrodes which are placed on the scalp. The basic components of the EEG device are the electrodes, the signal amplifier and the computer to monitor signal. Electrodes are placed on the scalp in a certain order. A conductive gel is used to provide conductivity between the scalp and the electrodes. The pyramidal cells which are parallel with each other and normal to the cortical surface are suggested to be the generators of the EEG. When the group of neurons are activated, the signal is propagated through scalp and detected by electrodes. The measured electrical potential by the electrodes are send to the amplifier.


References:
1. Vidal, JJ (1973). "Toward direct brain-computer communication". Annual review of biophysics and bioengineering 2: 157–80.
2. Chang S. Nam; Anton Nijholt; Fabien Lotte (2018). “Brain–Computer Interfaces Handbook: Technological and Theoretical Advances”, CRC Press pp.1-33.
3. [https://www.sciencedirect.com/science/article/pii/S1110866515000237](https://www.sciencedirect.com/science/article/pii/S1110866515000237)
4. ****Bidirectional brain-computer interfaces**** [https://pubmed.ncbi.nlm.nih.gov/32164851/](https://pubmed.ncbi.nlm.nih.gov/32164851/)
