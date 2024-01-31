# Carbon-Aware Data Center Modelling, Assessment, and Optmization

## Project Information

### Project Description
This project is a joint collaboration between Alibaba Cloud and the University of Hong Kong. The project aims to develop advanced modelling and assessment methods for Alibaba cloud data centers to help optimize the operation and reduce carbon emissions. The collaboration is carried out through the scheme Alibaba Innovative Research (AIR). In this website, some important findings in the form of figures and analysis are presented in the [research output](#research-outcomes) section.


### AIR Project
[AIR](https://university.aliyun.com/activity/air) program is a collaborative platform between Alibaba Cloud and academic institutions to conduct scientific research. Its aim is to explore cutting-edge research in computer science, intelligent science, and related fields, and accelerate the application of research results. 

### Energy Digitalization Lab
[Energy Digitalization Laboratory](http://www.eeyiwang.com/index.html) at The University of Hong Kong (EDL@HKU) focuses on the digitalization of power and energy systems with an emphasis on the distribution and consumer side, including data analytics, data privacy, cyber-physical-social systems, Internet-of-things, etc. The overall goal is to make the distribution systems more adaptive to accommodate the high penetration of renewable energy towards a decarbonized future.

## Research Outcomes
When a workload is submitted to the internet data center (IDC), like a transaction request or a machine learning training request, operators will divide workload into computing tasks/jobs and schedule them to run on IDC servers.

<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
<img src="https://github.com/ryyao-2022/AIR-Project-Carbon-Modelling-Assessment-and-Optimization/blob/main/images/data%20center%20workflow.png" alt="IDC Workflow" style="width:70%; height:70%;">
</div>

Workloads can be classified into two types: online and batch. Online jobs, such as transaction requests, are processed immediately, whereas batch jobs can be scheduled more flexibly as long as they are completed by the deadline. The flexibility of batch jobs is essential for optimizing data centers, as operators can allocate tasks to times and locations with high renewable generation to reduce carbon emissions.

In our project, we aim to develop **carbon aware modelling, assessment, and optimization** methods to reduce carbon emission.

<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
<img src="https://github.com/ryyao-2022/AIR-Project-Carbon-Modelling-Assessment-and-Optimization/blob/main/images/our%20research%20framework.png" alt="Research Framework" style="width:70%; height:70%;">
</div>

The project is divided into three sub-tasks, each concerning one specific aspect of . Firstly, we focus on the short carbon intensity forecasting to Some key findings or methodologies are summarized as below.

### Carbon Intensity Forecasting
Carbon intensity, or grid carbon intensity, measures the carbon emission per energy consumed with unit gCO2/kWh. This statistics is closely related renewable generation and can be used as guideline for low carbon electricity consumption. It is critical to develop accurate short term forecasting methods so that data center operators can optimally place their computing tasks in times and regions with lower carbon intensity.

<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
<img src="https://github.com/ryyao-2022/AIR-Project-Carbon-Modelling-Assessment-and-Optimization/blob/main/images/carbon%20forecasting%20framework.png" alt="Carbon Forecasting Framework" style="width:70%; height:70%;">
</div>

To achieve lower forecasting error, Figure in this project we propose a leveled forecasting framework with feature enigeering method for performance enhancement as shown in the figuire above.

### Data Center Electricity Consumption Flexibility Assessment

The energy-intensive Internet data centers (IDCs) offer a high degree of power consumption flexibility, which has been extensively studied as a potential solution to enhance the flexibility of power systems. In IDCs, computational workloads are often comprised of interdependent tasks. Therefore, to accurately assess the power consumption flexibility of IDCs, it is crucial to consider the interdependency of computational tasks. We propose a framework for deriving a compatible task dependency-aware IDC load model which is easy to embed for demand reponses from current grid as shown in figure below.

<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
<img src="https://github.com/ryyao-2022/AIR-Project-Carbon-Modelling-Assessment-and-Optimization/blob/main/images/flexibility%20assessment%20framework.png" alt="Flexibility Assessment Framework" style="width:70%; height:70%;">
</div>

Our proposed framework derives a more accurate flexibility assessment showcased in the figure below. 

<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
<img src="https://github.com/ryyao-2022/AIR-Project-Carbon-Modelling-Assessment-and-Optimization/blob/main/images/flexibility%20assessment%20result.png" alt="Flexibility Assessment Result" style="width:70%; height:70%;">
</div>

### Data Center Carbon Aware Computing Power Modelling

Computing power refers to the capability of a computer or a computing system to perform calculations, process data, and execute tasks.

FLOPS (Floating Point Operations Per Second) is a common unit used to measure the computing power of a system, specifically in terms of floating-point arithmetic operations. It represents the number of floating-point calculations a computer or processor can perform in one second.