+++
url_slides = ""
date = "2016-10-26T14:13:22+08:00"
url_code = ""
image_preview = ""
math = false
abstract_short = "Cloud applications generate a mix of flows with and without deadlines. Scheduling such mix-flows is a key challenge; our experiments show that trivially combining existing schemes for deadline/non-deadline flows is problematic. For example, prioritizing deadline flows hurts flow completion time (FCT) for non-deadline flows, with minor improvement for deadline miss rate. We present Karuna, a first systematic solution for scheduling mix-flows. "
title = "Scheduling Mix-flows in Commodity Datacenters with Karuna"
url_video = ""
selected = true
url_project = ""
url_dataset = ""
abstract = "Cloud applications generate a mix of flows with and without deadlines. Scheduling such mix-flows is a key challenge; our experiments show that trivially combining existing schemes for deadline/non-deadline flows is problematic. For example, prioritizing deadline flows hurts flow completion time (FCT) for non-deadline flows, with minor improvement for deadline miss rate. We present Karuna, a first systematic solution for scheduling mix-flows. Our key insight is that deadline flows should meet their deadlines while minimally impacting the FCT of non-deadline flows. To achieve this goal, we design a novel Minimal-impact Congestion control Protocol (MCP) that handles deadline flows with as little bandwidth as possible. For non-deadline flows, we extend an existing FCT minimization scheme to schedule flows with known and unknown sizes. Karuna requires no switch modifications and is backward compatible with legacy TCP/IP stacks. Our testbed experiments and simulations show that Karuna effectively schedules mix-flows, for example, reducing the 95th percentile FCT of non-deadline flows by up to 47.78% at high load compared to pFabric, while maintaining low (<5.8%) deadline miss rate."
authors = [
  "Li Chen", "Kai Chen", "Wei Bai", "Mohammad Alizadeh"
]
image = ""
publication = "Proceedings of the 2016 conference on ACM SIGCOMM 2016 Conference"
publication_short = "ACM SIGCOMM'16"
url_pdf = "http://dl.acm.org/citation.cfm?id=2934888"
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
