# Awesome Photonic Design Automation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Here the repo contains many useful references in the area of photonic design automation (PDA). The goal of PDA is to use algorithmic methods (such as graph theory, optimization methods, statistics, and machine learning) to ease human burden when designing a photonics chip. The original goal of this repo is to help readers quickly get familiar with a area by reading the listed references.

The reference list below will be updated regularly along the author's reading and research. Want to contribute? If you find some overlooked papers (or even a whole overlooked area), please open issues, contact the author at [zhengqi@mit.edu](mailto:zhengqi@mit.edu), or pull requests. For more info about the author, please see his homepage: [https://zhengqigao.github.io/](https://zhengqigao.github.io/).

## Electromagnetic (EM) Basics

- [John D. Jackson, 'Classical Electrodynamics'](https://www.wiley.com/en-us/Classical+Electrodynamics%2C+3rd+Edition-p-9780471309321) 
    - A classical textbook in EM. It is very comprehensive and math dense. It is more appropriate to readers who have background in EM.

- [David J. Griffiths, 'Introduction to Electrodynamics'](https://www.cambridge.org/highereducation/books/introduction-to-electrodynamics/3AB220820DBB628E5A43D52C4B011ED4#overview)
    - A classical textbook in EM. Compared to Jackson's, Griffiths's is more beginner friendly. It has many graphical illustrations and the math derivation is step by step. However, a few advanced topics are not covered (e.g., Green functions).

- [David H. Staelin, Ann Morgenthaler, and Jin Au Kong 'Electromagnetic Waves'](https://www.pearson.com/us/higher-education/program/Staelin-Electromagnetic-Waves/PGM63919.html)
    - A Classical textbook in EM. Jackson's and Griffiths's start from electrostatics, while this book directly starts from electrodynamics. In this sense, it is more suitable if you are looking for a book 'more cut to the point'.

- [Katsunari Okamoto, 'Fundamentals of Optical Waveguides'](https://www.elsevier.com/books/fundamentals-of-optical-waveguides/okamoto/978-0-12-525096-2)

    - The first two chapters give good explanations on modes in waveguide. 

- [William Hayt and John Buck, 'Engineering Electromagnetic'](https://www.mheducation.com/highered/product/engineering-electromagnetics-hayt-buck/M9780078028151.html)



## Introduction to Integrated Silicon Photonics

- [Richard Soref 'The Past, Present, and Future of Silicon Photonics'](https://ieeexplore.ieee.org/document/4032698)

    - A bit old though, published on 2006, but still a good overall summary.

- [Wim Bogaerts and Lukas Chrostowski, 'Silicon photonics circuit design: methods, tools and challenges'](https://onlinelibrary.wiley.com/doi/full/10.1002/lpor.201700237)

- [Lukas Chrostowski and Michael Hochberg, 'Silicon Photonics Design From Devices to Systems'](https://www.cambridge.org/core/books/silicon-photonics-design/BF3CF13E8542BCE67FD2BBC7104ECEAB) 

- [Wim Bogaerts, Martin Fiers, and Pieter Dumon 'Design Challenges in Silicon Photonics'](https://ieeexplore.ieee.org/abstract/document/6691908)

- [Near Margalit et al., 'Perspective on the future of silicon photonics and electronics'](https://aip.scitation.org/doi/10.1063/5.0050117)

- [Dan-Xia Xu et al., 'Silicon Photonic Integration Platform—Have We Found the Sweet Spot?'](https://ieeexplore.ieee.org/document/6709757?arnumber=6709757)

- [Zhengqi Gao, 'Introduction to Photonic Design Automation'](https://zhengqigao.github.io/articles/Introduction_to_Photonic_Design_Automation.pdf)

    - A 2-page newbie-friendly article. Only high school knowledge required.

## Inverse Design (Shape/Topology Optimization)

Adjoint method plus gradient descent optimization appears to be the main stream currently. Using gradients in optimization is named first-order method. On the other hand, zero-order method (optimization without gradient) is occasionally used in inverse design of silicon photonics. 

- [Alexander Y. Piggott et al., 'Inverse design and demonstration of a compact and broadband on-chip wavelength demultiplexer'](https://www.nature.com/articles/nphoton.2015.69)

- [Alexander Y. Piggott et al., 'Fabrication-constrained nanophotonic inverse design'](https://www.nature.com/articles/s41598-017-01939-2)

- [Christopher M. Lalau-Keraly et al., 'Adjoint shape optimization applied to electromagnetic design'](https://opg.optica.org/oe/fulltext.cfm?uri=oe-21-18-21693&id=260994)

- [Mohammad H. Tahersima et al., 'Deep Neural Network Inverse Design of Integrated Photonic Power Splitters'](https://www.nature.com/articles/s41598-018-37952-2)

- [Zhaocheng Liu et al., 'Tackling Photonic Inverse Design with Machine Learning'](https://onlinelibrary.wiley.com/doi/full/10.1002/advs.202002923)

- [Wei Ma et al., 'Deep learning for the design of photonic structures'](https://www.nature.com/articles/s41566-020-0685-y)

- [Armand C. R. Niederberger et al., 'Sensitivity analysis and optimization of sub-wavelength optical gratings using adjoints'](https://opg.optica.org/oe/fulltext.cfm?uri=oe-22-11-12971&id=286390)

    - Not limited to silicon photonics.

- [K. Kojima et al., 'Deep Neural Networks for Inverse Design of Nanophotonic Devices'](https://ieeexplore.ieee.org/document/9316743)

- [Zhengqi Gao et al., 'Automatic Design of a Broadband Directional Coupler via Bayesian Optimization'](https://github.com/zhengqigao/BayesOpt-JLT2022)

## Surrogate Model for Simulation (EM Field Prediction)

- [Rahul Trivedi et al., 'Data-driven acceleration of photonic simulations'](https://www.nature.com/articles/s41598-019-56212-5)

- [Tyler W. Hughes et al., 'Wave physics as an analog recurrent neural network'](https://www.science.org/doi/10.1126/sciadv.aay6946)

- [M. Raissi, P. Perdikaris, and G.E. Karniadakis, 'Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations'](https://www.sciencedirect.com/science/article/pii/S0021999118307125)

- [Yingheng Tang et al., 'Physics-informed recurrent neural network for time dynamics in optical resonances'](https://www.nature.com/articles/s43588-022-00215-2)

- [Mingkun Chen et al., 'WaveY-Net: physics-augmented deep-learning for high-speed electromagnetic simulation and optimization'](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12011/120110C/WaveY-Net--physics-augmented-deep-learning-for-high-speed/10.1117/12.2612418.full?SSO=1)

- [Joowon Lima and Demetri Psaltis, 'MaxwellNet: Physics-driven deep neural network training based on Maxwell’s equations'](https://aip.scitation.org/doi/10.1063/5.0071616)

- [Zongyi Li et al., 'Fourier Neural Operator for Parametric Partial Differential Equations'](https://arxiv.org/abs/2010.08895)

- [Jiaqi Gu et al., 'NeurOLight: A Physics-Agnostic Neural Operator Enabling Parametric Photonic Device Simulation'](https://arxiv.org/abs/2209.10098)

## Programmable Photonics 

 - [Wim Bogaerts et al., 'Programmable photonic circuits'](https://www.nature.com/articles/s41586-020-2764-0)

 - [Xiangfeng Chen et al., 'Graph Representation for Programmable Photonic Circuits'](https://ieeexplore.ieee.org/document/9056549)

- [Daniel Pérez-López et al., 'Programmable Integrated Silicon Photonics Waveguide Meshes: Optimized Designs and Control Algorithms'](https://ieeexplore.ieee.org/document/8873623)

- [Saumil Bandyopadhyay, Ryan Hamerly, and Dirk Englund, 'Hardware error correction for programmable photonics'](https://opg.optica.org/optica/fulltext.cfm?uri=optica-8-10-1247&id=459915)

- [Daniel Pérez-López et al., 'Multipurpose self-configuration of programmable photonic circuits'](https://www.nature.com/articles/s41467-020-19608-w)

- [Wim Bogaerts's presentation on programmable photonics](https://www.youtube.com/watch?v=CBhdLTTbYoM&t=2048s)

     - Highly recommended. A really nice introduction with lots of figures!

- [Aitor López et al., 'Auto-routing algorithm for field-programmable photonic gate arrays'](https://opg.optica.org/oe/fulltext.cfm?uri=oe-28-1-737&id=425613)

- [Zhengqi Gao et al., 'Automatic Synthesis of Light Processing Functions for Programmable Photonics: Theory and Realization'](https://arxiv.org/abs/2208.14453)

## Optical Neural Network

- [Yichen Shen et al., 'Deep learning with coherent nanophotonic circuits'](https://www.nature.com/articles/nphoton.2017.93?TB_iframe=true&width=921.6&height=921.6)

- [Ying Zuo et al., 'All-optical neural network with nonlinear activation functions'](https://opg.optica.org/optica/fulltext.cfm?uri=optica-6-9-1132&id=417261)

- [Ryan Hamerly et al., 'Large-Scale Optical Neural Networks Based on Photoelectric Multiplication'](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.9.021032)

- [J. Bueno et al., 'Reinforcement learning in a large-scale photonic recurrent neural network'](https://opg.optica.org/optica/fulltext.cfm?uri=optica-5-6-756&id=392687)

- [Qiming Zhang et al., 'Artificial neural networks enabled by nanophotonics'](https://www.nature.com/articles/s41377-019-0151-0)

- [H. Zhang et al., 'An optical neural chip for implementing complex-valued neural network'](https://www.nature.com/articles/s41467-020-20719-7)

## Variation: Impact, Modeling, and Calibration

- [I. Zand et al., 'Effects of coupling and phase imperfections in programmable photonic hexagonal waveguide meshes'](https://opg.optica.org/prj/fulltext.cfm?uri=prj-8-2-211&id=426491)

- [S. Bandyopadhyay et al., 'Effects of coupling and phase imperfections in programmable photonic hexagonal waveguide meshes'](https://opg.optica.org/optica/fulltext.cfm?uri=optica-8-10-1247&id=459915)

- [D. Boning et al., 'Variation-Aware Methods and Models for Silicon Photonic Design-for-Manufacturability'](https://ieeexplore.ieee.org/abstract/document/9547833)

- [Z. Zhang et al., 'Enabling Wavelength-Dependent Adjoint-Based Methods for Process Variation Sensitivity Analysis in Silicon Photonics'](https://ieeexplore.ieee.org/abstract/document/9272849)

- [X. Wang et al., 'Narrow-band waveguide Bragg gratings on SOI wafers with CMOS-compatible fabrication process'](https://opg.optica.org/oe/fulltext.cfm?uri=oe-20-14-15547&id=239269)

- [D. Melati et al., 'Real photonic waveguides: guiding light through imperfections'](https://re.public.polimi.it/retrieve/handle/11311/863356/52650/AOP2013_Melati.pdf)

- [S. Johnson et al., 'Perturbation theory for Maxwell’s equations with shifting material boundaries'](https://math.mit.edu/~stevenj/papers/JohnsonIb02.pdf)

- [Y. Xing et al., 'Accurate extraction of fabricated geometry using optical measurement'](https://opg.optica.org/prj/fulltext.cfm?uri=prj-6-11-1008&id=399133)

## Optical Phased Array (Antenna Array, Beam Steering) 

- [Matt Longbrake, 'True time-delay beamsteering for radar'](https://ieeexplore.ieee.org/document/6531062)

- [Taehwan Kim et al., 'A Single-Chip Optical Phased Array in a Wafer-Scale Silicon Photonics/CMOS 3D-Integration Platform'](https://ieeexplore.ieee.org/abstract/document/8828069)

- [A. Hajimiri et al., 'Integrated Phased Array Systems in Silicon'](https://ieeexplore.ieee.org/document/1495910)



... To be updated