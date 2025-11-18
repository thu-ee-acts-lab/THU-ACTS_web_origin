---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-04-21
type: landing

banner:
  title: "THU-ACTS"

sections:
  - block: slider
    content:
      slides:
        - title: Our Latest Work Has Been Accepted by VLSI 2025!
          content: |
             <p style = "font-size:1em; color:white">  A 94Hz Inference and 7.4mJ/epoch Fine-tune Edge SoC for Diffusion-based <br> Robot Manipulation  with 
             Speculation and Disturbance Enhancement </p>
          
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: VLSI2025.jpg  
              filters:
                brightness: 0.6
            position: center
            color: '#666'
          link:
            icon: 
            icon_pack: 
            text: Learn More
            url: ../post/2025-vlsi/  
        - title: Our Latest Work Has Been Accepted by TCAD 2025!
          content: 
            <p style = "font-size:1em; color:white"> SASDenSebLE:A Compact Vision Transformer Inference Architecture 
             <br>with Saturation-Approximate Softmax Dataflow Enabling Sequence-<br>Parallelism Boosted Layer-Fusion Execution
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: TCAD2025.jpg  
              filters:
                brightness: 0.6
            position: center
            color: '#555'
          link:
            icon: 
            icon_pack: 
            text: Learn More
            url: ../post/2025-tcad/
        - title: Our Latest Work Has Been Accepted by MLSys 2025!
          content: 
           <p style = "font-size:1em; color:white"> HyC-LoRA:Memory Efficient LoRA Fine-tuning 
            <br>with Hybrid Activation Compressions
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: MLSys2025_slide.jpg
              filters:
                brightness: 0.6

            position: center
            color: '#333'
          link:
            icon: 
            icon_pack: 
            text: Learn More
            url: ..post/2025-mlsys/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '750px'
      # Make the slides full screen within the browser window?
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 1500

  - block: slider
    content:
      slides:
        - title: 
            <br>
            <br>     
            Tsinghua University
            <br> 
            Advanced Computing Technology & Systems (ACTS) Lab
            <br>
            <br>
          content: 
          
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: chip.jpg  
              filters:
                brightness: 0.65
            position: center
            color: '#bbbbbbff'
          # link:
          #   icon: 
          #   icon_pack: 
          #   text: 详细情况
          #   url: ../post/2025-vlsi/  

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '500px'
      # Make the slides full screen within the browser window?
      is_fullscreen: false



  # - block: hero
  #   content:
  #     title: 
  #       <br>
  #       <br>     
  #       清华大学
  #       <br>
  #       先进计算技术与系统
  #       <br>
  #       实验室
  #       <br>
  #       <br>
  #     align: left
  #     background:
  #       image:
  #         # Specify an image from `assets/media/`
  #         # or delete the image section to remove it
  #         filename: MLSys2025_slide.jpg
  #         filters:
  #           brightness: 0.6
  #       position: center
  #       color: '#333'
  #   design:
  #     # background:
  #     #   gradient_end: '#F2F963'
  #     #   gradient_start: '#540054'
  #     #   text_color_light: true    



  - block: hero
    content:
      image:
        filename: welcome.jpg
      text: |
        <p> &nbsp &nbsp &nbsp &nbsp Our research focuses on foundational computing technologies for embodied intelligence systems. Facing the challenges of multi-task integration, real-time interaction, and energy-efficient computation in embodied applications such as robotics, we rethink traditional “reconstruction-based’’ accelerator design paradigms.

        Following a software-deconstruction → hardware-simplification → iterative-optimization methodology, we pursue full-stack innovation—from emerging circuit techniques and architecture simplification strategies to efficient application-level algorithms.

        Our goal is to explore new design paradigms and deliver domain-general computing chips and systems that bridge circuit-level innovations with system-level architectural advances.</p>



  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: HongyangJia
      # Override your profile text from `authors/admin/_index.md`?
      text: 
 
    design:
      view:

    

  - block: collection
    id: posts
    content:
      title: Research Directions
            <br>
            <br>


      subtitle: ''
      text: 
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - field
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      
    design:
      # Choose a listing view
      view: showcase
      # Choose single or dual column layout
      columns: '1'


 
  - block: collection
    id: posts
    content:
      title: Past Research Work
      subtitle: ''
      text: 
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - publication
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      
    design:
      # Choose a listing view
      view: showcase
      # Choose single or dual column layout
      columns: '1'


  # - block: collection
  #   content:
  #     title: 最新工作情况
  #     subtitle:
  #     text:
  #     count: 5
  #     offset: 0
  #     order: date
  #     page_type: post
  #   design:
  #     view: compact
  #     columns: '1'

  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - 课题组导师 
        - 研究生
        - 本科生
        - 工程师
      sort_by: Params.last_name
      sort_ascending: true
    design:
      # Show user's social networking links? (true/false)
      show_social: false
      # Show user's interests? (true/false)
      show_interests: false
      # Show user's role?
      show_role: true
      # Show user's organizations/affiliations?
      show_organizations: true






---

