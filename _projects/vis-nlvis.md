---
layout: page
title: NL2VIS
description: Translating natural langauge to visualizations
img: assets/img/nlvis.jpg
importance: 1
category: vis
related_publications: DBLP:journals/tvcg/LuoTLTCQ22, DBLP:conf/sigmod/Luo00CLQ21, DBLP:conf/edbt/QinL0018
---


Supporting the translation from natural language (NL) query to visualization (NL2VIS) can simplify the creation of data visualizations because if successful, anyone can generate visualizations by their natural language from the tabular data. The state-of-the-art NL2VIS approaches (e.g., NL4DV and FlowSense) are based on semantic parsers and heuristic algorithms, which are not end-to-end and are not designed for supporting (possibly) complex data transformations. Deep neural network powered neural machine translation models have made great strides in many machine translation tasks, which suggests that they might be viable for NL2VIS as well. 

We present ncNet, a Transformer-based sequence-to-sequence model for supporting NL2VIS, with several novel visualization-aware optimizations, including using attention-forcing to optimize the learning process, and visualization-aware rendering to produce better visualization results. To enhance the capability of machine to comprehend natural language queries, ncNet is also designed to take an optional chart template (e.g., a pie chart or a scatter plot) as an additional input, where the chart template will be served as a constraint to limit what could be visualized. We conducted both quantitative evaluation and user study, showing that ncNet achieves good accuracy in the nvBench benchmark and is easy-to-use.