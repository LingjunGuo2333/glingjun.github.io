---
permalink: /
title: "Lingjun's Homepage!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi there, welcome to my homepage! I wish to share my academic and personal interests with you here!

I'm a second year master student [@UMIOE](https://ioe.engin.umich.edu/), where I have taken courses focused on theoretical side of optimization. I was also fortunate enough to join into Prof.[Salar Fattahi](https://fattahi.engin.umich.edu/)'s research group working on basis function decomposition for deep neural networks. Prior to that, I recieved my B.S. degree in [Mathematics and Applied Mathematics](https://math.fudan.edu.cn/) in Fudan University, China.  

You can find my CV [here](https://github.com/LingjunGuo2333/glingjun.github.io/tree/master/files/CV_lingjun_guo.pdf) if interested!

Research Interests
======

I'm interested in optimization theories and modeling real world problems. In particular, I'm interested in theories and applications of optimization in healthcare, machine learning and market, etc. I'm also interested in mathematical models in sociology problems. 

Projects:
======

Basis Function Decomposition for Deep Neural Networks
------
<img src="gradient-descent-optimal.jpg">

In this work, we showed that for certain basis functions, deep neural networks (DNNs) can <b>monotonically</b> learn the coefficients for these bases. More specifically, we construct theoretic basis functions for symmetric matrix (SM) and orthogonal symmetric tensors (OST), respectively. Using these basis functions, we give new convergence results for SM and OST decomposition problems. In practice, we propose conjugate after kernel (A-CK) after training as basis functions for practical DNNs, and we demonstrate the monotone learning phenomenon for a wide range of models, datasets, solvers, and loss functions.

[Behind the scenes of gradient descent: A trajectory analysis via basis function decomposition.](https://arxiv.org/abs/2210.00346)[Code.](https://github.com/jianhaoma/function-basis-decomposition)

Distributed Semi-smooth Newton Augmented Lagrangian algorithm for high dimensional data
------
In this work, we proposed a distributed semi-smooth second-order algorithm for Lasso loss in high-dimensional data. To be specific, different features of data are only known to local workers in a master-worker network, where worker-to-worker communication is prohibited. We propose a distributed algorithm using a semi-smooth Newton Augmented Lagrangian method, and it can reach high accuracy in a comparable time. Our method converges even faster when applied with good initialization points.



Preprints:
======
Jianhao Ma, <b>Lingjun Guo</b>, and Salar Fattahi. Behind the scenes of gradient descent: A trajectory analysis via basis function decomposition. 2022.
[arXiv preprint arXiv:2210.00346](https://arxiv.org/abs/2210.00346). [[code]](https://github.com/jianhaoma/function-basis-decomposition)

Contact:
------
Please feel free to drop an email to me: [lingjunguo2333@gmail.com](mailto:lingjunguo2333@gmail.com) or [glingjun@umich.edu](mailto:glingjun@umich.edu).
