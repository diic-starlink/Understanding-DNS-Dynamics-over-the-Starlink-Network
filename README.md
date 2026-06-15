# Understanding-DNS-Dynamics-over-the-Starlink-Network
Repository for paper ["Understanding DNS Dynamics over the Starlink Network"](https://robert-richter.me/pdfs/starlink-dns-dynamics.pdf) published at IFIP Networking 2026. It won the ["Best Paper: Honorable Mention"](https://robert-richter.me/pdfs/2026-ifip-networking-best-paper-honorable-mention.pdf) award.

> **Abstract.** Low-Earth Orbit (LEO) satellite networks have emerged as a viable Internet connectivity option, yet their Domain Name System (DNS) behavior remains largely unexplored. This paper presents the first dedicated measurement study of DNS performance in the Starlink network. Using RIPE Atlas infrastructure, we analyze DNS resolution times across various countries over a 13-month observation period from January 2025 to February 2026. We investigate three research questions: which DNS resolvers Starlink users commonly employ, how different resolvers compare in performance, and what influences DNS latencies. Our measurements reveal that DNS latency in Starlink is predominantly determined by the satellite hop rather than terrestrial routing, with the CGNAT hop (100.64.0.1) accounting for approximately 69 % of total latency in traceroute measurements. Reducing this latency would only work by locating the resolver closer to the Starlink user. We also examine Starlink’s subscription-based DNS handling and find that unverified users are assigned a restricted resolver (34.145.127.1) that resolves only specific domains. Additionally, we identify SpaceX-operated IPv6 DNS resolvers that appear co-located with PoPs, potentially offering performance benefits through geographic proximity. Our findings provide insights into the design of the DNS ecosystem for LEO satellite networks.

## Dataset
![](https://zenodo.org/badge/DOI/10.5281/zenodo.20642922.svg)

The dataset is hosted on Zenodo: https://zenodo.org/records/20642922. It includes all relevant details to use the data properly.

## Contact Details

In case you have more questions, please reach out! Find all details on https://hpi.de/en/bajpai/team/.
