---
title: "Better Lost in Transition Than Lost in Space: SLAM State Machine"
date: 2019-01-04
---

A Simultaneous Localization and Mapping
(SLAM) system is a complex program consisting of several
interconnected components with different functionalities such as
optimization, tracking or loop detection. Whereas the literature
addresses in detail how enhancing the algorithmic aspects of
the individual components improves SLAM performance, the
modal aspects, such as when to localize, relocalize or close a
loop, are usually left aside. In this paper, we address the modal
aspects of a SLAM system and show that the design of the
modal controller has a strong impact on SLAM performance
in particular in terms of robustness against unforeseen events
such as sensor failures, perceptual aliasing or kidnapping. We
preset a novel taxonomy for the components of a modern
SLAM system, investigate their interplay and propose a highly
modular architecture of a generic SLAM system using the
Unified Modeling Language TM (UML) state machine formalism.
The result, called SLAM state machine, is compared to the
modal controller of several state-of-the-art SLAM systems and
evaluated in two experiments. We demonstrate that our state
machine handles unforeseen events much more robustly than
the state-of-the-art systems.


__DOI__: [10.1109/IROS40897.2019.8968182](https://doi.org/10.1109/IROS40897.2019.8968182)  
[Link to the article](/resources/2019_paper_colosi_slam_state_machine.pdf)  
BibTex:  
<pre>
@inproceedings{colosi2019better,
  title={{Better Lost in Transition Than Lost in Space: SLAM State Machine}},
  author={Colosi, Mirco and Haug, Sebastian and Biber, Peter and Arras, Kai O and Grisetti, Giorgio},
  booktitle={2019 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={362--369},
  year={2019},
  organization={IEEE}
}
</pre>
