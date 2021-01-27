# Salesforce

Salesforce Development guidelines.

![Apex Logo](./assets/apex_325x136.png)

## Getting Started

### Prerequisites

* [Salesforce CLI](https://developer.salesforce.com/tools/sfdxcli)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Salesforce Extensions for VS Code](https://developer.salesforce.com/tools/extension_vscode)

### Branching Model: Git Flow

* [Tableless - Gerenciando seus branches com o Git Flow](https://tableless.com.br/git-flow-introducao/)
* [Atlassian - Gitflow Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)

## Deployment

You can use the commands below to deploy metadata against any org.

### Deploying a single component

Use the command below to deploy a single metadata file to an org from command line using Salesforce CLI.

To test a deploy, add the `--checkonly` parameter to the command.


```bash
sfdx force:source:deploy --sourcepath "./force-app/main/default/flows/A_ProcessBuilder.flow-meta.xml" --testlevel=RunSpecifiedTests --runtests=notests --loglevel fatal
```

### Deploying a package

Use the command below to deploy a `package.xml` file and its contents:

```bash
sfdx force:source:deploy --manifest "./manifest/package-myFeature.xml" --testlevel=RunSpecifiedTests --runtests=notests --loglevel fatal
```
