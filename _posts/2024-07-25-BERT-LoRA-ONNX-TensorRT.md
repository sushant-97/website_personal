---
description: Accelerating BERT Inference with LoRA and TensorRT for Stack Overflow Question Classification
title: Accelerating BERT Inference with LoRA and TensorRT
toc: true
badges: true
comments: true
author: Sushant P.
categories: [nlp, bert, LoRA, fast-inference]
image: images/posts/content.png
cover: images/covers/content.png
layout: notebook
permalink: /blog/:year:month:day/medical-content-generation
sticky_rank: 2
---

<p>This post was originally published on the <a href="https://medium.com/@sushant.pargaonkar97/accelerating-bert-inference-with-lora-and-tensorrt-edit-d6beb2add24d">Medium ML Blog</a></p>

<h1 id="1.-Introduction">1. Introduction<a class="anchor-link" href="#1.-Introduction"> </a>
<p>This project, while serving as a comprehensive guide to understanding, implementing, and optimizing transformer-based models for improved performance and efficiency, is also a representation of my learning journey and serves as a portfolio piece showcasing some skills I have picked up along the way in machine learning and natural language processing.</p>

<p>The goal of this project is to provide fast inference for BERT based model using quantization and lora and deploy using TensorRT. In this we first finetuing the BERT-LoRA on trainng set and then quantize the model using transformer-deploy libray. In the end we export the model to ONXX framework and deploy by provided ONXX graph to TensorRT. In this way we have utilized major techniques of optimization of transformer model for production with minimal reduction in accuracy.</p>

<p>We achive 4x speed up over BERT base model with minimal(approx 0.4%) loss in accuracy. The code is documented and published on <a href="https://github.com/sushant-97/Fine-Tuning-BERT-with-LoRA-for-Stack-Overflow-Question-Classification">GitHub</p>


<h1 id="2.-Full Post">2. Full Post<a class="anchor-link" href="#2.-Full Post"> </a>
<p>... <a href="https://github.com/sushant-97/Fine-Tuning-BERT-with-LoRA-for-Stack-Overflow-Question-Classification"> (continue reading here)</a></p>