# Microsoft Defender for DevOps demo

This repository is used to demonstrate some of security capabilities of Microsoft Defender for DevOps.

## Use cases

### Secrets exposure

Identify leaked secrets in your repos using, Secret scanning. Those alerts will be reflected in MDfC.

Leaked secret alerts in the GitHub menu:

![Secret alerts](media/leaked_secrets_menu.png)

Alert details for an Azure Storage Account SAS (secret) stored in a config file:

![Azure SAS](media/azure_sas.png)

### Vulnerabilities discovery

Discover vulnarable dependencies using GitHub Dependabot.

Message rceived by the dev while pushing code to the repo:

![VSCode vulnerability](media/vscode_vulnerability_msg.png)

Details of the alert within the GitHub Dependabot menu:

![Dependabot alert](media/dependabot_menu.png)

As potential remediation Dependabot propose to upgrade the dependency verion, in a pull request:

![Dependabot PR](media/dependabot_pr.png)

#
