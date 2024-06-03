# DevOps Engineer

**DevOps Engineering** is a practice that combines software development (Dev) and IT operations (Ops) to shorten the development life cycle and provide continuous delivery with high software quality. It emphasizes automation, collaboration, and integration between development and operations teams to improve agility and efficiency.

## Contents

- [DevOps-Tools](https://github.com/jingwora/DevOps-Engineer/blob/main/docs/DevOps%20Tools.md)
- [CICD-pipeline-tutorial](https://github.com/jingwora/DevOps-Engineer/blob/main/docs/CICD-pipeline-tutorial.md)


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
| Feature                     | Normal Development                  | DevOps                              | MLOps                                | LLMOps                              |
|-----------------------------|-------------------------------------|-------------------------------------|--------------------------------------|-------------------------------------|
| **Scope**                   | General software development        | Continuous integration and delivery | Machine learning model lifecycle     | Large language model lifecycle      |
| **Objective**               | Building and maintaining software   | Streamlining software delivery and infrastructure changes | Developing, deploying, and maintaining ML models | Developing, deploying, and maintaining LLMs |
| **Development Cycle**       | Waterfall, Agile, DevOps            | Agile, CI/CD                        | Iterative, data-centric, CI/CD        | Iterative, data-centric, CI/CD       |
| **Key Components**          | Code, testing, deployment           | Code, automation, monitoring        | Data, model training, deployment, monitoring | Data, model training, fine-tuning, deployment, monitoring |
| **Data Handling**           | Minimal, specific to application    | Application-specific configurations | Extensive, involves data preprocessing and management | Extensive, large datasets, specialized preprocessing |
| **Infrastructure**          | General-purpose servers, cloud      | Cloud-native, containerization, orchestration (Kubernetes) | GPU/TPU clusters, specialized ML infrastructure | High-performance computing clusters, specialized LLM infrastructure |
| **Tooling**                 | IDEs, CI/CD tools                   | CI/CD pipelines, monitoring tools (Nagios, Prometheus) | ML frameworks (TensorFlow, PyTorch), MLOps platforms (Kubeflow, MLflow) | LLM frameworks (Transformers), LLMOps platforms (LangChain) |
| **Testing**                 | Unit tests, integration tests       | Automated tests, continuous testing | Model validation, cross-validation, A/B testing | Model validation, benchmarks, scenario-based testing |
| **Deployment**              | CI/CD pipelines, containerization   | Automated deployment, infrastructure as code | Model serving, CI/CD for ML, containerization   | Model serving, CI/CD for LLMs, containerization          |
| **Monitoring**              | Application performance monitoring  | Application and infrastructure monitoring | Model performance, drift detection    | Model performance, drift detection, ethical and bias monitoring |
| **Collaboration**           | Developers, QA, Ops                 | Developers, QA, Ops, Security       | Data scientists, ML engineers, DevOps | Data scientists, LLM engineers, DevOps                  |
| **Challenges**              | Bug fixes, feature updates, scalability | Automation, continuous improvement  | Data quality, model drift, retraining | Data quality, model drift, hallucination, ethical considerations |
| **Examples**                | Web applications, mobile apps       | Web services, microservices         | Recommendation systems, image classifiers | Chatbots, text generation systems, language understanding models |


--- 

**Continuous Integration (CI)** is a development practice where developers frequently merge their code changes into a central repository, preferably several times a day. Each check-in is then verified by an automated build, allowing teams to detect problems early.

[Build - Test]

**Continuous Deployment** is a software development practice where code changes are automatically prepared for a release to production. It extends the Continuous Integration process by deploying all code changes to a testing environment, and sometimes to a production-like environment, after the build stage. 

[Release]

---



