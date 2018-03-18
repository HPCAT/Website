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

<img src="/img/Pictures/option6.png" hspace="20" vspace="10" border="0" align="left" style="float: left; width: 350px;">
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

<br>

<center>
<img src="/img/Pictures/hete1.png" align="center" style="float: center;width: 700px;">
</center>

<br>

#### R. Morris, A. K. Kodi and A. Louri, "<a href="/papers/micro12.pdf">Dynamic Reconfiguration of 3D Photonic Networks-on-Chip for Maximizing Performance and Improving Fault Tolerance</a>," in <i>Proceedings of the 2012 45th Annual IEEE/ACM International Symposium on Microarchitecture</i>, Vancouver, BC, 2012, pp. 282-293.

<p style="text-align: justify;">
As power dissipation in future Networks-on- Chips (NoCs) is projected to be a major bottleneck,
researchers are actively engaged in developing alternate power-efficient technology solutions. Photonic
interconnects is a disruptive technology solution that is capable of delivering the communication
bandwidth at low power dissipation when the number of cores is scaled to large numbers. Similarly, 3D
stacking is another interconnect technology solution that can lead to low energy/bit for communication.
In this paper, we propose to combine photonic interconnects with 3D stacking to develop a scalable,
reconfigurable, power-efficient and high-performance interconnect for future many-core systems, called
R-3PO (Reconfigurable 3D-Photonic Networks-on- Chip).
</p>

<p style="text-align: justify;">
We propose to develop a multi-layer photonic
interconnect that can dynamically reconfigure without system intervention and allocate channel
bandwidth from less utilized links to more utilized communication links. In addition to improving
performance, reconfiguration can re-allocate bandwidth around faulty channels, thereby increasing the
resiliency of the architecture and gracefully degrading performance. For 64-core reconfigured network,
our simulation results indicate that the performance can be further improved by 10%-25% for Splash-2,
PARSEC and SPEC CPU2006 benchmarks, whereas simulation results for 256-core chip indicate a
performance improvement of more than 25% while saving 6%-36% energy when compared to state-of-
the-art on-chip electrical and optical networks.
</p>

<br>

<center>
<img src="/img/Pictures/hete2.png" align="center" style="float: center;width: 450px;">
<img src="/img/Pictures/hete3.png" align="center" style="float: center;width: 400px;">
</center>

<br>

#### R. Morris, A. K. Kodi and A. Louri, "<a href="/papers/iccd12.pdf">3D-NoC: Reconfigurable 3D photonic on-chip interconnect for multicores</a>," in <i>Proceedings of the 2012 IEEE 30th International Conference on Computer Design (ICCD)</i>, Montreal, QC, 2012, pp. 413-418.

<p style="text-align: justify;">
The power dissipation of metallic interconnects in future multicore architectures is projected to be a
major bottleneck as we scale to sub-nanometer regime. This has motivated researchers to develop
alternate power-efficient technology solutions to the performance limitations of future multicores.
Nanophotonic interconnects (NIs) is a disruptive technology solution that is capable of delivering the
communication bandwidth at low power dissipation when the number of cores is scaled to large numbers.
Similarly, 3D stacking is another interconnect technology solution that can lead to low energy/bit for
communication.
</p>

<p style="text-align: justify;">
In this paper, we propose to combine NIs with 3D stacking to develop a scalable,
reconfigurable, power-efficient and high-performance interconnect for future many-core systems called
3D-NoC. We propose to develop a multi-layer NIs that can dynamically reconfigure without system
intervention and allocate channel bandwidth from less utilized links to more utilized communication links.
Our simulation results indicate that the performance can be further improved by 10%-25% for Splash-2,
PARSEC and SPEC CPU2006 benchmarks.
</p>

<br>

<center>
<img src="/img/Pictures/hete4.png" align="center" style="float: center;width: 400px;">
<img src="/img/Pictures/hete5.png" align="center" style="float: center;width: 600px;">
</center>

<br>

### 2. Heterogeneous Technologies

#### A. Sikder, A. Kodi, S. Kaya, D. Carbaugh, S. Laha, A. Louri, H. Xin and J. Wu, "<a>Sustainability in Network-on-Chips by Exploring Heterogeneity in Emerging Technologies,</a>" to appear in <i>IEEE Transactions on Sustainable Computing</i>, 2018.

<p style="text-align: justify;">
With the scaling of technology, the computing industry is experiencing a shift from multi-core to many-
core architectures. However, traditional metallic-based on-chip interconnects may not scale to support
many-core architectures due to high power dissipation, and increased communication latency. Attention
has recently shifted to emerging technologies such as silicon-photonics and wireless interconnects to
implement future on-chip communications. Although emerging technologies show promising results for
power-efficient, low-latency, and scalable on-chip interconnects, the use of single technology may not be
sufficient to scale future architectures. This encourages the introduction of heterogeneity in the use of
emerging technologies for NoCs.
</p>

<p style="text-align: justify;">
In this paper, we extend the heterogeneous architecture Optical-
Wireless Network-on- Chip (OWN [1]) to Reconfigurable Optical-Wireless Network-on- Chip (R-OWN) by
introducing run-time reconfigurable wireless channels. Like OWN, R-OWN is designed such that one-hop
photonic interconnect is used up to 64 cores (called a cluster) and communication beyond a cluster is one-
hop wireless to limit the network diameter to a maximum of three hops. The photonic bandwidth is
efficiently shared using time division multiplexing (TDM) while the wireless bandwidth is shared using
frequency division multiplexing (FDM). Packets routed across technologies are proved to be deadlock-
free. We propose a preliminary assessment of implementing heterogeneous technologies with the router
microarchitecture.
</p>

<p style="text-align: justify;">
Further, we also discuss the design of horn antenna for implementing the wireless
channels. Our results indicate that R-OWN improves the performance (throughput and latency) by 15%
when compared to OWN while consuming 7% more energy than OWN. Further, OWN and R-OWN
improve energy-efficiency by 54-61% when compared to WCube and CMesh architectures respectively. It
should be noted that both OWN and R-OWN require less area than state-of- the-art wired, wireless and
optical on-chip networks.
</p>

<br>

<center>
<img src="/img/Pictures/hete6.png" align="center" style="float: center; width: 500px;">
</center>

<br>

### 3. Communication in Heterogeneous ArchitecturesExtending the Power-Efficiency and Performance of Photonic Interconnects for Heterogeneous Multicores with Machine Learning

#### S. V. Winkle, A. Kodi, R. Bunescu and A. Louri, "<a>Extending the Power-Efficiency and Performance of Photonic Interconnects for Heterogeneous Multicores with Machine Learning,</a>" to appear in <i>Proceedings of the 24th IEEE International Symposium on High-Performance Computer Architecture (HPCA)</i>, Vienna, 2018.

</font>
<br>
<br>
