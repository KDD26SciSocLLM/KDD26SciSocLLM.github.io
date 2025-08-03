---
layout: profiles
permalink: /speakers/
title: Speakers
description: BIO OF SPEAKERS
nav: true
nav_order: 5
profiles:
  - align: left
    image: huaxiu_yao.jpg
    image_circular: true
    more_info: >
      <p class="name">Jian Tang</p>
      <p class="institution">Montreal Institute for Learning Algorithms</p>
      

  - align: left
    image: WK.jpg
    image_circular: true
    more_info: >
      <p class="name">Wang-Cheng Kang</p>
      <p class="institution">Google DeepMind</p>
---

**[Dr. Huaxiu Yao](https://www.huaxiuyao.io/)** is a tenure-track Assistant Professor in the Department of Computer Science, with a joint appointment in the School of Data Science and Society at the University of North Carolina at Chapel Hill. He was previously a Postdoctoral Scholar in Computer Science at Stanford University, where he worked with Chelsea Finn. His current research focuses on developing agentic multimodal foundation models that are widely generalizable and well-aligned with human preferences. He is also committed to applying these methods to real-world data science challenges in domains such as robotics and biomedicine. Dr. Yao has authored over 80 publications in top machine learning venues, including ICML, ICLR, and NeurIPS, and has served as a (Senior) Area Chair and workshop organizer at conferences such as ICML, NeurIPS, ICLR, ACL, and EMNLP. His research has been recognized with several honors, including TMLR Outstanding Paper Award, KDD 2024 Best Paper Award, Amazon Research Award, Cisco Faculty Award, AAAI 2024 New Faculty Highlights, PharmAlliance Early Career Researcher Award, NC TraCS Innovation to Impact Awards, and UNC Junior Faculty Development Award.

***Title: From Evaluation to Actionability: Closing Factuality Gaps in Medical Large Vision–Language Models***

Abstract: Medical large vision–language models (Med-LVLMs) have advanced rapidly, yet their clinical deployment remains constrained by persistent factuality gaps, especially in high-stakes settings where even rare hallucinations are unacceptable. This talk outlines a layered pathway from evaluation to actionability. We begin with CARES, a benchmark that systematically identifies failure modes in Med-LVLMs by evaluating deficiencies in factuality, robustness, and uncertainty estimation. Building on these insights, MMedPO introduces clinically grounded multimodal preference optimization, enhancing factual alignment through counterfactual supervision and lesion-aware training to reduce clinically harmful errors. However, alignment alone cannot keep pace with evolving medical knowledge. To address this, MMed-RAG incorporates domain-aware retrieval across modalities and specialties, employing adaptive context selection and retrieval-guided pre-tuning to dynamically balance reliance on internal model knowledge versus external information. For complex clinical scenarios requiring multi-step reasoning and interdisciplinary collaboration, we present MMedAgent-RL, which implements a generalist-to-specialist agentic workflow and uses reinforcement learning to optimize collaborative decision-making, enabling more faithful and interpretable end-to-end reasoning. Together, these components form a practical and extensible framework that improves factual reliability and clinical decision quality while maintaining transparency. The talk concludes with strategies for integration and a discussion of open challenges in scaling this framework to real-world clinical applications.


---

**[Dr. Wang-Cheng Kang](https://cseweb.ucsd.edu/~wckang/)** is a Staff Research Scientist and Manager at Google DeepMind, where he leads a team dedicated to shaping the future of commercial experiences through Generative AI. Dr. Kang is widely recognized for his pioneering work of introducing self-attention to sequential behavior modeling (SASRec), which has since become a foundational baseline influencing the design of numerous systems in both academia and industry. Dr. Kang completed his Ph.D. in Computer Science at UC San Diego, with prior internships at Google Brain, Pinterest Labs, and Adobe Research. His work received ACM RecSys'17 Best Paper Runner-up, and has been featured in prominent media outlets such as MIT Technology Review and the Daily Mail.

***Title: What's Next for User Modeling: From Sequential Recommendation to Conversational Agents***

Abstract: This talk charts the evolution of user modeling, beginning with its deep roots in sequential recommendation. We will trace the progression of key techniques used to model user intent, from foundational matrix factorization and RNN-based approaches to the powerful self-attention mechanisms of Transformers. The focus will be on how these models historically interpreted "silent" user histories to predict future actions. We will then explore the paradigm shift initiated by the era of Large Language Models, where the focus moves from analyzing past behaviors to engaging in dynamic, context-rich dialogues. This transformation redefines the very nature of user context and sets the stage for the next generation of personalized, conversational experiences.



