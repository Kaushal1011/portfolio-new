---
layout: inner
title: Projects
permalink: /projects/
---

### My Projects

#### Systems Projects

- **Indexooor**  
  _Low-level smart contract indexing solution_  
  Indexooor Stack is an open-source project for indexing and querying smart contract data. It has a unique database schema that allows for fetching full arrays and mappings from smart contracts, without the need for smart contracts to emit events. The stack is composed of several submodules, each serving a specific purpose: Core, Queriooor, Goooi-queriooor, Simulatooor, and Op-geth.
    *Brownie Points: Our repo has 40 stars on github! :)*  
  - [Code](https://github.com/indexooor/indexooor-stack)  
  - [Video Demo](https://ethglobal.com/showcase/indexooor-2j0f9)

- **Autonomous Car: Bosch Future Mobility Challenge 2022**  
  _1/10th scale level 2.5 autonomous car_  
  Developed an autonomous driving car capable of navigating in a miniature smart city, performing manoeuvres such as lane-keeping, following traffic signs and traffic lights, intersection navigation, overtaking, and parking. Secured 11th rank globally among 52 teams in Bosch Future Mobility Challenge held in Romania. Created a zmq-based IPC for multiprocessing python environment for real-time processing for an autonomous driving scenario. Integrated Openvino with RaspberryPI and trained yolov5 for sign and object detection. Engineered a creative replacement of state machines to model behaviours using a custom algorithm based on a ‘priority-queue’ like data structure  
  - [Report](https://drive.google.com/file/d/11QEVMVKBsas6qBmj7B8ELXAtcT--a-Yj/view?usp=sharing)  
  - [Sign Detection Notebook](https://www.kaggle.com/code/arpitvaghela9210/sign-detection-for-bosch-future-mobility-challenge/notebook)

- **Graph Simulation on Cloud**  
  This project includes three sub-projects, leveraging Scala, Spark, and Hadoop for graph traceability and vulnerability detection. All deployments are on AWS using EC2, Lambda, S3, and EMR:  
  - **Graph Traceability Analysis**: Developed a solution to detect perturbations in graphs using Scala and Hadoop MapReduce, deployed on AWS EMR. Applied this solution to track potential Man-in-the-Middle (MitM) attacks in networks.  
    - [Code](https://github.com/Kaushal1011/CS441SimRankForGraphs)  
    - [Video Demo](https://youtu.be/jWgNTsbx1Gk?si=LGEht6hKE4dFVuQ1)
  - **MitM Attack Simulator**: Designed a Scala-based simulator to model network vulnerabilities. The simulator uses GraphX (Pregel API) to test various attack scenarios and assess network security.
    - [Code](https://github.com/Kaushal1011/CS441ManInMiddleAttackSimulator)  
    - [Video Demo](https://youtu.be/GUwFFERfLxg?si=QNfRHakConve8d-z)  
  - **Distributed Catch Me Game**: Created an interactive game using Akka-HTTP, hosted on AWS. The game leverages graph theory and distributed systems concepts to simulate adversarial scenarios.  
    - [Code](https://github.com/Kaushal1011/CS441GraphCatchMeRest)  
    - [Video Demo](https://youtu.be/cBSIG3KCM2U)

- **Encrypted Integrity-Preserving Filesystem**  
  _FUSE-based encrypted filesystem with Merkle Tree verification_  
  Designed a FUSE-based filesystem with AES-GCM encryption and Merkle Tree verification to maintain data integrity. The system also features dynamic cloud storage backup using Google Drive API, ensuring scalability and ease of use.  
  - [Code](https://github.com/Kaushal1011/encryptedFS-WMerkelProofs)

- **Distributed City Surveillance**  
  _Detect guns and knives in public places_  
  Created a surveillance platform using AI for weapon detection in public spaces. The system collects location data via a mobile app and applies AI models for real-time detection of dangerous objects such as guns and knives.  
  - [Code](https://github.com/Kaushal1011/DistributedCitySureveillanceSystem)  
  - [Video Demo](https://youtu.be/-DlXvhqaOBI)

---

#### AI Projects

- **AutoNet**
  _"Neural architecture search for CNN, SaaS."_
  Conceptualized and implemented a microservices-based architecture to search and train a CNN model for uploaded images using the “DARTS: Differential Architecture Search” algorithm to search for a CNN model. Developed various components of the architecture performing intercommunication using Kafka.
  - [Code](https://github.com/arpitvaghela/autoNet)
  - [Video Demo](https://youtu.be/icMs8bZsRao)

- **Autonomous Greenhouse Control**  
  _Control greenhouse parameters using reinforcement learning_  
  Created an autonomous control system based on reinforcement learning for controlling greenhouses as a web application deployed on AWS. Used multiple technologies such as Tensorflow, AWS, FastAPI, Dash Python, and Tableau. Contributed by building the RL model, backend API, and cloud architecture for the project on AWS. Published in [“Deep Reinforcement Learning for Agriculture: Principles and Use Cases”](https://link.springer.com/chapter/10.1007/978-981-16-5847-1_4).  
  - [Code](https://github.com/Kaushal1011/AutonomousGreenhouseControl)  
  - [Presentation](https://github.com/Kaushal1011/AutonomousGreenhouseControl/blob/main/AOBD_AutonomousGreenhouseControl.pdf)

- **Stereo Depth Estimation**  
  _Estimate depth from stereo images for autonomous driving_  
  Evaluated the performance of multiple stereo depth estimation algorithms on unstructured stereo vision data. This project utilized both real-world data from ApolloScape and simulated data from CARLA.  
  - [Report](https://drive.google.com/file/d/11QEVMVKBsas6qBmj7B8ELXAtcT--a-Yj/view?usp=sharing)
  - [IEEE Publication](https://ieeexplore.ieee.org/abstract/document/10421800)

- **Fweelts**  
  _Sentiment analysis from Twitter data_  
  Developed a sentiment analysis tool that processes and categorizes Twitter data into normal, financial, and emotional sentiment types. The tool applies NLP techniques to extract valuable insights from social media data.  
  - [Code](https://github.com/Kaushal1011/Fweelts)  
  - [Video Demo](https://youtu.be/eIp2K6CeRc0)

- **Qupid**  
  _AI-powered team builder_  
  Built a novel team-building algorithm that matches individuals based on the cosine similarity of their profile descriptions. The algorithm uses a language model trained on data scraped from Twitter.  
  - [Code](https://github.com/Kaushal1011/Qupid)  
  - [Video Demo](https://youtu.be/Y8q1dmxS2MY)

- **Congestion Control in Networks**  
  _Smart congestion control algorithm using reinforcement learning_  
  Created an RL-based solution for optimizing network traffic and managing congestion in real-time environments.  
  - [Presentation](https://docs.google.com/presentation/d/11PuQr1LnJ-OR_AUouXZ6jvsSiNYVokR17L47SHlfkpQ/edit?usp=sharing)

- **Pollumeter**  
  _Predict future AQI using time series data_  
  Built a model to analyze and predict future Air Quality Index (AQI) based on historical time series data.  
  - [Code](https://github.com/Kaushal1011/pollumeter)

---

