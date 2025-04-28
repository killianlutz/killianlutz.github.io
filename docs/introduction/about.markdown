---
layout: page
title: About
permalink: /about/
---

I work on the optimal control of (open) quantum systems and its applications to quantum computing. This work is carried out under the supervision of [Emmanuel Franck](https://irma.math.unistra.fr/~franck/index.html) (INRIA) and [Yannick Privat](https://yannick-privat.perso.math.cnrs.fr) (IECL). We closely collaborate with the group of physicists [Q-Dyno](https://www.ipcms.fr/en/equipe/theoretical-quantum-dynamics-of-nano-objects-dyno/) at IPCMS.

# <span style="color:#e67e22"> Research project in a nutshell </span>

We aim to develop numerical methods suited to the *control* of *non-isolated* discrete quantum systems modelled by the *GKS-Lindblad* equation. We are especially interested in qu*d*its, an alternative to the quantum analogue of 'bits' in classical computing. 

An example of such control problem relates to running algorithms on a quantum computer. Given a quantum algorithm, we study and estimate numerically the optimal experimental setup driving qudits from an the "input" logical value to the desired "output" logicial value. Here, optimal means running the algorithm as accurately and quickly as possible.

Brief interactive [introduction](https://github.com/killianlutz/BlochBallAnim.jl) to this matter.

What makes this task challenging? Mathematically it is about *non-linear* control theory. Numerically, it is about optimizing a criterion which depends upon *exponentially many* variables.

