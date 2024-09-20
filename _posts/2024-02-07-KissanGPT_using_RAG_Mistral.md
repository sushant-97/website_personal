---
description: chatbot designed to promptly respond to farmers' inquiries, leveraging historical data from Krishi Seva Kendra
title: KissanGPT:Revolutionizing Farmer Assistance with AI
toc: true
badges: true
comments: true
author: Sushant P., Ashish Goswami
categories: [generative ai, natural language processing, web app]
image: images/posts/content.png
cover: images/covers/content.png
layout: notebook
permalink: /blog/:year:month:day/kissangpt
sticky_rank: 1
---

<p>In this blog, we introduce KissanGPT—a chatbot designed to automate responses to farmers' inquiries using cutting-edge Generative AI. This solution was developed as part of the PANIIT LLM competition held at <a href="https://www.iitg.ac.in/">IIT Guwahati</a>, and leverages Mistral API to address real-world agricultural problems. </p>

<h1 id="1.-Introduction">
1. Introduction <a class="anchor-link" href="#1.-Introduction"></a>
<p> Agriculture is the backbone of many economies, especially in India, where farmers rely on timely and accurate information to make critical decisions. The Krishi Seva Kendra (KSK) provides vital assistance to farmers by answering queries related to crop management, weather predictions, pest control, and more. However, during peak seasons like the monsoon, KSK often struggles to keep up with the surge in requests due to staff shortages, leading to delays in response time.

Generative AI and transformer-based large language models (LLMs) have been in the top headlines recently. These models demonstrate impressive performance in question answering, text summarization, code, and text generation. Today, LLMs are being used in real settings by companies. In this post, we explore how LLMs can be used to answer farmer queries.</p>

<p> Krishi Seva Kendra faces challenges during peak seasons due to staff shortages, leading to delayed responses to farmers' queries. The main goal of the KSK is to address farmer queries over phone call or text message. But during peak time such as monsoon season there is serge in request from farmers and hence there is need to automate these request in real time.</p>

<p>Could LLMs, with their advanced text generation capabilities, help streamline this process by assisting krushi experts in their query answering process?</p>

<p> 
To answet this question, we have developed a prototype of question-answering model based on Mistral model for farmer queries. We have built a RAG pipeline using LanceDB and we rerank the retrived information using bge-reranker-base. Finally, we leverage the mixtral-8x7b-instruct model to generate a coherent and accurate response based on the reranked data.
</p>

<p>
The potential of Generative AI in sectors like agriculture is immense. KissanGPT showcases how advanced language models can streamline processes, offering real-time assistance to farmers who need it the most. By automating the query-handling process, we’re enabling farmers to make informed decisions, ultimately supporting sustainable agriculture practices.
</p>

<p id="2.-Code Link">2. Full Post<a class="anchor-link" href="#2.-For a deeper dive into the project, including code and implementation details, visit our"> </a>
<p>... <a href="https://github.com/sushant-97/KisaanGPT/tree/main/"> (Continue reading here)</a></p>