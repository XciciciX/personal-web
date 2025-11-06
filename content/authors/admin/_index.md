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
role: Graduate Student in Computer Science

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: University of Southern California
    url: https://viterbischool.usc.edu/
  - name: cicipan@live.com

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'cicipan@live.com'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/XciciciX
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/xixiao-pan/

education:
  - area: M.S. Computer Science
    institution: University of Southern California, Viterbi School of Engineering
    date_start: 2025-08-25
    date_end: 2027-05-02
    summary: |
      GPA: 4.0/4.0

      Courses included:
      - Multimedia System Design
      - LLM
      - Operating System
      - Advanced Analysis of Algorithms
  - area: B.S.E. Data Science Engineering
    institution: University of Michigan, College of Engineering
    date_start: 2023-09-01
    date_end: 2025-05-02
    summary: |
      GPA: 3.8/4.0

      Courses included:
      - Data Analysis: Data Mining, Machine Learning
      - Artificial Intelligence: Computer Vision, Natural Language Processing, Computer Graphics and GenAI
      - Software Development: Distributed Systems, Search Enginer, Computer Networks, Web Development, Database Management, VR/AR Development
      - Computer Architecture: Computer Organization
  - area: B.E. Electrical and Computer Engineering
    institution: Shanghai Jiao Tong University, UM-SJTU Joint Institute
    date_start: 2021-09-01
    date_end: 2025-05-01
    summary: |
      GPA: 3.7/4.0

      Courses included:
      - Artificial Intelligence: Deep Learning
      - Math: Linear Algebra, Calculus, Discrete Mathematics
      - Circuits: Signal Processing, Logical Design

work:
  - position: Software Development Engineer Intern
    company_name: AMD
    company_url: 'https://www.amd.com/en.html'
    company_logo: custom/amd-logo.png
    date_start: 2024-05-15
    date_end: 2025-04-01
    summary: |
      Responsibilities include:
      - Designed and implemented Wingman AI Debug Agent, utilizing React and Django, featuring real-time monitoring dashboards and intelligent controllers that interpret natural language commands to automate driver development workflows, resulting in 70% increased development efficiency.
      - Integrated AMD’s proprietary LLM API to decompose complex tasks into structured subtasks using a custom-built interpreter framework.
      - Boosted task execution accuracy by 30% through prompt engineering, few-shot learning, and role-based message design, while reducing latency by up to 40% via response caching and prompt deduplication.
      - Optimized model architecture and attention mechanisms for Stable Diffusion XL Turbo and Stable Diffusion 3 by applying multi-head attention transformations, ONNX graph rewrites, and transformer structure improvements—resulting in up to 3× inference speedups on AMD GPUs.
      - Reduced memory footprint and boosted throughput through quantization techniques including FP16 and INT4 AWQ, and by converting PyTorch models to ONNX format using Microsoft Olive for cross-platform, high-performance inference deployment.

  - position: Student Researcher/Machine Learning Engineer Intern
    company_name: Grundfos
    company_url: 'https://www.grundfos.com/us'
    company_logo: custom/amd-logo.png
    date_start: 2025-06-02
    date_end: 2025-08-10
    summary: |
      Responsibilities include:
      - Built a testbed with water pumps integrating multiple industrial-grade sensors (pH, EC, DO, and liquid flow) via RS485 communication to monitor water quality parameters with high accuracy.
      - Collected Ethylene glycol concentration every half day continuously in an abnormal envrionment.
      - Developed a LSTM+CNN model to predict the remaining useful life of the cooling system, which achieved 96% accuracy in a 14-day period.
  
  - position: AI Developer Intern
    company_name: Artisk.ai
    company_url: https://www.artisk.ai/
    company_logo: ''
    date_start: 2025-03-01
    date_end: 2025-05-28
    summary: |
      Responsibilities include:
      - Engineered a production-ready AI logo customization platform with an OpenCV-based image processor, deployed as a containerized Flask microservice with Docker on GCP with print-ready logo transformations supporting 10,000+ daily customization requests.
      - Implemented a Redis-based asynchronous task queue with request polling and real-time updates, enabling smooth client-side interaction via JavaScript while ensuring efficient and non-blocking image processing workflows.

  - position: Student Contributor
    company_name: Artisk.ai
    company_url: https://www.artisk.ai/
    company_logo: ''
    date_start: 2025-02-01
    date_end: 2025-03-01
    summary: |
      Responsibilities include:
      - Engineered an AI-powered learning web using Claude 3 LLM via AWS Bedrock, with custom prompt engineering and validation to automatically generate study materials from uploaded files.
      - Implemented Redis-based caching for template graph data, reducing backend cold-start time to near-instant load by storing precomputed data; managed Redis cluster with custom TTL policies.
      - Developed scalable RESTful APIs using FastAPI to support full CRUD operations on Neo4j-stored graph data (e.g., Thought nodes, relationships) and file upload; implemented response caching with Redis, and applied request batching and selective data hydration to improve API response times.



  - position: Research Intern - Advised by Professor Paul Green
    company_name: University of Michigan Transportation Research Institute
    company_url: https://www.umtri.umich.edu/
    company_logo: ''
    date_start: 2024-01-10
    date_end: 2024-12-10
    summary: |
      Responsibilities include:
      - Developed an immersive driving simulator in Unreal Engine 4 with realistic map to study driver workload and distraction by using visual occlusion.
      - Exported the data of 10 km long I-94 highway in Detroit to RoadRunner to create the virtual road with realistic road pattern.
      - Made an immersive environment and optimized rendering speed by 4x using macro variation and level-of-detail (LOD) techniques for foliage, road signs, and environmental assets, reducing frame drops and ensuring a high update rate.

  - position: Backend Development Intern
    company_name: Ping An Technology Co., Ltd.
    company_url: 
    company_logo: ''
    date_start: 2023-05-04
    date_end: 2023-08-01
    summary: |
      Responsibilities include:
      - Led iBatis-to-MyBatis migration by developing an industry-standard Java-based transformation utility with regex pattern matching that reduced manual migration effort by 90%.
      - Implemented RocketMQ-based messaging system with support for retry logic and Dead Letter Queues (DLQ) to ensure message reliability and failure recovery in core loan repayment processing workflows.

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
        percent: 80
        icon: devicon/pytorch
      - name: Java
        description: ''
        percent: 50
        icon: devicon/python
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

  - title: 'Scalable Search Engine'
    url: https://github.com/XciciciX/SearchEngine
    date: '2025-01-10'
    awarder: May 2025
    icon: 
    summary: |
      The project is a fully distributed web-scale search engine, designed and implemented from the ground up with components for crawling, parsing, indexing, and ranking. It employs a multi-threaded and multi-process architecture, where each node independently maintains its own crawler, parser, frontier, and index while coordinating through a SHA-256–based URL hashing system for distributed load balancing. To prevent duplicate crawling, each node maintains Bloom filters for inter-node communication and forwards out-of-domain URLs to the correct server over TCP/IP.

      The indexing subsystem supports runtime index construction and duplicate detection through shingling, stemming, and token normalization, storing compressed posting lists in chunked index files for efficient access. Queries are compiled into Boolean and phrase constraints via a Constraint Solver and Query Compiler, which builds layered ISR structures (ISRAnd, ISROr, ISRPhrase) to support complex query logic. A two-stage ranking pipeline combines a heuristic ranker—leveraging structural and frequency-based features—with a neural ML ranker trained in Python and deployed via ONNX for fine-grained relevance scoring.

      This distributed design enables parallel query processing and runtime indexing across multiple nodes, providing resilience to individual node failures. The final system achieved strong retrieval performance with an NDCG score of 0.7827, demonstrating the engine’s ability to produce rankings comparable to commercial search engines while remaining fully self-contained and horizontally scalable.

  - title: 'Distributed Key-Value Storage'
    url: https://github.com/XciciciX/Distributed_KV_System
    date: '2024-10-01'
    awarder: December 2024
    icon: 
    summary: |
      The project is a fault-tolerant sharded key/value storage system built on top of the Paxos consensus protocol to ensure strong consistency across distributed servers. The system partitions data into shards and assigns each shard to a replica group, where Paxos maintains agreement on the sequence of operations within the group. A centralized Shard Master, also replicated using Paxos, manages dynamic reconfiguration by balancing shard assignments when replica groups join or leave the system.

      To guarantee linearizable consistency during reconfiguration, the system synchronizes data transfers between groups through shard migration protocols that use coordinated RPCs (AssignShard and PullShard). Each client request carries configuration metadata to prevent stale operations during configuration changes. The design achieves single-copy semantics under concurrent updates and network partitions, ensuring availability and correctness even when a minority of servers fail.


  - title: 'miProxy – HTTP Video Proxy'
    url: https://github.com/XciciciX/miProxy
    date: '2024-08-20'
    awarder: December 2024
    icon: 
    summary: |
      The project is an adaptive HTTP proxy designed for MPEG-DASH video streaming, capable of dynamically selecting video bitrates based on real-time network throughput. It integrates a custom DNS-based load balancer to distribute client requests among multiple CDN servers, optimizing both latency and load distribution. Advanced adaptive streaming techniques are applied to monitor connection bandwidth and automatically adjust segment bitrates to maintain stable playback quality.

      For performance evaluation, a multi-node CDN environment was simulated using Mininet, where the proxy achieved consistent load balancing (<5% variance) and sustained up to 30% higher average bitrate utilization under fluctuating bandwidth conditions. The system supports concurrent client connections and ensures smooth playback by combining intelligent bitrate adaptation with efficient TCP data forwarding and throughput estimation.
      
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
    url: http://ec2-54-152-252-86.compute-1.amazonaws.com/accounts/login/
    date: '2024-03-01'
    awarder: January 2024
    icon: 
    summary: |
     The project is an online social media platform that simulates Instagram, complete with user profiles and interactive posts enhanced by UI effects. The platform includes core features such as user authentication (login and logout), the ability to create and interact with posts, comment on them, like posts, and follow other users.
     For the backend, I employed SQL to manage the database, efficiently storing and retrieving user data, posts, and relationships between users. To enable seamless communication between the client and server, REST API in Python was used. On the frontend, I utilized React to build responsive and dynamic user interfaces, while the server-side logic and routing were handled using Flask. This combination of Flask and React created a cohesive, interactive platform where the client-side experience smoothly integrated with server-side functionality.
  - title: 'Database Management: Online Banking System Simulator'
    url: https://github.com/XciciciX/BankManagementSystem.git
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

Hi! I’m an AI developer and full-stack engineer passionate about transforming intelligent systems into real-world products. I am a first year grad student in University of Southern California studying Computer Science. I recently graduated with dual B.S.E. degrees in Data Science Engineering from the University of Michigan and Electrical & Computer Engineering from Shanghai Jiao Tong University, and I’m currently seeking 2026 summer intern opportunities.

Over four internships at companies and startups including AMD, Ping An Technology, Artisk.ai, and GetStitch.ai, I’ve built and deployed production-level applications spanning AI developer tools, generative design, computer vision, education platforms, and distributed systems. I love working across the stack—from building deep learning inference pipelines to designing intuitive web interfaces and scalable backend services.

My technical toolkit includes Python, C++, JavaScript, Go, React, Flask, FastAPI, Redis, Docker, PyTorch, ONNX, MongoDB, MySQL, Neo4j, and cloud platforms like AWS and GCP.
