# MICROSOFT SENTINEL MITRE ATT&CK CAMPAIGNS WORKBOOK

This workbook helps you assess your Microsoft Sentinel Analytics Detection coverage against an ATT&CK Campaign.Furthermore, this tool enables defenders to continue aligning their Sentinel day-to-day SOC operations to the MITRE ATT&CK framework.

<p align="center">
<img src="Static/CampaignsWorkbook.png?raw=true" alt="logo" style="width:1400px"></a>
</p>

First you need to create a watchlist containing your Microsoft Sentinel Analytics Coverage. In order to do that, export the Analytics table from the deployed workbook and use the script <strong>Coverage2CSV.py</strong> to create a CSV file containing the techniques coveraged by your sentinel analytics rules. Use that csv file to create a watchlist. Name it coverage. 

Then, create 2 watchlists using the 2 other csv files: <strong>CampaignsTTPs.csv</strong> and <strong>TechniquesV12.csv</strong>. Name the watchlists <strong>ATTACKcampaignsTTP</strong> and <strong>TechniquesV12</strong>. 

Now you can evaluate your Microsoft Sentinel Analytics coverage against the different Campaigns

<p align="center">
<img src="Static/screen.png?raw=true" alt="logo" style="width:1400px"></a>
</p>
<p align="center">
<img src="Static/screen2.png?raw=true" alt="logo" style="width:1400px"></a>
</p>
<p align="center">
<img src="Static/screen3.png?raw=true" alt="logo" style="width:1400px"></a>
</p>
