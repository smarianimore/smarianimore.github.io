---
title: "Research themes"
permalink: /research/
toc: true
toc_icon: "fas fa-book-open"
---

## Overview

My research activity revolves around two prominent themes: how to best **coordinate** an ensamble of digital entities towards a systemic goal, and how to provide **"intelligent" support** to human activities through digital tools.

As such, I'm **doing** (or did) research activities in the following fields:
 - **learning to coordinate** in multi-agent systems
 - **argumentation-based coordination**
 - **causal reasoning** in multi-agent systems
 - self-organising mechanisms and systems
 - socio-cognitive models of behaviour and interaction to enhance coordination mechanisms
 - logic programming as a form of "Edge intelligence"
 - blockchain technologies and smart contracts for distributed and decentralised coordination
 - application of the above to pervasive systems such as the **Internet of Things**
 - application of the above to socio-technical systems such as information systems
 - **decision support systems in healthcare** applications for patient empowerment 
 - decision support systems in healthcare applications for clinical practice 


## Learning to coordinate

<figure style="width: 50%" class="align-left">
  <a href="https://doi.org/10.1109/PerComWorkshops51409.2021.9431003"><img src="{{ site.url }}{{ site.baseurl }}/assets/comorea.png" alt="A first approach to learning to coordinate with Bayesian networks."></a>
  <figcaption>A first approach to learning to coordinate with Bayesian networks. Adjacent rooms learn to coordinate window operation to set luminosity.</figcaption>
</figure> 

**Problem**: Agents in multi-agent systems are usually equipped with *pre-defined interaction* means (e.g. messaging abilities)
and *fixed coordination protocols* to abide to.
This cannot cope with highly dynamic scenarios demanding for adaptation.

**Solution**: *Let agents learn* how to interact and coordinate at best.

**Goal**: *Improve agents adaptation* abilities also along the interaction dimension of computation.

**Methods**: Transfer (multi-agent) *reinforcement and Bayesian learning* techniques 
to the multi-agent domain and across coordination tasks.

**Reference publications**:
 - [Developing a "Sense of Agency" in IoT Systems: Preliminary Experiments in a Smart Home Scenario](https://doi.org/10.1109/PerComWorkshops51409.2021.9431003) (paywall, [ask me a copy](mailto:stefano.mariani@unimore.it))
 - [Argumentation-Based Coordination in IoT: A Speaking Objects Proof-of-Concept](https://doi.org/10.1007/978-3-030-34914-1_17) (paywall, [ask me a copy](mailto:stefano.mariani@unimore.it))

## Coordination in socio-technical systems

<figure style="width: 50%" class="align-left">
  <a href="https://doi.org/10.1016/j.scico.2019.102317"><img src="{{ site.url }}{{ site.baseurl }}/assets/integration.png" alt="The two approaches to design coordination in socio-technical systems."></a>
  <figcaption>The two approaches to design coordination in socio-technical systems.</figcaption>
</figure> 

**Problem**: *Socio-technical systems*[^1] cannot be coordinated with the same mechanisms and techniques used for purely technical systems.

**Solution**: Consider *socio-cognitive* theories of action and interaction while designing such coordination mechanisms and techniques.

**Goal**: *Improve* system coordination outcomes, however defined on a functional or non-functional perspective.

**Methods**: Exploit humans social interactions and cognitive stance to *adapt* system behaviour.

**Reference publications**:
 - [Coordination in Socio-technical Systems: Where are we now? Where do we go next?](https://doi.org/10.1016/j.scico.2019.102317) (paywall, [ask me a copy](mailto:stefano.mariani@unimore.it))
 - [An Argumentation-Based Perspective Over the Social IoT](https://rdcu.be/caUtN)
 - [Coordination of Complex Sociotechnical Systems: Self-organisation of Knowledge in MoK](https://doi.org/10.1007/978-3-319-47109-9) (book)

[^1]: According to my own interpretation, briefly: *systems featuring "humans-in-the-loop" which are not merely users but actively contribute in the system's own functioning*. For the original definition see [Trist](https://www.lmmiller.com/blog/wp-content/uploads/2013/06/The-Evolution-of-Socio-Technical-Systems-Trist.pdf) and [Baxter-Sommerville](https://ieeexplore.ieee.org/abstract/document/8147295) (paywall).

## Coordination in pervasive systems

<figure style="width: 50%" class="align-left">
  <a href="https://doi.org/10.1007/978-3-030-34914-1_17"><img src="{{ site.url }}{{ site.baseurl }}/assets/speaking.jpeg" alt="Speaking objects endow IoT devices with goal-oriented behaviour and dialogical interaction."></a>
  <figcaption>New abstraction layers and rich forms of interaction are needed to cope with IoT scenarios increasing complexity.</figcaption>
</figure>

**Problem**: Coordination in pervasive systems cannot be done by individually and imperatively programming each partecipating device: the levels of *abstraction* and *autonomy* are too low.

**Solution**: Consider ways to let devices figure out how to participate to a systemic *goal* given by designer or arising dynamically according to *context*.

**Goal**: Increase system's *robustness* through device and system autonomy.

**Methods**: Endow devices with *learning* capabilities and *goal-oriented* behaviour, and the system with rich forms of interaction (e.g. *argumentation*).

**Reference publications**:
 - [Coordinating Distributed Speaking Objects](https://doi.org/10.1007/978-3-030-34914-1_17) (paywall, [ask me a copy](mailto:stefano.mariani@unimore.it))
 - [Spatial Tuples: Augmenting Reality with Tuples](https://onlinelibrary.wiley.com/doi/abs/10.1111/exsy.12273) (paywall, [ask me a copy](mailto:stefano.mariani@unimore.it))

## Decision support systems in healthcare

<figure style="width: 50%" class="align-left">
  <a href=""><img src="{{ site.url }}{{ site.baseurl }}/assets/dss.png" alt="A novel decision support system architecture helps scientists and clinicians collaboration."></a>
  <figcaption>The novel decision support system architecture designed during the <a href="https://connecare.eu">Connecare project</a>.</figcaption>
</figure>

**Problem**: Designing decision support systems for the healthcare domain is difficult for many reasons, amongst which
    (1) support *portability* of the machine learning *pipeline*
    (2) optimise the trade-off between well-assessed *best practices* and *patient-specific data*
    (3) guarantee *interpretable* suggestions.

**Solution**: Respectively
    (1) rely on well-assessed *software engineering* principles
    (2) design a coherent conceptual and technological framework for the broad domain of so-called *cognitive systems*
    (3) adopt transparent and *explainable* algorithms.

**Goal**: Extend *adoption* and improve *performance* of decision support systems in healthcare

**Methods**: Again, respectively
    (1) rely on *standards* such as [PFA](http://dmg.org/pfa/) for machine learning pipelines representation and sharing and prefer *web* technologies for deployment
    (2) integrate the *BDI* agent architecture with *machine learning* methods
    (3) prefer explainable algorithms or adopt *argumentation*

**Reference publications**:
 - [Developing an ML pipeline for asthma and COPD: The case of a Dutch primary care service](https://doi.org/10.1002/int.22568)
 - [Augmenting BDI Agency with a Cognitive Service: Architecture and Validation in Healthcare Domain](https://doi.org/10.1007/s10916-021-01780-1) (paywall, [ask me a copy](mailto:stefano.mariani@unimore.it))
 - [Risk Prediction as a Service: a DSS architecture promoting interoperability and collaboration](https://doi.org/10.1109/CBMS.2019.00069) (paywall, [ask me a copy](mailto:stefano.mariani@unimore.it))
