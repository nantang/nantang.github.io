---
layout: post
title:  Red Bird 2023 Project
date:   2023-11-01 16:40:16
description: Data Analytics over Multi-modal Data Lakes using Large Language Models
tags: project
categories: blockquotes
---
### Title: Data Analytics over Multi-modal Data Lakes using Large Language Models 

### 基于大语言模型和多模态数据湖的数据分析 

It has three main components:

### 1. Improving large language models (LLMs) through fine-tuning

A common problem for LLMs to be used on industrial applications is that these LLMs are simply not good enough. Although many companies have a lot of data assets, however, it is common that after fine-tuning using these data assets, the LLMs are still not good enough. There are multiple reasons:

<ul>
    <li>Data is not good</li> 
    <li>Data is not enough</li>
    <li>How to best fine-tune LLMs for certain data types are still unknown, such as table learning or knowledge graph learning</li>
</ul>

Moreover, we do have specific applications to work on:

<ul>
    <li>LLMs for creative educations, especially machine learning courses. <strong> Please contact Prof. Wei Wang (weiwcs@hkust-gz.edu.cn) if you are interested in this thread. </strong> </li> 
    <li>LLMs for database problems, such as NL2SQL</li>
    <li>LLMs for table learning</li>
</ul>

<hr>

### 2. Retrieval-augmented generation

For data analytics using multi-modal data lakes, including text files, tables, relational databases, knowledge graphs, it is not reliable to use LLMs to directly give answers. A more reliable way is to first retrieve the datasets that are needed to answer a given query or doing a certain data analytics, and then use LLMs or other existing tools (such as databases) to do the reasoning. 

So far, how to index text files are widely studied and used, but how to index (large) tables or graphs are still an open problem. Hence, there are many open problems about given a natural language, retrieving:

<ul>
    <li>text file(s)</li> 
    <li>table(s)</li>
    <li>graph(s)</li>
    <li>image(s)</li>
    <li>or a combination of the above files</li>
</ul>

and then doing the reasoning.

Please refer to the Symphony paper (https://www.cidrdb.org/cidr2023/papers/p51-chen.pdf) for a vision on this thread.

I envision that <strong>retrieving required multi-modal datasets for a given natural language query</strong> will be the bottleneck that many commercial applications of LLMs for data analytics cannot be grounded. 

### 3. Data analytics over multi-modal data using LLMs

This is more from the application side, where the required datasets are provided (for example, from the above retrieval exercise). There are multiple directions we are pursuing:

<ul>
    <li>Multi-modal IoT data analytics. <strong> Please contact Prof. Kaishun Wu (wuks@hkust-gz.edu.cn) if you are interested in this thread. </strong></li>
    <li>LLM powered data visualizations/stories/videos <strong> Please contact Prof. Yuyu Luo (yuyuluo@hkust-gz.edu.cn) if you are interested in this thread. </strong> </li>     
    <li>H.A.R.V.I.S (HKUST AR for VIS): This is a LLM and AR powered system for data visualization</li>
</ul>
