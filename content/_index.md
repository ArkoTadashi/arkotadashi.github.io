---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: 'Download CV'
        url: 'uploads/Arko Sikder - CV.pdf'
      headings:
        about: ''
        education: ''
        interests: ''
        toefl: 'TOEFL Scores'
      sections:
        - title: ''
          items: toefl

  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: features
    content:
      title: "TOEFL Scores"
      text: "September 2024"
      items:
        - name: "Reading"
          description: "28/30"
          icon: "bolt"
        - name: "Listening"
          description: "27/30"
          icon: "bolt"
        - name: "Speaking"
          description: "22/30"
          icon: "bolt"
        - name: "Writing"
          description: "26/30"
          icon: "bolt"
    design:
      columns: "2"
      background:
  - block: resume-awards
    content:
      title: Awards
      username: admin
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
      
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My journey in Computer Science has been driven by a deep passion for problem-solving. While working on my undergraduate thesis, I discovered the exciting world of computer science research. This experience was transformative – it showed me how my competitive programming background could evolve into meaningful research contributions.

        What excites most me about research is finding elegant solutions to complex problems that affects us in our day-to-day life.

        Currently, I'm channeling my enthusiasm by mentoring young competitive programmers while preparing for my PhD. I'm eager to connect with researchers and potential advisors! 🚀

    design:
      columns: '1'
  
---
