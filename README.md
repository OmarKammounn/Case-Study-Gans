# Gans Data Engineering Project

## Overview
Welcome to the Gans Data Engineering Project, completed during a Data Science bootcamp. In this project, I tackled the challenge of building an automated data pipeline for Gans, a startup specializing in e-scooter-sharing systems. The project aimed to create a robust and scalable solution to collect, transform, and store various data sources critical for optimizing e-scooter operations.

## Project Phases
The project unfolded in several key phases, each focused on specific aspects of the data pipeline:

### Part 1: Data Collection
During this phase, I employed web scraping and APIs to gather essential data that would fuel Gans' decision-making process. I extracted demographical information about cities, weather forecasts, and flight arrival data for tourists.

### Part 2: Data Storage and Transformation
This phase involved the creation of a MySQL database with a well-defined relational schema to store the collected data. I used Python's SQLAlchemy library to connect Python with MySQL, enabling seamless data insertion and transformation.

### Part 3: Cloud Deployment
In this final phase, I migrated the data pipeline to the cloud using Amazon Web Services (AWS). I set up an AWS RDS instance using `boto3` and deployed data collection scripts as AWS Lambda functions. Additionally, I scheduled automatic script execution using AWS CloudWatch Events.

## Tools and Technologies Used
Throughout the project, I harnessed various tools and libraries, including:
- **Web Scraping**: Utilized the `beautifulsoup` library to extract data from websites.
- **APIs**: Employed the `requests` library to interact with APIs and retrieve data.
- **MySQL and SQLAlchemy**: Created and managed the MySQL database using SQLAlchemy for data storage and transformation.
- **AWS and `boto3`**: Set up cloud resources on AWS, including RDS and Lambda, using the `boto3` library for seamless integration.

## Key Skills Acquired
This project provided an opportunity to develop a range of skills:
- Web scraping techniques for extracting structured data from websites.
- Interfacing with APIs to retrieve data from external sources.
- Creating and managing databases, as well as designing relational schemas.
- Utilizing cloud services, such as AWS RDS and Lambda, for efficient data pipeline deployment.
- Scheduling and automating tasks using AWS CloudWatch Events.

## Conclusion
The Gans Data Engineering Project was an immersive learning experience, showcasing the end-to-end process of building an automated data pipeline. By gathering, transforming, and deploying data using a cloud-based infrastructure, the project aimed to support Gans' e-scooter operations through informed decision-making and optimization strategies.
