---
# Leave the homepage title empty to use the site title
title:
date: 2026-06-14
type: landing

sections:
  - block: hero
    content:
      title: Kostadinov Lab
      image:
        filename: PCdendrites_DK169.png
      text: |
        ## Centre for Developmental Neurobiology, 
        ## King's College London
        <br>
        The execution of most of the brain’s essential functions – such as sensing our world, moving through it, and learning to adapt to its challenges – requires the concerted action of multiple brain regions. We seek to uncover the mechanisms that organize long-range circuits formed between the cerebellum and the forebrain during development, and to define how activity patterns in these multi-regional circuits facilitate the execution of both sensorimotor and cognitive behaviours. Our goal is to create a unified understanding of these seemingly distinct functional roles by defining common principles of multi-regional computations performed by cerebellar circuits and their partners.

        To achieve these goals, we combine molecular, functional, and computational techniques in mice performing complex behavioural tasks. These tools allow us to map the organizational logic of connections between the cerebellum and its partners, uncover shared activity patterns in these long-range circuits, and define causal contributions of the cerebellar activity patterns to computations in partner regions and to behaviour. This work will generate new insights into the cerebellum's diverse roles and provide a rigorous foundation for quantitative, multiscale theories of learning and computation that can be applied throughout the brain.
        We study the roles of the cerebellum in brain-wide computations and behaviour.
    design:
      css_class: landing-hero
      spacing:
        padding: ['50px', '0', '50px', '0']
  
  - block: collection
    content:
      title: Latest news
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
      page_type: news-and-fun
    design:
      view: article-grid
      columns: '2'
      spacing:
        padding: ['50px', '0', '50px', '0']
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: Latest Papers
      text: ""
      count: 3
      filters:
        folders:
          - publication
        # publication_type: 'journal-article'
    design:
      view: article-grid
      columns: '1'
      spacing:
        padding: ['50px', '0', '50px', '0']

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./team/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'

  - block: markdown
    content:
      title: |
        <span id="contact"></span>
        Contact
      text: |
        <div class="contact-grid">

          <div class="contact-text">
          
          [Centre for Developmental Neurobiology](https://devneuro.org/cdn/index.php) <br>
          Institute of Psychiatry, Psychology & Neuroscience <br>
          King's College London <br>
          New Hunt's House <br>
          Guy's Campus <br>
          London SE1 1UL <br>
          United Kingdom
          <br>

          Email: [dkneurolab@gmail.com](mailto:dkneurolab@gmail.com)

          </div>

          <div class="contact-map">

          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6391.766999439189!2d-0.09411536350078539!3d51.502269807126524!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48760359f4a8c70b%3A0x1ba74218895f2644!2sNew%20Hunt&#39;s%20House!5e0!3m2!1sen!2suk!4v1781537885458!5m2!1sen!2suk"
            width="100%"
            height="350"
            style="border:0;"
            loading="lazy">
          </iframe>

          </div>

        </div>
    design:
      spacing:
          padding: ['50px', '0', '20px', '0']
---
