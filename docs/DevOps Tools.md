## DevOps Tools

| Lifecycle Stage | GitHub                                           | GitLab                            | Atlassian        | Azure                         | AWS                                   | GCP                                        | Red Hat                                 | Other                                   |
|-----------------|--------------------------------------------------|-----------------------------------|------------------|-------------------------------|---------------------------------------|--------------------------------------------|-----------------------------------------|-----------------------------------------|
| Plan            | GitHub Projects, GitHub Issues                   | GitLab Issue Board                | Jira, Confluence | Azure Boards                  | AWS CodeStar                          | Google Issue Tracker                       | -                                       | Trello, Asana                           |
| Code            | GitHub Repositories                              | GitLab SCM                        | Bitbucket        | Azure Repos                   | AWS CodeCommit                        | Cloud Source Repositories                  | -                                       | Subversion, Mercurial                   |
| Build           | GitHub Actions, GitHub CI                        | GitLab CI/CD                      | Bamboo           | Azure Pipelines               | AWS CodeBuild                         | Cloud Build                                | OpenShift CI/CD                         | Jenkins, CircleCI, Travis CI            |
| Test            | GitHub Actions, GitHub CI                        | GitLab CI/CD                      | Bamboo           | Azure Test Plans              | AWS CodeBuild                         | Cloud Test Lab                             | -                                       | Selenium, JUnit, TestNG, Cypress, Mocha |
| Release         | GitHub Actions, GitHub Release                   | GitLab CI/CD, GitLab Releases     | Bamboo           | Azure Pipelines               | AWS CodePipeline                      | Cloud Build                                | OpenShift CI/CD                         | Jenkins, CircleCI, GoCD                 |
| Deploy          | GitHub Actions, GitHub Pages, GitHub Deployments | GitLab CI/CD, GitLab Environments | Bamboo           | Azure Pipelines               | AWS CodeDeploy, AWS Elastic Beanstalk | Google Kubernetes Engine                   | OpenShift, Ansible                      | Docker, Kubernetes, Helm, Puppet        |
| Operate         | GitHub Apps, Webhooks                            | GitLab Monitoring                 | -                | Azure DevOps                  | AWS OpsWorks, AWS Systems Manager     | Google Operations (formerly Stackdriver)   | OpenShift, Ansible                      | Nagios, Grafana, Prometheus, Chef       |
| Monitor         | GitHub Actions, Webhooks                         | GitLab Monitoring                 | -                | Azure Monitor                 | Amazon CloudWatch                     | Google Operations (formerly Stackdriver)   | -                                       | Splunk, New Relic, Datadog, Zabbix, ELK |
| ---             |                                                  |                                   |                  |                               |                                       |                                            |                                         |                                         |
| IaC             | GitHub Actions (for IaC automation)              | GitLab Terraform Integration      | -                | Azure Resource Manager, Bicep, Terraform | AWS CloudFormation, Terraform         | Google Cloud Deployment Manager, Terraform | Ansible, OpenShift (supports IaC tools) | Terraform, Puppet, Chef, SaltStack      |

### Explaination
This table provides a comprehensive comparison of various tools and platforms across the DevOps lifecycle stages. Each column represents a different vendor or category of tools, while each row corresponds to a specific stage in the DevOps lifecycle. This format helps users easily compare and contrast the functionalities offered by each tool and platform at different stages of development, from planning through monitoring.

The purpose of this table is to aid IT professionals, project managers, and developers in selecting the right tools for their DevOps needs by providing a clear, side-by-side comparison of what each tool and platform offers at various stages of the software development lifecycle. This overview enables organizations to better align their tool choices with their specific workflow requirements and strategic goals, fostering more efficient and effective DevOps practices.

### Column Descriptions:
- GitHub: This column showcases tools and services provided by GitHub, focusing on project management, source code management, continuous integration and delivery, and monitoring. Key offerings include GitHub Projects, GitHub Issues, GitHub Actions, and GitHub Repositories.

- GitLab: Similar to GitHub, this column highlights GitLab's integrated suite that covers everything from issue tracking and source code management to CI/CD pipelines and monitoring, all within one platform.

- Atlassian: Atlassian’s tools are grouped together to emphasize their strengths in project planning, issue tracking, and build automation, with popular tools like Jira, Confluence, and Bamboo.

- Azure: Represents Microsoft's cloud services that support various DevOps practices such as Azure Boards for project management, Azure Repos for source control, and Azure Pipelines for CI/CD.

- AWS: This column covers Amazon Web Services' offerings that facilitate DevOps processes, including AWS CodeStar for project management, AWS CodeCommit for source control, and AWS CodeBuild for building and testing applications.

- GCP: Google Cloud Platform’s tools, such as Google Issue Tracker and Cloud Build, are featured here, emphasizing GCP’s integration and scalability in cloud-based DevOps environments.

- Red Hat: Focuses on enterprise-level solutions provided by Red Hat, including OpenShift for container orchestration and Ansible for automation, which support robust deployment and operational capabilities.

- Other: This column includes a variety of additional tools that are widely used in the industry but not tied to a specific major platform. These include Jenkins, CircleCI, Docker, Kubernetes, and more, covering various aspects of building, deploying, and monitoring applications.

### Row Descriptions:
- Plan: Tools and services used for project planning and issue tracking.
- Code: Platforms and services that support version control and source code management.
- Build: Tools that automate the building of code, a key component of continuous integration practices.
- Test: Solutions that automate testing, ensuring that code changes are viable and stable.
- Release: Tools that manage and automate the release process, enabling continuous delivery.
- Deploy: Technologies that automate the deployment process, ensuring smooth and scalable application rollouts.
- Operate: Tools that help in the operation and management of applications in production environments.
- Monitor: Solutions that provide monitoring and logging capabilities to track the performance and health of applications.


### Infrastructure as Code（IaC)

Infrastructure as Code (IaC) is a key practice in the field of DevOps that automates the provisioning and management of infrastructure through code instead of manual processes. 


**Terraform:** Developed by HashiCorp, Terraform allows users to define and provision infrastructure across a variety of service providers using a high-level configuration language. It is known for its ability to manage both cloud and on-premises resources.

**Ansible:** Owned by Red Hat, Ansible is an open-source tool that automates software provisioning, configuration management, and application deployment. Ansible uses YAML for its playbooks and is appreciated for its simplicity and agentless architecture.

**AWS CloudFormation:** Specifically designed for AWS, CloudFormation allows users to define and provision AWS infrastructure using a declarative template. It integrates deeply with AWS services and manages dependencies between resources effectively.

**Azure Resource Manager (ARM):** ARM is the native IaC tool for Microsoft Azure, providing a management layer that enables users to create, update, and delete resources in their Azure account. It uses JSON to define the resources.

- Tutorial: https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-create-first-template?tabs=azure-cli

- Temaplate: https://learn.microsoft.com/en-us/samples/browse/?expanded=azure&products=azure-resource-manager

**Google Cloud Deployment Manager:** Similar to AWS CloudFormation and ARM, this tool is for Google Cloud Platform. It enables users to write flexible templates and configurations and deploy resources repeatably.
