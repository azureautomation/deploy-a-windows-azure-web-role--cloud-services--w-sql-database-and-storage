Deploy a Windows Azure Web Role (Cloud Services) w/ SQL Database and Storage
============================================================================

            

[Windows Azure Scripting Center](http://www.windowsazure.com/en-us/documentation/scripts) |
[Get Started with Windows Azure PowerShell](http://go.microsoft.com/fwlink/?linkid=320929&clcid=0x409) |
[Windows Azure Web Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=web&service=all)

Description

This sample script demonstrates how to deploy a .NET corporate site into a Cloud Service with SQL Database and Storage Account.


During the process, it will create a Storage Account, SQL Database, and Cloud Service and change the configuration file (*.cscfg) of the project.


At the end of the script it starts the browser and shows the site. The sample package has a Web site that checks the Azure SQL and Storage connection

Example
 
Scenario
You want to take a Package (*.cspkg) and config file (*.cscfg) to create a corporate site on Web Role with a Windows Azure SQL Database and Storage Account.
Requirements

  *  PowerShell Version 3.0 
  *  Windows Azure PowerShell 0.6.18 
See Also

  *  [ServiceConfiguration.Cloud.cscfg](https://github.com/WindowsAzure/azure-sdk-tools-samples/blob/master/solutions/web/EnterpiseSite/ServiceConfiguration.Cloud.cscfg)

  *  [WebCorpHolaMundo.Azure.cspkg](https://github.com/WindowsAzure/azure-sdk-tools-samples/blob/master/solutions/web/EnterpiseSite/WebCorpHolaMundo.Azure.cspkg)

  *  [Windows Azure Web Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=web&service=all)

Script Content

The content of the script is reproduced below

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
