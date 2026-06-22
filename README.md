# AZ-400 Microsoft DevOps Certification Study Guide

- [Official certification page](https://learn.microsoft.com/en-us/credentials/certifications/exams/az-400/)
- [Study Guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-400)
- [Reddit Prep](https://www.reddit.com/r/AzureCertification/comments/1rfnfga/just_passed_az400_my_impressions_and_preparation/)

## My reading list

- [AZ-400: Development for Enterprise DevOps](https://learn.microsoft.com/en-us/training/paths/az-400-work-git-for-enterprise-devops/)
    - [What is DevOps?](https://learn.microsoft.com/en-us/training/modules/introduction-to-devops/2-what-is-devops) - interesting on process
    - Deployment strategies to consider
        - [Blue-Green](https://www.redhat.com/en/topics/devops/what-is-blue-green-deployment)
        - [Canary](https://docs.cloud.google.com/deploy/docs/deployment-strategies/canary#:~:text=A%20canary%20deployment%20is%20a,users%20before%20rolling%20out%20fully.)
            - [Differentiate between Canary release vs blue green deployment](https://www.reddit.com/r/devops/comments/1m777h8/scratching_my_head_trying_to_differentiate/)
        - [Feature Flag](https://confidence.spotify.com/blog/feature-flags?gad_source=1&gad_campaignid=23888641138&gbraid=0AAAABDu614F2k8KG-9iMw0o6x4EKC1tak&gclid=EAIaIQobChMIgvaWrbWQlQMVGn9BAh26iQzfEAAYAiAAEgKoIfD_BwE)
    - Azure Repos [Product](https://azure.microsoft.com/fr-fr/products/devops/repos) (sub product of azure devops) | [doc](https://learn.microsoft.com/en-us/azure/devops/repos/?view=azure-devops)
    - Azure Devops [Product](https://azure.microsoft.com/en-us/products/devops)

- [Plan Agile with GitHub Projects and Azure Boards](https://learn.microsoft.com/en-us/training/modules/plan-agile-github-projects-azure-boards/)
    - Project types:
        - User owned and organization owned
        - [Types of GitHub accounts](https://docs.github.com/en/get-started/learning-about-github/types-of-github-accounts)

## Skills Measured (as of April 24, 2026)

### Design and implement processes and communications (10–15%)

#### Design and implement traceability and flow of work

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Design and implement a structure for the flow of work, including GitHub Flow | ⬜ | [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) | |
| Design and implement a strategy for feedback cycles, including notifications and GitHub issues | ⬜ | [GitHub Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) \| [Azure DevOps Notifications](https://learn.microsoft.com/en-us/azure/devops/notifications/about-notifications) | |
| Design and implement integration for tracking work, including GitHub projects, Azure Boards, and repositories | ⬜ | [GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) \| [Azure Boards Integration](https://learn.microsoft.com/en-us/azure/devops/boards/github/) | [LAB Agile Plan and Portfolio Management with Azure Boards](https://learn.microsoft.com/en-us/training/modules/plan-agile-github-projects-azure-boards/12-agile-plan-portfolio-management-azure-boards) |
| Design and implement source, bug, and quality traceability | ⬜ | [Traceability in Azure DevOps](https://learn.microsoft.com/en-us/azure/devops/boards/queries/link-work-items-support-traceability) \| [End-to-end traceability](https://learn.microsoft.com/en-us/azure/devops/cross-service/end-to-end-traceability) | |

#### Design and implement appropriate metrics and queries for DevOps

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Design and implement a dashboard, including flow of work, such as cycle times, time to recovery, and lead time | ⬜ | [Azure DevOps Dashboards](https://learn.microsoft.com/en-us/azure/devops/report/dashboards/dashboards) \| [Analytics](https://learn.microsoft.com/en-us/azure/devops/report/dashboards/analytics-widgets) | |
| Design and implement appropriate metrics and queries for project planning | ⬜ | [Project Planning Queries](https://learn.microsoft.com/en-us/azure/devops/boards/queries/query-by-workflow-changes) \| [Velocity](https://learn.microsoft.com/en-us/azure/devops/report/dashboards/team-velocity) | |
| Design and implement appropriate metrics and queries for development | ⬜ | [Code Quality Metrics](https://learn.microsoft.com/en-us/azure/devops/report/dashboards/analytics-widgets#code-quality-widgets) \| [Git Analytics](https://learn.microsoft.com/en-us/azure/devops/report/dashboards/analytics-widgets#git-widgets) | |
| Design and implement appropriate metrics and queries for testing | ⬜ | [Test Analytics](https://learn.microsoft.com/en-us/azure/devops/pipelines/test/test-analytics) \| [Test Results](https://learn.microsoft.com/en-us/azure/devops/pipelines/test/review-continuous-test-results-after-build) | |
| Design and implement appropriate metrics and queries for security | ⬜ | [Security Metrics](https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-devops-introduction) \| [Secure DevOps Kit](https://learn.microsoft.com/en-us/azure/devops/organizations/security/) | |
| Design and implement appropriate metrics and queries for delivery | ⬜ | [Deployment Frequency](https://learn.microsoft.com/en-us/azure/devops/report/dashboards/analytics-widgets#deployment-widgets) \| [Release Analytics](https://learn.microsoft.com/en-us/azure/devops/pipelines/reports/pipelinereport) | |
| Design and implement appropriate metrics and queries for operations | ⬜ | [Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-monitor/overview) \| [Application Insights](https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview) | |

#### Configure collaboration and communication

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Document a project by configuring wikis and process diagrams, including Markdown and Mermaid syntax | ⬜ | [Azure DevOps Wiki](https://learn.microsoft.com/en-us/azure/devops/project/wiki/wiki-create-repo) \| [Mermaid Diagrams](https://learn.microsoft.com/en-us/azure/devops/project/wiki/wiki-markdown-guidance#add-mermaid-diagrams-to-a-wiki-page) | |
| Configure release documentation, including release notes and API documentation | ⬜ | [Release Notes](https://learn.microsoft.com/en-us/azure/devops/pipelines/release/approvals/gates) \| [GitHub Releases](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases) | |
| Automate creation of documentation from Git history | ⬜ | [Git History](https://learn.microsoft.com/en-us/azure/devops/repos/git/review-history) \| [Release Notes Automation](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/github-release-v1) | |
| Configure integration by using webhooks | ⬜ | [Service Hooks](https://learn.microsoft.com/en-us/azure/devops/service-hooks/overview) \| [GitHub Webhooks](https://docs.github.com/en/webhooks) | |
| Configure integration between Azure Boards and GitHub repositories | ⬜ | [Azure Boards + GitHub](https://learn.microsoft.com/en-us/azure/devops/boards/github/) \| [GitHub Integration](https://learn.microsoft.com/en-us/azure/devops/boards/github/connect-to-github) | |
| Configure integration between GitHub or Azure DevOps and Microsoft Teams | ⬜ | [Azure DevOps + Teams](https://learn.microsoft.com/en-us/azure/devops/pipelines/integrations/microsoft-teams) \| [GitHub + Teams](https://learn.microsoft.com/en-us/microsoftteams/platform/samples/integrating-with-github) | |

---

### Design and implement a source control strategy (10–15%)

#### Design and implement branching strategies for the source code

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Design a branch strategy, including trunk-based, feature branch, and release branch | ⬜ | [Branch Strategy](https://learn.microsoft.com/en-us/azure/devops/repos/git/git-branching-guidance) \| [Trunk-based Development](https://learn.microsoft.com/en-us/devops/develop/how-microsoft-develops-devops) | |
| Design and implement a pull request workflow by using branch policies and branch protection rules | ⬜ | [Branch Policies](https://learn.microsoft.com/en-us/azure/devops/repos/git/branch-policies) \| [GitHub Branch Protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches) | |
| Implement branch merging restrictions by using branch policies and branch protection rules | ⬜ | [Branch Permissions](https://learn.microsoft.com/en-us/azure/devops/repos/git/branch-permissions) \| [Require Pull Request Reviews](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches#require-pull-request-reviews-before-merging) | |

#### Configure and manage repositories

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Design and implement a strategy for managing large files, including Git Large File Storage (LFS) and git-fat | ⬜ | [Git LFS](https://learn.microsoft.com/en-us/azure/devops/repos/git/manage-large-files) \| [GitHub LFS](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-git-large-file-storage) | |
| Design a strategy for scaling and optimizing a Git repository, including Scalar and cross-repository sharing | ⬜ | [Scalar](https://github.com/microsoft/scalar) \| [Git Performance](https://learn.microsoft.com/en-us/azure/devops/repos/git/git-config#performance-settings) | |
| Configure permissions in the source control repository | ⬜ | [Repository Permissions](https://learn.microsoft.com/en-us/azure/devops/repos/git/set-git-repository-permissions) \| [GitHub Permissions](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-repository-roles/repository-roles-for-an-organization) | |
| Configure tags to organize the source control repository | ⬜ | [Git Tags](https://learn.microsoft.com/en-us/azure/devops/repos/git/git-tags) \| [GitHub Tags](https://docs.github.com/en/repositories/releasing-projects-on-github/viewing-your-repositorys-releases-and-tags) | |
| Recover specific data by using Git commands | ⬜ | [Git History](https://learn.microsoft.com/en-us/azure/devops/repos/git/review-history) \| [Undo Changes](https://learn.microsoft.com/en-us/azure/devops/repos/git/undo) | |
| Remove specific data from source control | ⬜ | [Remove Files from Git](https://learn.microsoft.com/en-us/azure/devops/repos/git/remove-binaries) \| [Git Filter-Repo](https://github.com/newren/git-filter-repo) | |

---

### Design and implement build and release pipelines (50–55%)

#### Design and implement a package management strategy

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Recommend package management tools including GitHub Packages and Azure Artifacts | ⬜ | [Azure Artifacts](https://learn.microsoft.com/en-us/azure/devops/artifacts/start-using-azure-artifacts) \| [GitHub Packages](https://docs.github.com/en/packages/learn-github-packages/introduction-to-github-packages) | |
| Design and implement package feeds and views for local and upstream packages | ⬜ | [Artifact Feeds](https://learn.microsoft.com/en-us/azure/devops/artifacts/concepts/feeds) \| [Upstream Sources](https://learn.microsoft.com/en-us/azure/devops/artifacts/concepts/upstream-sources) | |
| Design and implement a dependency versioning strategy for code assets and packages, including semantic versioning (SemVer) and date-based (CalVer) | ⬜ | [Package Versioning](https://learn.microsoft.com/en-us/azure/devops/artifacts/concepts/package-versioning) \| [Semantic Versioning](https://semver.org/) | |
| Design and implement a versioning strategy for pipeline artifacts | ⬜ | [Pipeline Artifacts](https://learn.microsoft.com/en-us/azure/devops/pipelines/artifacts/pipeline-artifacts) \| [Build Artifacts](https://learn.microsoft.com/en-us/azure/devops/pipelines/artifacts/build-artifacts) | |

#### Design and implement a testing strategy for pipelines

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Design and implement quality and release gates, including security and governance | ⬜ | [Release Gates](https://learn.microsoft.com/en-us/azure/devops/pipelines/release/approvals/gates) \| [Approvals](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/approvals) | |
| Design a comprehensive testing strategy, including local tests, unit tests, integration tests, and load tests | ⬜ | [Testing Strategy](https://learn.microsoft.com/en-us/azure/devops/pipelines/ecosystems/dotnet-core#run-your-tests) \| [Azure Load Testing](https://learn.microsoft.com/en-us/azure/load-testing/overview-what-is-azure-load-testing) | |
| Implement tests in a pipeline, including configuring test tasks, configuring test agents, and integration of test results | ⬜ | [Run Tests](https://learn.microsoft.com/en-us/azure/devops/pipelines/test/test-analytics) \| [Test Tasks](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/vstest-v2) | |
| Implement code coverage analysis | ⬜ | [Code Coverage](https://learn.microsoft.com/en-us/azure/devops/pipelines/test/review-code-coverage-results) \| [Coverage Tools](https://learn.microsoft.com/en-us/azure/devops/pipelines/test/codecoverage-for-pullrequests) | |

#### Design and implement pipelines

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Select a deployment automation solution, including GitHub Actions and Azure Pipelines | ⬜ | [Azure Pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/get-started/what-is-azure-pipelines) \| [GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions) | |
| Design and implement a GitHub runner or Azure DevOps agent infrastructure, including cost, tool selection, licenses, connectivity, and maintainability | ⬜ | [Azure Pipeline Agents](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/agents) \| [Self-hosted Runners](https://docs.github.com/en/actions/hosting-your-own-runners/managing-self-hosted-runners/about-self-hosted-runners) | |
| Design and implement integration between GitHub repositories and Azure Pipelines | ⬜ | [GitHub + Azure Pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/repos/github) \| [Service Connections](https://learn.microsoft.com/en-us/azure/devops/pipelines/library/service-endpoints) | |
| Develop and implement pipeline trigger rules | ⬜ | [Pipeline Triggers](https://learn.microsoft.com/en-us/azure/devops/pipelines/build/triggers) \| [GitHub Actions Triggers](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows) | |
| Develop pipelines by using YAML | ⬜ | [YAML Schema](https://learn.microsoft.com/en-us/azure/devops/pipelines/yaml-schema/) \| [YAML Pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/get-started/pipelines-get-started) | |
| Design and implement a strategy for job execution order, including parallelism and multi-stage pipelines | ⬜ | [Multi-stage Pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/stages) \| [Dependencies](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/stages#specify-dependencies) | |
| Develop and implement complex pipeline scenarios, such as hybrid pipelines, VM templates, and self-hosted runners or agents | ⬜ | [Deployment Groups](https://learn.microsoft.com/en-us/azure/devops/pipelines/release/deployment-groups/) \| [VM Templates](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/scale-set-agents) | |
| Create reusable pipeline elements, including YAML templates, task groups, variables, and variable groups | ⬜ | [YAML Templates](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/templates) \| [Variable Groups](https://learn.microsoft.com/en-us/azure/devops/pipelines/library/variable-groups) | |
| Design and implement checks and approvals by using YAML-based environments | ⬜ | [Environments](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/environments) \| [Checks](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/approvals) | |

#### Design and implement deployments

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Design a deployment strategy, including blue-green, canary, ring, progressive exposure, feature flags, and A/B testing | ⬜ | [Deployment Patterns](https://learn.microsoft.com/en-us/azure/devops/pipelines/release/deployment-patterns) \| [Progressive Exposure](https://learn.microsoft.com/en-us/devops/operate/safe-deployment-practices) | |
| Design a pipeline to ensure that dependency deployments are reliably ordered | ⬜ | [Stage Dependencies](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/stages#specify-dependencies) \| [Deployment Jobs](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/deployment-jobs) | |
| Plan for minimizing downtime during deployments by using load balancing, rolling deployments, and deployment slot usage and swap | ⬜ | [Deployment Slots](https://learn.microsoft.com/en-us/azure/app-service/deploy-staging-slots) \| [Rolling Deployments](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/deployment-jobs#rolling-deployment) | |
| Design a hotfix path plan for responding to high-priority code fixes | ⬜ | [Hotfix Workflow](https://learn.microsoft.com/en-us/azure/devops/repos/git/git-branching-guidance#manage-releases) \| [Emergency Changes](https://learn.microsoft.com/en-us/devops/operate/safe-deployment-practices) | |
| Design and implement a resiliency strategy for deployment | ⬜ | [Deployment Resiliency](https://learn.microsoft.com/en-us/azure/architecture/framework/devops/release-engineering-cd#deployment-resiliency) \| [Rollback Strategies](https://learn.microsoft.com/en-us/azure/devops/pipelines/release/deployment-patterns#rollback) | |
| Implement feature flags by using Azure App Configuration Feature Manager | ⬜ | [Feature Management](https://learn.microsoft.com/en-us/azure/azure-app-configuration/concept-feature-management) \| [Feature Flags](https://learn.microsoft.com/en-us/azure/azure-app-configuration/use-feature-flags-dotnet-core) | |
| Implement application deployment by using containers, binaries, and scripts | ⬜ | [Container Deployment](https://learn.microsoft.com/en-us/azure/devops/pipelines/ecosystems/containers/acr-template) \| [Script Deployment](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/azure-cli-v2) | |
| Implement a deployment that includes database tasks | ⬜ | [Database Deployment](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/sql-azure-dacpac-deployment-v1) \| [DACPAC](https://learn.microsoft.com/en-us/sql/relational-databases/data-tier-applications/data-tier-applications) | |

#### Design and implement infrastructure as code (IaC)

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Recommend a configuration management technology for application infrastructure | ⬜ | [IaC Overview](https://learn.microsoft.com/en-us/devops/deliver/what-is-infrastructure-as-code) \| [Configuration Management](https://learn.microsoft.com/en-us/azure/architecture/framework/devops/automation-infrastructure) | |
| Implement a configuration management strategy for application infrastructure | ⬜ | [ARM Templates](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/overview) \| [Terraform](https://learn.microsoft.com/en-us/azure/developer/terraform/overview) | |
| Define an IaC strategy, including source control and automation of testing and deployment | ⬜ | [IaC Best Practices](https://learn.microsoft.com/en-us/azure/architecture/framework/devops/automation-infrastructure) \| [Testing IaC](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/test-toolkit) | |
| Design and implement desired state configuration for environments, including Azure Automation State Configuration, Azure Resource Manager, Bicep, and Azure Machine Configuration | ⬜ | [Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview) \| [Azure Automation DSC](https://learn.microsoft.com/en-us/azure/automation/automation-dsc-overview) \| [Machine Configuration](https://learn.microsoft.com/en-us/azure/governance/machine-configuration/overview) | |
| Design and implement Azure Deployment Environments for on-demand self-deployment | ⬜ | [Azure Deployment Environments](https://learn.microsoft.com/en-us/azure/deployment-environments/overview-what-is-azure-deployment-environments) \| [Dev Box](https://learn.microsoft.com/en-us/azure/dev-box/overview-what-is-microsoft-dev-box) | |

#### Maintain pipelines

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Monitor pipeline health, including failure rate, duration, and flaky tests | ⬜ | [Pipeline Reports](https://learn.microsoft.com/en-us/azure/devops/pipelines/reports/pipelinereport) \| [Test Analytics](https://learn.microsoft.com/en-us/azure/devops/pipelines/test/test-analytics) | |
| Optimize a pipeline for cost, time, performance, and reliability | ⬜ | [Pipeline Optimization](https://learn.microsoft.com/en-us/azure/devops/pipelines/build/triggers#batching-ci-runs) \| [Parallel Jobs](https://learn.microsoft.com/en-us/azure/devops/pipelines/licensing/concurrent-jobs) | |
| Optimize pipeline concurrency for performance and cost | ⬜ | [Concurrency](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/stages#specify-concurrency) \| [Job Limits](https://learn.microsoft.com/en-us/azure/devops/pipelines/licensing/concurrent-jobs) | |
| Design and implement a retention strategy for pipeline artifacts and dependencies | ⬜ | [Retention Policies](https://learn.microsoft.com/en-us/azure/devops/pipelines/policies/retention) \| [Artifact Retention](https://learn.microsoft.com/en-us/azure/devops/artifacts/how-to/delete-and-recover-packages) | |
| Migrate a pipeline from classic to YAML in Azure Pipelines | ⬜ | [Classic to YAML](https://learn.microsoft.com/en-us/azure/devops/pipelines/migrate/from-classic-pipelines) \| [YAML Migration](https://learn.microsoft.com/en-us/azure/devops/pipelines/get-started/pipelines-get-started) | |

---

### Develop a security and compliance plan (10–15%)

#### Design and implement authentication and authorization methods

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Choose between Microsoft Entra service principals and managed identities for Azure resources (system-assigned and user-assigned) | ⬜ | [Managed Identities](https://learn.microsoft.com/en-us/entra/identity/managed-identities-azure-resources/overview) \| [Service Principals](https://learn.microsoft.com/en-us/entra/identity-platform/app-objects-and-service-principals) | |
| Implement and manage GitHub authentication, including GitHub Apps, GITHUB_TOKEN, and personal access tokens | ⬜ | [GitHub Apps](https://docs.github.com/en/apps/creating-github-apps/about-creating-github-apps/about-creating-github-apps) \| [GITHUB_TOKEN](https://docs.github.com/en/actions/security-guides/automatic-token-authentication) \| [PATs](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) | |
| Implement and manage Azure DevOps service connections and personal access tokens | ⬜ | [Service Connections](https://learn.microsoft.com/en-us/azure/devops/pipelines/library/service-endpoints) \| [PATs](https://learn.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate) | |
| Design and implement permissions and roles in GitHub | ⬜ | [GitHub Roles](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-repository-roles/repository-roles-for-an-organization) \| [Custom Roles](https://docs.github.com/en/enterprise-cloud@latest/organizations/managing-peoples-access-to-your-organization-with-roles/about-custom-repository-roles) | |
| Design and implement permissions and security groups in Azure DevOps | ⬜ | [Permissions](https://learn.microsoft.com/en-us/azure/devops/organizations/security/permissions) \| [Security Groups](https://learn.microsoft.com/en-us/azure/devops/organizations/security/about-permissions) | |
| Recommend appropriate access levels, including stakeholder access in Azure DevOps and outside collaborator access in GitHub | ⬜ | [Access Levels](https://learn.microsoft.com/en-us/azure/devops/organizations/security/access-levels) \| [Outside Collaborators](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-outside-collaborators/adding-outside-collaborators-to-repositories-in-your-organization) | |
| Configure projects and teams in Azure DevOps | ⬜ | [Create Project](https://learn.microsoft.com/en-us/azure/devops/organizations/projects/create-project) \| [Teams](https://learn.microsoft.com/en-us/azure/devops/organizations/settings/add-teams) | |

#### Design and implement a strategy for managing sensitive information in automation

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Implement and manage secrets, keys, and certificates by using Azure Key Vault | ⬜ | [Azure Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/general/overview) \| [Key Vault in Pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/release/azure-key-vault) | |
| Implement and manage secrets and secretless authentication (for example, workload identity federation/OpenID Connect) in GitHub Actions and Azure Pipelines | ⬜ | [GitHub Secrets](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions) \| [OIDC](https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/about-security-hardening-with-openid-connect) \| [Workload Identity](https://learn.microsoft.com/en-us/azure/devops/pipelines/release/configure-workload-identity) | |
| Design and implement a strategy for managing sensitive files during deployment, including Azure Pipelines secure files | ⬜ | [Secure Files](https://learn.microsoft.com/en-us/azure/devops/pipelines/library/secure-files) \| [Variable Groups](https://learn.microsoft.com/en-us/azure/devops/pipelines/library/variable-groups) | |
| Design pipelines to prevent leakage of sensitive information | ⬜ | [Secret Scanning](https://docs.github.com/en/code-security/secret-scanning/about-secret-scanning) \| [Pipeline Security](https://learn.microsoft.com/en-us/azure/devops/pipelines/security/overview) | |

#### Automate security and compliance scanning

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Design a strategy for security and compliance scanning, including dependency, code, secret, and licensing scanning | ⬜ | [DevOps Security](https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-devops-introduction) \| [GitHub Security](https://docs.github.com/en/code-security/getting-started/github-security-features) | |
| Configure Microsoft Defender for Cloud DevOps Security | ⬜ | [Defender for DevOps](https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-devops-introduction) \| [Connect GitHub](https://learn.microsoft.com/en-us/azure/defender-for-cloud/quickstart-onboard-github) | |
| Configure GitHub Advanced Security for both GitHub and Azure DevOps | ⬜ | [GitHub Advanced Security](https://docs.github.com/en/get-started/learning-about-github/about-github-advanced-security) \| [GHAS for Azure DevOps](https://learn.microsoft.com/en-us/azure/devops/repos/security/configure-github-advanced-security-features) | |
| Integrate GitHub Advanced Security with Microsoft Defender for Cloud | ⬜ | [GHAS + Defender](https://learn.microsoft.com/en-us/azure/defender-for-cloud/github-advanced-security-defender-for-cloud) \| [Security Integration](https://learn.microsoft.com/en-us/azure/defender-for-cloud/integration-github-advanced-security) | |
| Automate container scanning, including scanning container images and configuring an action to run CodeQL analysis in a container | ⬜ | [Container Scanning](https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-containers-introduction) \| [CodeQL](https://docs.github.com/en/code-security/code-scanning/introduction-to-code-scanning/about-code-scanning-with-codeql) | |
| Automate analysis of licensing, vulnerabilities, and versioning of open-source components by using Dependabot alerts | ⬜ | [Dependabot](https://docs.github.com/en/code-security/dependabot/dependabot-alerts/about-dependabot-alerts) \| [Dependency Scanning](https://learn.microsoft.com/en-us/azure/devops/repos/security/github-advanced-security-dependency-scanning) | |

---

### Implement an instrumentation strategy (5–10%)

#### Configure monitoring for a DevOps environment

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Configure Azure Monitor and Azure Monitor Logs to integrate with DevOps tools | ⬜ | [Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-monitor/overview) \| [Log Analytics](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-analytics-overview) | |
| Configure collection of telemetry by using Application Insights, VM Insights, Container Insights, Azure Monitor for Storage, and Azure Monitor for Networks | ⬜ | [Application Insights](https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview) \| [VM Insights](https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-overview) \| [Container Insights](https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-overview) | |
| Configure monitoring in GitHub, including enabling insights and creating and configuring charts | ⬜ | [GitHub Insights](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/viewing-insights-for-your-organization) \| [Repository Insights](https://docs.github.com/en/repositories/viewing-activity-and-data-for-your-repository/viewing-traffic-to-a-repository) | |
| Configure alerts for events in GitHub Actions and Azure Pipelines | ⬜ | [Pipeline Notifications](https://learn.microsoft.com/en-us/azure/devops/pipelines/integrations/slack) \| [GitHub Notifications](https://docs.github.com/en/actions/monitoring-and-troubleshooting-workflows/notifications-for-workflow-runs) | |

#### Analyze metrics from instrumentation

| Skill | Status | Suggested | Resources |
|-------|--------|-----------|-----------|
| Inspect infrastructure performance indicators, including CPU, memory, disk, and network | ⬜ | [Performance Monitoring](https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-performance) \| [Metrics Explorer](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/metrics-getting-started) | |
| Analyze metrics by using collected telemetry, including usage and application performance | ⬜ | [Application Insights Analytics](https://learn.microsoft.com/en-us/azure/azure-monitor/app/analytics) \| [Usage Analysis](https://learn.microsoft.com/en-us/azure/azure-monitor/app/usage-overview) | |
| Inspect distributed tracing by using Application Insights | ⬜ | [Distributed Tracing](https://learn.microsoft.com/en-us/azure/azure-monitor/app/distributed-tracing) \| [Application Map](https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-map) | |
| Interrogate logs using basic Kusto Query Language (KQL) queries | ⬜ | [KQL Overview](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/) \| [Log Queries](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/get-started-queries) | |
