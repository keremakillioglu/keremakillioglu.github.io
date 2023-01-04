---
layout: project
title: Cardinality Estimation in Graph DBs
comments: true
---

My master’s thesis is on cardinality estimation in Streaming Graph Data Management Systems (SGDMS). I have been developing a novel cardinality estimation technique on top of the [S-Graffito](https://dsg-uwaterloo.github.io/s-graffito/) project, where my research group built a SGDMS that addresses the processing of OLTP and OLAP queries. I am enthusiastic about this project since I am contributing to the development of the first query optimizer that is native to streaming graph databases, and we are taking the first steps in building complete graph native systems.

In my master's thesis, I have been building a logically simple and computationally efficient system. Using sliding windows as a method to address the constraints of the streaming environment, I summarized the data within the windows into a sketch and developed a novel method to estimate cardinality. I appreciate the simplicity of my estimation technique as it applies fundamental estimation techniques used in relational systems. Yet, the end-to-end solution is flexible and powerful enough to control for accuracy and efficiency.

I am still in the process of completing the project as of this writing.