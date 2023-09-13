---
layout: inner
title: Projects
permalink: /projects/
---

### My Projects

All of my projects contain a good amount of system design :). Some are monoliths, microservices while once is an autonomous agent in a multiprocessing environment with a good amount of IPC. These are the domains from AI/General which these systems are created for and utilise a few algorithms from them.

- [Blockchain](#1-indexooor)
- [Computer Vision](#2-autonomous-car-bosch-future-mobility-challenge-2022)
- [Reinforcement Learning](#6-autonomous-greenhouse-control)
- [NLP/Timeseries](#8-qupid)
- [Data](#12-smart-sampling-synthesiser)
- [Software Development](#14-everecon)

> Blockchain

#### 1. Indexooor

**_"Low level smart contract indexing solution"_**

Indexooor Stack is an open-source project for indexing and querying smart contract data. It has a unique database schema that allows for fetching full arrays and mappings from smart contracts, without the need for smart contracts to emit events. The stack is composed of several submodules, each serving a specific purpose: Core, Queriooor, Goooi-queriooor, Simulatooor, and Op-geth.
*Brownie Points: Our repo has 28 stars on github! :)*

- [Working Video](https://ethglobal.com/showcase/indexooor-2j0f9)
- [Code](https://github.com/indexooor/indexooor-stack)

> _Computer Vision_

<!-- <br> -->

#### 2. Autonomous Car: Bosch Future Mobility Challenge 2022

**_"1/10th scale level 2.5 autonomous car"_**

Developed an autonomous driving car capable of navigating in a miniature smart city, performing manoeuvres such as lane-keeping, following traffic signs and traffic lights, intersection navigation, overtaking, and parking. Secured 11th rank globally among 52 teams in Bosch Future Mobility Challenge held in Romania. Created a zmq-based IPC for multiprocessing python environment for real-time processing for an autonomous driving scenario. Integrated Openvino with RaspberryPI and trained yolov5 for sign and object detection. Engineered a creative replacement of state machines to model behaviours using a custom algorithm based on a ‘priority-queue’ like data structure

- [Kaggle Gist by @arpitvaghela](https://www.kaggle.com/code/arpitvaghela9210/sign-detection-for-bosch-future-mobility-challenge/notebook)
- [Report](https://drive.google.com/file/d/11QEVMVKBsas6qBmj7B8ELXAtcT--a-Yj/view?usp=sharing)

#### 3. AutoNet

**_"Neural architecture search for CNN, SaaS."_**

Conceptualized and implemented a microservices-based architecture to search and train a CNN model for uploaded images using the “DARTS: Differential Architecture Search” algorithm to search for a CNN model. Developed various components of the architecture performing intercommunication using Kafka.

- [Code](https://github.com/arpitvaghela/autoNet)
- [Video Demo](https://youtu.be/icMs8bZsRao)

#### 4. Stereo Depth Estimation

**_"Estimate depth from stereo images"_**

Evaluated the effectiveness of multiple stereo depth estimation algorithms on an unstructured stereo vision for autonomous driving on data collected from the real-world(Apolloscape) and Carla.

- [Report](https://drive.google.com/file/d/11QEVMVKBsas6qBmj7B8ELXAtcT--a-Yj/view?usp=sharing)

#### 5. Distributed City Surveillance

**_"Detect guns and knives in public places"_**

Created a location sourcing platform for security bodies, used for sourcing unsafe locations by collecting data from a mobile app and an AI application that detect guns and knives.

- [Code](https://github.com/Kaushal1011/DistributedCitySureveillanceSystem)
- [Video Demo](https://youtu.be/-DlXvhqaOBI)

> _Reinforcement Learning_

<!-- <br> -->

#### 6. Autonomous Greenhouse Control

**_"Control greenhouse parameter using RL."_**

Created an autonomous control system based on reinforcement learning for controlling greenhouses as a web application deployed on AWS. Used multiple technologies such as Tensorflow, AWS, FastAPI, Dash Python, and Tableau. Contributed by building the RL model, backend API, and cloud architecture for the project on AWS. Published in [“Deep Reinforcement Learning for Agriculture: Principles and Use Cases”](https://link.springer.com/chapter/10.1007/978-981-16-5847-1_4).

- [Code](https://github.com/Kaushal1011/AutonomousGreenhouseControl)
- [Presentation](https://github.com/Kaushal1011/AutonomousGreenhouseControl/blob/main/AOBD_AutonomousGreenhouseControl.pdf)

#### 7. Congestion Control in Networks

Smart congestion control algorithm using reinforcement learning.

- [Presentation](https://docs.google.com/presentation/d/11PuQr1LnJ-OR_AUouXZ6jvsSiNYVokR17L47SHlfkpQ/edit?usp=sharing)

> _NLP/Time Series_

<!-- <br> -->

#### 8. Qupid

**_"Build teams made for each other with the power of AI"_**

Developed a novel team-making algorithm based on the cosine similarity of profile descriptions using a language model trained on data scraped from Twitter.

- [Code](https://github.com/Kaushal1011/Qupid)
- [Video Demo](https://youtu.be/Y8q1dmxS2MY)

#### 9. Fweelts

Detect sentiments from twitter data. Normal, Financial & Emotional.

- [Code](https://github.com/Kaushal1011/Fweelts)
- [Video Demo](https://youtu.be/eIp2K6CeRc0)

#### 10. Stock Price from Fundmentals Prediction

Predict if a stock will go up in the next 3 months based on fundamentals

- [Code](https://github.com/Kaushal1011/CSE523-Machine-Learning-Quantcats)

#### 11. Pollumeter

Detect future AQI by analysing time series data.

- [Code](https://github.com/Kaushal1011/pollumeter)

> _Data_

<!-- <br> -->

#### 12. Smart Sampling Synthesiser

Use FFT like algo based on LinReg to replicate audio as synth

- [Code](https://github.com/Kaushal1011/S3_Smart_Sampling_Synthesiser)

> _Software Development_

<!-- <br> -->

#### 13. Help More

A crowd sourcing platform that sources community service by rewarding people for their service. Uses blockchain lending pool.

- [Code](https://github.com/Kaushal1011/help-more)

#### 14. Everecon

A platform for community management and event listing. Project for software development, Extreme Programming and Kaban.

- [Code](https://github.com/arpitvaghela/EveRecon-api)
