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

## <center> Optical Interconnects for the Design of Large Scale Symmetric Multiprocessors </center>
<!--[](/img/People/Sebastian.jpg)-->
<font size="+1">

### Project Motivation

<br>	

<p style="text-align: justify;">
Symmetric multiprocessors (SMPs) are attractive parallel computers widely used, since they provide a global physical address space and a symmetric access to the entire memory with increased flexibility and programmability. SMPs use fast snooping protocols to maintain cache coherence by broadcasting every request on the shared bus connecting all modules. Contention to acquire the bus in addition to faster processing capabilities of current processors degrades the performance of the shared bus. As the bus speed increases, the processor boards connected to the bus behave as stubs resulting in reflections of bus signals. Other fundamental problems such as impedance mismatch, stray capacitance, D I noise and crosstalk significantly affect the speed improvements of the shared bus. Therefore, the bus speed and the coherence overhead limit the rate at which address requests can be broadcast to all the processors/memory modules. This address rate/bandwidth is the main scaling limit, which cannot follow the increasing demands of faster and large number of processors, limiting the scalability of shared-bus based SMPs.
</p>

### Project Description

<br>

<p style="text-align: justify;">
One technology that can provide high communication bandwidth, low latency and scalability is optical interconnection technology. The recent advances in optical interconnect devices and packaging techniques such as multi-dimensional arrays of vertical cavity surface emitting lasers (VCSELs), arrays of photodetectors (PDs) and waveguide optics are making optical interconnects a serious and potentially viable interconnect technology for parallel computing. Optical pulses can co-exist on the same optical line without interference if they are sufficiently separated. Even though requests can be pipelined by electrical interconnects, the rate at which requests from successive processors can be pipelined using optical technology is much greater and can be achieved without using any expensive multiplexer/demultiplexer circuits. In addition, the delay on optical signal or clock paths (fibers or waveguides) is not strongly dependent on temperature as in the case of electronics, and signal or clock edges do not degrade substantially over the scale of a computer room. It is likely possible to retain absolute timing accuracy in the delivery of optical signals of 10-100 ps over several meters. Moreover, optical interconnect based systems are easily scalable either by adding extra wavelengths or fiber channels in order to incorporate additional processors.
</p>

<p style="text-align: justify;">
This project proposes an integrated solution to solve the address bandwidth requirements of large, scalable SMPs and still use fast snooping protocols to maintain cache coherence with low-latency using optical technology. An address sub-network, called Optical Symmetric Multiprocessor Network (SYMNET) using parallel optical interconnects is proposed with one-to-many communications. Parallel optical interconnects provide higher-bandwidth density product as compared to serial interconnects which provide higher bandwidth product. SYMNET, not only uses passive optical interconnects that increases the speed of the proposed network, but also pipelines address requests at a much faster rate than electronics. By using passive optical technology as opposed to more complex optical switching networks, the optical signal transfer in SYMNET is much faster since there is no optical switching or conversion. This results in increasing the address bandwidth for snooping and provides the impetus to develop scalable SMPs with hundreds of processors using optical interconnects, while using snooping cache coherence schemes. However, the preservation of cache coherence can no longer be maintained with the usual snooping protocols. We have introduced a modified snooping coherence protocol, called Coherence in SYMNET (COSYM) and verified its correctness using several transient states. SYMNET using the COSYM protocol is compared against electrical bus based systems using the MOESI protocol with Splash-2 benchmarks.
</p>

<center>
<img src="/img/Pictures/pic1.jpg" align="center" style="float: center; width: 500px;">
</center>

<center>
<img src="/img/Pictures/pic2.jpg" align="center" style="float: center; width: 500px;">
</center>

<center>
<img src="/img/Pictures/pic3.jpg" align="center" style="float: center; width: 500px;">
</center>

### Publications

<br>

<p style="text-align: justify;">
A. Louri and A. K. Kodi, &ldquo;<a href="/papers/tpds_symnet.pdf">An optical
interconnection network and a modified snooping protocol for the design
of large-scale symmetric multiprocessors (SMPs)</a>,&rdquo; in <i>IEEE
Transactions on Parallel and Distributed Systems</i>, vol. 15, no. 12,
pp. 1093-1104, Dec. 2004.
</p>

<p style="text-align: justify;">
A. K. Kodi and A. Louri, &ldquo;<a href="/papers/symnet_fio_03.pdf">Parallel
Optical Interconnection Network for SMPs</a>,&rdquo; in <i>Proceedings of Frontiers in Optics
2003</i>, Tucson, AZ, 2003, pp. 1-1.
</p>

<p style="text-align: justify;">
A. Louri and    A. K. Kodi, &ldquo;<a href="/papers/aiccsa03.pdf">Design of
large-scale symmetric multiprocessors (SMPs) using parallel optical
interconnects</a>,&rdquo; in <i>Proceedings of the ACS/IEEE International Conference on Computer
Systems and Applications, 2003</i>, Tunis, Tunisia, 2003, pp. 11-14.
</p>

<p style="text-align: justify;">
A. Louri and A. K. Kodi, &ldquo;<a href="/papers/symnet.pdf">SYMNET: an
optical interconnection network for scalable high-performance symmetric
multiprocessors</a>,&rdquo; in <i>Applied Optics</i>, vol. 42, no. 17, pp.
3407-3417, June 2003.
</p>

<p style="text-align: justify;">
A. Louri and A. K. Kodi, &ldquo;<a href="/papers/ieee_symnet.pdf">Parallel
optical interconnection network for address transactions in large-scale
cache coherent symmetric multiprocessors</a>,&rdquo; in <i>IEEE Journal of
Selected Topics in Quantum Electronics, Special Issue on Optical
Interconnects</i>, vol. 9, no. 2, pp. 667-676, Mar.-Apr. 2003.
</p>

<p style="text-align: justify;">
A. Louri and A. K. Kodi, &ldquo;<a href="/papers/symnet.pdf">Scalable
Optical Interconnection Networks for Symmetric Multiprocessors
(SMPs)</a>&rdquo;, in <i>Optics in Information Systems, SPIE&rsquo;s International
Technical Group Newsletter</i>, vol. 14, no. 1, pp. 7-8, Mar. 2003.
</p>

<p style="text-align: justify;">
A. K. Kodi and A. Louri, &ldquo;<a>Optical Interconnects for Large-Scale
Symmetric Multiprocessor Networks,</a>&rdquo; in <i>Proceedings of Optics in Computing 2002</i>,
Taipei, 2002, pp. 1-1.
</p>

<p style="text-align: justify;">
A. K. Kodi and A. Louri, &ldquo;<a href="/papers/leos01.pdf">Y-junction based
addressing in optical symmetric multiprocessor networks</a>,&rdquo; in <i>Proceedings of the 14th
Annual Meeting of the IEEE Lasers and Electro-Optics Society (LEOS
&lsquo;01)</i>, San Diego, CA, 2001, pp. 865-866.
</p>





</font>
<br>
<br>
