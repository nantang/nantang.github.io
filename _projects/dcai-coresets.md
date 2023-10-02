---
layout: page
title: Coreset selection
description: Selecting a subset of train data
img: assets/img/coresets.jpg
importance: 2
category: dcai
related_publications: DBLP:journals/pacmmod/ChaiL0FM0L023, DBLP:conf/kdd/Chai000LDW23, DBLP:journals/pvldb/WangC0L022
---


Data-effective machine learning (ML) (a.k.a. data-centric AI) aims at obtaining high-quality
training data to release the value of AI, because it is well-known that dirty data may severely degrade the performance of ML models.

Data-efficient ML focuses on making the training process more efficient. A commonly used
strategy is to select a core subset of training data (or coreset) to represent the entire dataset such that ML models trained on the coreset can achieve similar performance to the ML models trained on the entire dataset.

Apparently, users desire both data-effective ML (for training better ML models) and data-efficient ML (for saving training cost).