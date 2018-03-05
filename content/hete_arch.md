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

## <center> Accelerator-rich Heterogeneous Architectures </center>
<!--[](/img/People/Sebastian.jpg)-->
<font size="+1">

#### Current Researchers: TBD;

<br>

<img src="/img/Pictures/hetev3.png" hspace="20" vspace="10" border="0" align="left" style="float: left; width: 350px;">
<p style="text-align: justify;">
In the dark silicon era, only a fraction of transistors on a chip can be switched simultaneously due to
constrained power budget. To improve energy-efficiency, general-purpose cores are augmented with
specialized hardware or accelerators. These accelerators, which are optimized for specific applications
(e.g., application-specific integrated circuits), can improve energy efficiency per operation by orders
of magnitude over software running on general-purpose cores.
</p>

<p style="text-align: justify;">
The integration of general-purpose
cores with accelerators on the same chip in a heterogeneous design environment, places several
challenges on the NoC design. The NoC needs to be heterogeneous to support different cores and
accelerators and different activated subsets of on-chip nodes. Besides, traffic over the NoC can have
dynamically varying patterns based on application demands. In this research project, we address the
NoC design challenges, by fully exploring the traffic models of diverse types of cores and accelerators,
and then designing network architectures that can be configured to adapt to specific workloads.
</p>

<p style="text-align: justify;">
Additionally, we consider heterogeneous technologies for the implementation of these accelerator-
rich architectures. Recent 3-D integration techniques have enabled multiple logic dies, and memory
dies of different technologies (SRAM, DRAM, NVM etc.) to be integrated on the same chip.
</p>

<p style="text-align: justify;">
It
complicates NoC design by incorporating new vertical channels and enabling more flexible memory
access schemes. We are exploring 3-D NoC design and heterogeneous technologies for fast and high-
bandwidth inter-core communication and on-chip memory access.
</p>

### 1. On-Chip Interconnects in 3-D Architectures 

#### R. W. Morris, A. K. Kodi, A. Louri and R. D. Whaley, "<a href="/papers/IEEETrans_Comp_Jan2014.pdf">Three-Dimensional Stacked Nanophotonic Network-on-Chip Architecture with Minimal Reconfiguration</a>," in <i>IEEE Transactions on Computers</i>, vol. 63, no. 1, pp. 243-255, Jan. 2014.

<p style="text-align: justify;">
As throughput, scalability, and energy efficiency in network-on- chips (NoCs) are becoming critical, there is
a growing impetus to explore emerging technologies for implementing NoCs in future multicore and
many-core architectures. Two disruptive technologies on the horizon are nanophotonic interconnects
(NIs) and 3D stacking. NIs can deliver high on-chip bandwidth while delivering low energy/bit, thereby
providing a reasonable performance-per- watt in the future. Three-dimensional stacking can reduce the
interconnect distance and increase the bandwidth density by incorporating multiple communication
layers. In this paper, we propose an architecture that combines NIs and 3D stacking to design an energy-
efficient and reconfigurable NoC. 
</p>

<p style="text-align: justify;">
We quantitatively compare the hardware complexity of the proposed
topology to other nanophotonic networks in terms of hop count, network diameter, radix, and photonic
parameters. To maximize performance, we also propose an efficient reconfiguration algorithm that
dynamically reallocates channel bandwidth by adapting to traffic fluctuations. For 64-core reconfigured
network, our simulation results indicate that the execution time can be reduced up to 25 percent for
Splash-2, PARSEC, and SPEC CPU2006 benchmarks. Moreover, for a 256-core version of the proposed
architecture, our simulation results indicate a throughput improvement of more than 25 percent and
energy savings of 23 percent on synthetic traffic when compared to competitive on-chip electrical and
optical networks.
</p>

</font>
<br>
<br>
