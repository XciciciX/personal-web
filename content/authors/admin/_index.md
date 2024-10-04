---
# Display name
title: Xixiao Pan

# Name pronunciation (optional)

# Full name (for SEO)
first_name: Xixiao
last_name: Pan

# Status emoji
status:
  icon: 

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Undergraduate Student

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: University of Michigan
    url: https://umich.edu/
  - name: xixiaoxx@umich.edu

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:your-email@example.com'
    label: E-mail Me
  - icon: brands/x
    url: https://twitter.com/GetResearchDev
  - icon: brands/github
    url: https://github.com/gcushen
  - icon: brands/linkedin
    url: https://www.linkedin.com/
  - icon: brands/instagram
    url: https://www.instagram.com/

education:
  - area: B.S.E. Data Science Engineering
    institution: University of Michigan, College of Engineering
    date_start: 2023-09-01
    date_end: 2025-05-02
    summary: |
      GPA: 3.8/4.0

      Courses included:
      - Artificial Intelligence: Data Mining, Machine Learning, Computer Vision, Natural Language Processing, Computer Graphics and GenAI
      - Software Development: Computer Networks, Web Development, Database Management, VR/AR Development
      - Computer Architecture: Computer Organization
  - area: B.E. Electrical and Computer Engineering
    institution: Shanghai Jiao Tong University, UM-SJTU Joint Institute
    date_start: 2021-09-01
    date_end: 2025-05-01
    summary: |
      GPA: 3.7/4.0

      Courses included:
      - Math: Linear Algebra, Calculus, Discrete Mathematics
      - Circuits: Signal Processing, Logical Design

work:
  - position: Software Development Engineer Intern
    company_name: AMD
    company_url: 'https://www.amd.com/en.html'
    company_logo: custom/amd-logo.png
    date_start: 2024-05-15
    date_end: 2024-12-01
    summary: |2-
      Responsibilities include:
      - Deployed five deep learning models including diffusions and LLMs on Windows platform. Embedded models into a software in development.
      - Exported PyTorch models as ONNX models to generally apply on all platforms.
      - Optimize LLM models through AWQ quantization.
      - Improved Stable Diffusion 3x faster by transformer optimization and quantization.

  - position: Research Intern - Advised by Professor Paul Green
    company_name: University of Michigan Transportation Research Institute
    company_url: https://www.umtri.umich.edu/
    company_logo: ''
    date_start: 2024-01-01
    date_end: 
    summary: |
      Responsibilities include:
      - Exported the data of 10 km long I-94 highway in Detroit to RoadRunner to create the virtual road with realistic road pattern.
      - Built an easy-to-use driving simulator platform in Unreal Engine 4 with Carla.
      - Made an immersive environment with foliage and sigs in the simulator with random distribution. The rendering was 4x faster by optimization.

  - position: Research Student - Advised by Professor Qinya Li
    company_name: Shanghai Jiao Tong University
    company_url: https://www.cs.sjtu.edu.cn/en/Faculty.aspx
    company_logo: ''
    date_start: 2022-06-01
    date_end: 2023-06-01
    summary: |
      Responsibilities include:
      - Read papers related to SimCLR model and MoCo model for unsupervised multimedia data quality assessment technology.
      - Learned scripts of SimCLR from Github and reproduced code with PyTorch.
      - Implemented the deep residual network (ResNet-50) and Very Deep Convolutional Networks (VGG).

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: C++
        description: ''
        percent: 90
        icon: devicon/cplusplus
      - name: Python
        description: ''
        percent: 90
        icon: devicon/python
      - name: PyTorch
        description: ''
        percent: 60
        icon: devicon/pytorch
      - name: JavaScript
        description: ''
        percent: 50
        icon: devicon/javascript
      - name: Linux
        description: ''
        percent: 70
        icon: devicon/linux
      - name: SQL
        description: ''
        percent: 90
        icon: devicon/mysql
      - name: React
        description: ''
        percent: 60
        icon: devicon/react
      - name: RStudio
        description: ''
        percent: 70
        icon: devicon/rstudio   
      - name: Unreal Engine
        description: ''
        percent: 80
        icon: devicon/unrealengine
      - name: Unity
        description: ''
        percent: 40
        icon: devicon/unity
      - name: Agile
        description: ''
        percent: 100
        icon: devicon/confluence
      - name: Github
        description: ''
        percent: 100
        icon: devicon/github
      
      
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Hiking
        description: ''
        percent: 30
        icon: person-simple-walk
      - name: Travelling
        description: ''
        percent: 100
        icon: person-simple-walk
      - name: Photography
        description: ''
        percent: 80
        icon: camera
      - name: Dancing
        description: ''
        percent: 100
        icon: person-simple-walk

languages:
  - name: English
    percent: 100
  - name: Chinese
    percent: 100
  - name: Spain
    percent: 25

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: 'Scalable Web Search Engine: Similar to Google'
    url: 
    date: '2024-04-01'
    awarder: January 2024
    icon: 
    summary: |
      The project is a robust search website equipped with a comprehensive document database, allowing users to input queries and receive the most relevant results efficiently. This project applied advanced information retrieval techniques, including text analysis using Term Frequency-Inverse Document Frequency (tf-idf) to assess the importance of words within documents, and link analysis with PageRank to measure the authority and relevance of documents based on their link structures.
      For faster and more scalable performance, parallel data processing using MapReduce is employed. It improves the speed of analyzing large datasets by distributing the workload across multiple nodes. The project can handle high volumes of queries and data while delivering accurate and timely search results.
      
  - title: 'Lipstick Expert'
    url: https://lipstickexpert.netlify.app/
    date: '2024-04-01'
    awarder: January 2024
    icon: 
    summary: |
      The Lipstick Expert is a web search engine to guide consumers how to select the most suitable lipstick based on price, benefit, and color in the rapidly expanding cosmetic market. The project crawls data from YouTube and Sephora, and then utilizes natrual language processing and machine learning model to develop an algorithm for product scores. Finally, it returns the top recommended lipstick choices for consumers. 
      The data collection process crawls the ten most related products from YouTube Lipstick videos, and the product details on Sephora. Data is crawled by BeautifulSoup, Youtube API and Sephora API.
      Our model determines product scores by considering factors such as mention frequency, popularity metrics, and sentiment analysis from natural language processing. The model is trained and optimized based on Kendall-tau distance using Python.
  - title: 'Full-stack Web Development: Simulate Instagram'
    url: 
    date: '2024-03-01'
    awarder: January 2024
    icon: 
    summary: |
     The project is an online social media platform that simulates Instagram, complete with user profiles and interactive posts enhanced by UI effects. The platform includes core features such as user authentication (login and logout), the ability to create and interact with posts, comment on them, like posts, and follow other users.
     For the backend, I employed SQL to manage the database, efficiently storing and retrieving user data, posts, and relationships between users. To enable seamless communication between the client and server, REST API in Python was used. On the frontend, I utilized React to build responsive and dynamic user interfaces, while the server-side logic and routing were handled using Flask. This combination of Flask and React created a cohesive, interactive platform where the client-side experience smoothly integrated with server-side functionality.
  - title: 'Database Management: Online Banking System Simulator'
    url: 
    date: '2023-10-01'
    awarder: November 2023
    summary: |
     This project develops a real-time online banking system simulator using C++, featuring a comprehensive database for managing transactions and user accounts. The system provides functionality for querying transaction history and performing revenue analysis. It designs algorithms for fraud detection, transaction scheduling, and fee calculation, while implementing data structures such as priority queues and hash tables to ensure efficient transaction processing and secure operations.
  - title: 'Machine Learning Application: Predicting Depression Condition'
    url: https://drive.google.com/file/d/1vWFGVaCjnExiOHQB4iJ9GQKmKlXU-pFx/view?usp=drive_link
    date: '2023-10-01'
    awarder: December 2024
    summary: |
     This project explores the prediction of depression severity by integrating biochemical and socioeconomic indicators using data from the NHANES 2017-2020 dataset. It addresses the role of biochemical markers, such as cholesterol and protein levels, in predicting depression and employs oversampling techniques to balance the dataset. Using LASSO regression and Random Forest modeling, the study identifies key biochemical variables related to depression, achieving an RMSE of 4.31.
     Additionally, the project investigates the impact of socioeconomic factors on depression through logistic regression and K-Nearest Neighbors (KNN) models. The analysis reveals that higher education levels and lower poverty rates correlate with reduced likelihood of depression, with the KNN model achieving approximately 70% accuracy in identifying depressed individuals. These findings highlight the importance of combining biochemical and socioeconomic predictors to improve understanding and diagnosis of depression.
 
  - title: 'DinoSnap: Dinosaur World'
    url: https://eecs498-group6.netlify.app/
    date: '2024-05-01'
    awarder: April 2024
    summary: |
      DinoSnap is an educational VR game that is meant to teach players about dinosaurs and different dinosaur eras through a unique and interactive atmosphere. Our goal is to have the player learn more about the history of dinosaurs whilst having a fun and immersive experience.
  - title: 'AnnArbor Go'
    url: https://xcicicix.github.io/p2_498.html
    date: '2024-03-01'
    awarder: February 2024
    summary: |
     It is an AR mobile application designed by Unity in a team of two. It simulates the game Pokemon Go with the settings in Ann Arbor. In this game, you have one exploration mode with Mapbox in Unity and one interaction mode with AR to grow trees in Ann Arbor. You can earn leaves as currency by growing trees and unlock products in the shop. Squirrals will appear randomly near the tree and harm your trees. You need to use acorns to fight them. We used Github for version control and JIRA for manamgement.
  - title: 'SummerSara'
    url: https://focs.ji.sjtu.edu.cn/silverfocs/demo/2022/p2team15/
    date: '2022-04-01'
    awarder: July 2022
    summary: |
      It is a web game mainly written by Elm language. It is a puzzle game simulated by game Rust Lake. You are trapped in a 7-day loop. You need to find the way out by interacting with different NPCs and locations. A lot of small games are hidden in different locations. You can explore a lot of things. In this game, the logic is realized by a functional programming language Elm and the front-end is realized by CSS. We used Github for version control and team manamgement.
---

Hi! I am a senior student in University of Michigan majoring in Data Science Engineering. And I have a dual degree in Shanghai Jiao Tong University in Electrical and Computer Engineering. 
I am currently looking for job or research opportunities related to Artificial Intelligence and Software Development Engineer in 2025 Summer.

I have experience in Machine Learning, Deep Learning, and Big Model Optimization. I also have experience in web full stack development and game engine development.

I am currently learning Computer Vision and Computer Graphics. I am interested in Deep Learning and Big Model Applications.
