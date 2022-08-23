
![readme header](/assets/visual_header.jpg)

# **Beyond Notebooks** - Prediction Services in Python

## **A Serverless ML Prediction Services**
**Beyond Notebooks: Serverless ML Prediction Services** is an open and free Machine Learning course where you can learn to build serverless ML systems with only `Python` and open tools. It is led by [Jim Dowling](https://www.kth.se/profile/jdowling), Associate Professor at KTH Royal University and Co-founder of [Hopsworks](https://hopsworks.ai).

## **Why is this course different?**
We want to minimize the steps needed for you to build a working ML system. **We won’t include _Docker_** any operations beyond  `GitHub` and `API calls`. We won’t teach you `DevOps`, but we will show you where you can dive deeper to learn more in different parts of serverless ML systems.

## **Why surfing;**
- You do not know about this problem domain - which is applicable to many data scientists
- You do not have expertise about the field; 
- It is a fun problem to solve

### **Learning Outcome**
- **Develop** a production-quality analytical ML Service running on serverless infrastructure
- **Write pipelines** that produce features from new or existing data
- **Operationalize feature pipelines** and training pipelines
- **Operationalize model** deployment
- **Operationalize feature/model monitoring**


### **What does it mean to put a model in production?**
- You need a prediction service that can, by itself, take new data and make predictions with the new data using a model you trained
- You need to surface your predictions to your Prediction Service

Of course, you want to add testing of features and models. You want versioning to support updates. They’re part of the __advanced module__. 


### **Timeline**
***Self paced***; the modules are meant to be taken individually in a self paced manner, a minimal knowledge is required to achieve the output of the course; you will mostly need to be pro-efficient in Python and understand the fundamentals of computer science and machine learning. You can refer to the ressources sections for additional material. 

## **How does it look:**
_diagram to be here_ 
</br>
</br>

# **Modules**
### **Module 01 - How to write Pipelines in Python**
- Refactor notebooks into Python modules/functions and Notebooks
  - Enables reuse of functions and pytest to test functions
- Github Actions
  - How to write and schedule Python programs as pipelines 
  - Dependency management
  - Environment variables
- What is a pipeline?
  - End-to-End Pipeline
  - Feature Pipeline
  - Training Pipeline
  - Inference Pipeline
- Feature types
- Feature Pipelines with Pandas
  - EDA, Aggregations, Dimensionality Reduction, Transformations, Data Validation
  - EDA/feature-types to guide feature transformations
- **Exercises**: Run your first Python program as a Github Action

### **Module 02 - Features and Models with Hopsworks**
- Feature engineering - aggregations
- Feature engineering - dimensionality reductions
- Feature engineering - transformations
- Feature Groups for writing
- Feature Views for reading
- Training Pipeline
- Model Evaluation
- Batch Inference Pipeline
- **Exercises**: Run a feature pipeline and a training/inference pipeline 

### **Module 03 - Build a Prediction Service**
- UI with Github Pages
- Synthetic data generation for the feature pipeline
  - https://www.activestate.com/blog/top-10-python-packages-for-creating-synthetic-data/ 
- Batch Pipeline
- **Exercises**: Design a UI for Github Pages. Run the feature and inference pipelines with synthetic data. Put it together in a system - e.g., titanic survival.

# **Tutorials**
### **Tutorial 01 - Build a Surf Height Prediction Service** 
- Surfing wave height prediction
  - Domain Knowledge
  - Feature Pipelines
  - Batch Prediction Pipeline
  - Training Pipeline
  - Github Actions
  - UI with Github Pages 
- **Exercises**: Build the analytical serverless ML Service

### **Tutorial 02 -Electricity Price Prediction Service**
- Electricity Prices
  - Domain Knowledge
  - Feature Pipelines
  - Batch Prediction Pipeline
  - Training Pipeline
  - Github Actions
  - UI with Github Pages 
- **Exercises**: Build the analytical serverless ML Service
</br>
</br>

# **Future Work**
### **Advanced Learning Outcomes:**
- Develop a production-quality operational ML Service  running on serverless infrastructure
- Learn how to automate testing and deploying new features and models
- Learn how to monitor models and features

### **Advanced Course-**
- ***Module 04*** - Testing and Versioning
- ***Module 05*** - Monitoring and Alerting
- ***Module 06*** - Real-Time Machine Learning
- ***Module 07*** - Dashboards and UIs

</br>
</br>

# **Some Useful Ressources**
**Awesome MLOps** - a collection of links and resources for MLOps
https://github.com/visenger/awesome-mlops

**Machine Learning Ops** - a collection of resources on how to facilitate Machine Learning Ops with GitHub.
https://mlops.githubapp.com/

**MLOps Community** - A place to have discussions about MLOps.
https://mlops.community

**MLOps Zoomcamp** - teaches practical aspects of productionizing ML services.
https://github.com/DataTalksClub/mlops-zoomcamp

