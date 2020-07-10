---
title: "[Qos and performance metrics for container-based virtualization in cloud environments"
collection: publications
permalink: /publications/containers2019
venue: "Proceedings of the 20th International Conference on Distributed Computing and Networking"
date: 2019-1-1
citation: '<b>Isam Mashhour Al Jawarneh</b>,  Paolo Bellavista, Luca Foschini, Giuseppe Martuscelli, Rebecca Montanari, Amedeo Palopoli, Filippo Bosi'
---
[[Paper]](https://dl.acm.org/doi/abs/10.1145/3288599.3288631) [[BIBTEX]](http://IsamAljawarneh.github.io/files/bib/containers2019.bib) [[RIS]](http://IsamAljawarneh.github.io/files/ris/containers2019.ris) [[plain]](http://IsamAljawarneh.github.io/files/txt/containers2019.txt) 



## Abstract
Current cloud deployments heavily depend on hypervisor-based virtualizations. 
The overarching characteristics of Docker and containerization have given them a momentum in their widespread adoption recently as alternatives for their counterparts. However, 
little research has been done for comparing the QoS of both technologies, thus leaving the domain without widely accepted performance metrics. 
Aiming at informing the decision of the best fit in a specific cloud deployment, we have designed performance metrics that compare the performance of both designs in an in-house 
cluster deployed by using OpenStack. We focus on well-established representatives as baselines, including KVM from the hypervisor-based side, LXD from the container-based 
side in addition to Docker. Our results show that containerization is not a predominant fit-all solution that can always replace hypervisors for all cluster deployment and 
application scenarios. It can instead be thought of as a complementary solution to use for specific application scenarios that are constrained with conditions that are solved 
by containerization merits.
