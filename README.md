# ClearSharePointCache
Clearing SharePoint Cache using PowerShell Script
This documentation provides step-by-step instructions on how to clear the SharePoint cache using a PowerShell script. Clearing the cache can help resolve issues related to outdated or corrupt cache files, improving SharePoint performance and resolving certain functionality problems.
Prerequisites:
1.	SharePoint farm administrator access.
2.	SharePoint Management Shell installed on the server where the script will be executed.
Execution:
1.	Please download SPCacheCleaner.ps1 file.
2.	Open SharePoint Management Shell with administrative privileges.
3.	Now open downloaded file.
4.	Execute the script .
5.	The script will execute the specified commands to clear the SharePoint cache.
6.	Monitor the PowerShell console for any errors or messages related to the cache clearing process. Once the script execution is complete, you should see a confirmation message.
Additional Considerations:
•	It is recommended to perform cache clearing during scheduled maintenance windows or non-peak hours to minimize any potential impact on SharePoint users.
•	Clearing the SharePoint cache may temporarily affect performance as cache files are regenerated. Users might experience slower page loads or delays until the cache is fully rebuilt.
•	It is a best practice to take a backup of the SharePoint farm before performing any maintenance tasks, including cache clearing.
