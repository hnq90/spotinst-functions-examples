[![Spotinst Serverless Functions](./assets/functions.jpg)](https://serverless.com/framework/docs/providers/spotinst/)

[Spotinst Functions Website](https://spotinst.com/products/spotinst-functions/) • [Spointst Community Slack](https://join.slack.com/t/spotinst-community/shared_invite/enQtMjM5MjUzMDYwMzY4LTQ4YjNkODgyNmE3MGE4ZjU3MjdmZmQ0ZTk3NTZmOTNmZmI3NjFhYjYwNzI1MzAxMzM1Yzk3NTY5MDhiN2U3Zjg) • [Spotinst Serverless Documentation](https://serverless.com/framework/docs/providers/spotinst/) • [Spoitinst Serverless Help](https://help.spotinst.com/hc/en-us/categories/115000701089-Spotinst-Functions-)

# Spotinst Serverless Examples

Here are a few examples to help you get started with Spotinst Serverless Functions

## Getting Started 

If you are new to using Spotinst Serverless Functions you can view the documentation on the [Serverless Fameworks Documentation](https://serverless.com/framework/docs/providers/spotinst/). You will need to have the serverless framework installed on your local machine as well as set up your Spotinst credentials.

## Examples

Each of the projects listed here have their own `README.md` that will help you set up each project and their use cases

**Have an example?** Fork this repository and submit a PR for review

### Clone Subdirectory

To clone just one of the projects listed bellow you will need to perform a sparse checkout of the repository. To do this enter the following into the terminal

1. Create a new project directory and enter the root
```
mkdir {Project Name}
cd {Project Name}
```

2. Initialize the new directory as a Git repository and add the remote end point for this repository
```
git init
git remote add -f origin https://github.com/spotinst/spotinst-functions-examples
```

3. Enable Git to perform only sparse checkout allowing you to pull ony the project that you want
```
git config core.sparsecheckout true
```

4. Add the project that you want to clone to the .git/info/sparse-checkout file so when you pull you will only pull the project specified
```
echo {Project Directory Name} >> .git/info/sparse-checkout
git pull origin master
```



| Example | Runtime  |
|:--------------------------- |:-----|
|[Node Spotinst API Get All Elastigroups](https://github.com/spotinst/spotinst-functions-examples/tree/master/node-spotinst-api-getGroups) </br> This example shows you how to connect to the Spotinst API and return all the Elastigroups that were created in the past hour| nodeJS |
|[Node Spotinst API Suspend/Unsuspend Scaling Policies](https://github.com/spotinst/spotinst-functions-examples/tree/master/node-spotinst-api-suspendPolicy) </br> This example shows you how to connect to the Spotinst API to suspend or unsupend scaling policies on your elastigroups| nodeJS |
|[Node MySQL Connection](https://github.com/spotinst/spotinst-functions-examples/tree/master/node-mysql-connection) </br> This example shows you how to connect to a MySQL table and insert new values or return all the entries in your table| nodeJS |
|[Python MySQL Connection](https://github.com/spotinst/spotinst-functions-examples/tree/master/python-mysql-connection) </br> This example shows you how to connect to a MySQL table and insert new values or return all the entries in your table| Python |

