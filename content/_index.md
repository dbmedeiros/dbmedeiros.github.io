---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
        
  - block: about.biography
    id: about
    content:
      title: Welcome!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
 
  - block: collection
    id: research
    content:
      title: Journal Articles
      filters:
        folders:
          - journalarticles
    design:
      columns: '2'
      view: compact
      
  - block: collection
    id: research
    content:
      title: Book Sections
      filters:
        folders:
          - booksections
    design:
      columns: '2'
      view: compact
    
---
