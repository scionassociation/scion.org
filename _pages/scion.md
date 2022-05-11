---
layout: page
title: SCION
permalink: /scion
background: grey
---
<br>

### What is SCION?
SCION is the first clean-slate Internet architecture designed to provide route control, failure isolation, and explicit trust information for end-to-end communication. SCION organizes existing ASes into groups of independent routing planes, called isolation domains, which interconnect to provide global connectivity. Isolation domains provide natural isolation of routing failures and misconfigurations, give endpoints strong control for both inbound and outbound traffic, provide meaningful and enforceable trust, and enable scalable routing updates with high path freshness. As a result, the SCION architecture provides strong resilience and security properties as an intrinsic consequence of its design. Besides high security, SCION also provides a scalable routing infrastructure, and high efficiency for packet forwarding. As a path-based architecture, SCION end hosts learn about available network path segments, and combine them into end-to-end paths that are carried in packet headers. Thanks to embedded cryptographic mechanisms, path construction is constrained to the route policies of ISPs and receivers, offering path choice to all the parties: senders, receivers, and ISPs. This approach enables path-aware communication, an emerging trend in networking. These features also enable multi-path communication, which is an important approach for high availability, rapid failover in case of network failures, increased end-to-end bandwidth, dynamic traffic optimization, and resilience to DDoS attacks.

### Why a clean-slate design? Why can't we adopt existing solutions?
The Internet was not designed as a high-security network. Security improvements
primarily address specific attacks, but do not solve the fundamental problems
and often introduce new undesirable consequences (e.g., BGPSEC prevents route
hijacking but causes delayed route convergence, and does not support prefix
aggregation which contributes to reduce scalability). With a clean-slate design,
we can fundamentally improve the security to a level that is unlikely to be
achievable through incremental changes.

<br>
<a class="btn btn-primary btn-lg" href="https://scion-architecture.net">
    <i class="fas fa-user-graduate"></i> SCION Website
</a>
<a class="btn btn-primary btn-lg" href="https://github.com/scionproto/scion">
    <i class="fab fa-github"></i> Source Code
</a>
<a class="btn btn-primary btn-lg" href="https://docs.scion.org">
    <i class="fas fa-book"></i> Documentation
</a>
<br>