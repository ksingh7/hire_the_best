## Introduction
This is a repository contains instructions for technical evaluation.

## Environment Details
- Get a Free OpenShift Sandbox Environment by registering [here](https://developers.redhat.com/developer-sandbox/get-started) 

## Part-1 (OpenShift) (Mandatory)
### Tasks
- Connect / Login to OpenShift using `oc` CLI on your local machine
- Create a new OpenShift Project with same name as your `First Name`
- Use the provided sample application `yaml` files and deploy the app in your OpenShift project
- Make sure you are able to access the application from your local browser

## Part-2 (Containers) (Mandatory)
### Tasks
- Create a Dockerfile that prints "Hello World" on the console
- Build the container image and push it to any public registry
- Run the container image from public registry (hint : `docker run`)
  

## Part-3 (Ansible) (Bonus Points)
### Tasks
- Create a new OpenShift project called `ansible-is-great`
- Create a ansible playbook to deploy the provided `yaml` files to OpenShift environment under the project `ansible-is-great`
- Run the ansible playbook
- Make sure you are able to access the application from your local browser
