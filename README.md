# Operationalizing-an-AWS-ML-Project
In this project will prepare the dogImage classification model to be deployed for production .

![bikeshare](https://github.com/yasserelsawaf/Operationalizing-an-AWS-ML-Project/blob/4273adf76905c4fcf278ea1b11f08d2788e3c7ec/MLOps-Architecture.png)

#Overview:

Using several important tools and features of AWS to adjust, improve, configure, and prepare the trained model with for production-grade deployment ,
Taking raw ML code and preparing it for production deployment is a common task for ML engineers, and it's very important for the following reasons:

1-ML code alone isn't sufficient for most business scenarios. Real business situations require ML code to integrate with other infrastructures, like API's, applications, or other websites that require ML code to be correctly configured. You'll configure some crucial production infrastructure for an ML pipeline in this project.
2-If ML code is deployed in a way that's not optimal, it can lead to cost overruns or bad performance. You'll choose and deploy optimal computing resources for your ML code in this project.
3-When ML code is moved to production deployment, security is always a concern, since poor security can lead to data leaks or performance issues. You'll configure and optimize ML pipeline security in this project.


Following aspects of AWS machine learning operations:

- Managing computing resources efficiently
- Training models with large datasets using multi-instance training
- Setting up high-throughput, low-latency pipelines
 -AWS security
 
Thiis project will complete the following steps:

- Train and deploy a model on Sagemaker, using the most appropriate instances.
- Set up multi-instance training in your Sagemaker notebook.
- Adjust your Sagemaker notebooks to perform training and deployment on EC2.
- Set up a Lambda function for your deployed model. Set up auto-scaling for your deployed endpoint as well as concurrency for your Lambda function.
- Ensure that the security on your ML pipeline is set up properly.
