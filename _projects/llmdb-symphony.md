---
layout: page
title: Symphony
description: Retrieval-augmented language models using multi-modal data lakes.
img: assets/img/symphony.jpg
importance: 1
category: llmdb
related_publications: DBLP:conf/cidr/ChenG0FM023
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/symphony.jpg" title="Symphony vision" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Multi-modal data lakes, which contain datasets in different formats such as text, tables, and knowledge graphs, have become increasingly popular for many organizations. 

Large language models, as generative models, cannot ensure the correctness of generative data. 

Given any natural language query, Symphony will first retrieve (possibly multiple) datasets from data lakes, which are then used for reasoning to answer the given query.