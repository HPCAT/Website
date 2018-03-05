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

## <center> Scalable Cache Coherent Scheme for Distributed Shared Memory Systems </center>
<!--[](/img/People/Sebastian.jpg)-->
<font size="+1">

### Project Description

<br>	

<p style="text-align: justify;">
As we slowly approach the physical limits of processor and memory speed, it is becoming more attractive to use multiprocessors to increase computing power. Two kinds of parallel processors have become popular: tightly coupled shared memory multiprocessor and distributed memory multiprocessors. A tightly coupled multiprocessor system consisting of multiple CPU's and a single global physical memory is more straightforward to program but it has a serious bottleneck: Main memory is accessed via common bus – a serialization point that limits system size to tens of processors. 
</p>

<p style="text-align: justify;">
To scale to larger numbers of processors, designers distributed the memory throughout the machine and used a scalable interconnect to enable processor - memory pairs to communicate. DSM is an architectural approach designed to overcome the scaling limitations of symmetric shared memory multiprocessors while retaining a shared memory model for communication and programming. DSM multiprocessors achieve this by using a memory that is physically distributed but logically implements a single shared address space, allowing the processor to communicate through, and share the contents of, the entire memory. The globally addressable memory model is retained, although memory access times are no longer uniform. The actual time to access a datum could depend on exactly which memory contained the desired address, in reality there is a big difference was between addresses in local memory and addresses in remote memory and hence the name NUMA. DSM multiprocessors also called NUMA (non-uniform memory access). 
</p>

<p style="text-align: justify;">
The communication speed of the traditional interconnection networks, however, cannot match that of the processors, thus degrading system performance. Introducing local caches greatly improves system performance but, cache consistency must be maintained if many copies are allowed to exist in different processors at the same time. Snooping protocols rely on the broadcasting of the information to all caches in the system. The primary problem introduced by this approach in bus saturation. The directory-based coherence protocol removes the broadcast bottleneck that prevents scalability of the snoopy bus based coherence. Directory-based schemes rely on an extra structure, called the directory, which tracks which processors have cached any given block in main memory. Because the directory tracks which caches have copies of any given memory block, a coherence protocol can use the directory to maintain a consistent view of memory. Most recent DSM related research has emphasized on designing efficient directory organization and cache coherence protocols. 

</p>

<p style="text-align: justify;">
There are two fundamental problems associated with Distributed Shared Memory systems. The directory structure is not scalable with the increase in the number of processors in the system and the variable amount of remote latency incurred in order to obtain data from a remote location. In order to solve the DSM problem we have to look at these two factors and provide a comprehensive system addressing the above issues.
</p>


</font>
<br>
<br>
