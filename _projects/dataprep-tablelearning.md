---
layout: page
title: Table representation learning
description: Relational pre-trained transformer
img: assets/img/dataprep-tablelearning.jpg
importance: 1
category: dataprep
related_publications: DBLP:journals/pvldb/TangFLTDLMO21
---

Can AI help automate human-easy but computer-hard data preparation tasks that burden data scientists, practitioners, and crowd workers? We answer this question by presenting RPT, a denoising autoencoder for tuple-to-X models (“X ” could be tuple, token, label, JSON, and so on). 

RPT is pre-trained for a tuple-to-tuple model by corrupting the input tuple and then learning a model to reconstruct the original tuple. It adopts a Transformer-based neural translation architecture that consists of a bidirectional encoder (similar to BERT) and a left-to-right autoregressive decoder (similar to GPT), leading to a generalization of both BERT and GPT. The pre-trained RPT can already support several common data preparation tasks such as data cleaning, auto-completion and schema matching. 

Better still, RPT can be fine-tuned on a wide range of data preparation tasks, such as value normalization, data transformation, data annotation, etc. To complement RPT, we also discuss several appealing techniques such as collaborative training and few-shot learning for entity resolution, and few-shot learning and NLP question-answering for information extraction. In addition, we identify a series of research opportunities to advance the field of data preparation.