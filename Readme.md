# Sonarcloud integration with GiHub Actions

## Sonarcloud
SonarCloud is a cloud-based code quality and security service. The main features of SonarCloud are:
    * 25 languages: Java, JS, C#, C/C++, Objective-C, TypeScript, Python, ABAP, PLSQL, T-SQL and more.
    * Thousands of rules to track down hard-to-find bugs and quality issues thanks to powerful static code analyzers.
    * Cloud CI Integrations, with Travis, Azure DevOps, BitBucket, AppVeyor and more.
    * Deep code analysis, to explore all source files, whether in branches or pull requests, to reach a green Quality Gate and promote the build.
    * Fast and Scalable

SonarCloud uses state-of-the-art techniques in *static code analysis* to find problems, and potential problems, in the code that you and your team write.

*Static analysis* is called static because it does not rely on actually running the code (analysis of running code is called dynamic analysis). As a result, SonarCloud offers an additional layer of verification, different from automated testing and human code-review. 

> [!IMPORTANT]
> SonarCloud does not work with on-premises code repositories.

When you first sign up for SonarCloud you have to choose which DevOps platform you want to connect to.

## GitHub Actions
GitHub Actions makes it easy to automate all your software workflows, now with world-class CI/CD. Build, test, and deploy your code right from GitHub. Make code reviews, branch management, and issue triaging work the way you want. 

GitHub provides Linux, Windows, and macOS virtual machines to run your workflows, or you can host your own self-hosted runners in your own data center or cloud infrastructure.

A **workflow** is a configurable automated process that will run one or more jobs. Workflows are defined by a YAML file checked in to your repository and will run when triggered by an event in your repository, or they can be triggered manually, or at a defined schedule.

Workflows are defined in the `.github/workflows` directory in a repository, and a repository can have multiple workflows, each of which can perform a different set of tasks. For example, you can have one workflow to build and test pull requests, another workflow to deploy your application every time a release is created, and still another workflow that adds a label every time someone opens a new issue.
