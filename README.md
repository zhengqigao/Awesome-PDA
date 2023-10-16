# Awesome Photonic Design Automation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


The goal of Photonics Design Automation is to use algorithmic methods (such as graph theory, optimization methods, statistics, and machine learning) to ease human burden when designing a photonics chip. Here the repo contains many useful references related to photnoics circuits from various perspectives, such as theory, modeling, application. I am hoping to inspire readers to excavate and then address underlying design problems using algorithms. Together, we will push design automation being a necessary compnonent in the photonic design flow and help its design easier than ever.

The reference list below will be updated regularly along the author's reading and research. Want to contribute? If you find some overlooked papers (or even a whole overlooked area), please open issues, contact the author at [zhengqi@mit.edu](mailto:zhengqi@mit.edu), or pull requests. For more info about the author, please see his homepage: [https://zhengqigao.github.io/](https://zhengqigao.github.io/).

## Warm Up: Prediction of the Market, BigTech Company

- [Global Silicon Photonics Market Size Revenue Expected to Grow USD 9.14 Billion by 2030](https://www.prnewswire.com/news-releases/global-silicon-photonics-market-size-revenue-expected-to-grow-usd-9-14-billion-by-2030--with-27-4-cagr-polaris-market-research-301539481.html)

- [Report: Rapid Growth Ahead for Silicon Photonics](https://www.optica-opn.org/home/industry/2022/august/report_rapid_growth_ahead_for_silicon_photonics/)

- [Intel Labs Announces Integrated Photonics Research Advancement](https://www.intc.com/news-events/press-releases/detail/1555/intel-labs-announces-integrated-photonics-research)

- [Nvidia shows what optically linked GPU sytems might look like](https://www.nextplatform.com/2022/08/17/nvidia-shows-what-optically-linked-gpu-systems-might-look-like/)

- [Google Details TPUv4 and its Crazy Optically Reconfigurable AI Network](https://www.servethehome.com/google-details-tpuv4-and-its-crazy-optically-reconfigurable-ai-network/)

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


- [Allan W. Snyder, John D. Love, 'Optical Waveguide Theory'](https://link.springer.com/book/10.1007/978-1-4613-2813-1)

    - Classical and comprehensive.

## Introduction to Integrated Silicon Photonics

- [Richard Soref 'The Past, Present, and Future of Silicon Photonics'](https://ieeexplore.ieee.org/document/4032698)

    - A bit old though, published on 2006, but still a good overall summary.

- [Winnie N. Ye and Yule Xiong, 'Review of silicon photonics: history and recent advances'](https://www.tandfonline.com/doi/full/10.1080/09500340.2013.839836?scroll=top&needAccess=true)

- [Wim Bogaerts and Lukas Chrostowski, 'Silicon photonics circuit design: methods, tools and challenges'](https://onlinelibrary.wiley.com/doi/full/10.1002/lpor.201700237)

- [Lukas Chrostowski and Michael Hochberg, 'Silicon Photonics Design From Devices to Systems'](https://www.cambridge.org/core/books/silicon-photonics-design/BF3CF13E8542BCE67FD2BBC7104ECEAB) 

- [Wim Bogaerts, Martin Fiers, and Pieter Dumon 'Design Challenges in Silicon Photonics'](https://ieeexplore.ieee.org/abstract/document/6691908)

- [Near Margalit et al., 'Perspective on the future of silicon photonics and electronics'](https://aip.scitation.org/doi/10.1063/5.0050117)

- [Dan-Xia Xu et al., 'Silicon Photonic Integration Platform—Have We Found the Sweet Spot?'](https://ieeexplore.ieee.org/document/6709757?arnumber=6709757)

- [Zhengqi Gao, 'Introduction to Photonic Design Automation'](https://zhengqigao.github.io/articles/Introduction_to_Photonic_Design_Automation.pdf)

    - A 2-page newbie-friendly article. Only high school knowledge required.


## Numerical Simulation Techniques (Mode, FDTD, S-Matrix, etc.)

Effective Index Method:  

- [K. S. Chiang, 'Analysis of optical fibers by the effective-index method'](https://opg.optica.org/ao/fulltext.cfm?uri=ao-25-3-348&id=29059)

- [Lec22: Waveguide design Effective Index method](https://www.youtube.com/watch?v=Jb9Qzm88qbo)

Eigenmode Solver:

- [P. Lusse, et al., 'Analysis of vectorial mode fields in optical waveguides by a new finite difference method'](https://ieeexplore.ieee.org/document/285331)

- [Zhaoming Zhu and Thomas G. Brown, 'Full-vectorial finite-difference analysis of microstructured optical fibers'](https://opg.optica.org/oe/fulltext.cfm?uri=oe-10-17-853&id=69852)

Couple Mode Theory:

- [A. Yariv, 'Coupled-mode theory for guided-wave optics'](https://ieeexplore.ieee.org/document/1077767)

- [Wei-Ping Huang, 'Coupled-mode theory for optical waveguides: an overview'](https://opg.optica.org/josaa/fulltext.cfm?uri=josaa-11-3-963&id=676)

Finite Difference Time Domain (FDTD):

- [John B. Schneider, 'Understanding the Finite-Difference Time-Domain Method'](https://eecs.wsu.edu/~schneidj/ufdtd/ufdtd.pdf)

Scattering Matrix:

- [Interconnect S-Parameter Simulator (SPS)](https://optics.ansys.com/hc/en-us/articles/360034919853-INTERCONNECT-S-Parameter-Simulator-SPS-)

Mode Expansion:

- [Using and understanding Mode Expansion Monitors](https://optics.ansys.com/hc/en-us/articles/360034902433-Using-and-understanding-Mode-Expansion-Monitors)

    - A rough description on how Lumerical impelments mode expansions.

Why MZI is universal:

- [M. Reck et al.,'Experimental realization of any discrete unitary operator'](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.73.58)

- [W. Clements et al., 'Optimal design for universal multiport interferometers'](https://opg.optica.org/optica/fulltext.cfm?uri=optica-3-12-1460&id=355743)

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

- [Zhengqi Gao et al., 'Automatic Synthesis of Broadband Silicon Photonic Devices Via Bayesian Optimization'](https://github.com/zhengqigao/BayesOpt-JLT2022)


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

- [Z. Lu et al., 'Performance prediction for silicon photonics integrated circuits with layout-dependent correlated manufacturing variability'](https://opg.optica.org/oe/viewmedia.cfm?uri=oe-25-9-9712&html=true)

- [Y. Xing et al., 'Capturing the effects of spatial process variations in silicon photonic circuits'](https://pubs.acs.org/doi/10.1021/acsphotonics.2c01194)

- [A.D. Simard et al., 'Impact of Sidewall Roughness on Integrated Bragg Gratings'](https://ieeexplore.ieee.org/document/6060839)

- [Z. Gao et al., 'Few-Shot Bayesian Performance Modeling for Silicon Photonic Devices Under Process Variation'](https://ieeexplore.ieee.org/abstract/document/10109764)

- [A. Hiraiwa, 'Statistical Model of Line-Edge and Line-Width Roughness for Device Variability Analysis'](https://ieeexplore.ieee.org/document/5751665)

## Optical Phased Array (Antenna Array, Beam Steering) 

- [Matt Longbrake, 'True time-delay beamsteering for radar'](https://ieeexplore.ieee.org/document/6531062)

- [Taehwan Kim et al., 'A Single-Chip Optical Phased Array in a Wafer-Scale Silicon Photonics/CMOS 3D-Integration Platform'](https://ieeexplore.ieee.org/abstract/document/8828069)

- [A. Hajimiri et al., 'Integrated Phased Array Systems in Silicon'](https://ieeexplore.ieee.org/document/1495910)


## Photonics for Quantumn 

- [Ali W. Elshaari et al., 'Hybrid integrated quantum photonic circuits'](https://www.nature.com/articles/s41566-020-0609-x)

- [C. Taballione, '8 × 8 programmable quantum photonic processor based on silicon nitride waveguides'](https://arxiv.org/abs/1805.10999)

## Electronic-Photonic Co-simulation

To me, this topic is a very important one, yet at a very immature stage. The futuer of circuits in my understanding will be a mixture of electronics and photonics on the same chip. Thus, electronic and photonic co-simulation is of huge interest. There are a few works exploring along this direction; even a commerical product, [OptiSpice](https://optiwave.com/optispice-overview/), is now available. However, personally, I feel that the current paradigm for co-simulation is far from satisfying, while tremendous efforts should be devoted to this topic. Of course, since {E,H} for photonics and {I,V} for electronics locate at two different abstract physical level, this topic won't be easy.

- [Cheryl Sorace-Agaskar et al., 'Electro-optical co-simulation for integrated CMOS photonic circuits with VerilogA'](https://opg.optica.org/oe/fulltext.cfm?uri=oe-23-21-27180&id=330111)

- [Mark A. Neifeld and Wu-Chun Chou, 'Spice-based optoelectronic system simulation'](https://opg.optica.org/ao/fulltext.cfm?uri=ao-37-26-6093&id=43271)

## Layout

- [An open-source layout tool targeting integrated photonic circuit layout](https://gdsfactory.github.io/gdsfactory/)

- [Ahmadreza Farsaei, 'Introduction to Layout Design and Automation of Photonic Integrated Circuits'](https://link.springer.com/book/10.1007/978-3-031-25288-4)

## System-Level Electro-Optical Integration

- [S. Chen et al., 'Single-chip microprocessor that communicates directly using light'](https://www.nature.com/articles/nature16454)

- [Amir H Atabaki et al., 'Integrating photonics with silicon nanoelectronics for the next generation of systems on a chip'](https://www.nature.com/articles/s41586-018-0028-z)

