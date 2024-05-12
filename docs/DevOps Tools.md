## DevOps Tools

| Lifecycle Stage | GitHub                                           | Azure            | AWS                                   | GCP                                      | Other                           |
|-----------------|--------------------------------------------------|------------------|---------------------------------------|------------------------------------------|---------------------------------|
| Plan            | GitHub Projects, GitHub Issues                   | Azure Boards     | AWS CodeStar                          | Google Issue Tracker                     | Jira, Confluence, Trello, Asana |
| Code            | GitHub Repositories                              | Azure Repos      | AWS CodeCommit                        | Cloud Source Repositories                | Bitbucket       |
| Build           | GitHub Actions, GitHub CI                        | Azure Pipelines  | AWS CodeBuild                         | Cloud Build                              | Jenkins, Maven, Gradle          |
| Test            | GitHub Actions, GitHub CI                        | Azure Test Plans | AWS CodeBuild                         | Cloud Test Lab                           | Selenium, JUnit, TestNG         |
| Release         | GitHub Actions, GitHub Release                   | Azure Pipelines  | AWS CodePipeline                      | Cloud Build                              | Jenkins, Bamboo      |
| Deploy          | GitHub Actions, GitHub Pages, GitHub Deployments | Azure Pipelines  | AWS CodeDeploy, AWS Elastic Beanstalk | Google Kubernetes Engine                 | Ansible, Docker, Kubernetes     |
| Operate         | GitHub Apps, Webhooks                            | Azure DevOps     | AWS OpsWorks, AWS Systems Manager     | Google Operations (formerly Stackdriver) | Nagios, Grafana, Prometheus     |
| Monitor         | GitHub Actions, Webhooks                         | Azure Monitor    | Amazon CloudWatch                     | Google Operations (formerly Stackdriver) | Splunk, New Relic, Datadog      |

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

Git Hosting Services
These platforms provide remote hosting for Git repositories, facilitating collaboration, issue tracking, and sometimes CI/CD pipelines.

- **GitHub:** The most popular Git repository hosting service, offering collaboration features, GitHub Actions for CI/CD, and a robust ecosystem of integrations.
- **GitLab:** A comprehensive DevOps platform providing repository management, built-in CI/CD, issue tracking, and more, all within a single application.
- **Bitbucket:** Hosted by Atlassian, this service integrates well with JIRA and other Atlassian products, providing repository hosting and CI/CD via Bitbucket Pipelines.
- **Azure Repos:** Part of Azure DevOps, it offers Git repository hosting and integration with Azure Boards for project management and Azure Pipelines for CI/CD.


### Automation Tools
These tools are primarily focused on automating parts of the development workflow, particularly around continuous integration and deployment.

Jenkins
- **GitHub Actions:** Allows you to automate, customize, and execute your software development workflows right within your GitHub repository.
- **GitLab CI/CD:** Provides a powerful and integrated CI/CD service within GitLab, supporting complex workflows.
- **Jenkins:** An extendable open-source CI/CD server that can automate various stages of your delivery pipeline. It’s highly customizable with plugins.
- **CircleCI:** A CI/CD tool that integrates deeply with GitHub and Bitbucket, known for its performance and easy configuration.

### Workflow Models
Workflow models define conventions for using Git to enhance the development process, making it more structured and manageable.
- **Git Flow:** A branching model proposed by Vincent Driessen. It's especially suited for projects with scheduled release cycles, defining specific roles for branches.
- **GitHub Flow:** A simpler alternative to Git Flow, optimized for continuous deployment. It typically uses a single main branch with feature branches.
- **GitLab Flow:** Combines feature-driven development and feature branching with issue tracking, closely integrating with the CI/CD capabilities of GitLab.



### Infrastructure as Code（IaC)

Infrastructure as Code (IaC) is a key practice in the field of DevOps that automates the provisioning and management of infrastructure through code instead of manual processes. 


**Terraform:** Developed by HashiCorp, Terraform allows users to define and provision infrastructure across a variety of service providers using a high-level configuration language. It is known for its ability to manage both cloud and on-premises resources.

**Ansible:** Owned by Red Hat, Ansible is an open-source tool that automates software provisioning, configuration management, and application deployment. Ansible uses YAML for its playbooks and is appreciated for its simplicity and agentless architecture.

**AWS CloudFormation:** Specifically designed for AWS, CloudFormation allows users to define and provision AWS infrastructure using a declarative template. It integrates deeply with AWS services and manages dependencies between resources effectively.

**Azure Resource Manager (ARM):** ARM is the native IaC tool for Microsoft Azure, providing a management layer that enables users to create, update, and delete resources in their Azure account. It uses JSON to define the resources.

- Tutorial: https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-create-first-template?tabs=azure-cli

- Temaplate: https://learn.microsoft.com/en-us/samples/browse/?expanded=azure&products=azure-resource-manager

**Google Cloud Deployment Manager:** Similar to AWS CloudFormation and ARM, this tool is for Google Cloud Platform. It enables users to write flexible templates and configurations and deploy resources repeatably.
