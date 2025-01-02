# End-to-End CI/CD Pipeline for Node.js Web Application using AWS CI/CD Services 🚀

Build a CI/CD pipeline for a Node.js web application using AWS CI/CD services (**CodeBuild, CodeDeploy, CodePipeline**).

## Architecture Description 📝

The architecture of the CI/CD pipeline is as follows:
Users start by pushing a new commit to the GitHub repository. This triggers the pipeline, which consists of three stages: **Source, Build, and Deploy**. The Source stage pulls the source code from the GitHub repository. The Build stage uses AWS CodeBuild to Test the Node.js web application. The Deploy stage uses AWS CodeDeploy to deploy the Node.js web application to an Elaastic Beanstalk environment.
**Note:** The build stage in this project is used to test the Node.js web application. In a real-world scenario, you would also include the build process in this stage.



## Prerequisites 📋

- An AWS account with the necessary permissions to create the required resources.
- GitHub account

#>

## Usage 🛠️

1. Clone or download the repository.
```sh
git clone https://github.com/334yash/awsci-cd.git
```
2. Follow the steps mentioned in the [Steps](#steps-) section.
3. Clean up the resources by following the [Clean Up](./Steps/step5.md) steps.

## Contributing 🖇️

Pull requests are welcome for any changes.

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Author 🙋‍♂

- [yash r](linkedin.com/in/yash-raut-9b035531b) on LinkedIn.
