# UTS 2023 Internships

### ***What is CI/CD?***
**CI/CD** is the process of automating software development workflows and deploying better quality code frequently. Following continuous and iterative process it helps to avoid and overcome failure in codes and bugs. CI means **Continuous Integration** and CD means **Continuous Delivery and Deployment**. In software development and operations (DevOps), CI/CD simplifies software coding, testing, and deployment by providing teams with a centralised repository for storing work and automated tools to merge and test code on a continuous basis. CI was first proposed by Gandy Booch in his 1991 method. CI is the process where frequent merging of several tiny changes into main branch of version control platform is occured by the development team members. CI enables developers to develop independently, forming their own coding "branch" to execute minor changes. As the developer develops, they can capture snapshots of the source code, generally using a versioning tool like Git. The developer may focus on new features; if an issue arises, Git can simply revert the code to its earlier state. Instead of producing code alone and publishing it to the master monthly, which may result in time-consuming bug fixes and inadequate version control, the CI/CD development approach allows teams to submit code changes regularly. On the other hand, CD is the process where development team produces programs in short period of time frequently so that it can be reliable and ready for the deployment state. Once the code has been tested and developed as part of the CI process, continuous delivery takes over during the final steps to guarantee it can be deployed to any environment at any time. With continuous delivery, the software is built so that it can be deployed to production at any time. Continuous deployment is also known as CD in the CI/CD process. After passing a sequence of specified tests, such as integration tests that examine code in a copycat environment to validate code integrity, continuous deployment automatically distributes code changes to end users. Continuous deployment allows teams to release new or updated software often and as quickly as possible.

![](https://www.synopsys.com/glossary/what-is-cicd/_jcr_content/root/synopsyscontainer/column_1946395452/colRight/image_copy.coreimg.svg/1663683682045/cicd.svg)
###### *Figure: Continuous Integration/Continuous Delivery and Development(CI/CD)*

### ***A few commonly used for CI/CD and why they are used***

- **Jenkins**: Jenkins is a veteran CI Tool with a long proven track record. It is open source and driven by community updates. Jenkins is primarily intended to an on-premise installation.
    - On-premise
    - Open source
    - Robust addon / plugin ecosystem
- **CircleCI**: CircleCI is CI Tool that gracefully pairs with Github, one of the most popular version control system cloud hosting tools. CircleCi is one of the most flexible CI Tools in that it supports a matrix of version control systems, container systems, and delivery mechanisms. 
    - Notification triggers from CI events
    - Performance optimized for quick builds
    - Easy debugging through SSH and local builds
    - Analytics to measure build performance
- **GitLab**: Gitlab is a new CI Tool which offers a full DevOps experience. Gitlab was created with intentions to improve Github’s overall experience. Gitlab offers a modern UX with container support.
    - On-prem or cloud hosting
    - Continuous security testing
    - Easy to learn UX
- **TeamCity**: TeamCity is a JetBrains’s build management and continuous integration server. TeamCity is a continuous integration tool that helps building and deploying different types of projects. 
    - Extensibility and Customization
    - Provides better code quality for any project
    - Remote run and pre-tested commit
- **Bamboo**: Bamboo is a continuous integration server that automates the management of software application releases, thus creating a continuous delivery pipeline. 
    - Supports up to 100 remote build agents 
    - Run batches of tests in parallel and get feedback quickly
    - Creates images and pushes into a registry


These are a few tools that are used for CI/CD however there are many other tools used based on different test cases. The tools are usualy used to make the developement more efficient by making it automated. As with most automation strategies, CI/CD relies on tools to achieve optimal workflows. CI/CD tools help store the environment-specific parameters that must be packaged with each delivery. CI/CD automation then makes any necessary service calls to web servers, databases, and other services that need restarting. It can also execute other procedures following deployment.

![](https://www.redhat.com/cms/managed-files/styles/wysiwyg_full_width/s3/ci-cd-flow-desktop_0.png?itok=QgBYmjA2)
###### *Figure: CI/CD Pipelines*



## References 
1. [https://about.gitlab.com/topics/ci-cd/](https://about.gitlab.com/topics/ci-cd/)
2. [https://en.wikipedia.org/wiki/CI/CD](https://en.wikipedia.org/wiki/CI/CD)
3. [https://en.wikipedia.org/wiki/Continuous_integration](https://en.wikipedia.org/wiki/Continuous_integration)
4. [https://www.ibm.com/cloud/blog/ci-cd-pipeline](https://www.ibm.com/cloud/blog/ci-cd-pipeline)
5. [https://www.synopsys.com/glossary/what-is-cicd.html](https://www.synopsys.com/glossary/what-is-cicd.html)
6. [https://www.atlassian.com/continuous-delivery/continuous-integration/tools](https://www.atlassian.com/continuous-delivery/continuous-integration/tools)
7. [https://katalon.com/resources-center/blog/ci-cd-tools](https://katalon.com/resources-center/blog/ci-cd-tools)
8. [https://www.guru99.com/top-20-continuous-integration-tools.html](https://www.guru99.com/top-20-continuous-integration-tools.html)
8. [https://www.redhat.com/en/topics/devops/what-cicd-pipeline](https://www.redhat.com/en/topics/devops/what-cicd-pipeline)



#### Author: Akibur Rahman Choton 