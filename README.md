# vsts-privatebuildagent-azure

## Motivation
We had some problems with using Hosted VSTS Agents. More specifically, we had long building times and the free 240 build minutes where not enough anymore. Thats we started to do research about good work arounds. Ultimately, we have come to private agents with whom we have recently had very good experiences.

Now we would like to **share** our insights with you.

 
## Screenshots
Include logo/demo screenshot etc.

## Tech/framework used
<b>Built with</b>
- [Chocolatey](https://chocolatey.org/)
- [Azure Ressource Manager Template](https://azure.microsoft.com/de-de/features/resource-manager/)
- [PowerShell](https://powershell.org/)

## Features
Use this repository as Infrastructure as a Code to deploy a VM containing a VSTS private Agent into your Azure Ressource Group.
Currently we offer:
 - A windows based version to build and release .NET Core and Node.js projects

## Installation
You can use the [Deploy-AzureResourceGroup](..\windows_based\Deploy-AzureResourceGroup.ps1) to deploy our solution into Azure.

Or you can use our Azure Marketplace offer and configure your vsts agent via a user interface.

MIT © 2018 [white duck Gesellschaft für Softwareentwicklung GmbH](https://whiteducksoftware.com/)
