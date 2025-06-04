---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: '<strong>Now Solving:</strong> Global Optimal AI'
      filename: log1.png
      text: '<p class="text-2xl font-light" style="font-family:Times New Roman, sans-serif;">Our research group focuses on the design and implementation of large-scale local and global optimization algorithms to solve problems that arise in diverse decision-making paradigms such as machine learning, data analysis, and estimation as well as stochastic optimization, optimal control, and complex networks.</p>'
      primary_action:
        text: Learn more
        url: https://hugoblox.com/templates/
      secondary_action:
        text: Joint us
        url: /#positions
      announcement:
        text: "Announcing the release of version 1."
        link:
          text: "Read more"
          url: "/#research"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "bg-white"
      background:
        color: "white"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: collection
    id: news
    content:
      title: News
      subtitle: ''
      text: 'Check out our recent publications below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - news
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
      view: compact
      # Choose single or dual column layout
      columns: '2'
  - block: cta-image-paragraph
    id: research
    content:
      items:
        - title: Research
          text: >
             Our research group focuses on the design and implementation of large-scale local and global optimization algorithms to solve problems that arise in diverse decision-making paradigms such as machine learning, data analysis, and estimation as well as stochastic optimization, optimal control, and complex networks. Our algorithms combine mathematical techniques and emerging high-performance computing hardware (e.g., multi-core CPUs, GPUs, and computing clusters) to achieve 
             computational scalability. The goal is to make these developments accessible to academic and industrial users by implementing algorithms on easy-to-use and extensible 
             software libraries.<br><br>
             Furthermore, We have applied the algorithms and tools to help collaborators address engineering and scientific questions that arise in diverse application 
             domainsincluding conflict resolution in energy system design, robust control of crystallization systems, predictive control of wind turbines, power management in 
             large networks, estimation of microbial growth models, and image classification for contaminant detection. <br><br>
          # Upload image to `assets/media/` and reference the filename here
          image: aboutus.png
          button:
            text: Joint us
            url: /#positions
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Hugo Smith"
          role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: collection
    id: publications
    content:
      title: Publications
      subtitle: ''
      text: 'Check out our recent publications below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - pub
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
      view: card                    
      columns: '1'                   
      card:
        css_class: "shadow-lg rounded-xl border border-gray-200 p-4 bg-white"
  - block: markdown
    id: members
    content:
      title: "Members"
      text: |
        <div class="grid grid-cols-2 gap-6">
          <div class="flex items-center space-x-4">
            <img src="/media/testimonial-1.jpg" class="rounded-full w-10 h-10" alt="Kaixun">
            <div>
              <h3 class="text-xl font-bold">Dr. Kaixun Hua</h3>
              <p>Postdoc – Global Optimization</p>
            </div>
          </div>
          <div class="flex items-center space-x-4">
            <img src="/media/testimonial-1.jpg" class="rounded-full w-10 h-10" alt="Jiayang">
            <div>
              <h3 class="text-xl font-bold">Jiayang Ren</h3>
              <p>Ph.D. Student – Clustering</p>
            </div>
          </div>
        </div> 
  - block: features
    id: people
    content:
      title: People
      text: Build your site with blocks 🧱
      items:
        - name: Optimized SEO
          image: testimonial-1.jpg
          description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
        - name: Fast
          icon: bolt
          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
        - name: Easy
          icon: sparkles
          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
        - name: No-Code
          icon: code-bracket
          description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        - name: Highly Rated
          icon: star
          description: Rated 5-stars by the community.
        - name: Swappable Blocks
          icon: rectangle-group
          description: Build your pages with blocks - no coding required! 
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Build your future-proof website
          text: As easy as 1, 2, 3!
          feature_icon: check
          features:
            - "Future-proof - edit your content in text files"
            - "Website is generated by a single app, Hugo"
            - "No JavaScript knowledge required"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Get Started
            url: https://hugoblox.com/templates/
        - title: Large Community
          text: Join our large community on Discord - ask questions and get live responses
          feature_icon: bolt
          features:
            - "Dedicated support channel"
            - "3,000+ users on Discord"
            - "Share your site and get feedback"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Join Discord
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: features
    id: positions
    content:
      title: <p class="text-5xl font-bold" style="font-family:Times New Roman, sans-serif;">Positions</p>
      text: >
            <p class="text-2xl font-bold" style="font-family:Times New Roman, sans-serif;">We are actively seeking future postdoctoral researchers, graduate students, visiting students, and undergraduate students.</p>
            <p class="text-2xl font-light" style="font-family:Times New Roman, sans-serif; text-indent: 2em;">👉 Please <span class="font-bold">send your CV to</span> <span style="text-decoration: underline;">yankai.cao@ubc.ca.</span>. </p> 
            <p class="text-2xl font-light" style="font-family:Times New Roman, sans-serif; text-indent: 2em;">👉  Please <span class="font-bold">provide the following information:</span>   degree program and university, graduation year, GPA, class rank, English proficiency test score, desired start date, research summary, and future research plans (for postdocs). </p> 
            <p class="text-2xl font-light" style="font-family:Times New Roman, sans-serif; text-indent: 2em;">👉 Please apply through <a href="https://www.grad.ubc.ca/prospective-students/application-admission" target="_blank" class="underline text-blue-600 hover:text-blue-800"> UBC Graduate School</a>.</p>
            <p class="text-2xl mb-8 font-light" style="font-family:Times New Roman, sans-serif; text-indent: 2em;">👉  <a href="funding/"> Here is for <span style="text-decoration: underline;">Funding Opportunities</span> </a>. </p>
            <p class="text-3xl font-bold" style="font-family:Times New Roman, sans-serif;"><strong>To Ph.D./ Master Candidates: </strong></p>
            <p class="text-2xl font-light italic" style="font-family:Times New Roman, sans-serif;">Ideal candidates will have a strong background in process modeling, control, optimization, and excellent communication skills. Students with a major in Control Engineering, Chemical Engineering, Automation Engineering, Systems Engineering, Industrial Engineering, Computer Science or Applied Mathematics are preferred.</p>
      items:
        - name: Optimized SEO
          icon: magnifying-glass
          description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
        - name: Fast
          icon: bolt
          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
        - name: Easy
          icon: sparkles
          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
        - name: No-Code
          icon: code-bracket
          description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        - name: Highly Rated
          icon: star
          description: Rated 5-stars by the community.
        - name: Swappable Blocks
          icon: rectangle-group
          description: Build your pages with blocks - no coding required!
 
---
