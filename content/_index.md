---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing
share: true

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/cv.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks-purple.svg # stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: true # true

  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2


  # - block: markdown
  #   content:
  #     title: Feed
  #     subtitle: LinkedIn
  #     text: |-
  #       <div id="feed" class='sk-ww-linkedin-profile-post' data-embed-id='25423379' height='400'></div><script src='https://widgets.sociablekit.com/linkedin-profile-posts/widget.js' async defer></script>
        
        
# <iframe src='https://widgets.sociablekit.com/linkedin-profile-posts/iframe/25423379' frameborder='0' width='100%' height='1000'></iframe>      
        
# <div id="feed" class='sk-ww-linkedin-profile-post' data-embed-id='25423379' height='400'></div><script src='https://widgets.sociablekit.com/linkedin-profile-posts/widget.js' async defer></script>


#  <div class='sk-ww-linkedin-profile-post flex-none m-w-[130px] mx-auto md:mx-0' data-embed-id='25423379'></div><script src='https://widgets.sociablekit.com/linkedin-profile-posts/widget.js' async defer></script>
       

# <iframe src='https://www.juicer.io/api/feeds/nikolaos-zioulis/iframe' frameborder='0' width='1000' height='1000' style='display:block;margin:0 auto;'></iframe>    

# <script type="text/javascript" src="https://www.juicer.io/embed/nikolaos-zioulis/embed-code.js" async defer></script>      
        
# <div class='sk-ww-linkedin-profile-post flex-none m-w-[130px] mx-auto md:mx-0' data-embed-id='25423379'></div><script src='https://widgets.sociablekit.com/linkedin-profile-posts/widget.js' async defer></script>
        
# <iframe src='https://widgets.sociablekit.com/linkedin-profile-posts/iframe/25423379' frameborder='10' width='1000' height='1000'></iframe>
  
  - block: collection
    content:
      title: Recent Publications
      # subtitle: Sub
      text: For a complete list of publications please visit my [__`Google Scholar`__](https://scholar.google.com/citations?user=f7hypjsAAAAJ) profile.
      filters:
        folders:
          - publication
        exclude_featured: false
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: date-title-summary # date-title-summary # card # compact # citation
  - block: collection
    id: events
    content:
      title: Events & Talks
      filters:
        folders:
          - event
    design:
      view: card # article-grid
      columns: 1

  - block: markdown
    content:
      title: Feed
      subtitle: LinkedIn
      text: |-
        <div id="feed" class='sk-ww-linkedin-profile-post' data-embed-id='25423379' height='400'></div><script src='https://widgets.sociablekit.com/linkedin-profile-posts/widget.js' async defer></script>

  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]


  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---