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
      text: <br><span style="font-size:125%;">윤혜민의 포트폴리오 홈페이지에 오신 것을 환영합니다😃 이메일hyemin9973@gmail.com 연락처010-9973-5063</span> 
      
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: background.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'

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