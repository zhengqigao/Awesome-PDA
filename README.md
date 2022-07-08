# Awesome Photonic Design Automation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Here the repo contains many useful references in the area of photonic design automation (PDA). The goal of PDA is to use algorithmic methods (such as graph theory, optimization methods, statistics, and machine learning) to ease human burden when designing a photonics chip. The original goal of this repo is to help readers quickly get familiar with a area by reading the listed references.

The reference list below will be updated regularly along the author's reading and research. If you find some overlooked papers (or even a whole overlooked area), please open issues, contact the author at [zhengqi@mit.edu](mailto:zhengqi@mit.edu), or pull requests. For more info about the author, please see his homepage: [https://zhengqigao.github.io/](https://zhengqigao.github.io/).

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



## Introduction to integrated silicon photonics


- [Wim Bogaerts and Lukas Chrostowski, 'Silicon photonics circuit design: methods, tools and challenges'](https://onlinelibrary.wiley.com/doi/full/10.1002/lpor.201700237)

- [Lukas Chrostowski and Michael Hochberg, 'Silicon Photonics Design From Devices to Systems'](https://www.cambridge.org/core/books/silicon-photonics-design/BF3CF13E8542BCE67FD2BBC7104ECEAB) 

- [Wim Bogaerts, Martin Fiers, and Pieter Dumon 'Design Challenges in Silicon Photonics'](https://ieeexplore.ieee.org/abstract/document/6691908)

- [Near Margalit et al., 'Perspective on the future of silicon photonics and electronics'](https://aip.scitation.org/doi/10.1063/5.0050117)

- [Dan-Xia Xu et al., 'Silicon Photonic Integration Platform—Have We Found the Sweet Spot?'](https://ieeexplore.ieee.org/document/6709757?arnumber=6709757)

- [Zhengqi Gao, 'Introduction to Photonic Design Automation'](https://zhengqigao.github.io/articles/Introduction_to_Photonic_Design_Automation.pdf)

    - A 2-page newbie-friendly article. Only high school knowledge required.

## Inverse design (shape/topology optimization)

Adjoint method plus gradient descent optimization appears to be the main stream currently. Using gradients in optimization is named first-order method. On the other hand, zero-order method (optimization without gradient) is occasionally used in inverse design of silicon photonics. 

- [Alexander Y. Piggott et al., 'Inverse design and demonstration of a compact and broadband on-chip wavelength demultiplexer'](https://www.nature.com/articles/nphoton.2015.69)

- [Christopher M. Lalau-Keraly et al., 'Adjoint shape optimization applied to electromagnetic design'](https://opg.optica.org/oe/fulltext.cfm?uri=oe-21-18-21693&id=260994)

- [Mohammad H. Tahersima et al., 'Deep Neural Network Inverse Design of Integrated Photonic Power Splitters'](https://www.nature.com/articles/s41598-018-37952-2)

- [Zhaocheng Liu et al., 'Tackling Photonic Inverse Design with Machine Learning'](https://onlinelibrary.wiley.com/doi/full/10.1002/advs.202002923)

... To be updated