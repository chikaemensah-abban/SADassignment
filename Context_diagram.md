Context diagram



\# Domain Context Mapping



\## Context Diagram



```mermaid

flowchart LR

&#x20;   PM\["Patient Management<br/><br/>Primary Entities:<br/>Patient<br/>Appointment<br/>Patient Record"]



&#x20;   BI\["Billing \& Insurance Claims<br/><br/>Primary Entities:<br/>Invoice<br/>Insurance Claim<br/>Payment"]



&#x20;   LD\["Lab Test Diagnostics<br/><br/>Primary Entities:<br/>Lab Test Order<br/>Test Result<br/>Lab Report"]



&#x20;   PM -->|"Patient and appointment information"| BI

&#x20;   PM -->|"Patient and test request information"| LD

&#x20;   LD -->|"Test results"| PM

&#x20;   BI -->|"Billing and claim status"| PM





* **Patient Management** 

&#x20;Patient

&#x20;Appointment

&#x20;Patient Record

* **Billing \& Insurance Claims** 

&#x20;Invoice

&#x20;Insurance Claim 

&#x20;Payment

* **Lab Test Diagnostics** 

&#x20;Lab Test Order

&#x20;Test Result

&#x20;Lab Report

