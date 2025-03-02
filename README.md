# EneRIC - Connecting People

## Introduction
EneRIC is an **innovative solution** designed to address connectivity challenges in developing regions. It focuses on the complexities of deploying 5G networks in rural areas, where infrastructure and operational costs are extremely high. Through **network virtualization and artificial intelligence**, EneRIC enables a more accessible and sustainable implementation.

---

## PRESENTATION 

Presentation: https://youtu.be/MoCf6IZouzw

---

## DEMO 

Demo YT: https://youtu.be/S1zDiraVovY

---

## Table of Contents
1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Problem and Solution](#problem-and-solution)  
4. [How It Works](#how-it-works)  
5. [Benefits](#benefits)  
6. [Installation Guide](#installation-guide)  
7. [Contact](#contact)

---

## Features
- **Cost Reduction**: Decreases both initial investment (CapEx) and operational expenses (OpEx).  
- **AI Optimization**: Utilizes optimization algorithms to lower energy consumption.  
- **RAN Virtualization**: Implements a **virtualized RAN** to minimize reliance on proprietary hardware.  
- **ORAN Compatibility**: Integrated with **ORAN Alliance** specifications to ensure interoperability.  
- **AI-Driven Energy Manager**: Maximizes energy efficiency to make 5G deployment more sustainable.

---

## Problem and Solution

### Problem
- High infrastructure costs make 5G deployment unfeasible in many underdeveloped countries.  
- Traditional deployment models fail to adapt to the economic realities of these regions.  
- Lack of reliable energy infrastructure to power base stations.

### Solution
- Use of **open-source radio software** to remove dependence on proprietary hardware.  
- **RAN Virtualization** (vCU and vDU) to reduce costs and increase flexibility.  
- **AI-based network controller** for dynamic management of energy and resources.  
- **Integration of renewable energies** to ensure network self-sufficiency.

---

## How It Works
1. **Infrastructure Virtualization**: Replace physical units with virtualized software.  
2. **AI-Driven RAN**: An AI system optimizes network performance and reduces energy consumption.  
3. **Low-Cost Deployment**: Employ mobile nodes and renewable energy to minimize expenses.  
4. **Intelligent Energy Manager**: An AI-driven system for energy optimization.

---

## Benefits
- **Lower Costs**: Up to **65% reduction in OpEx** in optimal scenarios.  
- **Sustainability**: Enhances energy usage with AI and renewable sources.  
- **Greater Accessibility**: Facilitates connectivity expansion in underserved regions.  
- **Scalability**: Can be adapted to different countries and deployment contexts.

---


## Installation Guide

### Prerequisites
- Aimlapi API Key
- Open5gs            
- Oran-sc-ric       
- srsRAN_Project     
- srsRAN_4G          

### Steps
1. Download the VMWARE (Open5GS, gnb) and all the libraries needed from this repository:
   ```bash
   https://drive.google.com/drive/folders/1MwMBT5h5eNWnwrvjOuCB-dtzFCIkHX8m?usp=sharing

2. Install dependencies:
   ```bash
   As we provide you with the fully configured VMware environment, you theoretically won’t need to install anything else. However, for transparency, all libraries used (which are open source) are specified in the requirements.txt file.

    
3. Set up API keys:
   - Navigate to  ' oran-sc-ric/xApps/python/ '
   - Edit the file named 'kpm_mon_xapp.py'
   - Search the CLIENT API KEY and change the API_KEY specified to your own:
     ```bash
      AIML_API_KEY = "your_aiml_api_key"
     
4. PREPARE THE VIRTUAL ENVIRONMENT
   - Once you have both VMWARE deployed and the API_KEY execute this commands.
    ```bash
     1. En la VMWARE de open5gs:
          1. sudo nmcli con up ogstun

     2. En la VMWARE de gnb:
          1. sudo ip netns add ue1

5. EXECUTE THE DEMO
   - Now theoretically the environment it's working fine.
   - Follow the following DEMO to execute all needs to simulate the trafic.
   - DEMO: [https://youtu.be/S1zDiraVovY] 



## Contact
For any questions or feedback, feel free to reach out:

Email: aitormurgui@gmail.com [TELECOS] eloylloveras@gmail.com [IA]

GitHub: https://github.com/eloylloveras

LinkedIn: 

Aitor: https://www.linkedin.com/in/aitor-murgui-gonz%C3%A1lez-a744b1227/

Eloy: https://www.linkedin.com/in/eloylloverasgil/





