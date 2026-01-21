# AzureTrainingBySaurav
downeload .net 8 (https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
Install VS Code
(Troubleshooting the Local Catalog
In the next lecture you're going to run the catalog component locally, on your own computer.

In most cases, this goes smoothly without any problem. In some cases, however, there might be some problems, and here are some steps to help you troubleshoot them:



1. If you're on Windows, and when running the code you get the following error in the Output window: Unable to find fallback package folder 'C:\Program Files (x86)\Microsoft\Xamarin\NuGet\ :

There's a problem in the NuGet package manager configuration. Please run the following steps, and this should resolve the problem:

    - Remove the nuget.config file from the %appdata%\NuGet folder

    - Restart VS Code

    - Run the project, and it should work fine.)
Remove spending limit:
    https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/spending-limit#remove-the-spending-limit-in-azure-portal
    
   ARM template deployment command
===============================
az deployment group create --resource-group optimized-vm-rg --template-file template.json --parameters parameters.json
==================================
IMDS Links
==========
http://169.254.169.254/metadata/instance?api-version=2021-12-13

http://169.254.169.254/metadata/scheduledevents?api-version=2020-07-01
open catlog folder and in the command type (dotnet publish -o publish) when you run this publish folder is created after that go to file exploral for the folder and copy all things from the publish folder

