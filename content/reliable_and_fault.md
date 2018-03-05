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

## <center> Reliable and Fault-Tolerant Network-on-Chips for Multi-Core Architectures and Embedded Systems </center>
<!--[](/img/People/Sebastian.jpg)-->
<font size="+1">

### Project Description

<br>	

<p style="text-align: justify;">
This research addresses the reliability and fault tolerance of the Network-on-Chip (NoC) as the number of cores on the chip increases. It balances reliability, power-efficiency and performance. It consists of four inter related projects: (1) Multi-layer fault tolerance spanning from devices to applications (2) Tackling both hard faults and soft errors within a NoC router (3) Tackling only hard faults within a NoC router (4) Tackling only soft errors within a NoC router.
</p>

### Publications

<br>

#### Multi-Layer Fault Tolerance

<p style="text-align: justify;">
Recently, NoC reliability research has made significant strides and has developed a suite of canonical approaches to improve failure resistance including the use of redundant components and logic for self-repair at the circuit layer, redundant wires and error correction codes at the data layer, and reconfiguration and fault-tolerant routing algorithms at the network layer. Unfortunately much of the current techniques focus on a single-layer (or few layers). A major drawback of these approaches is that their lack of system-wide information (system here is the entire NoC) across all the layers forces them to consider local optimizations within the given layer and impose worst-case power and performance overheads. There is very little research that exploits interactions across all the layers in order to provide system-wide reliability with globally optimized power, performance, and costs. This research deals with proposing a comprehensive, cooperative and adaptive multi-layer approach for designing reliable NoCs from fault susceptible components, with globally-optimized power, performance and costs.
</p>

#### Tackling both hard faults and soft errors within a NoC Router

<p style="text-align: justify;">
P. Poluri and A. Louri, &ldquo;<a href="/papers/shield-paper.pdf">Shield: A
Reliable Network-on-Chip Router Architecture for Chip
Multiprocessors</a>,&rdquo; in <i>IEEE Transactions on Parallel and
Distributed Systems</i>, vol. 27, no. 10, pp. 3058-3070, Oct. 2016.
</p>

<p style="text-align: justify;">
The increasing number of cores on a chip has made the Network on Chip (NoC) concept the standard communication paradigm for Chip Multiprocessors. A fault in an NoC leads to undesirable ramifications that can severely impact the performance of a chip. Therefore, it is vital to design fault-tolerant NoCs. In this paper, we present Shield, a reliable NoC router architecture that has the unique ability to tolerate both hard faults and soft errors in the routing pipeline using techniques such as spatial redundancy, exploitation of idle cycles, bypassing of faulty resources and selective hardening. Using Mean Time to Failure and Silicon Protection Factor metrics, we show that Shield is six times more reliable than the baseline-unprotected router and is at least 1.5 times more reliable than existing fault tolerant router architectures.We introduce a new metric called Soft Error Improvement Factor and show that the soft error tolerance of Shield has improved by three times in comparison to the baseline-unprotected router. This reliability improvement is accomplished by incurring an area and power overhead of 34% and 31% respectively. Latency analysis using SPLASH-2 and PARSEC reveals that in the presence of faults, latency increases by a modest 13% and 10% respectively.
</p>

#### Tackling hard faults within a NoC Router

<p style="text-align: justify;">
P. Poluri and A.    Louri, &ldquo;<a href="/papers/ipdps14.pdf">An Improved
Router Design for Reliable On-Chip Networks</a>,&rdquo; in <i>Proceedings of the 2014 IEEE 28th
International Parallel and Distributed Processing Symposium</i>,
Phoenix, AZ, 2014, pp. 283-292.
</p>

<p style="text-align: justify;">
Aggressive technology scaling into the deep nanometer regime has made the Network-on-Chip (NoC) in multicore architectures increasingly vulnerable to faults. This has accelerated the need for designing reliable NoCs. To this end, we propose a reliable NoC router architecture capable of tolerating multiple permanent faults. The proposed router achieves a better reliability without incurring too much area and power overhead as compared to the baseline NoC router or other fault-tolerant routers. Reliability analysis using Mean Time to Failure (MTTF) reveals that our proposed router is six times more reliable than the baseline NoC router (without protection). We also compare our proposed router with other existing fault-tolerant routers such as BulletProof, Vicis and RoCo using Silicon Protection Factor (SPF) as a metric. SPF analysis shows that our proposed router is more reliable than the mentioned existing fault tolerant routers. Hardware synthesis performed by Cadence Encounter RTL Compiler using commercial 45nm technology library shows that the correction circuitry incurs an area overhead of 31% and power overhead of 30%. Latency analysis on a 64-core mesh based NoC simulated using GEM5 and running SPLASH-2 and PARSEC benchmark application traffic shows that in the presence of multiple faults, our proposed router increases the overall latency by only 10% and 13% respectively while providing better reliability.
</p>

<br>

<p style="text-align: justify;">
P. Poluri and A. Louri, &ldquo;<a href="/papers/sbac13.pdf">Tackling
Permanent Faults in the Network-on-Chip Router Pipeline</a>,&rdquo; in <i>Proceedings of the 2013
25th International Symposium on Computer Architecture and High
Performance Computing</i>, Porto de Galinhas, 2013, pp. 49-56.
</p>

<p style="text-align: justify;">
The proliferation of multi-core and many-core chips for performance scaling is making the Network-on-Chip (NoC) occupy a growing amount of silicon area spanning several metal layers. The NoC is neither immune to hard faults and transient faults nor unaffected by the adverse increase in hard faults caused by technology scaling. The ramifications for the NoC are immense: a single fault in the NoC may paralyze the working of the entire chip. To this end, we propose a Permanent Fault Tolerant Router (PFTR) that is capable of tolerating multiple permanent faults in the pipeline. PFTR is designed by making architectural modifications to individual pipeline stages of the baseline NoC router. These architectural modifications involve adding minimum extra circuitry and exploiting temporal parallelism to accomplish fault tolerance. Tolerance of multiple faults is achieved by striking a balance between three important design factors namely, area overhead, power overhead and reliability. We use Silicon Protection Factor (SPF) as the reliability metric to assess the reliability improvement of the proposed architecture. SPF takes into account the number of faults required to cause failure and the area overhead of the additional circuitry to evaluate reliability. SPF calculation reveals that the proposed PFTR is 11 times more reliable than the baseline NoC router. Synthesis results using Cadence Encounter RTL Compiler at 45nm technology show that the additional circuitry adds an area overhead of 31% and power overhead of 30% with respect to the baseline NoC router. PFTR provides much better reliability with much less overhead as compared to other fault tolerant routers such as BulletProof, Vicis and RoCo.
</p>

<br>

<p style="text-align: justify;">
Jacques Henri Collet, Ahmedmed Louri, Vivek Tulsidas Bhat, and Pavan
Poluri. 2011. <a href="/papers/Fault-ROBUST.pdf">ROBUST: a new
self-healing fault-tolerant NoC router</a>. In <i>Proceedings of the 4th
International Workshop on Network on Chip Architectures</i> (NoCArc
&lsquo;11). ACM, New York, NY, pp. 11-16.
</p>

<p style="text-align: justify;">
This work addresses the general problem of making Network-on-Chips (NoCs) routers totally self-healing in massively defective technologies. There are three main contributions. First, we propose a new hardware approach based on Built-In Self-Test techniques and multi-functional blocks (called Universal Logic Blocks, ULBs) to autonomously diagnose permanent faults and repair faulty units. ULBs have the capability to assume the functionality of various functional units within the router through simple reconfiguration and thus enable the repair of multiple permanent faults within the NoC router. Second, we propose a new reliability metric and introduce a probabilistic model to estimate the router reliability improvement achieved by the protection circuitry. Third, we compare our architecture to two router architectures (Vicis and Bulletproof) and we show that our design provides superior reliability improvement especially in extremely defective nanoscale technologies (i.e., typically above 30% of faulty routers). The most striking result is that the self-healing of the routers enables maintaining the communications at fault levels, where it is normally impossible to preserve communications.
</p>


#### Tackling Soft Errors within the NoC Router

<p style="text-align: justify;">
P. Poluri and A. Louri, &ldquo;<a href="/papers/STNR.pdf">A Soft Error
Tolerant Network-on-Chip Router Pipeline for Multi-Core Systems</a>,&rdquo; in
<i>IEEE Computer Architecture Letters</i>, vol. 14, no. 2, pp. 107-110,
July-Dec. 2015.
</p>

<p style="text-align: justify;">
Network-on-Chip (NoC) paradigm is rapidly evolving into an efficient interconnection network to handle the strict communication requirements between the increasing number of cores on a single chip. Diminishing transistor size is making the NoC increasingly vulnerable to both hard faults and soft errors. This paper concentrates on soft errors in NoCs. A soft error in an NoC router results in significant consequences such as data corruption, packet retransmission and deadlock among others. To this end, we propose Soft Error Tolerant NoC Router (STNR) architecture, that is capable of detecting and recovering from soft errors occurring in different controlstages of the routing pipeline. STNR exploits the use of idle cycles inherent in NoC packet routing pipeline to perform time redundant executions necessary for soft error tolerance. In doing so, STNR is able to detect and correct all single transient faults in the control stages of the pipeline. Simulation results using PARSEC and SPLASH-2 benchmarks show that STNR is able to accomplish such high level of soft error protection with a minimal impact on latency (an increase of 1.7 % and 1.6 % respectively). Additionally, STNR incurs an area overhead of 7% and power overhead of 13% as compared to the baseline unprotected router.
</p>



</font>
<br>
<br>
