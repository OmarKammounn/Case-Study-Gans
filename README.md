# Gans Data Engineering Project

## Overview
Welcome to the Gans Data Engineering Project, which was completed during a Data Science bootcamp. In this project, the challenge of building an automated data pipeline for Gans, a startup specializing in e-scooter-sharing systems, was tackled. The project aimed to create a robust and scalable solution to collect, transform, and store various critical data sources for optimizing e-scooter operations.

## Project Phases
The project unfolded in several key phases, each focused on specific aspects of the data pipeline:

### Part 1: Data Collection
During this phase, essential data that would fuel Gans' decision-making process was gathered using web scraping and APIs. Demographical information about cities, weather forecasts, and flight arrival data for tourists were extracted.

### Part 2: Data Storage and Transformation
This phase involved the creation of a MySQL database with a well-defined relational schema to store the collected data. The Python's SQLAlchemy library was used to connect Python with MySQL, enabling seamless data insertion and transformation.

### Part 3: Cloud Deployment
In this final phase, the data pipeline was migrated to the cloud using Amazon Web Services (AWS). An AWS RDS instance was set up using `boto3`, and data collection scripts were deployed as AWS Lambda functions. Additionally, automatic script execution was scheduled using AWS CloudWatch Events.

## Tools and Technologies Used
Throughout the project, various tools and libraries were harnessed, including:
- **Web Scraping**: The `beautifulsoup` library was utilized to extract data from websites.
- **APIs**: The `requests` library was employed to interact with APIs and retrieve data.
- **MySQL and SQLAlchemy**: The MySQL database was created and managed using SQLAlchemy for data storage and transformation.
- **AWS and `boto3`**: Cloud resources on AWS, including RDS and Lambda, were set up using the `boto3` library for seamless integration.

## Key Skills Acquired
This project provided an opportunity to develop a range of skills:
- Web scraping techniques for extracting structured data from websites.
- Interfacing with APIs to retrieve data from external sources.
- Creating and managing databases, as well as designing relational schemas.
- Utilizing cloud services, such as AWS RDS and Lambda, for efficient data pipeline deployment.
- Scheduling and automating tasks using AWS CloudWatch Events.

## Conclusion
The Gans Data Engineering Project was an immersive learning experience, showcasing the end-to-end process of building an automated data pipeline. By gathering, transforming, and deploying data using a cloud-based infrastructure, the project aimed to support Gans' e-scooter operations through informed decision-making and optimization strategies.
