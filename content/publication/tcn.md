+++
image = ""
math = false
selected = false
publication_short = "ACM CoNEXT'16"
publication = "The 12th International Conference on emerging Networking EXperiments and Technologies"
url_pdf = ""
image_preview = ""
title = "Enabling ECN over Generic Packet Scheduling"
url_code = ""
url_slides = ""
abstract = "Explicit Congestion Notification (ECN) is crucial for production datacenters, but current queue-length based ECN/RED implementation does not work with generic packet schedulers, leading to either degraded network performance or violated scheduling policies. In this paper, we first dive into this issue and reveal that the invalidity of ECN/RED lies in the difficulty of measuring changing queue capacities under various schedulers and traffic dynamics. Then we present TCN, a simple yet effective ECN solution, by combining two successful ideas: the sojourn time from CoDel and the instantaneous marking from DCTCP. Using packet sojourn-time, as opposed to queue-length, as the congestion signal, TCN eliminates the need of measuring dynamic queue capacities, making it suitable for arbitrary schedulers with traffic dynamics. By performing stateless instantaneous ECN marking rather than complex stateful dropping, TCN is inexpensive to implement on commodity switching chips. Through extensive testbed experiments and large-scale simulations, we show TCN can strictly preserve scheduling policies while providing desirable network performance. For example, TCN significantly reduces the average and 99th percentile completion time for small flows by up to 82.8% and 95.3% compared to current practice in a testbed experiment with production workload."
url_dataset = ""
url_project = ""
abstract_short = ""
url_video = ""
authors = [
  "Wei Bai", "Kai Chen", "Li Chen", "Changhoon Kim", "Haitao Wu",
]
date = "2016-12-26T14:13:17+08:00"

+++
