# Fraud Detection using IBM AutoAI
Cleaning and Detecting Fraud in the dataset using IBM studio Auto AI

# What is IBM Auto AI?
Strategic investments in AI can be a game changer. To fulfill the promise of AI, organizations are now tackling skill-set gaps, deployment and governance processes. In particular, businesses are seeking an alternative where citizen data scientists can quickly get started, and expert data scientists can speed experimentation time from weeks and months to minutes and hours. They need a multimodal data science and AI environment where data and analytics specialists collaborate with other experts and optimize model performance end-to-end.

To help simplify an AI lifecycle management cycle, AutoAI automates:

* Data preparation
* Model development
* Feature engineering
* Hyper-parameter optimization

# Steps:
1. Create free IBM [Cloud](https://cloud.ibm.com/registration) Account
2. Create a new Watson Studio project
3. Add Data
4. Start Experiment
5. Selecet Pipeline
6. Deploy Model

## 1. Create free IBM [Cloud](https://cloud.ibm.com/registration) Account
To get started, you need to first create your IBM cloud account. You can enter a free plan from
[here](https://cloud.ibm.com/registration).

## 2. Create a new Watson Studio project
goto IBM Cloud> Create resource> Watson Studio and create a free plan. 
Once done, crate a new project.
Create Object Cloud Storage and add it to your project.

## 3. Add Data
Download Fraud detection data in csv from this repo.
Click on Assets and select Browse and add the csv file from your file system.

## 3. Add AutoAI Asset
* Click on Add to project and select AutoAI experiment.
* Give AutoAI experiment a name.
* Associate a Machine Learning Service.
* Create a new free ML service.
* Select that ML service and click associate service.
* Click reload on the main page of AutoAI experiment and select create.

## 4. Start Experiment
* Add your csv file that you uploaded before to thr experiment.
* Select the column name to predict
* Run the rxperiment.

## 5. Selecet Pipeline
* Wait for your experiment to build and complete and select a pipeline with best accuracy.
* You can even download the perticular notebook for a pipeline bu clicking at save as.

## 6. Deploy Model
* Select a model amdnd save it.
* View it in project and promote deployment space.
* Add a new target space and click create.
* Goto your deployment space and select your model.
* Crete an online deployment.
* Once deployment is done, you can use your data to test predict your model.

Check out more resources from here,
[IBM Developers AutoAI](https://www.crowdcast.io/e/fraud-prediction-using-autoai/1) and
[Github repository](https://github.com/IBM/predict-fraud-using-auto-ai)
