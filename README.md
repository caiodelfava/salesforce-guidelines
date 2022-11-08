# Salesforce Development Guidelines

![Apex Logo](./assets/apex_325x136.png)

## Getting Started

### Documentation

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)

### Prerequisites

- [Salesforce CLI](https://developer.salesforce.com/tools/sfdxcli)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Salesforce Extensions for VS Code](https://developer.salesforce.com/tools/extension_vscode)
- [Java 11](https://www.youtube.com/watch?v=gR1PujzQ53Q) ([Oracle](https://www.oracle.com/br/java/technologies/javase/jdk11-archive-downloads.html), [OpenJDK](https://openjdk.org/install/) or [Zulu](https://www.azul.com/downloads/?version=java-11-lts&package=jdk) (required for Data Loader))
- [Node.js](https://nodejs.org/en/download/) (active LTS version)
- [Prophet Debugger](https://marketplace.visualstudio.com/items?itemName=SqrTT.prophet)

### Recomended Setup

- [Salesforce Data Loader](https://login.salesforce.com/lightning/setup/DataLoader/home)
- [Git](https://git-scm.com/downloads)
- [Chocolatey](https://chocolatey.org/install) (for Windows users)

### Recomended VS Code Extensions

- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)
- [Salesforce Extension Pack (Expanded)](https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode-expanded)
- [Apex PMD](https://marketplace.visualstudio.com/items?itemName=chuckjonas.apex-pmd)
- [Apex Log Analyzer](https://marketplace.visualstudio.com/items?itemName=financialforce.lana)
- [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)
- [Salesforce Package.xml Generator](https://marketplace.visualstudio.com/items?itemName=VignaeshRamA.sfdx-package-xml-generator)
- [Salesforce CLI Command Builder](https://marketplace.visualstudio.com/items?itemName=VignaeshRamA.sfdx-command-builder)
- [Salesforce Reference](https://marketplace.visualstudio.com/items?itemName=Oblongmana.vscode-salesforce-doc-lookup)
- [Salesforce Documenter](https://marketplace.visualstudio.com/items?itemName=HugoOM.sfdx-autoheader)
- [Salesforce Commerce Cloud Productivity Pack](https://marketplace.visualstudio.com/items?itemName=gkkirilov.salesforce-commerce-cloud-productivity-pack)

### Recomended Browser Extensions

- [Salesforce inspector](https://chrome.google.com/webstore/detail/salesforce-inspector/aodjmnfhjibkcdimpodiifdjnnncaafh)
- [Salesforce UI Improver](https://chrome.google.com/webstore/detail/salesforce-ui-improver/cfihjphppakcdhnkbnjboipgblbjapha)
- [Demandware With Ease](https://chrome.google.com/webstore/detail/demandware-with-ease/ffhabonelknmejmdnekedmijlhebpcio)
- [Google Translate](https://chrome.google.com/webstore/detail/google-translate/aapbdbdomjkkjkaonfhkkikfgjllcleb)
- [Session Buddy](https://chrome.google.com/webstore/detail/session-buddy/edacconmaakjimmfgnblocblbcdcpbko)
- [Raindrop.io](https://chrome.google.com/webstore/detail/raindropio/ldgfbffkinooeloadekpmfoklnobpien)
- [Copytables](https://chrome.google.com/webstore/detail/copytables/ekdpkppgmlalfkphpibadldikjimijon)
- [EditThisCookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg)
- [Mobile View Switcher](https://chrome.google.com/webstore/detail/mobile-view-switcher/bmhfelbhbkeoldaiphchjibggnoodpcj)
- [Validity](https://chrome.google.com/webstore/detail/validity/bbicmjjbohdfglopkidebfccilipgeif)
- [Wappalyzer](https://chrome.google.com/webstore/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg)
- [Print Friendly & PDF](https://chrome.google.com/webstore/detail/print-friendly-pdf/ohlencieiipommannpdfcmfdpjjmeolj)

### Recomended Blogs

- [Salesforce Developers Blog](https://developer.salesforce.com/blogs/)
- [Salesforce Architects](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/data_model.htm)
- [Salesforce Apex Hours](https://www.youtube.com/channel/UChTdRj6YfwqhR_WEFepkcJw)
- [SFDC99](https://www.sfdc99.com/)
- [Souforce.cloud](https://souforce.cloud/)
- [SalesforceBen](https://salesforceben.com/)
- [Andy in the Cloud](https://andyinthecloud.com/)
- [SimplySfdc.com](https://www.simplysfdc.com/)
- [Bob Buzzard Blog](http://bobbuzzard.blogspot.com/)
- [Amit Salesforce](http://amitsalesforce.blogspot.com/)
- [Jitendra Zaa](https://www.jitendrazaa.com/blog/)
- [SfdcMonkey.com](https://sfdcmonkey.com/)

## Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Development

### Documentation

- [Apex Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/)
- [SOQL and SOSL Reference](https://developer.salesforce.com/docs/atlas.en-us.soql_sosl.meta/soql_sosl/)
- [Visualforce Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.pages.meta/pages/)
- [REST API Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/)
- [Salesforce Entity-Relationship Diagrams](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/data_model.htm)

### Branching Model: Git Flow

- [Tableless - Gerenciando seus branches com o Git Flow](https://tableless.com.br/git-flow-introducao/)
- [Atlassian - Gitflow Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)

## Deployment

### Documentation

- [Metadata API Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/)

### How Do You Plan to Deploy Your Changes?

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

You can also use the commands below to deploy metadata against any org.

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
