# Deploy-PHP-application-to-Azure-App-Service-using-Azure-Pipelines
Overview

Azure Pipelines helps you set up a highly customizable continuous integration (CI) and continuous delivery (CD) pipeline to target app services, virtual machines, or containers in Azure whether you are developing a .NET, Java, Node, PHP, or a Python app.

In this lab, you will configure Azure Pipelines for a PHP app to deploy on to an Azure Web App.

Objectives

Upon completion of this lab, you will be able to:

Set up a PHP Azure DevOps Project with Azure DevOps Demo Generator
Set up an Azure CI Pipeline
Set up an Azure Web App within the Release pipeline and deploy the PHP Application to the Azure Web App

Before you begin

Refer Getting Started before you follow the lab exercises.

Exercise 1: Create a PHP application project using the Azure DevOps Demo Generator
In this practice lab, you are going to work on a PHP project. The purpose is to create a system for the developer to understand the list of tasks that are triggered once the code is pushed to a shared repository.

While the code is a simple PHP application, you will use Azure Command Line Interface(CLI) to provision the infrastructure to deploy the build artifacts.

Use the Azure DevOps Demo Generator{:target="_blank"} to provision project on your Azure DevOps Organization. This URL will automatically select the PHP template in the demo generator.
