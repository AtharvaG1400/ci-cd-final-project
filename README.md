# ci-cd-final-project

## Project Name
CI/CD Pipeline for a Python Application

## Project Description
This project demonstrates Continuous Integration and Continuous Delivery using GitHub Actions, Tekton, and OpenShift Pipelines.

## Technologies Used
- Python and Flask
- GitHub Actions
- flake8
- nose
- Docker and Buildah
- Tekton
- Red Hat OpenShift

## Continuous Integration
The GitHub Actions workflow installs Python dependencies, checks the source code with flake8, and runs automated unit tests with nose.

## Continuous Delivery
The OpenShift Pipeline cleans the workspace, clones the repository, runs linting and tests, builds a container image, and deploys the application.

## Author
AtharvaG1400

# CI/CD Tools and Practices Final Project Template

This repository contains the template to be used for the Final Project for the Coursera course **CI/CD Tools and Practices**.

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
