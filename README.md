# CI/CD Tools and Practices Final Project Template

This repository contains the template to be used for the Final Project for the Coursera course **CI/CD Tools and Practices**.

## Project name:

Project name: ci-cd-final-project

## CI/CD Final Project

This project implements a complete CI/CD workflow for a RESTful microservice that manages counters. The goal is to automate code quality checks, testing, image building, and deployment using GitHub Actions, Tekton, and OpenShift Pipelines.

The Continuous Integration pipeline is created with GitHub Actions. It automatically runs when code is pushed or when a pull request is opened. The CI workflow checks out the code, installs dependencies, runs linting with Flake8, and executes unit tests with Nose.

The Continuous Delivery pipeline is created with OpenShift Pipelines and Tekton. It uses multiple tasks to clean the workspace, clone the repository, run linting, execute unit tests, build a container image with Buildah, and deploy the application to an OpenShift cluster.

This project demonstrates how CI/CD practices improve software quality, reduce manual work, and make application delivery faster, safer, and more reliable.

## Usage

This repository is to be used as a template to create your own repository in your own GitHub account. No need to Fork it as it has been set up as a Template. This will avoid confusion when making Pull Requests in the future.

From the GitHub **Code** page, press the green **Use this template** button to create your own repository from this template.

Name your repo: `ci-cd-final-project`.

## Setup

After entering the lab environment you will need to run the `setup.sh` script in the `./bin` folder to install the prerequisite software.

```bash
bash bin/setup.sh
```

Then you must exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## Tasks


## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## Author

Skills Network

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>
