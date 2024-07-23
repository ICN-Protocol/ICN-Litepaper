# Network Monitoring: SLA Oracle Network

#### A common problem within DePIN networks is ensuring the authenticity and integrity of resources and participants within the network, where traditional centralized validation methods are not applicable.&#x20;

***

This ‘DePIN verification problem’ includes verifying the availability, performance, and reliability of distributed resources, as well as maintaining trust among numerous independent and potentially anonymous entities.&#x20;

For ICN to offer competitive service levels, HPs must operate at peak levels and consistently meet required SLA standards to maintain high network performance. ICNP therefore includes a network of external SLA Oracle Nodes (SLA-ONs) that constantly monitor, verify, and report network health metrics, verifying availability, capacity, or specific service-level metrics such as bandwidth or latency. Due to their independence and the transparency of all data they obtain, SLA-ONs create a layer of trust and objectivity within a network that is trustless by design.&#x20;

The functionality available to SLA Oracle nodes will evolve from permissioned to trustless and from measuring simple metrics to applying DePIN proofs.&#x20;

SLA-ONs work by probing metrics from hardware nodes and, depending on proof availability and integration, performing checks via verifiable DePIN proofs. Providing robust and performant proofs (Proof-of-Storage, Proof-of-Bandwidth, etc.) is one of the core challenges that the DePIN space faces. Overcoming these challenges is the goal of hundreds of open-source projects and research initiatives.&#x20;

The network of SLA-ONs includes a modular proof interface, which allows the integration of additional or new verification methods over time as they become available.&#x20;

The SLA Oracle Network will perform a variety of tasks, ranging from monitoring (collecting and processing service performance metrics) to proof generation (producing verifiable proofs using local hardware metrics), to aggregation (collecting and aggregating reports, interfacing with smart contracts logic). In exchange for performing those tasks, SLA-ONs are rewarded with ICNT.&#x20;
