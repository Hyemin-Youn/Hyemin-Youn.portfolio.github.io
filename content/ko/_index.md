---
title: Home
date: 2023-10-24
type: landing

design:
  spacing: "0.5rem"

sections:
  - block: features
    content:
      title: <span style="font-size:125%">Hyemin-Youn portfolio homepage</span>
      text: |-
        <br><span style="font-size:100%;">윤혜민의 포트폴리오 홈페이지에 오신 것을 환영합니다😃 이메일 hyemin9973@gmail.com 연락처 010-9973-5063</span>
        <br><br>
        <!-- 카드 레이아웃 시작 -->
        <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 20px;">
          <div style="background-color: #fff; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 300px; text-align: center; padding: 20px;">
            <img src="https://via.placeholder.com/300x200" alt="Card Image" style="width: 100%; border-radius: 10px;">
            <h3>Project 1</h3>
            <p>Brief description of Project 1.</p>
            <a href="#" style="color: #007bff; text-decoration: none;">Learn more</a>
          </div>
          <div style="background-color: #fff; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 300px; text-align: center; padding: 20px;">
            <img src="https://via.placeholder.com/300x200" alt="Card Image" style="width: 100%; border-radius: 10px;">
            <h3>Project 2</h3>
            <p>Brief description of Project 2.</p>
            <a href="#" style="color: #007bff; text-decoration: none;">Learn more</a>
          </div>
        </div>
        <!-- 카드 레이아웃 끝 -->

  - block: biography
    content:
      username: admin
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      banner:
        filename: background.jpg
      biography:
        style: 'text-align: justify; font-size: 0.8em;'

  - block: experience
    content:
      username: admin
    design:
      date_format: 'January 2006'
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
