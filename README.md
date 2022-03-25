# Retirement notice
This workshop will be retired effective June 30, 2022. At that time the repository will be archived, and the materials will not be maintained.

For questions or concerns regarding the MCW library, email us at [AskMCW](mailto:AskMCW@microsoft.com). Please remember to include the title of the workshop in your email.

# MLOps

Wide World Importers (WWI) delivers innovative solutions for manufacturers. They specialize in identifying and solving problems for manufacturers that can run the range from automation, to providing cutting edge approaches that generate new opportunities. WWI has decades specializing in data science and application development that until now were separate units. They would like to unlock the greater, long-term value by combining the two units into one and follow one standardized process for operationalizing their innovations.

For this first proof of concept (PoC), WWI are looking to leverage Deep Learning technologies with Natural Language Processing (NLP) techniques to scan through vehicle component descriptions to find compliance issues with new regulations. The component descriptions are managed via a web application, and the web application takes the description and labels the component as compliant or non-compliant using the trained model. As part of this PoC, they want to ensure the overall process they create enables them to update both the underlying machine learning model and the web app in one, unified pipeline. They also want to be able to monitor the model's performance after it is deployed so they can be proactive with performance issues.

March 2022

## Target audience

- Data Scientists
- App Developers
- AI Engineers
- DevOps Engineers

## Abstracts

### Workshop

In this workshop, you will learn how Wide World Importers (WWI) can leverage Deep Learning technologies to scan through their vehicle specification documents to find compliance issues with new regulations and manage the classification through their web application. The entire process from model creation, application packaging, model deployment and application deployment needs to occur as one unified repeatable, pipeline.

At the end of this workshop, you will be better able to design and implement end-to-end solutions that fully operationalize deep learning models, inclusive of all application components that depend on the model.

### Whiteboard design session

In this whiteboard design session, you will work in a group to design a process Wide World Importers (WWI) can follow for orchestrating and deploying updates to the application and the deep learning model in a unified way. You will learn how WWI can leverage Deep Learning technologies to scan through their vehicle specification documents to find compliance issues with new regulations. You will standardize the model format to ONNX and observe how this simplifies inference runtime code, enabling pluggability of different models and targeting a broad range of runtime environments and most importantly improves inferencing speed over the native model. You will design a DevOps pipeline to coordinate retrieving the latest best model from the model registry, packaging the web application, deploying the web application, and inferencing web service. You will also learn how to monitor the model's performance after it is deployed so WWI can be proactive with performance issues.

At the end of this whiteboard design session, you will be better able to design end-to-end solutions that will fully operationalize deep learning models, inclusive of all application components that depend on the model.

### Hands-on lab

In this hands-on lab, you will learn how Wide World Importers (WWI) can leverage Deep Learning technologies to scan through their vehicle specification documents to find compliance issues with new regulations. You will standardize the model format to ONNX and observe how this simplifies inference runtime code, enabling pluggability of different models and targeting a broad range of runtime environments and most importantly, improves inferencing speed over the native model. You will build a DevOps pipeline to coordinate retrieving the latest best model from the model registry, packaging the web application, deploying the web application, and inferencing web service. After a first successful deployment, you will make updates to both the model, the web application, and execute the pipeline once to achieve an updated deployment. You will also learn how to monitor the model's performance after it is deployed so WWI can be proactive with performance issues.

At the end of this hands-on lab, you will be better able to implement end-to-end solutions that fully operationalize deep learning models, inclusive of all application components that depend on the model.

## Azure services and related products

- Azure Container Instances
- Azure DevOps
- Azure Kubernetes Service
- Azure Machine Learning Service
- ML Ops
- ONNX
  
## Related references

- [MCW](https://microsoftcloudworkshop.com/)

## Help & Support

We welcome feedback and comments from Microsoft SMEs & learning partners who deliver MCWs.  

***Having trouble?***

- First, verify you have followed all written lab instructions (including the Before the Hands-on lab document).
- Next, submit an issue with a detailed description of the problem.
- Do not submit pull requests. Our content authors will make all changes and submit pull requests for approval.

If you are planning to present a workshop, *review and test the materials early*! We recommend at least two weeks prior.

**Please allow 5 - 10 business days for review and resolution of issues.**
