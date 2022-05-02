## Introduction
This is a repository contains instructions for technical evaluation.

## Environment Details
- Get a Free OpenShift Sandbox Environment by registering [here](https://developers.redhat.com/developer-sandbox/get-started) 

## Part-1 (OpenShift) (Mandatory)
### Tasks
- Connect / Login to OpenShift using `oc` CLI on your local machine
- Use the provided sample application `yaml` files and deploy the app on OpenShift Sandbox
- Make sure you are able to access the application from your local browser

### Verification
- Upon accessing the application in your local browser, you should see the following:
![](https://raw.githubusercontent.com/ksingh7/hire_the_best/main/nginx.png)

## Part-2 (Containers) (Mandatory)
### Tasks
- Create a Dockerfile that prints "Hello World" on the console
- Build the container image and push it to any public registry
- Run the container image from public registry (hint : `docker run`)
  
### Verification
- List the container image locally
- Run the container image locally

## Part-3 (Ansible) (Bonus Points)
### Tasks
- Create an Ansible playbook to deploy the provided `yaml` files to OpenShift environment
- Run the Ansible playbook
- Make sure you are able to access the application from your local browser

### Verification
- Run the Ansible playbook to deploy the App
- Upon accessing the application in your local browser, you should see the following:
![](https://raw.githubusercontent.com/ksingh7/hire_the_best/main/nginx.png)