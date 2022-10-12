# Overview
You've made it to the last part of the course! It's time to work on your final project, Building a CI/CD Pipeline.
![overview](https://azureimages2022.blob.core.windows.net/imagesdevops2022/agile-project-management.png)

This project will give you an opportunity to demonstrate your ability to perform continuous delivery for a Python-based machine learning application using the Flask web framework. You will apply the skills you have acquired in this course to operationalize a Machine Learning Microservice API.

# Project estimate document
The plan project estimate is
![project-estimate](https://azureimages2022.blob.core.windows.net/imagesdevops2022/project_estimate.png)
We can get the file at https://azureimages2022.blob.core.windows.net/imagesdevops2022/project-management-template.xlsx

A Trello board for the project is
![trello-project-init](https://azureimages2022.blob.core.windows.net/imagesdevops2022/trello_project_init.png)
![trello-project](https://azureimages2022.blob.core.windows.net/imagesdevops2022/trello_project.png)
We can get the link to trello project at https://trello.com/b/mW6jdFMn/build-be

# CI: Configure GitHub Actions
Go to Actions, and then choose New workflow
![ci](https://azureimages2022.blob.core.windows.net/imagesdevops2022/CI_0.png)    
step 1:
![ci-1](https://azureimages2022.blob.core.windows.net/imagesdevops2022/CI_1.png)
step 2:
![ci-2](https://azureimages2022.blob.core.windows.net/imagesdevops2022/CI_2.png)
step 3:
![ci-3](https://azureimages2022.blob.core.windows.net/imagesdevops2022/CI_3.png)
step 4: update contain of file main-pipline.yml
![ci-4](hhttps://azureimages2022.blob.core.windows.net/imagesdevops2022/CI_4.png)
Final, we have:
![ci-F1](https://azureimages2022.blob.core.windows.net/imagesdevops2022/CI_F1.png)
![ci-F2](https://azureimages2022.blob.core.windows.net/imagesdevops2022/CI_F2.png)

# Continuous Delivery on Azure
In this diagram, you can see a continuous delivery of a flask application through the use of Azure Pipelines and Azure App service.
![cd-concept](https://azureimages2022.blob.core.windows.net/imagesdevops2022/CD_concept.png)
Azure DevOps Pipeline Agent

*Step by step create Azure DevOps Pipeline at

-We can get infomation about step 1 at: https://www.youtube.com/watch?v=QIFVOTGEnLY

-We can get infomation about step 2 at: https://www.youtube.com/watch?v=WVEpYa1WUjM

-We can get infomation about step 3 at: https://www.youtube.com/watch?v=mHKXksJDvUo