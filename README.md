# movie-recommendation-system

## Introduction

The project Movie Recommendation System is a desktop based application designed with Python using Google Collab, PyCharm, ML libraries. The main aim of this project is to develop a robust movie recommendation system model which consists of all the information regarding various movies based on some certain criterias mentioned by the user and thus setting one apart from the other. This helps the user to smoothly surf through related and similar movies  with ease. The application currently consists of three sections, one for searching related movies based on user input , another for rating movies and last one for searching movies based on user mood. In the future we will add other sections to make it more efficient. There is a provision for mood based recommendation. We combined content-based and collaborative filtering techniques to provide personalized recommendations. The system will leverage data from sources like TMDB and IMDb, and employ data preprocessing techniques to ensure data quality. We will prioritize user privacy and security by implementing strong security measures and complying with data privacy regulations. To ensure scalability and performance, we will utilize cloud-based infrastructure, caching, and load balancing. The user interface will be designed to be intuitive and user-friendly, offering features like personalized recommendations, social interactions, and mobile optimization. By carefully considering these factors, we aim to create a system that delivers an exceptional user experience.

## System analysis

System analysis is the process of studying the business processors and procedures, generally referred to as business systems, to see how they can operate and whether improvement is needed. This may involve examining data movement and storage, machines and technology used in the system, programs that control the machines, people providing inputs, doing the processing and receiving the outputs. While having a close inspection of a system we found that the databases of different types of movies,cast, crew, and many more data are required on which various types of operations will be performed.

It helps to quickly recommend accurately and give the user a strong sense of movies which he should watch or should find.

More information related to the movie can be provided to users.

## Problem Identification

The current movie recommendation system is limited by its reliance on a static dataset and a single user input. It lacks the ability to adapt to changing user preferences or incorporate real-time data updates. Additionally, the absence of user data collection prevents personalized recommendations and valuable insights into user behavior. To address these issues, the system requires enhancements such as a rating system, user history tracking, genre preferences, and regular data updates. By leveraging cloud-based infrastructure and implementing automation, the system can achieve scalability, efficiency, and the ability to deliver personalized recommendations based on user preferences and real-time data.

## Investigation phase

The investigation phase is also known as the fact-finding stage or the analysis of the current system. This is a detailed study conducted with the purpose of wanting to fully understand the existing system and to identify the basic information requirements. Various techniques may be used in fact-finding and all facts obtained must be recorded.


 A thorough investigation was done in every affected aspect when determining whether the proposed system is feasible enough to be implemented. As it was essential for us to find out more about the present system, we used the following methods to gather the information. 

1.Observation - Necessary to see the way the system works firsthand. 

2.Document sampling - These are all the documents that are used in the system. They are necessary to check all the data that enters and leaves the system. 

3.Questionnaires - These were conducted to get views of the other employees who are currently employed in the system.

## Analysis of the investigation

1. User-Friendly: The current system, likely manual or based on basic software, doesn't require specialized technical skills to operate. This simplicity reduces the need for extensive training and technical support.

2.Minimal Maintenance: The system has low maintenance costs as it doesn't involve sophisticated software or hardware. Regular updates, bug fixes, and security patches are minimal or non-existent.

## Software Requirement Specification

The Software Requirement Specification (SRS) serves as the foundational document for any software development endeavor. As software systems have grown increasingly intricate, the need for a structured approach to understanding and articulating requirements has become paramount.
The impetus for an SRS arises from the evolving needs of clients. As clients articulate their desires for software solutions, the SRS emerges as the mechanism for translating these ideas into a formal, unambiguous document. This document serves as a shared understanding between clients and developers, guiding the development process and ensuring that the final product aligns with the initial vision.
The SRS phase encompasses two primary activities:
1. Understanding the Problem:   First, we need to clearly understand what problem the software needs to solve.  We'll talk to the client to figure out their specific needs and expectations. We'll identify any constraints, such as budget or time, that might affect the project.
2. Defining the Requirements:  We'll outline the specific features and functions the software should have. We'll describe how the software should behave under different conditions. We'll define any quality, performance, or security standards the software must meet. We'll create a formal document, the SRS, to clearly communicate the requirements to the development team.

## System Requirements

Python: Version 3.6 or later

Jupyter Notebook: For interactive development and experimentation
Google Colab: For cloud-based machine learning and data science tasks
PyCharm: For professional Python development
Required Libraries:
I.	NumPy
II.	Pandas
III.	ast
IV.	nltk
V.	Scikit-learn
VI.	TensorFlow/Keras
VII.	pickle

## Data Requirements

I.	Movie Dataset: A large and diverse dataset containing movie information, user ratings, and other relevant metadata.
II.	Kaggle Account: Access to Kaggle for downloading and managing datasets.
III.	Data Storage: Sufficient storage space to store the dataset and trained models.

## Feasibility Study 

Before doing the project “Recommendation System” , we study and analyze all the existing or required functionalities of the system, the next task is to do the feasibility study for the project. All projects are feasible given unlimited resources and infinite time. Feasibility study includes consideration of all the possible ways to provide a solution to the given problem. The proposed solution should satisfy all the user requirements and should be flexible enough so that future changes can be easily done based on the future upcoming requirements


A.Economic Feasibility

This is a very important aspect to be considered while developing a project. We decided the technology based on the minimum possible cost factor. 
I.	 All hardware and software cost has to be borne by the organization.

II.	 Overall, we have estimated that the benefits the organization is going to receive from the proposed system will surely overcome the initial costs and the later on running cost for the system.

B.Technical Feasibility 

This included the study of function, performance and constraints that may affect the ability to achieve an acceptable system. For this feasibility study, we studied complete functionality to be provided in the system, as described in the system. For this feasibility study, we studied complete functionality to be provided in the system, as described in the System Requirement Specification (SRS) and checked if everything was possible using different types for frontend and backend platforms.

C. Operational Feasibility
 
No doubt the proposed system is fully GUI based that is very user friendly and all inputs to be taken are all self-explanatory even to a layman. Besides, proper training has been conducted to let people know the essence of the system so that they feel comfortable with the new system. As far our study is concerned the clients are comfortable and happy as a system has cut down their loads and doing.
