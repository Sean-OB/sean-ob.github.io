---
title: "Contrastive Decoding Improves Reasoning in Large Language Models"
collection: publications
permalink: /publication/2023-09-17-cd-reasoning
excerpt: 'We demonstrate that Contrastive Decoding achieves large out-of-the-box improvements on a variety of reasoning tasks.'
date: 2023-09-17
venue: 'arxiv'
paperurl: 'https://browse.arxiv.org/pdf/2309.09117.pdf'
citation: '<em>Sean O&apos;Brien</em>, Mike Lewis. (2023). &quot;Contrastive Decoding Improves Reasoning in Large Language Models.&quot; <i>arxiv preprint</i>.'
---
We demonstrate that Contrastive Decoding -- a simple, computationally light, and training-free text generation method proposed by Li et al 2022 -- achieves large out-of-the-box improvements over greedy decoding on a variety of reasoning tasks. Originally shown to improve the perceived quality of long-form text generation, Contrastive Decoding searches for strings that maximize a weighted difference in likelihood between strong and weak models. We show that Contrastive Decoding leads LLaMA-65B to outperform LLaMA 2, GPT-3.5 and PaLM 2-L on the HellaSwag commonsense reasoning benchmark, and to outperform LLaMA 2, GPT-3.5 and PaLM-540B on the GSM8K math word reasoning benchmark, in addition to improvements on a collection of other tasks. Analysis suggests that Contrastive Decoding improves over existing methods by preventing some abstract reasoning errors, as well as by avoiding simpler modes such as copying sections of the input during chain-of-thought. Overall, Contrastive Decoding outperforms nucleus sampling for long-form generation and greedy decoding for reasoning tasks, making it a powerful general purpose method for generating text from language models.

[Download paper here](https://browse.arxiv.org/pdf/2309.09117.pdf)

Recommended citation: O\'Brien & Lewis. (2023). "Contrastive Decoding Improves Reasoning in Large Language Models" <i>arxiv preprint</i>.