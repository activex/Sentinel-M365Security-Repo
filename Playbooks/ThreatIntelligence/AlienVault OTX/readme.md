#PB-Auto-TI-AVOTX
author: Marc Reinhardt

**Summary:**
This is a Logic App to import threat indicators from AlienVault into Azure Sentinel using the Graph Security API.

**Current Settings:**
-	Run once a day
-	Indicator Types: domain,email,FileHash-MD5,FileHash-SHA1,FileHash-SHA256,IPv4,URL,URI
-	Add to Sentinel


**Requirements:**
1.	Get an API key from AlienVault: https://otx.alienvault.com/
2.	Create an App  Registration in Azure AD: http://thewindowsupdate.com/2020/02/11/bring-your-threat-intelligence-to-azure-sentinel/
4.	Set the run variables (Tennant ID, Client ID, App Secret, and OTX API Key).

**Credits:***
Andrew Blumhardt - https://azurecloudai.blog/2020/11/19/how-to-connect-alienvault-otx-to-azure-sentinel/ 

**Change Log:***
23/12/2020 - Initial