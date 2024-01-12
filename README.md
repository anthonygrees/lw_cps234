# Lacework Compliance Assessment APRA CPS234
A beta Lacework compliance assessment for APRA CPS234.  The Assessment maps to broader categories that align with key aspects of cybersecurity:  
- `Access Control and Identity Management`: This involves measures that ensure only authorized users can access systems and data.  
- `Infrastructure and Network Security`: This includes practices that protect the physical and virtual aspects of IT infrastructure.  
- `Data Protection and Privacy`: This category focuses on safeguarding data from unauthorized access and ensuring privacy compliance.  
- `Incident Response and Monitoring`: This involves detecting, responding to, and monitoring security events.  
- `Governance, Risk, and Compliance (GRC)`: This encompasses practices related to policies, training, and compliance with legal and regulatory requirements.  
  
  
### 1. Configure Lacework API with Postman
This topic helps you get started with the Lacework API. It describes how to set up your API keys in the Lacework Console and then guides you through a few simple API calls using Postman.  
https://docs.lacework.net/api/postman-api-quickstart

  
### 2. Add the Compliance Assessment to Lacework
Use the Lacework API and create a report definition by invoking the following endpoint:
  
```bash
POST https://YourLacework.lacework.net/api/v2/ReportDefinitions
```
and pass in the JSON assessment for CPS234.  

![Lacework Agent](/images/postman.png)
  
### 3. View the Assessment in Lacework
Once the policies have run in Lacework the Assessment will show including the report.  

![Lacework Agent](/images/cps234.png)
  
