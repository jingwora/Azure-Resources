# DevOps Engineer

**DevOps Engineering** is a practice that combines software development (Dev) and IT operations (Ops) to shorten the development life cycle and provide continuous delivery with high software quality. It emphasizes automation, collaboration, and integration between development and operations teams to improve agility and efficiency.

## DevOps lifecycle:


**1. Plan:** Begin with planning the next iteration of the development process. This involves gathering requirements, defining tasks, and scheduling work.

**2. Code:** Developers write code, often using version control systems like Git to manage changes and collaborate.

**3. Build:** The code is compiled into a runnable instance, with tools like Maven or Gradle being used for building the software.

**4. Test:** Automated tests are run to ensure quality and functionality. This includes unit tests, integration tests, and sometimes user acceptance testing. 

**5. Release:** The software is prepared for release to a production-like environment. This step often involves final testing stages and the configuration of the release.

**6. Deploy:** Automated deployment tools (like Jenkins, Spinnaker, or Ansible) deploy the software to production environments.

**7. Operate:** The operation team manages and maintains the system to ensure it performs optimally.

**8. Monitor:** The entire infrastructure and application are monitored for issues. Tools like Prometheus, Grafana, or ELK Stack are used to log and visualize performance.

**9. Feedback and Optimize:** Feedback from monitoring tools and from users is gathered and analyzed to identify areas for improvement.

--- 

**Continuous Integration (CI)** is a development practice where developers frequently merge their code changes into a central repository, preferably several times a day. Each check-in is then verified by an automated build, allowing teams to detect problems early.

[Build - Test]

**Continuous Deployment** is a software development practice where code changes are automatically prepared for a release to production. It extends the Continuous Integration process by deploying all code changes to a testing environment, and sometimes to a production-like environment, after the build stage. 

[Release]

---

## DevOps Tools

| DevOps   Lifecycle Stage |        Azure       |                   AWS                   |                     GCP                    |             Other             |
|:------------------------:|:------------------:|:---------------------------------------:|:------------------------------------------:|:-----------------------------:|
| Plan                     | Azure   Boards     | AWS   CodeStar                          | Google   Issue Tracker                     | Jira,   Confluence, Trello, Asana    |
| Code                     | Azure   Repos      | AWS   CodeCommit                        | Cloud   Source Repositories                | GitHub,   GitLab, Bitbucket   |
| Build                    | Azure   Pipelines  | AWS   CodeBuild                         | Cloud   Build                              | Jenkins,   Maven, Gradle      |
| Test                     | Azure   Test Plans | AWS   CodeBuild                         | Cloud   Test Lab                           | Selenium,   JUnit, TestNG     |
| Release                  | Azure   Pipelines  | AWS   CodePipeline                      | Cloud   Build                              | Jenkins,   GitLab CI, Bamboo  |
| Deploy                   | Azure   Pipelines  | AWS   CodeDeploy, AWS Elastic Beanstalk | Google   Kubernetes Engine                 | Ansible,   Docker, Kubernetes |
| Operate                  | Azure   DevOps     | AWS   OpsWorks, AWS Systems Manager     | Google   Operations (formerly Stackdriver) | Nagios,   Grafana, Prometheus |
| Monitor                  | Azure   Monitor    | Amazon   CloudWatch                     | Google   Operations (formerly Stackdriver) | Splunk, New Relic, Datadog    |

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



## Infrastructure as Code（IaC)

### Azure Resource Management Template (ARM Template)
- Tutorial: https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-create-first-template?tabs=azure-cli

- Temaplate: https://learn.microsoft.com/en-us/samples/browse/?expanded=azure&products=azure-resource-manager
