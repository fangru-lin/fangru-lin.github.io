---
layout: page
permalink: /publications/
title: Publications
# description: My publications in preparation
years: 2024
nav: true
nav_order: 4
---
<!-- _pages/publications.md -->
<div class="News">

<h4 class="year">2025</h4>
  <h2>[ACL 2025 main] <a href="https://arxiv.org/pdf/2410.11005" target="_blank">One Language, Many Gaps: Evaluating Dialect Fairness and Robustness of Large Language Models in Reasoning Tasks</a></h2>
  <p>My internship project with MSR!</p>

  <!-- <img src="../assets/img/graph-llm.png" style="width: 60%;" alt="alternatetext"> -->

  <p>TL;DR: LLMs exhibit significant unfairness and brittleness to reasoning prompts expressed in dialects.</p>

  <p>1. Focusing on African American Vernacular English (AAVE), we present the first study on LLMs’ fairness and robustness to a dialect in canonical reasoning tasks (algorithm, math, logic, and comprehensive reasoning). </p>
  
  <p>2. We hire AAVE speakers, including experts with computer science backgrounds, to rewrite seven popular benchmarks, such as HumanEval and GSM8K. The result of this effort is ReDial, a dialectal benchmark comprising 1.2K+ parallel query pairs in Standardized English and AAVE. </p>

  <p>3. We use ReDial to evaluate state-of-the-art LLMs, including GPT4o/4/3.5-turbo, LLaMA-3.1/3, Mistral, and Phi-3. We find that, compared to Standardized English, almost all of these widely used models show significant brittleness and unfairness to queries in AAVE.</p> 
  
  <p>4. Furthermore, AAVE queries can degrade performance more substantially than misspelled texts in Standardized English, even when LLMs are more familiar with the AAVE queries.</p> 
  
  <p>5. Finally, asking models to rephrase questions in Standardized English does not close the performance gap but generally introduces higher costs.</p> 
  
  <p>6. Overall, our findings indicate that LLMs provide unfair service to dialect users in complex reasoning tasks.</p>

<h4 class="year">2024</h4>
  <h2>[ICML 2024] <a href="https://arxiv.org/abs/2402.02805" target="_blank">Graph-enhanced Large Language Models in Asynchronous Plan Reasoning</a></h2>
  <p>My first project in DPhil! Very excited to have collaborated with fantastic researchers!</p>

  <img src="../assets/img/graph-llm.png" style="width: 60%;" alt="alternatetext">

  <p>TL;DR: Off-the-shelf graph prompting consistently improves LLM performance in asynchronous planning.</p>

  <p>1. We automatically generate and open-source a high-quality dataset for asynchronous planning which requires both sequential and parallel efficient sheduling. </p>

  <p>2. We find that LLMs are extremely poor when they are not supplied with detailed task illustrations for efficient asynchronous planning.</p>

  <p>3. We propose an off-the-shelf prompting method Plan Like a Graph (PLaG) and we show that PLaG consistently boosts SOTA model performance over all complexity levels.</p>

  <p>4. Despite the performance boost, we still find that LLMs tend to suffer from severe degradataion with increasing task complexities, which highlights the limitations of using LLMs to simulate digital devices.</p>

<h4 class="year">2024</h4>
  <h2>[LREC-COLING 2024] <a href="https://arxiv.org/pdf/2404.03301" target="_blank">Probing Large Language Models for Scalar Adjective Lexical Semantics and Scalar Diversity Pragmatics</a></h2>
  <p>A short version of my master thesis!.</p>

  <img src="../assets/img/diversity.png" style="width: 60%;" alt="alternatetext">

  <p>TL;DR: LLMs are quite good at scalar adjective lexical semantics but not at scalar diversity pragmatics.</p>

  <p>Scalar adjectives pertain to various domain scales and vary in intensity within each scale (e.g. certain is more intense than likely on the likelihood scale). Scalar implicatures arise from the consideration of alternative statements which could have been made. They can be triggered by scalar adjectives and require listeners to reason pragmatically about them. Some scalar adjectives are more likely to trigger scalar implicatures than others. This phenomenon is referred to as scalar diversity. In this study, we probe different families of Large Language Models such as GPT-4 for their knowledge of the lexical semantics of scalar adjectives and one specific aspect of their pragmatics, namely scalar diversity. We find that they encode rich lexical-semantic information about scalar adjectives. However, the rich lexical-semantic knowledge does not entail a good understanding of scalar diversity. We also compare current models of different sizes and complexities and find that larger models are not always better. Finally, we explain our probing results by leveraging linguistic intuitions and model training objectives.</p>

</div>
