# Hub-sites-inventory-using-PnP-PowerShell-in-SharePoint-Online
In this script, we can get master inventory for all hub sites and their all associated sites from SharePoint online tenant. PnP PowerShell script to get all sites connected to a hub site:Using PnP PowerShell get all associated or connected sites to a particular hub site.
PnP PowerShell script to get all sites connected to a hub site:
Using PnP PowerShell get all associated or connected sites to a particular hub site.
Get master report for all sites and their hub sites from the SharePoint online tenant.
Prerequities:
Before executing this script we must install PnP PowerShell in the machine where we will execute this script.

For PnP PowerShell installation - we need to execute the below command in the PowerShell command window but need to ensure the Powershell version should be more 3.0.

(New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/sharepoint/PnP-PowerShell/master/Samples/Modules.Install/Install-SharePointPnPPowerShell.ps1')

For detailed installation please refer the below link:

https://global-sharepoint.com/powershell/office365-sharepoint-pnp-powershell-installation/

Paramaters:
 

###################variables section###################################

$userName = "Global-sharepoint2019@globalsharepoint2019.onmicrosoft.com - <Your User name>"

$passWord = "YourPassWord"

$siteURL="https://globalsharepoint2019-admin.sharepoint.com/ <Your sharepoint admin url>"

###################variables section ends here############################

Sample output:

PnP PowerShell script to get all sites connected to hub site: Test:

https://i0.wp.com/global-sharepoint.com/wp-content/uploads/2019/12/PnP-PowerShell-script-to-get-all-sites-connected-to-hub-site.jpg?w=1009&ssl=1

Master report for all hub sites in the SharePoint online tenant:

https://i0.wp.com/global-sharepoint.com/wp-content/uploads/2019/12/PnP-PowerShell-script-to-get-all-sites-connected-to-hub-site2.jpg?w=1001&ssl=1

All associated sites connected to a single hub site report:

https://i0.wp.com/global-sharepoint.com/wp-content/uploads/2019/12/PnP-PowerShell-script-to-get-all-sites-connected-to-hub-site3.jpg?w=1005&ssl=1



