# BusinessOps
Business Ops is the tool for adding all your extra [External Tools](https://docs.microsoft.com/en-us/power-bi/create-reports/desktop-external-tools) extensions for Power BI Desktop.

# Download
If you would like to download the latest copy of Business Ops please visit [PowerBI.tips - Business Ops](https://powerbi.tips/product/business-ops-beta/).

# Remove External Tools Using Business Ops
To remove external tools from Power BI desktop you can now do so directly in Business Ops.
1. Open Business Ops
1. On the left pane navigate to the tab named **Edit External Tools**
1. Towards the bottom of the window there will be a list of installed External Tools
1. **Click** on the **Trash Can** icon next to the tool that you wish to remove
> **Note:** Your external tool will be removed. To see this change in Power BI Desktop you must close Power BI Desktop and then reopen the application.

# Uninstall External Tools From Power BI Desktop
To un-install tools from Power BI desktop ribbon. 
Navigate in to the following directory on your PC
```
C:\Program Files (x86)\Common Files\Microsoft Shared\Power BI Desktop\External Tools
```
Within in this folder you will see a number of JSON files. All the files which start with a number such as
```
091-dax-beautifier.pbitool.json
```
were created by Business Ops installer.  
Select the files you wish to remove and delete them.  This will remove them from Power BI Desktop

`Important: You will need to restart power bi desktop to see the changes after the file has been deleted.`

# Version History
- **2021-09-12** version 2.0.1 - Major update, moved location of installed external tools in to program files directory
- **2020-11-21** version 0.0.11 - Update to Dax Beautifier, Open in Excel
- **2020-09-26** version 0.0.10 - Bug fixes for Hot Swap tool
- **2020-09-22** version 0.0.9 - Add, Open in Tableau, Report Builder, SQL Profiler, DAX Beautifier, Open in Excel, Version Checking
- **2020-08-13** version 0.0.8 - Initial Release