---
title: PolicySimulator
subtitle: A Simulation Framework for the Experimental Evaluation of Access Control Enforcement Mechanisms based on Business Processes

people:
    - StefanoBerlato
    - RobertoCarbone
    - SilvioRanise

peopleOrder: surname

publications:
    - POLSIM2023
---

### Description

While the security analysis of Access Control (AC) policies has received a lot of attention, the same cannot be said for their **enforcement**. As systems become more distributed (e.g., centralized services may become a *bottleneck*) and legal compliance constraints stricter (e.g., the problem of *honest but curious* Cloud providers in the light of privacy regulations), the **fine-tuning of AC enforcement mechanisms** is likely to become more and more important. This is especially true in scenarios where the quality of service may suffer from **computationally heavy security mechanisms** and low latency is a prominent requirement. 

As a first step towards a principled approach to fine-tune AC enforcement, we wrote a scientific article entitled "A Simulation Framework for the Experimental Evaluation of Access Control Enforcement Mechanisms based on Business Processes"; the article proposes a methodology providing the means to **measure the performance of AC enforcement mechanisms through the simulation of realistic deployment scenarios**. To do so, we base our methodology on Business Process Model and Notation (BPMN) workflows—that provide for an appropriate abstraction of the sequence of requests toward AC enforcement mechanisms performed by applications—to derive lists of AC operations (e.g., access a resource, revoke a permission) and execute them to evaluate and compare the performance of different mechanisms.

Please see [**the repository**](https://github.com/stfbk/PolicySimulator) for more details on the **Policy Simulator**.