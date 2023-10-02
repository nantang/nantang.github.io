---
layout: page
title: Data acquisition
description: Discovering and selecting training data from data lakes
img: assets/img/autodata.jpg
importance: 2
category: dcai
related_publications: DBLP:journals/pvldb/ChaiLTLL22, DBLP:journals/pvldb/LiuZCL021
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/autodata.jpg" title="Selective Data Acquisition" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In many supervised ML projects, the main bottleneck is the lack of sufficient labeled train data (a.k.a. data-centric ML), not which ML models to use and how to optimize these models (a.k.a. model-centric ML), especially for ML practitioners.

The process of getting more labeled data is known as data acquisition, which is categorized into two classes: human-in-the-loop and automatic data acquisition. Human-in-the-loop data acquisition includes weak supervision where users need to define rules (e.g., Snorkel, data programming), and crowd- and expert-sourcing. Automatic data acquisition uses automatic
methods to obtain more train data.