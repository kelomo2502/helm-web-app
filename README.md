# Deploying-Web-Application-Using-Helm-in-Kubernetes

Helm is a package manager for Kubernetes applications. It simplifies the deployment and management of applications on Kubernetes by providing a way to define, install, and upgrade even the most complex Kubernetes applications.
This practical exercise is designed for learners who are eager to dive into the world of Kubernetes, offering a hands-on experience with Helm, a key tool in modern cloud-native technology stacks. Throughout this project, you will learn how to utilize Helm to streamline the deployment and management of applications in a Kubernetes environment. By creating, configuring, and deploying a simple web application, you'll gain valuable insights into the efficiencies Helm brings to Kubernetes application management.

Imagine you're a chef in a large, busy kitchen. In this scenario, Kubernetes is the kitchen itself, equipped with all the necessary tools and stations, while the individual dishes you need to prepare are the applications. Now, Helm acts like a recipe book that not only contains recipes but also automates the preparation process. Each Helm chart is a recipe, specifying ingredients (containers, services, etc.) and the steps needed to create the dish (application). By using Helm, you're not just cooking one dish at a time; you're efficiently managing multiple dishes, ensuring each is prepared consistently and to the highest standard, no matter how busy the kitchen gets. This project will help you learn to be that efficient chef in the Kubernetes kitchen, making the process of deploying and managing applications as seamless as preparing a well-structured meal.

## Overview

In this project, you'll deploy a simple web application in a Kubernetes cluster using Helm. This project covers using Helm charts, customizing deployments with templates and values, installing and running Helm, and integrating Helm into a basic CI/CD pipeline.

## Step 1: Download and Install Vscode and helm

Let's get our hand on installing helm on different environment for different operating system (OS). But first we need to install **Vscode** for our os OS
[Download and Install VSCode](https://code.visualstudio.com/Download)

[Download and Install Helm](https://helm.sh/docs/intro/install/)

Verify that helm has been successfully installed by running

`helm version`

## Step 2: Create project directory

run `mkdir helm-web-app`
`cd helm-web-app`

## Step 3: Create a new helm chart

`helm create webapp`
