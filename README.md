## Title: End-to-End Machine Learning Pipeline for Network Security Threat Detection

### Summary:
Built a full-stack machine learning pipeline for detecting network threats using a masked dataset, with complete data ingestion, model training, experiment tracking, and cloud deployment.

### Key Steps:

* Data Handling: Ingested network traffic data into MongoDB and built ETL pipelines for transformation and validation.

* Model Development: Trained classification models to identify suspicious activity using modular Python scripts (main.py) and later integrated them into a FastAPI application (app.py) for real-time inference.

* Experiment Tracking: Used DagsHub for experiment versioning and tracking metrics during model iterations.

* Deployment: Containerized the FastAPI app with Docker, pushed the image to AWS ECR, and deployed it on AWS EC2 using CI/CD GitHub workflows.

### Tools & Technologies: Python, MongoDB, FastAPI, Docker, AWS ECR/EC2, GitHub Actions, DagsHub, scikit-learn