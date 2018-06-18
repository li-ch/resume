+++
url_dataset = ""
abstract = "Many existing data center network DCN flow scheduling schemes, that minimize flow completion times FCT assume prior knowledge of flows and custom switch functions, making them superior in performance but hard to implement in practice. By contrast, we seek to minimize FCT with no prior knowledge and existing commodity switch hardware. To this end, we present PIAS, a DCN flow scheduling mechanism that aims to minimize FCT by mimicking shortest job first SJF on the premise that flow size is not known a priori. At its heart, PIAS leverages multiple priority queues available in existing commodity switches to implement a multiple level feedback queue, in which a PIAS flow is gradually demoted from higher-priority queues to lower-priority queues based on the number of bytes it has sent. As a result, short flows are likely to be finished in the first few high-priority queues and thus be prioritized over long flows in general, which enables PIAS to emulate SJF without knowing flow sizes beforehand. We have implemented a PIAS prototype and evaluated PIAS through both testbed experiments and ns-2 simulations. We show that PIAS is readily deployable with commodity switches and backward compatible with legacy TCP/IP stacks. Our evaluation results show that PIAS significantly outperforms existing information-agnostic schemes, for example, it reduces FCT by up to 50% compared to DCTCP and L2DCT; and it only has a 1.1% performance gap to an ideal information-aware scheme, pFabric, for short flows under a production DCN workload."
authors = [
  "Wei Bai", "Li Chen", "Kai Chen", "Dongsu Han", "Chen Tian", "Hao Wang"
]
math = false
selected = false
url_code = ""
url_slides = ""
publication_short = "IEEE/ACM ToN"
title = "PIAS: Practical Information-Agnostic Flow Scheduling for Commodity Data Centers"
image = ""
image_preview = ""
url_project = ""
date = "2017-08-02T14:11:59+08:00"
abstract_short = ""
publication = "IEEE/ACM Transactions on Networking (TON), Volume 25 Issue 4, August 2017, Page 1954-1967"
url_video = ""
url_pdf = "https://dl.acm.org/citation.cfm?id=3148779"
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]
+++
