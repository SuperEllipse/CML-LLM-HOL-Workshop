# CML Large Language Models Hands-On-Lab Workshop

## About the Hands On Lab Workshops

The Hands-On Lab (HOL) Workshops are an initiative by Cloudera Solutions Engineering aimed at familiarizing CDP users with each Data Service. The content consists of a series of guides and exercises to quickly implement sample end-to-end use cases in the realm of Machine Learning, Datawarehousing, Data Engineering, Data Streaming and Operational Database.

The HOL is typically a three to four-hour event organized by Cloudera for CDP customers and prospects, where a small technical team from Cloudera Solutions Engineering provides cloud infrastructure for all participants and guides them through the completion of the labs with the help of presentations and open discussions.

The HOL contained in this GitHub repository is dedicated to Cloudera Machine Learning. CML is the CDP Data Service for machine learning and AI commonly in Private and Public Clouds.

The content is primarily designed for machine learning engineers, data scientists, and cloud architects. However, little to no code changes are typically required and non-technical stakeholders such as project managers and analysts are encouraged to actively take part.

HOL events are open to all CDP users and customers. If you would like Cloudera to host an event for you and your colleagues please contact your local Cloudera Representative or submit your information [through this portal](https://www.cloudera.com/contact-sales.html). Finally, if you have access to a CDE Virtual Cluster you are welcome to use this guide and go through the same concepts in your own time.

## About the Cloudera Machine Learning (CML) Service

Cloudera Machine Learning (CML) is Cloudera’s platform for machine learning and AI. CML unifies self-service data science and data engineering in a single, portable service as part of an enterprise data cloud for multi-function analytics on data anywhere.

Large scale organizations use CML to build and deploy machine learning and AI capabilities for business at scale, efficiently and securely. CML is built for the agility and power of cloud computing, but can also operate inside your private and secure data center.

## About the Labs

This Hands On Lab is designed to walk you through the Services's main capabilities and walk through the following use cases:

1. Prompting LLMs: Downloading and Prompting a pretrained LLM from Hugging on CML.
2. Advanced Prompting: Work with a pretrained model to set up advanced prompting using Langchain Framework.
3. Instruction Tuning with Lang Chain: Work with Langchain framework for Instruction Tuning and Context Augmentation.
4. Deploying Models in CML using CML API: Use CML API to deploy a model as an API Endpoint and test the model in a command line or Jupyter Notebook.
5. Finetuning to Finance Domain: Use a custom Dataset to demonstrate fine tuning using LoRA adapters on a financial Dataset.
6. Implementing a Vector Database in CML

## Step by Step Instructions

Detailed instructions are provided in the [step_by_step_guides](https://github.com/pdefusco/CML_LLM_HOL_Workshop/tree/main/step_by_step_guides) folder.

* [Link to the English Guide](https://github.com/pdefusco/CML_LLM_HOL_Workshop/tree/main/step_by_step_guides/english).

## Other CDP Hands On Lab Workshops

CDP Data Services include Cloudera Machine Learning (CML), Cloudera Operational Database (COD), Cloudera Data Flow (CDF) and Cloudera Data Warehouse (CDW). HOL Workshops are available for each of these CDP Data Services.

* [CDE Workshop](https://github.com/pdefusco/CDE119_ACE_WORKSHOP#cde-119-ace-hands-on-lab-workshop): Deploy an Ingestion, Transformation and Reporting pipeline with Spark 3.2. Learn about Iceberg's most popular features and orchestrate pipelines with Airflow. Use the CDE CLI and CDE Spark Submit Migration Tool to interact with CDE Virtual Clusters from your terminal.Finally, build a Python App leveraging the CDE API and monitor multiple CDE Virtual Clusters at the same time.
* [CDF Workshop](https://github.com/cloudera-labs/edge2ai-workshop): Build a full OT to IT workflow for an IoT Predictive Maintenance use case with: Edge Flow Management with MQTT and MiNiFi for data collection; Data Flow management was handled by NiFi and Kafka, and Spark Streaming with Cloudera Data Science Workbench (CDSW) model to process data. The lab also includes content focused on Kudu, Impala and Hue.
* [CDW Workshop](https://github.com/pdefusco/cdw-workshop): As a Big Data Engineer and Analyst for an Aeronautics corporation, build a Data Warehouse & Data Lakehouse to gain an advantage over your competition. Interactively explore data at scale. Create ongoing reports. Finally move to real-time analysis to anticipate engine failures. All using Apache Impala and Iceberg.
* [CML MLOps Workshop](https://github.com/pdefusco/CML_MLOps_ACE_HOL): Implement an end to end MLOps pipeline with MLFlow, Spark and PyTorch. Learn about MLFlow Tracking, MLFlow Registry, CML APIv2 and MLOps best practices including model interpretability and reproducibility. This workshop walks you through the steps to support a model in production with cutting-edge tools and frameworks.
* [CML Churn Workshop](https://github.com/ogakulov/CML_AMP_Churn_Prediction_mlflow): In this workshop you will build a Data ingestion and manipulation pipeline with Spark, leverage CML tooling for model development and experimentation and then deploy a model to a RESTful API endpoint. Finally you will build a frontend ML application to share your predictions.
