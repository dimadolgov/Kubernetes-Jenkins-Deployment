# Jenkins Deployment in Kubernetes 

This YAML file deploys Jenkins with VMware PowerCLI and Powershell plugins and many other in Kuberneted env...

- Namespaces
- Deployment
- Service
- ClusterRole and ClusterRoleBinding
- ServiceAccount
- PersistentVolume
- PersistentVolumeClaim
- StorageClass

## List of Plugins
```bash
- ansible  # Ansible plugin
- checks-api  # Jenkins Checks API plugin
- github-branch-source  # GitHub Branch Source plugin
- matrix-auth  # Matrix Authorization Strategy plugin
- saml  # SAML plugin
- ansicolor  # ANSI Color plugin
- cloud-stats  # Cloud Stats plugin
- github  # GitHub plugin
- matrix-project  # Matrix Project plugin
- schedule-build  # Schedule Build plugin
- antisamy-markup-formatter  # Antisamy Markup Formatter plugin
- cloudbees-bitbucket-branch-source  # CloudBees Bitbucket Branch Source plugin
- gitlab-plugin  # GitLab plugin
- metrics  # Metrics plugin
- scm-api  # SCM API plugin
- apache-httpcomponents-client-4-api  # Apache HttpComponents Client 4.x API plugin
- cloudbees-disk-usage-simple  # CloudBees Disk Usage Simple plugin
- gradle  # Gradle plugin
- mina-sshd-api-common  # Apache Mina SSHD Common API plugin
- script-security  # Script Security plugin
- apache-httpcomponents-client-5-api  # Apache HttpComponents Client 5.x API plugin
- cloudbees-folder  # CloudBees Folder plugin
- gson-api  # Gson API plugin
- mina-sshd-api-core  # Apache Mina SSHD Core API plugin
- sidebar-link  # Sidebar Link plugin
- asm-api  # ASM API plugin
- command-launcher  # Command Launcher plugin
- handy-uri-templates-2-api  # Handy URI Templates 2 API plugin
- oic-auth  # OIC Auth plugin
- simple-theme-plugin  # Simple Theme plugin
- audit-trail  # Audit Trail plugin
- commons-lang3-api  # Apache Commons Lang3 API plugin
- htmlpublisher  # HTML Publisher plugin
- okhttp-api  # OkHttp API plugin
- snakeyaml-api  # SnakeYAML API plugin
- authentication-tokens  # Authentication Tokens plugin
- commons-text-api  # Apache Commons Text API plugin
- instance-identity  # Instance Identity plugin
- opentelemetry  # OpenTelemetry plugin
- authorize-project  # Authorize Project plugin
- config-file-provider  # Config File Provider plugin
- ionicons-api  # Ionicons API plugin
- pam-auth  # PAM Auth plugin
- ssh-agent  # SSH Agent plugin
- blueocean-bitbucket-pipeline  # Blue Ocean Bitbucket Pipeline plugin
- configuration-as-code  # Configuration as Code plugin
- jackson2-api  # Jackson 2 API plugin
- parameter-separator  # Parameter Separator plugin
- ssh-credentials  # SSH Credentials plugin
- blueocean-commons  # Blue Ocean Commons plugin
- credentials-binding  # Credentials Binding plugin
- jakarta-activation-api  # Jakarta Activation API plugin
- parameterized-scheduler  # Parameterized Scheduler plugin
- ssh-slaves  # SSH Slaves plugin
- blueocean-config  # Blue Ocean Config plugin
- credentials  # Credentials plugin
- jakarta-mail-api  # Jakarta Mail API plugin
- parameterized-trigger  # Parameterized Trigger plugin
- sshd  # SSHD plugin
- blueocean-core-js  # Blue Ocean Core JS plugin
- cron_column  # Cron Column plugin
- javax-activation-api  # javax Activation API plugin
- pipeline-build-step  # Pipeline Build Step plugin
- structs  # Structs plugin
- blueocean-dashboard  # Blue Ocean Dashboard plugin
- dashboard-view  # Dashboard View plugin
- javax-mail-api  # javax Mail API plugin
- pipeline-github-lib  # Pipeline GitHub Libraries plugin
- subversion  # Subversion plugin
- blueocean-display-url  # Blue Ocean Display URL plugin
- display-console-output  # Display Console Output plugin
- jaxb  # JAXB plugin
- pipeline-graph-analysis  # Pipeline Graph Analysis plugin
- timestamper  # Timestamper plugin
- blueocean-events  # Blue Ocean Events plugin
- display-url-api  # Display URL API plugin
- jdk-tool  # JDK Tool plugin
- pipeline-groovy-lib  # Pipeline Groovy Libraries plugin
- token-macro  # Token Macro plugin
- blueocean-git-pipeline  # Blue Ocean Git Pipeline plugin
- docker-commons  # Docker Commons plugin
- jenkins-design-language  # Jenkins Design Language plugin
- pipeline-input-step  # Pipeline Input Step plugin
- trilead-api  # Trilead API plugin
- blueocean-github-pipeline  # Blue Ocean GitHub Pipeline plugin
- docker-java-api  # Docker Java API plugin
- jersey2-api  # Jersey 2 API plugin
- pipeline-milestone-step  # Pipeline Milestone Step plugin
- uipath-automation-package  # UiPath Automation Package plugin
- blueocean-i18n  # Blue Ocean Internationalization plugin
- docker-plugin  # Docker plugin
- jjwt-api  # JWT API plugin
- pipeline-model-api  # Pipeline Model API plugin
- uno-choice  # Uno-Choice plugin
- blueocean-jwt  # Blue Ocean JWT plugin
- docker-workflow  # Docker Workflow plugin
- jobConfigHistory  # Job Config History plugin
- pipeline-model-definition  # Pipeline Model Definition plugin
- powershell  # PowerShell plugin
- validating-string-parameter  # Validating String Parameter plugin
- variant  # Variant plugin
- bootstrap5-api  # Bootstrap 5 API plugin
- filesystem-list-parameter-plugin  # Filesystem List Parameter plugin
- kubernetes-credentials  # Kubernetes Credentials plugin
- prism-api  # Prism API plugin
- workflow-aggregator 
