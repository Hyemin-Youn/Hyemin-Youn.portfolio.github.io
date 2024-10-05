---
title: Home
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "0.2rem"

sections:
  - block: features
    content:
      title: <span style="font-size:125%">Hyemin-Youn portfolio homepage</span>
      text: <br><span style="font-size:100%;">😃Welcome to visit my website. Feel free to browse.</span>

        
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: /uploads/resume.pdf
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
      
# Languages 아래에 카드 섹션 추가
  - block: cards
    content:
      title: More Projects
      text: |-
        <br>
        <!-- 카드 레이아웃 시작 -->
        <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 20px;">
          <!-- 첫 번째 카드 -->
          <div style="background-color: #fff; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 300px; text-align: center; padding: 20px;">
            <img src="https://via.placeholder.com/300x200" alt="Card Image" style="width: 100%; border-radius: 10px;">
            <h3>Project 1</h3>
            <p>Brief description of Project 1.</p>
            <a href="#" style="color: #007bff; text-decoration: none;">Learn more</a>
          </div>
          <!-- 두 번째 카드 -->
          <div style="background-color: #fff; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 300px; text-align: center; padding: 20px;">
            <img src="https://via.placeholder.com/300x200" alt="Card Image" style="width: 100%; border-radius: 10px;">
            <h3>Project 2</h3>
            <p>Brief description of Project 2.</p>
            <a href="#" style="color: #007bff; text-decoration: none;">Learn more</a>
          </div>
          <!-- 세 번째 카드 -->
          <div style="background-color: #fff; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 300px; text-align: center; padding: 20px;">
            <img src="https://via.placeholder.com/300x200" alt="Card Image" style="width: 100%; border-radius: 10px;">
            <h3>Project 3</h3>
            <p>Brief description of Project 3.</p>
            <a href="#" style="color: #007bff; text-decoration: none;">Learn more</a>
          </div>
        </div>
        <!-- 카드 레이아웃 끝 -->
---
