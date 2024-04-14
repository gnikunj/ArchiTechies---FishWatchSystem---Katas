
# ArchiTechies-FishWatchSystem-Katas
<img width="328" alt="lo" src="https://github.com/gnikunj/ArchiTechies---FishWatchSystem---Katas/assets/16604629/a7f8ce3a-694e-46b9-8925-f69c06dbcfa1">

Architectural Design Solution for Intelligent Fish Watch System for Architectural Katas

# Introduction
This README provides an overview of the Intelligent AIoT based Fish Watch system, mentioning it's requirement, team details, solutioning approach, constraints and architectural decisions.

# Team Members
 - Nikunj Goel - Architect
 - Piyush Agarwal - Architect
 - Lukesh Garg - Architect

## Problem Statement
1. Farmers need to be able to see the collected information in dashboards which they can customize.
2. They also need to be able to specify thresholds at which alerts should be triggered this could be simple things like a PH going out of bound, but could also involve advanced warnings of adverse weather events which are expected.
3. Farmers track information about the fish harvested from each farm, and this information together with the raw data being collected should be used to build a model of what factors produce good harvests.
4. Each farm may have a variety of different fish specie. For large customers, they will want to be able to drive insights across several farms.
5. It’s vital that alerts be generated in a timely manner - a sharp degradation in water quality or adverse weather event could have massive implications if the farmer doesn’t have enough warning.
6. It’s assumed that more detailed information about fish behavior and water quality etc. will become richer over time as we are able to deploy more powerful device.
7. Fish Watch needs to be accessible from several devices, including rugged industrial devices used on the sea during harvest.
8. Fish farms are often in remote locations, where cellular signal may be poor, but You can assume that the hardware devices to capture water information and detect fish behavior already exist, but you need to define how these devices will send the information to the system.
9. Livestock Insights Inc is considering providing similar capabilities to cattle, and allowing aquariums to use the system to look after fish health.

## Solution Overview
Fish Watch encapsulates IOT devices, communication tools, and software that collaborate autonomously. It represents the amalgamation of the physical world with the digital realm, facilitating efficient monitoring the health condition of water & fish in Fish Farms. Fish watch helps to predicts the best ways to harvest & help to improve revenue to fish farmers with help of AI & ML techniques.

**Physical Representation:**
1. Utilizes a network of sensor devices strategically distributed across Fish Farms.
2. Sensors collect and transmit real-time data, forming the foundation of the real environment within the solution.

**Virtual Environment Integration:**
1. Integrates sensors capable of real-time data collection and transmission for Fish farms.
2. Data is processed using machine learning models and deep learning techniques, creating a virtual environment capable of remote farm monitoring.

**AIoT Based Framework:**
1. Monitors fish behavior, fish health, possible parasites, estimates growth, and assesses the aquaculture environment's water quality.
2. Incorporates low-cost hardware devices and best in class software tools for visualization and big data analytics.
3. Solution provides the predictive analysis to user about good harvest based on environmental & other factors.
4. Allows user to set the various parameters & thresholds to receive notification & alerts for any emergency to avoid any loss.

**Fish Watch Core Services:**
1. Data Collection Service: Collects data from sensors and cameras.
2. Cloud Computing Service: Processes data for storage over the cloud, predictive analysis and alters sending to user for better decision making.
3. Analytical Service: Provides customized data visualization through dashboards, web, and mobile applications.
   ![Solution Architecture Diagram](https://github.com/gnikunj/ArchiTechies---FishWatchSystem---Katas/assets/16604629/91f5e6aa-4770-4801-9c26-9e4a37802b3b)

# Repository Contents
1. Fish Watch - Detailed Solution Design Document [Link](https://github.com/gnikunj/ArchiTechies---FishWatchSystem---Katas/blob/main/ArchiTechies%20-%20Fish%20Watch%20Solution%20Design%20Document.pdf), it includes :
    - Requirements, Constraints & Assumption
    - Detailed Solution Overview
    - Solution Archutecture diagram
    - Sequence Diagram
    - System Diagram
    - Context Diagram
    - Component Diagram
    - Data Platform Diagram
    - Services Details
    - Architecture Decision points
    - Summarization & future plans

2. Architecture Decision Records - While designing the solution, various architectural points are found, please find details for them in following documents
    - ADR - AWS AI Model Deployment [Link](https://github.com/gnikunj/ArchiTechies---FishWatchSystem---Katas/blob/main/ADR/ADR%20-%20AWS%20AI%20Model%20Deployment.pdf)
    - ADR - Archiving Local Data Storage [Link](https://github.com/gnikunj/ArchiTechies---FishWatchSystem---Katas/blob/main/ADR/ADR%20-%20Archiving%20Local%20Data%20Storage.pdf)
    - ADR - Choice of AWS Cloud Provider [Link](https://github.com/gnikunj/ArchiTechies---FishWatchSystem---Katas/blob/main/ADR/ADR%20-%20Choice%20of%20AWS%20Cloud%20Provider.pdf)
    - ADR - LLM Wrapper [Link](https://github.com/gnikunj/ArchiTechies---FishWatchSystem---Katas/blob/main/ADR/ADR%20-%20LLM%20Wrapper.pdf)
    - ADR - LoRa Network & MQTT Protocol [Link](https://github.com/gnikunj/ArchiTechies---FishWatchSystem---Katas/blob/main/ADR/ADR%20-%20LoRa%20Network%20%26%20MQTT%20%20Protocol.pdf)
    - ADR - Microservice Architecture Framework [Link](https://github.com/gnikunj/ArchiTechies---FishWatchSystem---Katas/blob/main/ADR/ADR%20-%20Microservice%20Architecture%20Framework.pdf)
    - ADR - Multitenancy & Subscription based SaaS model [Link](https://github.com/gnikunj/ArchiTechies---FishWatchSystem---Katas/blob/main/ADR/ADR%20-%20Multitenancy%20%26%20Subscription%20based%20SaaS%20model.pdf)
    - ADR - Regional Local Data Storage [Link](https://github.com/gnikunj/ArchiTechies---FishWatchSystem---Katas/blob/main/ADR/ADR%20-%20Regional%20Local%20Data%20Storage.pdf)
    - ADR - Role-Based Access Control [Link](https://github.com/gnikunj/ArchiTechies---FishWatchSystem---Katas/blob/main/ADR/ADR%20-%20Role-Based%20Access%20Control.pdf)


# ArchiTechies-FishWatchSystem-Kata - Video Solution Link
[![ArchiTechies FishWatchSystem Video](http://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=VIDEO_ID "ArchiTechies FishWatchSystem Video")

Watch online here :
<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="
https://player.vimeo.com/video/934456612?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479"
frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="ArchiTechies_SopraSteria_Oreilly"></iframe></div><script src="https://player.vimeo.com/api/player.js">
 
</script>

