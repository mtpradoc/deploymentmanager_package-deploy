# deploymentmanager_package-deploy

Objectives:
- Develop and deploy a service, including the appication and not just the insfrastructure.
- Learn more advanced Deployment Manager template techniquers.
- Create a deployable package using pip.
- Follow best practices for testing an application prior to deploying it and after it is deployed.

Create the directory structure for the deployment

mkdir ~/echolb
mkdir ~/echolb/deployment-manager-examples
mkdir ~/echolb/echo
mkdir ~/echolb/echo/echo

The application requires Flask and Gunicorn frameworks.

The echo application consists of the following files:
__init__.py
default.cfg
setup.py
LICENSE.txt
MANIFEST.in
