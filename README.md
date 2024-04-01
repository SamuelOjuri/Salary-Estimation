# Salary Estimation - Stack Overflow 2023 Developer Survey

This repository contains the code and documentation for analyzing the Stack Overflow 2023 Developer Survey data to estimate salaries and develop a scalable data correction pipeline.

## Task 1: Data Quality Improvement and Model Training

### Overview

The first task involves cleaning and preparing the survey data, identifying data quality issues, and training machine learning models to predict developer salaries.

### Data Preparation and Analysis

- The data is loaded, and preliminary analysis is performed to understand its structure, missing values, and distributions.
- Data cleaning steps include handling missing values, removing outliers, and addressing data consistency issues.
- Features relevant to salary prediction are identified and retained for model training.

### Model Training

- Various regression models are trained and evaluated, including Linear Regression, Ridge Regression, Lasso Regression, Random Forest, Gradient Boosting, and Support Vector Regression.
- Model performance is compared using cross-validation and metrics such as Mean Squared Error (MSE).

## Task 2: Scalable Data Correction Pipeline Architecture

### Overview

The second task focuses on designing a scalable architecture for the data correction pipeline, leveraging cloud-based storage and tools for data ingestion, processing, and monitoring.

### Architecture Components

- **Google Cloud Storage (GCS):** Used for storing raw and processed data due to its scalability and global availability.
- **Google Cloud Pub/Sub:** Facilitates real-time data ingestion and event streaming.
- **Google Cloud Dataflow:** Enables scalable data processing, built on Apache Beam for both batch and stream processing.
- **Google Cloud Operations:** Provides monitoring and logging capabilities to track the pipeline's performance.

### Deployment Strategy

- Infrastructure as Code (IaC) is employed using Google Cloud Deployment Manager or Terraform to automate the provisioning and management of cloud resources.

### Security and Documentation

- Identity and Access Management (IAM) roles are configured for secure access to resources.
- Comprehensive documentation is maintained for system architecture, data flows, and security policies.

## Getting Started

Instructions for setting up the environment, running the data analysis, and deploying the data correction pipeline are provided to facilitate replication and adaptation of the processes involved.

## Contributions

We welcome contributions to enhance the analysis and the pipeline architecture. Please follow the guidelines provided for contributions.

## License

This project is licensed under the [LICENSE.md] file in the root directory of this source tree.

## Acknowledgments

- Stack Overflow for providing the dataset.
- Google Cloud Platform for the cloud services used in the pipeline architecture.

