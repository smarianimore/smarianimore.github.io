---
title: "New paper on ACM CSUR about coordination of autonomous vehicles!"
excerpt: ""
tags:
  - coordination
  - autonomous vehicles
  - cooperative driving
  - autonomy
  - ACM Computing Surveys
  - publication
header:
  teaser: /assets/autonomy-scale.png
---

I'm happy to announce that paper ["Coordination of Autonomous Vehicles: Taxonomy and Survey"](https://doi.org/10.1145/3431231) has been published on [ACM Computing Surveys](https://dl.acm.org/journal/csur)!
It took *almost 2 years* (:O), but here it is, finally :)

It is a joint work with [Franco Zambonelli](http://www.agentgroup.unimore.it/Zambonelli/) and [Giacomo Cabri](http://didattica.agentgroup.unimore.it/wiki/index.php/User:Giacomo_Cabri) with the ambition to shed light on the issue of **coordination of autonomous vehicles** to achieve cooperative driving, and the tradeoff between coordination enforcement and the **degree of autonomy** that vehicles have while participating in collective decision making.   

In brief, the paper first categorises traffic-related problems in a **bi-dimensional taxonomy** stemming from concurrency and coordination research (Table 1).

![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/coordination-problems.png)

Then we describe such problems in view of typical *concurrency and coordination terms*, such as **safety and liveness** properties (Table 2).

![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/traffic-to-coordination.png)

We then shift attention to *solutions* to such problems, and categorise approaches on a "autonomy scale" ordering the **degree of autonomy** left to vehciles in decision making during the coordination process (Figure 1).

![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/autonomy-scale.png)

Finally, we frame selected papers from the literature in the defined autonomy classes (Table 4).

![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/survey.png)

Hope you enjoy reading, and [contact me](mailto:stefano.mariani@unimore.it) for any further inquiry :)
