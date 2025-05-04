# Power-BI-Report-Generator-Bot

Power BI Report Generator Bot is a Python-based automation tool that streamlines the generation of Power BI reports by dynamically binding .pbit (Power BI template) files with user-provided CSV data sources. It significantly reduces manual effort in repetitive report creation, making it ideal for scenarios where multiple datasets need to be visualized using a consistent report structure.

The tool features an intuitive GUI built with Tkinter, enabling users to:
1.Upload CSV files as data inputs
2.Trigger the automated generation of .pbix report files
3.Optionally launch Power BI Desktop with auto-refresh enabled

Key Features
1.Template-Based Automation: Binds CSV data with a predefined .pbit template to generate .pbix reports.
2.User-Friendly Interface: No command-line use required—interact through a clean desktop GUI.
3.Auto-Refresh Support: Option to open generated reports in Power BI Desktop with data auto-refresh enabled.
4.Real-Time Status Logging: Displays logs to track generation progress.

Use Cases
This tool is flexible and can be used for:
1.Generating recurring reports with different datasets
2.Automating BI workflows across teams
3.Visualizing data in domains like Finance and Accounting,Sales and Marketing,Healthcare and Clinical Metrics,etc.

Note:
To use this tool, you must first manually create a Power BI .pbit template with the desired layout and visuals. This template is then reused to generate reports automatically for different datasets.
