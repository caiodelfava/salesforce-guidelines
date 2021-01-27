# Salesforce

Salesforce Development guidelines.

![Apex Logo](./assets/apex_325x136.png)

## Getting Started

### Prerequisites

* [Salesforce CLI](https://developer.salesforce.com/tools/sfdxcli)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Salesforce Extensions for VS Code](https://developer.salesforce.com/tools/extension_vscode)
* [Java](https://www.youtube.com/watch?v=gR1PujzQ53Q)

### Recomended VS Code Extensions

* [Salesforce Package.xml Generator](https://marketplace.visualstudio.com/items?itemName=VignaeshRamA.sfdx-package-xml-generator)
* [Salesforce CLI Command Builder](https://marketplace.visualstudio.com/items?itemName=VignaeshRamA.sfdx-command-builder)
* [Apex Log Analyzer](https://marketplace.visualstudio.com/items?itemName=financialforce.lana)

### Recomended Browser Extensions

* [Salesforce inspector](https://chrome.google.com/webstore/detail/salesforce-inspector/aodjmnfhjibkcdimpodiifdjnnncaafh)
* [Salesforce UI Improver](https://chrome.google.com/webstore/detail/salesforce-ui-improver/cfihjphppakcdhnkbnjboipgblbjapha)
* [Salesforce Data Exporter](https://chrome.google.com/webstore/detail/salesforce-data-exporter/fimhgbeiaffioifgjfcfjnphifipknao)
* [Copytables](https://chrome.google.com/webstore/detail/copytables/ekdpkppgmlalfkphpibadldikjimijon)
* [EditThisCookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg)

### Recomended Blogs

* [Salesforce Developers Blog](https://developer.salesforce.com/blogs/)
* [Salesforce Architects](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/data_model.htm)
* [Salesforce Apex Hours](https://www.youtube.com/channel/UChTdRj6YfwqhR_WEFepkcJw)
* [SFDC99](https://www.sfdc99.com/)
* [Souforce.cloud](https://souforce.cloud/)
* [SalesforceBen](https://salesforceben.com/)
* [Andy in the Cloud](https://andyinthecloud.com/)
* [SimplySfdc.com](https://www.simplysfdc.com/)
* [Bob Buzzard Blog](http://bobbuzzard.blogspot.com/)
* [Amit Salesforce](http://amitsalesforce.blogspot.com/)
* [Jitendra Zaa](https://www.jitendrazaa.com/blog/)
* [SfdcMonkey.com](https://sfdcmonkey.com/)

## Development

### Documentation

* [Apex Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/)
* [SOQL and SOSL Reference](https://developer.salesforce.com/docs/atlas.en-us.soql_sosl.meta/soql_sosl/)
* [Visualforce Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.pages.meta/pages/)
* [REST API Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)
* [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/)
* [Salesforce Entity-Relationship Diagrams](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/data_model.htm)

### Branching Model: Git Flow

* [Tableless - Gerenciando seus branches com o Git Flow](https://tableless.com.br/git-flow-introducao/)
* [Atlassian - Gitflow Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)

## Deployment

### Documentation

* [Metadata API Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/)
* [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/)

You can use the commands below to deploy metadata against any org.

### Deploying a package

Use the command below to deploy a `package.xml` file and its contents:

```bash
sfdx force:source:deploy --manifest "./manifest/my-package.xml" --testlevel=RunSpecifiedTests --runtests=notests --loglevel fatal
```

### Deploying a single component

Use the command below to deploy a single metadata file to an org from command line using Salesforce CLI.

To just validate a deployment add the `--checkonly` parameter to the command.

```bash
sfdx force:source:deploy --sourcepath "./force-app/main/default/flows/A_ProcessBuilder.flow-meta.xml" --testlevel=RunSpecifiedTests     --runtests=notests --loglevel fatal
```
