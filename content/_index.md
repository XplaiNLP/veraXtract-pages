---
# Leave the homepage title empty to use the site title
title:
date: 2025-02-27
type: landing

sections:
  - block: hero
    content:
      title: |
        <div style="display: flex; justify-content: center; align-items: center; text-align: center; height: 10vh;">
          VeraXtract
        </div>
        <div style="display: flex; justify-content: center; align-items: center; text-align: center; height: 10vh;">
          <span style="color:rgba(150, 148, 148, 0.87); font-size: 1rem;">
          a BMBF-funded Research Project at <a href="https://www.tu.berlin/en/qu" target="_blank"> TU Berlin</a>
          </span>
        </div>
    design:
      background:
        image:
          filename: welcome.jpg
          filters:
            brightness: 0.3
        text_color_light: true

  - block: markdown
    content:
      title: Welcome to VeraXtract
      text: |
        ### **VeraXtract: Verification and Extraction of Disinformation Narratives with Individualized Explanations**
        <!-- {style="color: grey"} -->

        The increasing prevalence of content on social media and online information consumption has accelerated the spread of disinformation, posing a significant threat to societal stability and security. Recent events — from geopolitical conflicts to public health crises — demonstrate how disinformation can influence public opinion. In response, we take a systematic, scientifically grounded approach to understanding and countering disinformation narratives.

        The urgent need to address this pervasive influence of disinformation, especially in light of rapidly changing digital media and ever-growing quantities of AI-generated content informs our central research question:
        
        **How can disinformation be concretely represented through narratives to provide a comprehensive overview of past, current, and emerging trends in disinformation?**

        ### Objectives

        By focusing on narrative structures, we aim to create a robust framework for analyzing disinformation in a clear and transparent manner. VeraXtract is structured around three overarching topics:

        1. **Narrative Extraction:**
          We develop methods to extract narratives from diverse sources and modalities — including media outlets, blogs, social media, and messaging channels. This involves defining what constitutes a narrative in the context of disinformation and applying techniques such as topic modeling, event extraction, summarization, and entity recognition.

        2. **Knowledge Base/Graph Development:**
          A dynamic knowledge base is being created to aggregate verified facts and documented disinformation. This resource will allow the visualization and analysis of trends by linking information across different time points and levels of detail in a knowledge graph.

        3. **Explainable AI:**
          Recognizing the importance of transparency, we place a strong emphasis on explainability in our systems. We develop methods that generate clear, understandable explanations for AI-driven analyses and evaluate them empirically, thereby fostering trust and facilitating informed decision-making among users.

        These main objectives are realized on three interconnected levels of abstraction:

        **Level 1 – Narrative Representation:**
        Extraction of narratives from continuously monitored text and image sources, including contributions from accredited fact-checkers and social media platforms.
        
        **Level 2 – Thematic Analysis:**
        A deeper examination of the underlying topics within these narratives, enabling users to track, understand, and analyze the evolution of disinformation themes.
        
        **Level 3 – Entity Analysis:**
        Investigation of key entities such as individuals, organizations, and locations. This level also involves identifying disinformation superspreaders and understanding their roles in disseminating false information.

        Integrating these research efforts delivers a comprehensive framework for understanding and combating disinformation in Germany. Our approach emphasizes transparency, traceability, and practical applicability, ensuring that our findings can inform both academic research and policy-making in a realistic and grounded manner.

  - block: portfolio
    content:
      title: Research
      subtitle: "Verification and Extraction of Disinformation Narratives with Individualized Explanations"
      text: |
        In the VeraXtract Project we focus on applied research of disinformation narratives at different Levels of Abstraction (LoAs). This includes the analysis and implementation of AI-based disinformation detection as well as transparency aspects through Explainable AI (xAI) at various LoAs.
        

      filters:
        # Folders to display content from
        folders:
          - research
        # Only show content with these tags
        tags: []
  
  - block: collection
    content:
      title: News
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: news
    design:
      view: compact
      columns: '2'

  - block: markdown
    content:
      title: Projects
      text: |
        ## Running

        ## Past
    design:
      columns: '2'

  - block: markdown
    content:
      title: Partnerships
      text: |
        <div style="display: flex; gap: 20px;">

          <div style="flex: 1;">
          Industry Collaborations

          - [Deutsche Presse-Agentur (dpa)](https://www.dpa.com/)
          - [Deutsche Welle (DW)](https://www.dw.com/en)
          - [Ubermetrics GmbH](https://www.ubermetrics.de/)
          - [nyonic GmbH](https://www.nyonic.com)
          - [delphai GmbH](https://www.delphai.com/)
          - [Crowdee GmbH](https://www.crowdee.de/)
          </div>

          <div style="flex: 1;">
          Academic Advisors

          - [Prof. Birgit Beck (TUB)](https://www.tu-berlin.de/)
          - [Prof. Joachim Meyer (TAU)](https://www.jmeyer.sites.tau.ac.il/)
          - [Dr. Sven Schmeier (DFKI)](https://www.dfki.de/web/dfki/en)
          </div>

        </div>

  
    design:
      columns: '2'
---
