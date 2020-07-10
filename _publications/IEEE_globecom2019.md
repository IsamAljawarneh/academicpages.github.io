---
title: "[Spatial-Aware Approximate Big Data Stream Processing](https://ieeexplore.ieee.org/abstract/document/9014291)"
collection: publications
permalink: /publications/IEEE_globecom2019
venue: "2019 IEEE Global Communications Conference (GLOBECOM)"
date: 2020-1-1
citation: '<b>Isam Mashhour Al Jawarneh</b>, Paolo Bellavista,  Luca Foschini, Rebecca Montanari'
---
[[Paper]](https://ieeexplore.ieee.org/abstract/document/9014291) [[BIBTEX]](http://IsamAljawarneh.github.io/files/bib/IEEE_globecom2019.bib) [[RIS]](http://IsamAljawarneh.github.io/files/ris/IEEE_globecom2019.ris) [[plain]](http://IsamAljawarneh.github.io/files/txt/IEEE_globecom2019.txt) 



## Abstract
The widespread adoption of ubiquitous IoT edge devices and modern telemetry spewing out unprecedented avalanches of spatially-tagged datasets that if could interactively be explored would offer deep insights into interesting natural phenomena, which might remain otherwise illusive. Online application of spatial queries is expensive, a problem that is further inflated by the fact that we, more than often, do not have access to a full dataset population in non- stationary settings. As a way of coping up, sampling stands out as a natural solution for approximating estimators such as averages and totals of some interesting correlated parameters. In any sampling design, representativeness remains the main issue upon which a method is regarded good or bad. In a loose way, in a spatial context, this means fairly sampling quantities in a way that preserves spatial characteristics so as to provide more accurate approximates for spatial query responses. Current big data management systems either do not offer over-the-counter spatial-aware online sampling solutions or, at best, rely on randomness, which causes too many imponderables for an overall estimation. We herein have designed a QoS- spatial-aware online sampling method that outperforms vanilla baselines by statically significant magnitudes. Our method sits atop Apache Spark Structured Streaming's codebase and have been tested against a benchmark that is consisting of millions-records of spatially- augmented dataset.


