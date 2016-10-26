+++
abstract_short = ""
image_preview = ""
url_video = ""
publication_short = "USENIX NSDI'16"
url_project = ""
math = false
url_pdf = "https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-bai.pdf"
date = "2016-04-26T14:13:05+08:00"
title = "Enabling ECN in Multi-Service Multi-Queue Data Centers"
url_dataset = ""
authors = [
  "Wei Bai", "Li Chen", "Kai Chen", "Haitao Wu",
]
publication = "13th USENIX Symposium on Networked Systems Design and Implementation (NSDI 16)"
url_code = ""
image = ""
url_slides = ""
abstract = "Recent proposals have leveraged Explicit Congestion Notification (ECN) to achieve high throughput low latency data center network (DCN) transport. However, most of them implicitly assume each switch port has one queue, making the ECN schemes they designed inapplicable to production DCNs where multiple service queues per port are employed to isolate different traffic classes through weighted fair sharing. In this paper, we reveal this problem by leveraging extensive testbed experiments to explore the intrinsic tradeoffs between throughput, latency, and weighted fair sharing in multi-queue scenarios. Using the guideline learned from the exploration, we design MQ-ECN, a simple yet effective solution to enable ECN for multi-service multiqueue production DCNs. Through a series of testbed experiments and large-scale simulations, we show that MQ-ECN breaks the tradeoffs by delivering both high throughput and low latency simultaneously, while still preserving weighted fair sharing."
selected = false

+++
