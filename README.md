## PORVIR-5G Project
<p align="justify">
</p>
<p align="center">
    <img src="PORVIR-5G-logo-fundo-claro.png"/> 
</p>

[Description](#description) | [Members](#members) | [Publications](#publications) | [Development](#development) | [News](#news) | [Acknowledgement](#acknowledgement)

## Description
<p align="justify">
The expected massive growth of mobile Internet traffic in 5G mobile networks introduces the need to change the operators’ networks. Such networks require a drastic transformation towards open, scalable and elastic ecosystems supporting new types of communication. The PORVIR-5G project will develop and demonstrate a programmable fronthaul and backhaul integrating wireless with optical-packet networks and cloud solutions. It is intended to exploit virtual network splits that optimise resource allocation across the wireless, optical, packet, and compute/storage domains. Key enablers for PORVIR-5G are (i) Slicing over packet, wireless, and optical resources, controlled by (ii) deep programmability interfaces, where the devices are configured by network functions to provide the required performance for the future applications on the Internet. This programmability allows a more refined (iii) end-to-end and multilayer orchestration, considering the quality of experience of the users for each type of applications over the network. This project will validate and demonstrate the proposed programmability and virtualization capabilities in three demonstrations, each one of them enabling the key performance demands of 5G networks: an Internet of Things demonstrator focusing on massive machine-type communication; a smart city demonstration for reliable and ultra-low latency flows; and a high bandwidth video demonstrator showcasing the next-generation mobile broadband. 
</p>

## Members
<p align="center">
    <img src="UFES.png" height="60"/> <img src="UFMG.png" height="100"/> <img src="UFRGS.png" height="70"/> <img src="UNICAMP.png" height="80"/> <img src="unisinos.png" height="100"/>
</p>

## Publications

<details><summary>G. Miranda, D. F. Macedo and J. M. Marquez-Barja, <i>"Estimating Video on Demand QoE from Network QoS through ICMP Probes,"</i> in IEEE Transactions on Network and Service Management, doi: <a href="https://doi.org/10.1109/TNSM.2021.3129610">10.1109/TNSM.2021.3129610</a>.</summary>
    <strong>Abstract:</strong> With the increasing traffic of vod, network providers are seeking to deliver high qoe for their users. Many methods have been proposed to assess vod-related qoe. Some of them rely on client instrumentation and reporting qoe information to network elements, such as Server and Network Assisted DASH, others are based on statistical methods that make qoe inferences using monitored network conditions, such as throughput and delays. In this article, we present a practical method to estimate qoe for vod using the widely supported icmp probes. Measured network conditions are used as input to a ml model that estimates qoe in terms of mos, based on the ITU-T P.1203 Recommendation. The estimation encompasses video quality switches and playback stalls. We estimate mos with an average rmse of 1.05 for a catalog of 25 different videos, training a model with sessions of the shortest video, and evaluating the generalization to the full catalog. We performed experiments using a virtualized setup as well as in a Wide Area Network.
    <strong>URL:</strong> <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9622751&isnumber=5699970">https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9622751&isnumber=5699970</a>
</details>
<br/>

<details><summary>G. Miranda, E. Municio, J. M. Marquez-Barja and D. F. Macedo, <i>"Machine Learning-based End-to-End QoE Monitoring Using Active Network Probing,"</i> in 25th Conference on Innovation in Clouds, Internet and Networks and Workshops (ICIN), 2022, Paris.</summary>
    <strong>Abstract:</strong> Abstract here!
    <strong>URL:</strong> To appear
</details>
<br/>

<details><summary>T. A. N. do Amaral, R. V. Rosa, D. M. and C. E. Rothenberg, An In-Kernel Solution Based on XDP for 5G UPF:  Design, Prototype and Performance Evaluation,"</i> in 1st Joint International Workshop on Network Programmability & Automation (NetPA), 2021.</summary>
    <strong>Abstract:</strong>The edge computing infrastructure can scale from datacenters to single
device. The well-known technology for fast packet processing is DPDK, which
has outstanding performance regarding the throughput and latency. However,
there are some drawbacks when the usage is done in the edge: (i) the
polling mechanism for packet processing keeps the CPU exclusively occupied
even if there is no traffic, leading to wasted resources; and (ii) DPDK
interface becomes unavailable for the applications inside the host, so the
integration between a non-DPDK application and a DPDK application becomes a
hard task. In this paper, we propose an open-source in-kernel 5G UPF
solution based on 3GPP Release 16 to be deployed in a restrictive
environment like MEC, where MEC host and UPF are collocated with the Base
Station, sharing the same computational and network resources. The solution
leverages the eBPF/XDP, a novel Linux kernel technology for fast packet
processing. We show it can scale and achieve 10 Mpps using only 60% of the
CPU with 6 cores.
    <strong>URL:</strong> <a href="https://github.com/navarrothiago/upf-bpf">https://github.com/navarrothiago/upf-bpf</a> 
</details>
<br/>

## Development 
Source routing (SR) is a prominent alternative to table-based routing for reducing the number of network states. Actually the traditional SR approaches, based on Port Switching, still maintain a state in the packet by using a header rewrite operation. The residue number system (RNS) is a promising way to achieve fully stateless SR, in which forwarding decisions at core nodes rely on a simple modulo operation over a route label. Nevertheless, such operation over integer arithmetic is not natively supported by commodity network hardware. Thus, PolKA proposes a novel RNS-based SR scheme that explores binary polynomial arithmetic using Galois field (GF) of order 2.

[![PolKA](https://github.com/nerds-ufes/polka/blob/main/mininet/figures/architecture.png | width=200)](https://nerds-ufes.github.io/polka/)

## News

### News #1 - Post-doctoral fellowship in 5G slicing, orchestration, and programmability
<p align="justify">
We are seeking candidates for a post-doctoral fellowship position for 12 months to work at a joint UFMG-UNICAMP-UFES-UNISINOS-UFRGS project. Due to the number of institutions as well as the situation with COVID-19, there is a great amount of flexibility in the place of work. The candidate will be allocated to one of the host universities and will work with researchers of the consortium. 
</p>
<p align="justify">
This scholarship is part of the Project, entitled “Programmability, Orchestration and Virtualization on 5G networks” (PORVIR-5G), which aims to develop new architectures and mechanisms to improve 5G networks in general. The post-doc candidate will work on the use of AI and machine learning in the orchestration of 5G networks, as well as network slicing and programmability of virtual networks. The project focuses on some of the 5G verticals, namely ultra high quality video, autonomous drones and Industry 4.0. More information at: <a href="https://porvir-5g-project.github.io/ ">https://porvir-5g-project.github.io/ </a>
</p>
    
**To succeed in this position, you are expected to have:**

* Strong motivation;
* A background in computer networks, namely network slicing, programmability;    
* Proficient in common computer programming languages (e.g., Java, C/C++, python);
* A background in AI and machine learning is a positive aspect to be considered in the selection process;
* Work experience in research labs abroad, during the Ph.D. period, is a positive aspect to be considered in the selection process;
* Strong problem solving and decision-making skills while using good judgment;
* Good research skills, the ability to work in a team, and communication skills with good written and spoken English are required;
* Experience in preparing/coordinating research project/students team is a plus.

**How to apply**

Interested candidates should fill the  <a href="https://forms.gle/RKa3e5nfrCPafEVx7 ">online form </a> until March 15th, 2022, by adding the documents listed below:
1. A motivation letter for the application;
2. Curriculum vitae, with list of publications, education background, research track-record, and previous experience;
3. Ph.D. degree certificate;
The most suited candidates will be invited for an interview (via videoconference) in the week following the application deadline.

**Additional Information**
<p align="justify"> 
        
Eligibility Criteria: Ph.D. in Computer Science or related areas.
The post-doctoral fellowship includes a monthly stipend of R$ 7.373,10 (about USD 1,380 and EUR 1,200), and research contingency funds (10% of the annual value of the fellowship, each year). For more details, check out Fapesp’s webpage  <a href="http://www.fapesp.br/en/5427 ">http://www.fapesp.br/en/5427 </a> .
 
</p>

## Acknowledgement
<p align="justify">
PORVIR-5G Project has received funding from the Brazilian Ministry of Science, Technology and Innovation (MCTI) through FAPESP.
</p>
<p align="center">
    <img src="mcti.png" height="70"/> <img src="fapesp.png" height="100"/> 
</p>


