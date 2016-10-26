+++
abstract = "Data-parallel computing frameworks (DCF) such as MapReduce, Spark, and Dryad etc. Have tremendous applications in big data and cloud computing, and throw tons of flows into data center networks. In this paper, we design and implement FLOWPROPHET, a general framework to predict traffic flows for DCFs. To this end, we analyze and summarize the common features of popular DCFs, and gain a key insight: since application logic in DCFs is naturally expressed by directed acyclic graphs (DAG), DAG contains necessary time and data dependencies for accurate flow prediction. Based on the insight, FLOWPROPHET extracts DAGs from user applications, and uses the time and data dependencies to calculate flow information 4-tuple, (source, destination, flow_size, establish_time), ahead-of-time for all flows. We also provide generic programming interface to FLOWPROPHET, so that current and future DCFs can deploy FLOWPROPHET readily. We implement FLOWPROPHET on both Spark and Hadoop, and perform extensive evaluations on a testbed with 37 physical servers. Our implementation and experiments demonstrate that, with time in advance and minimal cost, FLOWPROPHET can achieve almost 100% accuracy in source, destination, and flow size predictions. With accurate prediction from FLOWPROPHET, the job completion time of a Hadoop TeraSort benchmark is reduced by 12.52% on our cluster with a simple network scheduler."
title = "FLOWPROPHET: Generic and Accurate Traffic Prediction for Data-parallel Cluster Computing"
url_slides = ""
math = false
image = ""
date = "2015-06-29T14:12:54+08:00"
url_dataset = ""
abstract_short = ""
image_preview = ""
url_pdf = "http://ieeexplore.ieee.org/document/7164921/"
url_video = ""
publication_short = "IEEE ICDCS'15"
url_project = ""
publication = "Distributed Computing Systems (ICDCS), 2015 IEEE 35th International Conference on"
authors = [
  "Hao Wang", "Li Chen", "Kai Chen", "Ziyang Li", "Yiming Zhang", "Haibing Guan", "Zhengwei Qi", "Dongsheng Li", "Yanhui Geng"
]
url_code = ""
selected = false

+++
