# Financial-Risk-MLOps-Pipeline-AWS

### Overview

An end-to-end MLOps pipeline for training, deploying, monitoring, and retraining financial risk models using AWS-native services.  This project highlights production ML engineering, not just model building.

### Objectives
* Automate ML lifecycle
* Monitor model drift
* Enable safe retraining

### Architecture
* DateMaker Training
* SageMaker Endpoint
* Model Monitor
* CI/CD pipeline

### AWS Services Used
* Amazon SageMaker (Training, Pipelines, Endpoints)
* AWS CodePipeline / CodeBuild
* CloudWatch
* S3

### Explainability
* SHAP-based feature importance
* Drift comparison across model versions
* ### Repository Structure
~~~
/training
/pipelines
/monitoring
/models
README.md
~~~

### Key Outcomes
* Fully automated ML lifecycle
* Detects performance degradation
* Production-grade monitoring
