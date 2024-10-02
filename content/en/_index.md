---
title: Home
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "0.5rem"

sections:
  - block: features
    content:
      title: <span style="font-size:70%">Hyemin-Youn portfolio homepage</span>
      text: <br><span style="font-size:125%;">😃Welcome to visit my website. Feel free to browse.</span> 

  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: 'https://hyemin-youn.github.io/Hyemin-Youn.test.github.io/uploads/resume.pdf'
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: background.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 1em;'

  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: skills
    content:
      title: Skills & Hobbies
      username: admin
  - block: awards
    content:
      title: Projects
      username: admin
  - block: languages
    content:
      title: Languages
      username: admin
---