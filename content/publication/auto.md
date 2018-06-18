+++
url_slides = ""
date = "2018-06-18T14:13:22+08:00"
url_code = ""
image_preview = ""
math = false
abstract_short = "Traffic optimizations (TO, e.g. flow scheduling, load balancing) in datacenters are difficult online decision-making problems. Previously, they are done with heuristics relying on operators’ understanding of the workload and environment. Designing and implementing proper TO algorithms thus take at least weeks. Encouraged by recent successes in applying deep reinforcement learning (DRL) techniques to solve complex online control problems, we study if DRL can be used for automatic TO without human-intervention. To this end, we develop AuTO: an end-to-end automatic TO system that can collect network information, learn from past decisions, and perform actions to achieve operator-defined goals."
title = "AuTO: Scaling Deep Reinforcement Learning to Enable Datacenter-Scale Automatic Traffic Optimization"
url_video = ""
selected = true
url_project = ""
url_dataset = ""
abstract = "Traffic optimizations (TO, e.g. flow scheduling, load balancing) in datacenters are difficult online decision-making problems. Previously, they are done with heuristics relying on operators’ understanding of the workload and environment. Designing and implementing proper TO algorithms thus take at least weeks. Encouraged by recent successes in applying deep reinforcement learning (DRL) techniques to solve complex online control problems, we study if DRL can be used for automatic TO without human-intervention. However, our experiments show that the latency of current DRL systems cannot handle flow-level TO at the scale of current datacenters, because short flows (which constitute majority of traffic) are usually gone before decisions can be made. Leveraging long-tail distribution of datacenter traffic, we develop a two-level DRL system, AuTO, mimicking Peripheral & Central Nervous Systems in animals, to solve the scalability problem. Peripheral Systems (PS) reside on end-hosts, collect flow information, and make TO decisions locally with minimal delay for short flows. PS’s decisions are informed by a Central System (CS), where global traffic information is aggregated and processed. CS further makes individual TO decisions for long flows. With CS&PS, AuTO is an end-to-end automatic TO system that can collect network information, learn from past decisions, and perform actions to achieve operator-defined goals. We implement AuTO with popular machine learning framework and commodity servers, and deploy it on a 16-server testbed. Compared to existing approaches, AuTO reduces the TO turn-around time from weeks to ∼100 milliseconds while achieving superior performance. For example, it demonstrates up to 55.93% reduction in average flow completion time (FCT) over existing solutions."
authors = [
  "Li Chen", "Justinas Lingys", "Kai Chen", "Feng Liu",
]
image = ""
publication = "Proceedings of the conference on ACM SIGCOMM 2018 Conference"
publication_short = "ACM SIGCOMM'18"
url_pdf = ""
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

+++
