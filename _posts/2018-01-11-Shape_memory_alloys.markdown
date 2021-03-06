---
layout: post
title:  "Shape memory alloys"
date:   2018-01-11
author: "Joephy"
header-img: "img/post-bg-os-metro.jpg"
catalog: true
tag:
- Introduction/介绍
comments: true
---
An introduction to shape memory alloys
------------

The concepts of shape memory alloy and phase transition will be introduced. 

SMAs are materials that can remember their shapes under a thermo-mechanical loading. SMAs have two outstanding effects:

(1) Shape memory effect: it means that one can heat up the materials to recover the residual strain after a very huge plastic-like mechanical’s loading;
(2) Pseudoelasticity effect: it means that materials can go back to its original shape under a mechanical loading and unloading. Because these two outstanding mechanisms, SMAs have been widely used in industry and daily life, such as bio-simulation robot, stents and actuator.

![](https://raw.githubusercontent.com/joephy/joephy.github.io/master/_posts/img/SMA1.png)
![](https://raw.githubusercontent.com/joephy/joephy.github.io/master/_posts/img/SMA2.png)
![](https://raw.githubusercontent.com/joephy/joephy.github.io/master/_posts/img/SMA3.png)
![](https://raw.githubusercontent.com/joephy/joephy.github.io/master/_posts/img/SMA4.png)


The mechanism of the pseudoelasticity effect and shape memory effect is the thermo-elastic martensite phase transition. Usually, people call the high temperature phase austenite, whose symmetry is higher and energy potential is lower.For the low temperature phase, it is martensite, whose symmetry is lower and energy potential is higher. If the materials go through the phase transition from austenite to martensite, the entropy will decrease and material will release heat to the environment, inversely it is the same. 

Then, I will introduce the difference between two conditions: with external mechanical loading and without external mechanical loading.

(1) Without external mechanical loading: when heating up the materials from $M_f$ to $A_s$, the phase transition will initiate. Keep the temperature going up and reach $A_f$ the material totally becomes austenite. Inversely, when cooling down the austenitic alloy, when the temperature reach $M_s$, the alloy will begin transform and when the temperature below $M_f$, the alloy will become martensite again. In general, these four special temperature points obey the relation: $M_f < M_s < A_s < A_f$. This kind of effect relates to the shape memory effect but it is not the whole story of shape memory effect. I will explain later.


![](https://raw.githubusercontent.com/joephy/joephy.github.io/master/_posts/img/SMA5.png)

 (2) With external mechanical loading: Imagine that in the beginning, the SMAs is in martensite phase and the temperature is below $M_f$. Applying sufficient high stress will detwin the martensite and the shape of the alloy will change. After that, if we unload the material and make the external stress equaling to 0, it will still be detwinned martensite with no shape change. Then using some devices to heat up the material, let the temperature across the $A_f$ and it will go back to its original shape. If we cool it down below $M_f$ again, the alloy will not change its shape but the atoms inside will be arranged again and become twined martensite as the beginning. This process is the shape memory effect.

The shape memory effect concludes the thermal loading and the external mechanical loading. Bur for the pseudoelasticity effect, the process is clear. It will just happen under a constant temperature. Now let’s suppose the original situation of a SMAs is austenite and the temperature is fixed above $A_f$. Applying the external stress on the material until $\sigma_f$, the material will go through the process as the thermal loading process and become detwinned martensite accompany with huge shape change if the $\sigma_f$ is very high. If will recover back if we release it and the shape will go back to its original shape. This is the pseudoelasticity effect.


The reversible martensite phase transition is the reason for the shape memory effect and pseudoelasticity effect. But in real life, not all of the SMAs are highly reversible because dislocation, inclusions, defects in the material and geometric compatibility conditions will affect the reversibility of the materials. It means that maybe thousands times of phase transition in one material will break it into trash. So many researchers are working on it to improve the mechanical performances of the SMAs to spread the function of it.


Reference:

1. [J. M. Jani, M. Leary, A. Subic, and M. A. Gibson, "A review of shape memory alloy research, applications and opportunities," Materials & Design, vol. 56, pp. 1078-1113, 2014.](http://www.sciencedirect.com/science/article/pii/S0261306913011345)
2. [R. G. L. Alboul, C. M. M. Witkowski, and T. J. P. J. Penders, "Towards Autonomous Robotic Systems," 2013.](https://link.springer.com/content/pdf/10.1007/978-3-642-23232-9.pdf)
3. [N. Morgan, "Medical shape memory alloy applications—the market and its products," Materials Science and Engineering: A, vol. 378, no. 1, pp. 16-23, 2004.](http://www.sciencedirect.com/science/article/pii/S0921509303015132)
4. [F. T. Calkins and J. H. Mabe, "Shape memory alloy based morphing aerostructures," Journal of Mechanical Design, vol. 132, no. 11, p. 111012, 2010.](http://mechanicaldesign.asmedigitalcollection.asme.org/article.aspx?articleid=1450417)
5. [M. M. Ali and K. Takahata, "Frequency-controlled wireless shape-memory-alloy microactuators integrated using an electroplating bonding process," Sensors and Actuators A: Physical, vol. 163, no. 1, pp. 363-372, 2010.](http://www.sciencedirect.com/science/article/pii/S0924424710003651)
6. [M. Dolce and D. Cardone, "Mechanical behaviour of shape memory alloys for seismic applications 2. Austenite NiTi wires subjected to tension," International Journal of Mechanical Sciences, vol. 43, no. 11, pp. 2657-2677, 2001.](http://www.sciencedirect.com/science/article/pii/S0020740301000509)
7. [K. Bhattacharya, Microstructure of martensite: why it forms and how it gives rise to the shape-memory effect. Oxford University Press, 2003.](https://books.google.com.hk/books?hl=en&lr=&id=gas0P67KijcC&oi=fnd&pg=PA1&dq=K.+Bhattacharya,+Microstructure+of+martensite:+why+it+forms+and+how+it+gives+rise+to+the+shape-memory+effect.+Oxford+University+Press,+2003.&ots=n3ly8AE1ue&sig=wEyolXuAojGhsXgT_mZm7bgbAgU&redir_esc=y#v=onepage&q=K.%20Bhattacharya%2C%20Microstructure%20of%20martensite%3A%20why%20it%20forms%20and%20how%20it%20gives%20rise%20to%20the%20shape-memory%20effect.%20Oxford%20University%20Press%2C%202003.&f=false)
8. [Y. Song, X. Chen, V. Dabade, T. W. Shield, and R. D. James, "Enhanced reversibility and unusual microstructure of a phase-transforming material," Nature, vol. 502, no. 7469, pp. 85-88, 2013.](https://www.nature.com/articles/nature12532)

