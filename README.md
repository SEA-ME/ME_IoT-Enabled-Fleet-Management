# ME Project - IoT-Enabled Fleet Management
## Optimizing Logistics with IoT-Enabled Fleet Management using CARLA Telemetry  
</br>


# Index
#### [Introduction](#introduction-1)
#### [Background Information](#background-information-1)
#### [Project Goals & Objectives](#project-goals--objectives-1)
#### [Technical Requirements](#technical-requirements-1)
#### [System Architecture](#system-architecture-1)
#### [Software Design](#software-design-1)
#### [Implementation](#implementation-1)
#### [Project Timeline](#project-timeline-1)
#### [Collaboration and Teamwork](#collaboration-and-teamwork-1)
#### [Mentorship and Support](#mentorship-and-support-1)
#### [Reflection and Self-Assessment](#reflection-and-self-assessment-1)
#### [Submission](#submission-1)
#### [References](#references-1)
</br>


# Introduction

In the rapidly evolving world of logistics and supply chain management, new technologies are emerging that have the potential to revolutionize the way goods are transported and delivered. One such technology is IoT-enabled fleet management, which involves using connected devices and real-time data to optimize vehicle routes, reduce fuel consumption, and improve delivery times.

CARLA is a powerful simulation platform that provides a realistic environment for testing and developing autonomous vehicles. In this peer-to-peer educational project, participants will use telemetry data generated from CARLA simulations to explore the potential of IoT-enabled fleet management for improving logistics and efficiency.

The project will involve designing and implementing algorithms for IoT-enabled fleet management and evaluating their performance using the telemetry data. Participants will have the opportunity to work on real-world problems and gain hands-on experience with data analysis, simulation, and fleet management.

Through this project, participants will gain a deeper understanding of the benefits of IoT-enabled fleet management and the challenges and opportunities of implementing these technologies in the logistics and supply chain industries. They will also develop valuable skills in data analysis and simulation, making them well-prepared for careers in these exciting and rapidly evolving fields.

This project is designed for participants with a background in computer science, engineering, or a related field. However, it is also open to anyone with a strong interest in IoT and autonomous technology and a desire to learn about their potential for improving logistics and supply chain management.  
</br>


# Background Information

The logistics and supply chain industry has a long history, with evidence of organized transportation and delivery systems dating back thousands of years. However, it wasn't until the 20th century, with the development of the automobile and the growth of global trade, that the industry took on its modern form.

In recent decades, the logistics and supply chain industry has faced numerous challenges in delivering goods efficiently and effectively. The increasing demand for faster delivery times, improved customer service, and reduced costs has led to a need for new and innovative solutions. One such solution is IoT-enabled fleet management, which involves using connected devices and real-time data to optimize vehicle routes, reduce fuel consumption, and improve delivery times.

The concept of IoT-enabled fleet management can be traced back to the late 20th century, with the development of GPS technology and the advent of wireless communication. However, it was only in recent years, with the growth of the Internet of Things (IoT) and the increasing affordability of connected devices, that IoT-enabled fleet management has become a reality.

CARLA is a powerful and flexible open-source simulation platform for autonomous vehicles that provides a realistic environment for testing and development. It was developed by the Computer Vision Center in Spain and was released in 2017, becoming one of the most popular simulation platforms for autonomous vehicle research and development.

Telemetry data generated from CARLA simulations can provide valuable insights into the performance of IoT-enabled fleet management algorithms and the impact of various scenarios on logistics and efficiency. By using this data, participants in this project will have the opportunity to work on real-world problems and gain hands-on experience with data analysis, simulation, and fleet management.

Through this project, participants will learn about the benefits of IoT-enabled fleet management, the challenges and opportunities of implementing these technologies, and the role of autonomous vehicles in logistics and supply chain management. They will also develop valuable skills in data analysis and simulation, making them well-prepared for careers in these exciting and rapidly evolving fields.  
</br>


# Project Goals & Objectives

The goal of this project is to provide participants with a hands-on educational experience in IoT-enabled fleet management, using telemetry data from CARLA simulations. The objectives of the project are as follows:

1. To gain an understanding of the benefits of IoT-enabled fleet management, including improved logistics and efficiency, reduced fuel consumption, and improved delivery times.
2. To learn about the challenges and opportunities of implementing IoT-enabled fleet management technologies in real-world logistics and supply chain operations.
3. To develop skills in data analysis and simulation, including the use of telemetry data from CARLA simulations to evaluate IoT-enabled fleet management algorithms.
4. To understand the role of autonomous vehicles in logistics and supply chain management, and the potential impact of these technologies on the industry.
5. To gain practical experience in working with real-world data and simulations, and in developing and implementing algorithms for IoT-enabled fleet management.

By the end of the project, participants will have a deep understanding of the potential of IoT-enabled fleet management, and will be well-prepared for careers in these exciting and rapidly evolving fields. Whether they choose to pursue careers in industry, research, or academia, they will have the skills and knowledge needed to make a meaningful contribution to the development of this exciting field.  
</br>


# Technical Requirements

To participate in this project, participants will need the following technical requirements:

1. A computer with a recent version of Windows, macOS, or Linux, and at least 8 GB of RAM and a recent multi-core processor.
2. Access to the CARLA simulator, which can be downloaded for free from the CARLA website.
3. A programming environment for data analysis, such as Python, R, or MATLAB. Participants should have a basic understanding of programming, including the use of variables, loops, and functions.
4. A software development environment, such as Visual Studio Code, Eclipse, or PyCharm. Participants should have basic knowledge of software development, including the use of version control tools like Git and the ability to write and debug code.
5. A basic understanding of IoT technologies and protocols, including MQTT and REST.
6. Access to a data storage solution, such as a cloud-based data storage service or a local file system, to store and analyze the telemetry data generated from CARLA simulations.
7. An understanding of the basics of statistics and data analysis, including descriptive statistics, data visualization, and regression analysis.

While these technical requirements may seem daunting, participants will have access to detailed tutorials and resources to help them get up and running with the necessary tools and technologies. Additionally, participants will have the opportunity to work with a supportive community of peers and mentors, who can provide guidance and support throughout the project.  
</br>


# System Architecture

The system architecture for this project will include the following components:

1. The CARLA simulator, which will provide the telemetry data used for this project. The simulator will be used to generate real-world scenarios for the fleet of vehicles being managed.
2. The Raspberry Pi Racer (PiRacer), which will act as the "vehicle" in the simulation. The PiRacer will be outfitted with sensors, such as GPS and accelerometers, to generate the telemetry data used in the simulations.
3. A cloud-based data storage solution, such as Amazon Web Services (AWS) or Microsoft Azure, to store the telemetry data generated by the CARLA simulator and the PiRacer.
4. A software application, written in Python or a similar programming language, that will run on the PiRacer and collect the telemetry data from the sensors. This data will be transmitted to the cloud-based data storage solution, where it will be analyzed and processed.
5. A data analysis and visualization tool, such as Python's Pandas library or MATLAB, that will be used to analyze and visualize the telemetry data stored in the cloud.
6. A fleet management algorithm, written in Python or a similar programming language, that will use the telemetry data to make decisions about the fleet of vehicles being managed. This algorithm will be developed and tested by participants in the project.
7. A dashboard or user interface, that will allow participants to monitor and control the fleet management algorithm in real-time, and to view and analyze the telemetry data generated by the CARLA simulator and PiRacer.

Overall, this system architecture provides a flexible and scalable platform for participants to gain hands-on experience in IoT-enabled fleet management. By using the PiRacer and CARLA simulator, participants will have access to realistic and diverse data sets that will help them develop and test their fleet management algorithms in a controlled environment.  
</br>


# Software Design

The software design for this project will consist of several components, including:

1. The PiRacer software application, which will collect telemetry data from the sensors on the PiRacer and transmit the data to the cloud-based data storage solution. The software application will be written in Python and will use the MQTT protocol to transmit the telemetry data.
2. The data analysis and visualization tool, which will be used to analyze and visualize the telemetry data stored in the cloud. The tool will be written in Python or MATLAB and will use libraries such as Pandas, Matplotlib, or Plotly to visualize the data.
3. The fleet management algorithm, which will use the telemetry data to make decisions about the fleet of vehicles being managed. The algorithm will be written in Python or a similar programming language and will use machine learning or optimization techniques to make decisions about the fleet.
4. The dashboard or user interface, which will allow participants to monitor and control the fleet management algorithm in real-time, and to view and analyze the telemetry data generated by the CARLA simulator and PiRacer. The dashboard will be written in HTML, CSS, and JavaScript and will use a front-end framework such as React or Angular to build the user interface.

The software design for this project will follow industry-standard software development practices, including the use of version control tools, testing frameworks, and documentation tools. Participants will be encouraged to develop and maintain high-quality code, to write comprehensive test cases, and to document their code and algorithms.

Overall, this software design provides a flexible and scalable platform for participants to gain hands-on experience in IoT-enabled fleet management. The use of Python, MQTT, and cloud-based data storage provides a robust and efficient platform for participants to develop and test their fleet management algorithms.  
</br>


# Implementation

The implementation of this project will follow the following steps:

1. Set up the CARLA simulator and generate a scenario for the fleet of vehicles being managed.
2. Set up the PiRacer and equip it with sensors to generate telemetry data.
3. Set up the cloud-based data storage solution and configure it to receive the telemetry data from the PiRacer.
4. Develop and test the PiRacer software application, which will collect the telemetry data from the sensors and transmit the data to the cloud-based data storage solution.
5. Develop and test the data analysis and visualization tool, which will be used to analyze and visualize the telemetry data stored in the cloud.
6. Develop and test the fleet management algorithm, which will use the telemetry data to make decisions about the fleet of vehicles being managed.
7. Develop and test the dashboard or user interface, which will allow participants to monitor and control the fleet management algorithm in real-time, and to view and analyze the telemetry data generated by the CARLA simulator and PiRacer.

Throughout the implementation process, participants will be encouraged to use agile development methodologies, such as Scrum or Kanban, to manage their work and to collaborate with other participants. Participants will also be encouraged to use version control tools, such as Git, to manage their code and to collaborate with others.

At the end of the implementation process, participants will be encouraged to present their results and to share their findings with the rest of the group. Participants will also be encouraged to share their code and algorithms, to help others learn and build upon their work.

Overall, the implementation of this project will provide participants with hands-on experience in IoT-enabled fleet management, and will give them the opportunity to develop and test their algorithms in a realistic and controlled environment. The use of agile development methodologies, version control tools, and collaboration tools will ensure that participants have a positive and productive experience, and will help them to build their skills and knowledge in the field of IoT-enabled fleet management.  
</br>


# Project Timeline

* Week 1:
    * Introduction to the project and its goals and objectives.
    * Introduction to the CARLA simulator and the PiRacer.
    * Setting up the CARLA simulator and generating a scenario for the fleet of vehicles being managed.
* Week 2-3:
    * Setting up the PiRacer and equipping it with sensors.
    * Setting up the cloud-based data storage solution.
    * Development of the PiRacer software application, which will collect the telemetry data from the sensors and transmit the data to the cloud.
* Week 4-5:
    * Development of the data analysis and visualization tool.
    * Analysis and visualization of the telemetry data generated by the CARLA simulator and PiRacer.
* Week 6-7:
    * Development of the fleet management algorithm.
    * Testing and refinement of the fleet management algorithm.
* Week 8-9:
    * Development of the dashboard or user interface.
    * Integration of the PiRacer software application, data analysis and visualization tool, fleet management algorithm, and dashboard or user interface.
* Week 10:
    * Final testing and refinement of the system.
    * Presentation of results and sharing of findings with the rest of the group.

This timeline is meant to be flexible and can be adjusted based on the needs and progress of the participants. Participants will be encouraged to work at their own pace, and to collaborate with others to achieve the project goals and objectives. The use of agile development methodologies, version control tools, and collaboration tools will ensure that participants have a positive and productive experience, and will help them to build their skills and knowledge in the field of IoT-enabled fleet management.  
</br>


# Collaboration and Teamwork

Students will be working in teams of maximum six to complete this project. Each team member will be assigned specific tasks and responsibilities, and will be expected to contribute to the overall success of the project. Teams will be required to submit regular progress reports and to meet with the instructor for check-ins and feedback.  
</br>


# Mentorship and Support

Students will be provided with mentorship and support from the instructor throughout the project. The instructor will be available for questions and guidance, and will hold regular check-ins and progress reports to provide feedback and support.  
</br>


# Reflection and Self-Assessment

Students will be encouraged to reflect on their own learning and progress throughout the project. This will be done through self-assessment exercises and through feedback from the instructor and other team members.  
</br>


# Submission

At the end of the project, students will be required to submit the following items on Github:

1. Source code for the PiRacer software application.
2. Source code for the data analysis and visualization tool.
3. Source code for the fleet management algorithm.
4. Source code for the dashboard or user interface.
5. Detailed documentation of the code, including inline comments and technical reports.
6. Project presentation slides or video.
7. Final report summarizing the results of the project, including an analysis of the telemetry data, a description of the fleet management algorithm, and a discussion of the challenges and lessons learned during the implementation process.

The code and documentation should be well organized and well commented, to ensure that other participants can understand the logic and implementation of the code. The presentation and final report should be clear and concise, and should highlight the key findings and contributions of the project.

Overall, the code and documentation submitted on Github will serve as a record of the students' work and progress, and will help others to build upon their work and to learn from their experience.  
</br>


# References

Here are some open source references for an IoT-enabled fleet management system:

1. Node-RED: Node-RED is a flow-based development tool that makes it easy to develop and debug IoT applications. It can be used to collect and process data from various sources, including telemetry data from vehicles, and to transmit the data to a cloud-based data storage solution. (https://nodered.org)
2. InfluxDB: InfluxDB is a time series database that can be used to store and analyze telemetry data from vehicles. It is designed to handle high write and query loads, making it ideal for use in IoT applications. (https://www.influxdata.com/products/influxdb-overview)
3. Grafana: Grafana is an open source dashboard and visualization platform that can be used to visualize the telemetry data stored in InfluxDB. It provides a wide range of visualization options and can be easily customized to meet the specific needs of the fleet management system. (https://grafana.com)
4. Raspberry Pi: The Raspberry Pi is a low-cost, single-board computer that can be used to host the PiRacer software application. It has a range of connectivity options, including Wi-Fi and Ethernet, making it easy to integrate with other components of the fleet management system. (https://www.raspberrypi.org)
5. MQTT: MQTT is a publish-subscribe messaging protocol that can be used to transmit data between the PiRacer and the cloud-based data storage solution. It is designed to be lightweight and efficient, making it ideal for use in IoT applications. (https://mqtt.org)

These open source tools can be combined to create a complete IoT-enabled fleet management system that can collect, process, and visualize telemetry data from vehicles. The use of open source tools makes it easy to customize and extend the system, and helps to reduce costs and improve efficiency.