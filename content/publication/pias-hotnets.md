+++
publication = "Proceedings of the 13th ACM Workshop on Hot Topics in Networks"
authors = [
  "Wei Bai", "Li Chen", "Kai Chen", "Dongsu Han", "Chen Tian", "Weicheng Sun",
]
abstract = "Many existing data center network (DCN) flow scheduling schemes minimize flow completion times (FCT) based on prior knowledge of flows and custom switch designs, making them hard to use in practice. This paper introduces, Pias, a practical flow scheduling approach that minimizes FCT with no prior knowledge using commodity switches. At its heart, Pias leverages multiple priority queues available in commodity switches to implement a Multiple Level Feedback Queue (MLFQ), in which a PIAS flow gradually demotes from higher-priority queues to lower-priority queues based on the bytes it has sent. In this way, short flows are prioritized over long flows, which enables Pias to emulate Shortest Job First (SJF) scheduling without knowing the flow sizes beforehand. Our preliminary evaluation shows that Pias significantly outperforms all existing information-agnostic solutions. It improves average FCT for short flows by up to 50% and 40% over DCTCP [3] and L2DCT [16]. Compared to an ideal information-aware DCN transport, p-Fabric [5], it only shows 4.9% performance degradation for short flows in a production datacenter workload."
math = false
url_pdf = "http://dl.acm.org/citation.cfm?id=2673871"
url_video = ""
abstract_short = ""
url_slides = ""
selected = false
title = "PIAS: Practical information-agnostic flow scheduling for data center networks"
image_preview = ""
publication_short = ""
url_code = ""
url_dataset = ""
image = ""
url_project = ""
date = "2014-11-26T14:12:42+08:00"

+++
