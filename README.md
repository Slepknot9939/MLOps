# MLOps

What is MLOps?<br>
Answer:-<br>
    1) MLOps or ML Ops is a set of practices that aims to deploy and maintain machine learning models in production reliably and efficiently. ... When an algorithm is ready to be launched, MLOps is practiced between Data Scientists, DevOps, and Machine Learning engineers to transition the algorithm to production systems.<br>
  2)MLOps is a set of practices for collaboration and communication between data scientists and operations professionals. Applying these practices increases the quality, simplifies the management process, and automates the deployment of Machine Learning and Deep Learning models in large-scale production environments. It’s easier to align models with business needs, as well as regulatory requirements.
  
  ![image](https://user-images.githubusercontent.com/62091944/148631270-af0bc016-a417-46b7-a419-2c725298356b.png)

The key phases of MLOps are:<br>

* Data gathering<br>
* Data analysis<br>
* Data transformation/preparation<br>
* Model training & development <br>
* Model validation <br>
* Model serving <br>
* Model monitoring <br>
* Model re-training.<br>

Basic Difference between MLOps and DevOps.

![image](https://user-images.githubusercontent.com/62091944/148631416-cf5b1f46-322c-47ae-8356-e47430cb13a6.png)

 ML there are a few notable differences:<br>

* Continuous Integration (CI) is no longer only about testing and validating code and components, but also testing and validating data, data schemas, and models.<br>
* Continuous Deployment (CD) is no longer about a single software package or service, but a system (an ML training pipeline) that should automatically deploy another service <br>(model prediction service) or roll back changes from a model.
* Continuous Testing (CT) is a new property, unique to ML systems, that’s concerned with automatically retraining and serving the models<br>

![image](https://user-images.githubusercontent.com/62091944/148668326-3c9a8878-a66b-4bfd-b931-aede60fb3421.png)

MLOps best practices
At first, I wanted to just list 10 best practices, but after some research, I came to the conclusion that it would be best to cover the best practices for different components of an ML pipeline, namely: Team, Data, Objective, Model, Code, and Deployment.

The following list is distilled from various sources mentioned in the references:<br>

# Team<br>
* Use A Collaborative Development Platform<br>
* Work Against a Shared Backlog<br>
* Communicate, Align, and Collaborate With Others<br>
# Data<br>
* Use Sanity Checks for All External Data Sources<br>
* Track, identify, and account for changes in data sources.<br>
* Write Reusable Scripts for Data Cleaning and Merging<br>
* Combine and modify existing features to create new features in human­-understandable ways<br>
* Ensure Data Labelling is Performed in a Strictly Controlled Process<br>
* Make Data Sets Available on Shared Infrastructure (private or public)<br>
# Objective (Metrics & KPIs)<br>
* Don’t overthink which objective you choose to directly optimize, track multiple metrics at first.<br>
* Choose a simple, observable and attributable metric for your first objective<br>
* Set Governance Objectives<br>
* Enforce Fairness and Privacy<br><br>
# Model <br>
* Keep the first model simple and get the infrastructure right<br>
* Starting with an interpretable model makes debugging easier.<br>
# Training<br>
* Capture the Training Objective in a Metric that is Easy to Measure and Understand<br>
* Actively Remove or Archive Features That are Not Used<br>
* Peer Review Training Scripts<br>
* Enable Parallel Training Experiments<br>
* Automate Hyper-Parameter Optimisation<br>
* Continuously Measure Model Quality and Performance<br>
* Use Versioning for Data, Model, Configurations and Training Scripts<br>
# Code<br>
* Run Automated Regression Tests<br>
* Use Static Analysis to Check Code Quality<br>
* Use Continuous Integration<br><br>
# Deployment<br>
* Plan to launch and iterate.<br>
* Automate Model Deployment<br>
* Continuously Monitor the Behaviour of Deployed Models<br>
* Enable Automatic Rollbacks for Production Models<br>
* When performance plateaus, look for qualitatively new sources of information to add rather than refining existing signals.<br>
* Enable Shadow Deployment<br>
* Keep ensembles simple<br>
* Log Production Predictions with the Model’s Version, Code Version and Input Data<br>
* Human Analysis of the System & Training-Serving Skew<br>
* You are not a typical end user.<br>
* Measure the delta between models<br>
* When choosing models, utilitarian performance trumps predictive power.<br>
* Perform evolving data profiles checks<br>
* If you produce a model based on the data until January 5th, test the model on the data from January 6th and after.<br>
These best practices will serve as the foundation on which you will build your MLOps solutions, with that said we can now dive into the implementation details.

What is the use of MLOps?<br>
Answer:- MLOps accounts for the unique aspects of AI/ML projects in project management, CI/CD( continuous integration, continuous delivery, and continuous deployment.), and quality assurance, helping you improve delivery time, reduce defects, and make data science more productive. MLOps refers to a methodology that is built on applying DevOps practices to machine learning workloads.

What is MLOps technology?<br>
Answer:- Machine Learning Operations (MLOps) is a combination of processes, emerging best practices and underpinning technologies that provides a scalable, centralized and governed means to automate and scale the deployment and management of trusted ML applications in production environments.

What is MLOps and why do we need it?<br>
Answer:-Machine Learning Operations (MLOps) allows organizations to alleviate many of the issues on the path to AI with ROI by providing a technological backbone for managing the machine learning lifecycle through automation and scalability. ... AI and machine learning projects should be driving the future of your business.

What comes under MLOps?<br>
Answer:- Machine Learning systems can be categorized in eight different categories: data collection, data processing, feature engineering, data labelling, model design, model training and optimization, endpoint deployment, and endpoint monitoring.
