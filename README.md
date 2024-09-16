# BusinessOps
Business Ops is a single tool for installing and managing all of your favorite [External Tools](https://docs.microsoft.com/en-us/power-bi/create-reports/desktop-external-tools) for Power BI Desktop.

# Download
To download the latest copy of Business Ops, please visit [PowerBI.tips - Business Ops](https://powerbi.tips/product/business-ops-beta/).

# Installing External Tools with Business Ops
To install External Tools for use in Power BI Desktop, follow these instructions:
1. Open Business Ops (if not already installed, install first, then open)
2. In the left navigation pane, click on the tab named **External Tools**
3. In the list of External Tools on the page, find the External Tools you wish to install
4. Click the blue **Add** button next to each External Tool that you wish to install
> **Note:** If the External Tool you wish to install has a yellow **Download** button, you must click that first, wait for the download to complete, and then click the blue **Add** button

# Launching External Tools in Standalone Mode
In most cases, External Tools should be launched from the External Tools ribbon in Power BI Desktop, as this allows Power BI Desktop to pass information about the file you're currently working on to the External Tool, such as the connection string for the SSAS Tabular model. But sometimes, you may want to launch an External Tool in Standalone Mode, such as when you're using DAX Studio or Tabular Editor to connect directly to a semantic model that is published in the Power BI service. To launch an External Tool in Standalone Mode, follow these instructions:
1. Open Business Ops
2. In the left navigation pane, click on the tab named **External Tools**
3. Find the External Tool you wish to launch, and then click the dark gray **Open in New Window** symbol next to it.
4. [Optional] Once the External Tool is running, you can right-click on its icon in your taskbar, and select "Pin to Taskbar" or "Pin to Start," and this will allow you to launch that External Tool in Standalone Mode without having to open Business Ops first.
> **Note:** The **Open in New Window** symbol will only appear next to External Tools which support Standalone Mode.

# Removing External Tools with Business Ops
To remove External Tools from Power BI Desktop, follow these instructions:
1. Open Business Ops
2. In the left navigation pane, click on the tab named **External Tools**
3. **Click** on the black **Remove** button next to the External Tool that you wish to remove
> **Note:** If Power BI Desktop is already running, then you must close and re-open Power BI Desktop before the change will take effect

# Manually removing External Tools from Power BI Desktop
To manually remove External Tools from Power BI Desktop, follow these instructions:
1. Navigate to the following directory on your PC
```
C:\Program Files (x86)\Common Files\Microsoft Shared\Power BI Desktop\External Tools
```
2. Within in this folder, you will see a number of JSON files. Files which start with a number (e.g., `091-dax-beautifier.pbitool.json`) were installed by Business Ops.
3. Select the files you wish to remove, and delete them.
> **Note:** If Power BI Desktop is already running, then you must close and re-open Power BI Desktop before the change will take effect.

# Version History
- **2024-09-16** version 3.1.5 - Fix: Removed DAX.do and DAX.guide as they are not rendering in the app
- **2024-06-21** version 3.1.4 - Added: On-demand installation and updates support for Measure Killer and PBI Inpector
- **2023-06-27** version 3.1.3 - New feature: On-demand installation & updates via GitHub Releases API (DAX Studio, Tabular Editor 2 & 3, Bravo, and Report Analyzer)
- **2021-10-04** version 2.0.2 - Bug fixes for external tools file path location changes
- **2021-09-12** version 2.0.1 - Major update, moved location of installed external tools in to program files directory
- **2020-11-21** version 0.0.11 - Update to Dax Beautifier, Open in Excel
- **2020-09-26** version 0.0.10 - Bug fixes for Hot Swap tool
- **2020-09-22** version 0.0.9 - Add, Open in Tableau, Report Builder, SQL Profiler, DAX Beautifier, Open in Excel, Version Checking
- **2020-08-13** version 0.0.8 - Initial Release
