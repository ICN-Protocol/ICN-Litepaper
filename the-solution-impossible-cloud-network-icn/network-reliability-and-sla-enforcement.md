# Network Reliability and SLA Enforcement

#### If the SLA-ONs detect a network anomaly (i.e. a significant and persistent deviation from expected network performance and availability levels), ICNP allows for the initiation of a slashing protocol.&#x20;

***

The definition of a network anomaly can vary depending on the hardware class and an anomaly event can be triggered by multiple trigger events (e.g. committed capacity no longer available, bandwidth below threshold, etc.).&#x20;

In case of an anomaly report, HPs must restore their faulty node within a limited time window before the deposited ICNT slashing starts. When the slashing process begins, the HP's deposited ICNT is gradually reduced and rewards are put on hold until the anomaly is resolved. SPs can claim back unreleased rewards as compensation for loss of uptime.&#x20;
