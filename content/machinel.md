+++
title = "Research Topic"
description = "Greatness"
keywords = ["Graduate","Undergraduate","Student","Doctorate"]
+++

<head>
<style>
//p {
//    text-indent: 50px;
//    }
a {
    font-weight: 900;
    text-decoration: underline;
    }
br {
    line-height: 0.0;
}
</style>
</head>

## <center> Machine Learning for High Performance, Energy-Efficient and Reliable NoCs </center>
<!--[](/img/People/Sebastian.jpg)-->
<font size="+1">

#### Current Researchers: Ke Wang, Hao Zheng, Jie Luo;

<br>	

<img src="/img/Pictures/machinel3.jpg" hspace="20" vspace="10" border="0" align="left" style="float: left; width: 350px;">
<p style="text-align: justify;">
With continued aggressive technology scaling, Network-on- Chips (NoCs)
architectures are facing three major challenges including minimizing power
consumption, scaling performance and providing a reliable and robust
communication limited by area, power, and cost constraints.
</p>

<p style="text-align: justify;">
Researchers have
proposed various techniques individually tackling these challenges, while few
efforts to date have simultaneously targeted improving power, performance and
reliability together. Due to the complexity of the interactions among three
competing objectives and explosion of design space, it is harder to manually
design rules and strategies for interconnection system for optimizing power,
reliability and performance.
</p>
<br>
<p style="text-align: justify;">
In our research, we use Machine Learning (ML) algorithms, which can work with
high-dimensional data and automatically infer complex decisions, to balance
reliability, performance, and energy efficiency for NoCs. We first use supervised
ML algorithms to build predictive decision models, which can optimize competing
goals of two of the three targets (e.g. reliability and performance, performance
and power, etc.).
</p>

<p style="text-align: justify;">
We further use reinforcement learning (RL) to eschew the
prediction step and automatically learn a decision policy that directly maps
system-level states to optimal decisions which can yield maximum benefits on
reducing power, enhancing reliability, and improving performance
simultaneously.
</p>

### 1. Intelligent NoCs using Decision Tree (Supervised Learning) 

#### D. DiTomaso, T. Boraten, A. Kodi and A. Louri, "<a href="/papers/MICRO16.pdf">Dynamic error mitigation in NoCs using intelligent prediction techniques</a>," in <i>Proceedings of the 2016 49th Annual IEEE/ACM International Symposium on Microarchitecture (MICRO)</i>, Taipei, 2016, pp. 1-12.

<p style="text-align: justify;">
We develop a new approach to proactive fault-tolerance which uses machine
learning (ML) algorithms to predict and mitigate errors. We provide a
comprehensive fault-prediction system in which we (a) create a methodology to
obtain realistic data sets, (b) train a ML algorithm to predict timing faults on links,
and (c) mitigate for soft errors. We develop a fault model, which accounts for
parameter variation and device wear-out, to create training/testing data sets for
the ML algorithm. Using the training data set and the ID3 algorithm, we create
decision trees which can be used to accurately predict the number of errors.
Finally, we dynamically mitigate the errors using a combination of error correction
codes (ECC) and a relaxed transmission. Our network results indicate a 26.8%
reduction in packet retransmissions, a 3.31× speedup, and an energy savings of
60.0% on average over other designs.
</p>

### 2. Intelligent NoCs using Regression (Supervised Learning)

#### M. Clark, A. Kodi, R. Bunescu and A. Louri, "<a>LEAD: Learning-enabled Energy-Aware Dynamic Voltage/Frequency Scaling in NoCs,</a>" to appear in <i>Proceedings of the 55th Design Automation Conference (DAC)</i>, San Francisco, CA, 2018.

<p style="text-align: justify;">
Dynamic Voltage and Frequency Scaling (DVFS) is a popular technique that
allows dynamic energy to be saved, but it can potentially lead to loss in
throughput. We propose LEAD - Learning-enabled Energy-Aware Dynamic
voltage/frequency scaling for NoC architectures wherein we use machine learning
techniques to enable energy-performance trade-offs at reduced overhead cost.
LEAD enables a proactive energy management strategy that relies on an offline
trained regression model and provides a wide variety of voltage/frequency pairs
(modes). LEAD groups each router and the router’s outgoing links locally into the
same V/F domain, allowing energy management at a finer granularity without
additional timing complications and overhead. Our simulation shows an average
dynamic energy savings of 17% with a minimal loss of 4% in throughput and no
latency increase.
</p>

#### S. V. Winkle, A. Kodi, R. Bunescu and A. Louri, "<a>Extending the Power-Efficiency and Performance of Photonic Interconnects for Heterogeneous Multicores with Machine Learning,</a>" in <i>Proceedings of the 24th IEEE International Symposium on High-Performance Computer Architecture (HPCA)</i>, Vienna, 2018.

<p style="text-align: justify;">
As communication energy exceeds computation energy in future technologies,
traditional on-chip electrical interconnects face fundamental challenges in the
many-core era. Photonic interconnects have been proposed as a disruptive
technology solution due to superior performance per Watt, distance independent
energy consumption and CMOS compatibility for on-chip interconnects. Static
power due to the laser being always switched on, varying link utilization due to
spatial and temporal traffic fluctuations and thermal sensitivity are some of the
critical challenges facing photonics interconnects. We propose photonic
interconnects for heterogeneous multicores using a checkerboard pattern that
clusters CPU-GPU cores together and implements bandwidth reconfiguration
using local router information without global coordination. To reduce the static
power, we also propose a dynamic laser scaling technique that predicts the power
level for the next epoch using the buffer occupancy of previous epoch. To further
improve power-performance trade-offs, we also propose a regression-based
machine learning technique for scaling the power of the photonic link. Our
simulation results demonstrate a 34% performance improvement over a baseline
electrical CMESH while consuming 25% less energy per bit when dynamically
reallocating bandwidth. When dynamically scaling laser power, our buffer-based
reactive and ML-based proactive prediction techniques show 40 - 65% in power
savings with 0 - 14% in throughput loss depending on the reservation window
size.
</p>

#### D. DiTomaso, A. Sikder, A. Kodi and A. Louri, "<a>Machine learning enabled power-aware Network-on-Chip design,</a>" in <i>Proceedings of the Design, Automation &amp; Test in Europe Conference &amp; Exhibition (DATE), 2017</i>, Lausanne, 2017, pp. 1354-1359.

<p style="text-align: justify;">
NoC designs suffer from excessive static and dynamic power consumption. High
dynamic power consumption results from switching and storing data within
routers/links while excess static power is consumed when routers and links are
not utilized for communication and yet have to be powered up. We propose
LESSON (Learning Enabled Sleepy Storage Links and Routers in NoCs) to
reduce both static and dynamic power consumption by power-gating the links and
routers at low network utilization and moving the data storage from within the
routers to the links at high network utilization. As the network utilization increases
from low-to- high, to accommodate more traffic, we design the same channels to
flow traffic in either direction, thereby avoiding complex routing or look-ahead
wake-up algorithms. Machine learning algorithms predict when to power-gate the
channels and routers and when to increase the channel bandwidths such that
power savings are maximized while performance penalty is minimized. Our results
show that we can improve total network power consumption when compared to
conventional NoC buffer designs by 85.6% and when compared with aggressive
NoC buffer designs by 31.7%. Our predictor shows marginal performance
penalties and by dynamically changing the direction of the links, we can improve
packet latency by 14%.
</p>



</font>
<br>
<br>
