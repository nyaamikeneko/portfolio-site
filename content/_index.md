---
# Leave homepage title empty to fall back to the site title
title: ""
date: 2025-06-30
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  #######################################################################
  # Hero / Biography
  #######################################################################
  - block: resume-biography-3
    title: "Biography"
    content:
      # `admin` should correspond to a folder under `content/authors/`
      username: admin
      text: |-
        Hi! I’m Taro, an undergraduate student in Medicine at Nippon Medical School. I'm deeply interested in how the brain processes complex sensory inputs—like sound and light—especially in mouse models of psychiatric disorders. I use both dry and wet lab approaches to explore these mechanisms.My goal is to advance science that benefits the people most affected by disease — communities often overlooked by mainstream research and healthcare.
 
        I bring a strong foundation in both neuroscience and deep learning, with research experience at Kyoto University’s iCenter for iPS Cell Research and Application, Japan’s Ministry of Health, Labour and Welfare, and the Department of Physiology at Nippon Medical School.
 
        Always open to new collaborations or opportunities—feel free to reach out!
 #      button:
 #       text: Download CV
 #       url: uploads/resume.pdf
    design:
      css_class: light
      background:
        color: white


  #######################################################################
  # Research & Training
  #######################################################################
  - block: markdown
    content:
      title: "📚 Research & Training"
      text: |-
        **Experimental & Computational Skills**  
        • In-vivo mouse handling & high-density electrophysiology  
        • Machine-learning-driven data analysis  

        **Research Experience**  
        • Graduate School of @ University  
        • Center for iPS Cell Research & Application (CiRA)  
        • Ministry of Health, Labour and Welfare, Japan  
        • **CiNET** – Collaborative Center for Neuroimaging *(starting soon)*  

        **Formal Coursework**  
        • Deep Learning — University of Tokyo GCI (2024)  
        • Brain Science Training Program — RIKEN CBS  

    design:
      columns: "1"

  #######################################################################
  # Featured Publications
  #######################################################################
  - block: collection
    id: papers
    content:
      title: Projects
      filters:
        folders: [publication]
        featured_only: true
    design:
      view: article-grid
      columns: 2

  #######################################################################
  # Recent Publications (full list)
  #######################################################################
 # - block: collection
 #   content:
 #     title: Recent Publications
 #     filters:
 #       folders: [publication]
 #       exclude_featured: false
 #   design:
 #     view: citation

  #######################################################################
  # Talks
  ########################################################################
 #  - block: collection
 #    id: talks
 #    content:
 #      title: Recent & Upcoming Talks
 #      filters:
 #        folders: [event]
 #    design:
 #      view: article-grid
 #      columns: 1

  #######################################################################
  # News / Blog
  #######################################################################
 # - block: collection
 #   id: news
 #   content:
 #     title: Recent News
 #     page_type: post
 #     count: 5
 #     filters:
 #       exclude_future: false
 #       exclude_past: false
 #   design:
 #     view: date-title-summary
 #     spacing:
 #       padding: [0, 0, 0, 0]

  #######################################################################
  # Contact CTA
  #######################################################################
  - block: cta-card
    content:
      title: "🤝 Get in Touch"
      text: "Open to collaborations, internships, and joint projects. Email me anytime."
      button:
        text: Email Me
        url: "mailto:22taro.m.00@nms.ac.jp"
    design:
      card:
        css_class: "bg-primary-700"

---

