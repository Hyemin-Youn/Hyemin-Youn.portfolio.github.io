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
        <br><span style="font-size:100%;">윤혜민의 포트폴리오 홈페이지에 오신 것을 환영합니다😃</span>
        <br>
        <!-- 카드 레이아웃 시작 -->
        <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 20px;">
          <!-- 첫 번째 카드 -->
          <div style="background-color: #fff; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 300px; text-align: center; padding: 20px;">
            <img src="https://via.placeholder.com/600x300" alt="Card Image" style="width: 100%; border-radius: 10px;">
            <h3>(2024년) 학부연구생 모집</h3>
            <p>저희 연구실에서 학부연구생을 모집하니, 아래 내용을 확인해주세요.</p>
            <a href="#" style="color: #007bff; text-decoration: none;">Learn more</a>
          </div>
          <!-- 두 번째 카드 -->
          <div style="background-color: #fff; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 300px; text-align: center; padding: 20px;">
            <img src="https://via.placeholder.com/600x300" alt="Card Image" style="width: 100%; border-radius: 10px;">
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

  - block: awards
    content:
      title: Projects
      username: admin

  - block: languages
    content:
      title: Languages
      username: admin

---
