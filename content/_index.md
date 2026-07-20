---
# Leave the homepage title empty to use the site title
title:
date: 2026-06-14
type: landing

sections:
  - block: hero
    content:
      title: "Laboratory for multiregional neural circuits and behaviour"
      text: |
        ## Centre for Developmental Neurobiology, King's College London
        <br>
    design:
      css_class: title-banner
      spacing:
        padding: ['40px', '0', '20px', '0']

  - block: markdown
    content:
      title: 
      text: |
        We seek to understand the organizing principles of long-range circuits formed between the cerebellum and forebrain regions like the neocortex and basal ganglia and to define how activity patterns in these multiregional circuits facilitate the execution of both sensorimotor and cognitive behaviours.

        <div class="mt-4">
          <img src="/media/multiregional_loops_v2.png" alt="Description" class="img-fluid rounded d-block mx-auto multiregional-img">
        </div>
    design:
      css_class: intro-text
      spacing:
        padding: ['50px', '0', '50px', '0']
  
  - block: collection
    content:
      title: Recent news
      subtitle:
      text:
      count: 
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
