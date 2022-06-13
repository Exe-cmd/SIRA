## Welcome to the SIRA Project

SIRA is an open source SOAR, Case management and Threat intel Platform all in one.

Sira acts as an agent between your Ticketing System, SIEM, Wiki, EDR, IDS, Firewall, and many more using your own scripts to automate and integrate your SOC. 

### How to get started!
Clone the SIRA repository to your linux box. 

Run the python Webserver
```markdown
python3 -m http.server --directory /home/kali/SIRA
```
Access the Sira on port 8000/SIRA.html
```markdown
http://127.0.0.1:8000/SIRA.html
```
### SIRA Project
Sira Alerts serve as single pane of glass for all of your security tools. Sira automates the way you turn alerts into tickets for task management and then into incidents for reporting. 
![Sira Alerts](/SIRA/docs/assets/SIRAalerts.png)
Sira's Ticketing view allows alerts to be enriched in real time. This automation will take save valuable time in Incident Response scenarios.
![Sira Tickets](/SIRA/docs/assets/SIRAtickets.png)
Automate is the core SOAR function of Sira. Automate runs the way Sira interacts with Threat Intel, integrates Sira Alerts/Tickets/Incidents and controls the way Sira automates Incident Response.
![Sira Automate](/SIRA/docs/assets/SIRAautomate.png)
Intelligence ingests threat information from reliable resources. Intelligence then enriches, indexes and categorise the data to produce the most high fidelity feeds to be circulated out to your security tools.
![Sira Intel](/SIRA/docs/assets/SIRAintel.png)
Sira supports SSO, SAML, LDAP, 2FA, API integrations, Third-Party Plugins/Integrations, proxy compatiblae, and most importantly... Dark Mode!
![Sira Settings](/SIRA/docs/assets/SIRAsettings.png)































