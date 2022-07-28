---
title: "Student? Look no further!"
permalink: /students/
toc: true
toc_icon: "fas fa-book-open"
---

## Overview

If you like **programming**, **machine learning**, **data analysis**, tinkering with **Internet of Things** devices, or mess around with **networked computers**, you're in the right place :)

Here below you can find a list of proposed "activities", as well as a record of concluded thesis and internships.
Each ctivity may become a **thesis or internship** depending on the that goal we, together, decide to achieve, and on the expected effort required to achieve it.
Activities are roughly divided in categories, representing the research topic they are meant to deal with: if you find an appealing topic, but not a satisfactory proposal therein, [contact me](mailto:stefano.mariani@unimore.it) and we'll discuss your own proposals :)
Finally, the numbers you see both in categories and proposals of activities therein **are not** a ranking of importance or a priority score, but merely a **reference number** to ease communications.

If you find something appealing to you, here is the "protocol" that I usually follow for setting up the thesis or internship:

1. You [contact me](mailto:stefano.mariani@unimore.it) to tell me which categories or activities you find appealing
2. We set up a quick meeting (either virtual or in presence) where I better describe the topic or proposal, giving you an overview and some reference examples of activities
3. **If you are still interested**, I send you some reading material to give you an even better idea of the tasks to carry out as part of the proposed activity
4. **If you are still interested**, you [contact me](mailto:stefano.mariani@unimore.it) to formally set up the internship or thesis

**Until step (4)**, you are not expected to finish the activity: it's just you trying to understand if you will like such activity as thesis or internship :)

## 1) Reinforcement learning in multiagent systems

Mchine Learning (ML) is now pervasive in our everyday lives (Google translate, Siri speech recognition, etc.) and successfully applied in many application domains where a software (an *agent*) needs to learn to do something.
However, modern software is rarely a monolithic entity that does everything by itself, rather a collection of indipendent services that *collaborate* to carry out a given task (e.g. Siri is connected to your Calendar, weather service, apps, etc.).
Modern software is thus usually a *multiagent system* where multiple software entities need to *coordinate* to achieve a given goal.

Various forms of learning are used in multiagent systems (MAS) to let agents *individually* learn to accomplish a task, or to recognise a given state of the world.
Instead, letting agents *learn how to interact socially* is yet underexplored in scientific literature, but a promising topic to let multiagent systems self-organise to achieve a shared or system goal.

The following activities unfold within this theme.

**Activities**

 1. apply [reinforcement learning](https://towardsdatascience.com/the-ultimate-beginners-guide-to-reinforcement-learning-588c071af1ec) to [NetLogo](https://ccl.northwestern.edu/netlogo/) multi-agent system models for **self-organisation** such as [slime mold aggregation](http://www.netlogoweb.org/launch#http://www.netlogoweb.org/assets/modelslib/Sample%20Models/Biology/Slime.nlogo), [ant foraging](http://www.netlogoweb.org/launch#http://www.netlogoweb.org/assets/modelslib/Sample%20Models/Biology/Ants.nlogo), [prey-predator](http://www.netlogoweb.org/launch#http://www.netlogoweb.org/assets/modelslib/Sample%20Models/Biology/Wolf%20Sheep%20Predation.nlogo). The goal is to let agents learn to communicate / cooperate / coordinate to achieve a shared goal.
 2. apply [curriculum learning](https://hackmd.io/@FtbpSED3RQWclbmbmkChEA/Sy0IVj8Ju#Introduction) (read only the intro) in the same models
 3. apply [transfer learning](https://www.seldon.io/transfer-learning#:~:text=Transfer%20learning%20means%20taking%20the,to%20solve%20a%20specific%20task.) (just get the idea) in the same models
 4. apply [reinforcement learning](https://towardsdatascience.com/the-ultimate-beginners-guide-to-reinforcement-learning-588c071af1ec) to **cooperative driving** scenarios (such as intersection crossing by self-driving vehicles) in custom simulators such as [highway-env](https://highway-env.readthedocs.io/en/latest/index.html), [Flow](https://flow.readthedocs.io/en/latest/), or [SUMO-RL](https://github.com/LucasAlegre/sumo-rl). The goal is to let agents (vehicles, or traffic lights, or intersection controllers) learn how to drive in traffic.
 5. adapt existing multi-agent learning environments to learn how to communicate / cooperate / coordinate to achieve better results. Examplary environments (like "games"):

    * [PettingZoo MAgent](https://www.pettingzoo.ml/magent)
    * [PettingZoo MPE](https://www.pettingzoo.ml/mpe)
    * [PettingZoo StugHunt](https://github.com/NullDefault/Gym-Stag-Hunt)
    * [PettingZoo Social dilemmas](https://github.com/eugenevinitsky/sequential_social_dilemma_games)
    * [PettingZoo CookingZoo](https://github.com/DavidRother/gym-cooking) (inspired to popular game [Overcooked](https://store.epicgames.com/it/p/overcooked)!)
    * [DeepMind OpenSpiel](https://github.com/deepmind/open_spiel/blob/master/docs/games.md) (only some of them, such as Hanabi, Pathfinding, Routing game)
    * [Google Football](https://ai.googleblog.com/2019/06/introducing-google-research-football.html) (yes, you can get a grasp of what developing the AI for games like PES and FIFA may look like!)

**Concluded**

 - Riccardo Santi. *"Esperimenti di transfer learning per reti neurali con robot mobili."* Bachelor degree in Management Engineering, 2021/2022
 - Matteo Sigolotto. *"Apprendimento autonomo in sistemi IoT mediante Reti Bayesiane."* Master degree in Computer Science Engineering, 2018/2019

## 2) Causal discovery and inference in the Internet of Things

Under construction
{:class .notice--info}

## 3) Coordination of vehicles for urban traffic management

Being stuck in traffic is not funny for anyone...while self-driving cars could relieve us from the duty of daily driving, *cooperative driving* is necessary to enable self-driving cars to handle complex situations like crossing intersections, that require the coordination of multiple vehicles to establish a safe crossing order.
Urban traffic management is thus an abundant source of *coordination problems* that future autonomous and connected vehicles will need to tackle to successfully hit the streets.
The following activities unfold in this domain.

**Thesis**

 1. experiment with existing agent-based simulators adopted/adapted in traffic management domain
 2. design and implement an agent-based microscopic traffic simulator

**Internships**

 1. experiment with the [SUMO](https://sumo.dlr.de/docs/index.html) traffic simulator to implement state of the art intersection crossing strategies
 2. develop a Graphical User Interface (GUI) for a [simple simulator](https://github.com/DarioFerrari-git/AutoA) developed by graduate student Dario Ferrari

**Concluded**

 - Dario Ferrari. *"Coordinamento di veicoli autonomi basato su tecniche di argimentazione: simulatore ed esperimenti."* Bachelor degree in Management Engineering, 2021/2022.
 - Nicholas Glorio. *"Strategie per la gestione delle intersezioni in presenza di veicoli autonomi."* Master degree in Computer Science Engineering, 2020/2021.
 - Marco Gambelli. *"Gestione di incroci stradali per veicoli a guida autonoma basata su algoritmi a prenotazione e ad asta."* Master degree in Computer Science Engineering, 2020/2021.
 - Andrea Vitali. *"Esperimenti di coordinazione veicolare tramite blockchain."* Master degree in Computer Science Engineering, 2019/2020.
 - Enrico Rossini. *"Attraversamento di incroci per auto a guida autonoma: protocolli e simulazione."* Bachelor degree in Management Engineering, 2019/2020.

## 4) Argumentation protocols for joint deliberation/action and situation recognition in multiagent systems and IoT

Many daily activities we carry out are assisted by software (e.g. digital assistants like Siri, Alexa, etc.), that (1) exploit artificial intelligence techniques, e.g. Machine Learning (ML), to deliver their services, and (2) work together with many other software entities to accomplish tasks (e.g. Siri is connected to your Calendar, weather service, apps, etc.).

Using ML may result in *opaque* systems that re not easily comprehended in their decision making by the user (e.g. why is Netflix suggesting that?).
Moreover, having systems composed by multiple software pieces raises the problem of establishing how these pieces should *coordinate* to ahieve the desired goal.
Many techniques exist to make ML *explainable*, that is able to otivate their decisions to humans, and many other exist to define coordination protocols amongst independent software pieces dictating how each piece should behave.

*Computational argumentation* is a promising research area that could potentially solve both problems at once.

**Thesis**

 1. develop a software framework for [practical argumentation](https://nms.kcl.ac.uk/sanjay.modgil/ASPICtutorial.pdf)
 2. develop a software framework for playing *dialogue games* for multiagent negotiation and conflict resolution
 <!--- develop / experiment with a software framework for natural language processing for [argumentation mining](https://www.sciencedirect.com/science/article/pii/S0957417416304493?via%3Dihub) (e.g. [Apache OpenNLP](https://opennlp.apache.org), [Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/))-->

**Internships**

 1. surveying *commonsense reasoning* state of art
 2. experiment with the [Tweety Java library](https://tweetyproject.org) for computational argumentation
 3. experiment with the [ArgTuProlog](https://pika-lab.gitlab.io/argumentation/arg2p-kt/) system for computational argumentation

**Concluded**

 - Dario Ferrari. *"Coordinamento di veicoli autonomi basato su tecniche di argimentazione: simulatore ed esperimenti."* Bachelor degree in Management Engineering, 2021/2022.
 - Andrea Bicego. *"Progettazione di Servizi IoT basati su Protocolli di Argomentazione."* Master degree in Management Engineering, 2017/2018.

<!--## 4) Space-based coordination for smart cities applications

Under construction
{:class .notice--info}

**Internships**

 1. integrate [TuSoW](https://github.com/CoordaaS/TuSoW) and [Tile38](https://tile38.com) for efficient tuple-based, space-aware coordination
 2. experiment/expand [Tile38](https://tile38.com) to deal with arbitrary data (e.g. try geoJSON or implement ad-hoc representation)

<!--### Concluded-->

 <!--- Michele Donati. *"A modular and flexible web dashboard for mobile assets geo-tracking."* Bachelor degree in Computer Science Engineering. *(tentative title)*-->

## 5) Beyond AutoML: software engineering applied to machine learning pipelines

Under construction
{:class .notice--info}

**Thesis**

 1. design of a *modular* machine learning pipeline for predicting [health outcomes in COPD/asthma patients](https://www.connecare.eu/wp-content/uploads/2020/02/D3.4-Stratification-and-Mapping-DSS_DEF.pdf)

**Internships**

 1. using [PMML/PFA](http://dmg.org) for sharing machine learning models/pipelines across software platforms (e.g. R and Python)
 2. surveying *AutoML* state of art (e.g. open source libraries)
 3. serving machine learning models over the *web*

**Concluded**

 - Gabriele Rinaldi. *"Sviluppo di un'applicazione web per la fruizione di modelli predittivi."* Bachelor degree in Management Engineering, 2021/2022.
 - Benedetta Becchi. *"Sperimentazione della piattaforma KNIME: creazione di una pipeline di machine learning per il trattamento di dati sanitari."* Bachelor degree in Management Engineering, 2019/2020.

<!--## Information retrieval, clustering, and gossiping on the web

Under construction
{:class .notice--info}

**Internships**

 - surveying information retrieval technologies state of art (e.g. [Apache Lucene](https://lucene.apache.org), [Elasticsearch](https://www.elastic.co/guide/en/elasticsearch/reference/current/getting-started.html), [Terrier](http://terrier.org))
 - surveying semantic inference technologies state of art (e.g. [Apache Jena](https://jena.apache.org), [HermiT](http://www.hermit-reasoner.com/index.html))
 - surveying text mining technologies state of art (e.g. [Apache OpenNLP](https://opennlp.apache.org), [Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/))
-->

## Miscellaneous (e.g. students' proposals)

**Concluded**

 - Luca Morini. *"Non SprECO: la web app per monitorare il proprio impatto ambientale quotidiano."* Bachelor degree in Management Engineering, 2020/2021.
 - Nicola Romano. *"Finanza decentralizzata: dalla tecnologia Blockchain ad una nuova finanza."* Master degree in Management Engineering, 2020/2021.
 - Carla Marangi. *"La sicurezza informatica ai tempi del COVID: rischi e misure protettive per lo smart working."* Bachelor degree in Management Engineering, 2019/2020.
 - Alessandra Occhionero. *"Analisi della piattaforma AWS IoT Core: gestione di device IoT simulati."* Bachelor degree in Management Engineering, 2019/2020.
 - Luca Bartolini. *"Digital Twin per industria 4.0: piattaforme e scenari applicativi."* Bachelor degree in Management Engineering, 2019/2020.
 - Matteo Santacaterina. *"Analisi dati GeoJson a supporto di processi clinici: il Mapping DSS in CONNECARE."* Bachelor degree in Management Engineering, 2018/2019.
 - Andrea Canepari. *"Geolocalizzazione e stratificazione di pazienti critici su mappa: il caso del Mapping DSS in CONNECARE."* Bachelor degree in Management Engineering, 2018/2019.
 - Jacopo Stefani. *"SISTEMA DI SUPPORTO DECISIONALE IN AMBITO CLINICO: VISUALIZZAZIONE DEI PAZIENTI SU MAPPA."* Bachelor degree in Management Engineering, 2017/2018.
 - Andrea Alberini. *"Applicazione Java per l'ottimizzazione dell'attività fisica tramite messaggi motivazionali contestualizzati."* Bachelor degree in Management Engineering, 2017/2018.

See also the [legacy Unibo page](http://apice.unibo.it/xwiki/bin/view/StefanoMariani/CompletedTheses) for older thesis.

See also the [legacy Unibo page](https://apice.unibo.it/xwiki/bin/view/Panels/SMarStudents) for older projects / internships.
