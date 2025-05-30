

---

## Security Projects

<img src="images/cybersecurity-design.jpg?raw=true" width=250 height=300/>

---

### Validation of encryption algo's in use

Checking the current set of communication encryption algorithms in use (Data in Transit) as well as the encryption status of disk volumes (Data at Rest). Finally to compare compliance of the encryption algos in use to the published company standard and generating exception based reporting in PowerBI dashboard

[View on github](https://rengro46.github.io/encryption-algos/)

---

### Remediation of Aged Vulnerabilties

Investigate the reasons for aged (>60days) vulnerabilities to still exist, identify the reasons for these vuilnerabilities to still exist, and compile a remediation plan for those addressable with priorities and categorisations

[View on github](https://rengro46.github.io/aged-vulnerabilities/)

---

## Platform Architecture Projects

<img src="images/platform-architecture.jpg?raw=true" width=250 height=300/>

---

### Company Software Asset Portfolio review

Consolidation and remediation of company outdated software asset portfolio and the automation of future inventory updates

[View on github](https://rengro46.github.io/software-review/)

---

###  Design & deployment of asset service record review system for Managed Services clients

Using the current asset management system inventory databases (SCCM, AD, MDM, Intune, Solarwinds etc.) to populate the Service Record Review DataLake, which is then used to compare asset info in ServiceNow for Warranty status, incidents & service requests logged over past 12 months to determine the continued use or replacement status of equipment 

[View on github](https://rengro46.github.io/CMS/)

---

### Service Delivery Platform integration standardisation

Creating an API standard to be used by the business for all future System platform integration efforts. Previous efforts have resulted in myn one=to-one integrations being performed which inevitably led to duplication of effort and reduced security, due to the lack of prescribed security standards for the integration efforts. Using Microsoft's APIM standard, it was now possible to apply standards and a unified method using API endpoints and RBAC for enforcing strict permission based access across multiple systems.

[View on github](https://rengro46.github.io/APIM/)

---

## Product Manager Projects

<img src="images/product-management.png?raw=true" width=450 height=300/>

---

### Amazon Connect omnichannel client

Amazon Connect is a cloud-based contact center service designed to provide seamless customer interactions across multiple channels. This project aims to develop a custom omnichannel client that integrates voice, chat, email, and a ServiceNow feed into a single unified interface, enhancing agent productivity and improving customer experience.

[View on github](https://rengro46.github.io/omnichannel-client/)

---

### Voice Quality Monitoring

The creation of a voice quality monitoring system to track and report on real time quality metrics for Voice traffic on Managed Customer Call Centre environments and assit Voice Engineers to perform early detection and remediation of any Voice traffic anomalies

[View on github](https://rengro46.github.io/voice-quality/)

---

### SAP Account consolidation across all customer SAP instances

The development of a web portal to create a consolidated view of user accounts across all customer SAP instances to aid in the timely removal of accounts where access is no longer required for a user to a specific SAP instance

[View on github](https://rengro46.github.io/SAP-accounts/)

---

### Pro-forma invoice to initiate client's monthly order creation process 

Web Portal System for the automated creation of a pro-forma invoice by extracting info via client's Service Management API, using a Python Panda to consolidate info regarding service requests and monthly fixed billing line items onto the resulting PDF document which is then uploaded to client's billing system for validation and ingestion. 

[View on github](https://rengro46.github.io/proforma-invoice/)


---

### Post Incident Closure - Customer Satisfaction Survey

Creation of an automated mailer sytem to initate a measurement of customer satisfaction after the closure of an incident on Service Now. The client would receive an email pertaining to the closed incident and request the client to click on either a happy or sad face icon embedded in the email message. These icons were in turn linked back to an api endpoints which would then record status and save to a database. The database used for status records would be used to auto trigger escalation processes to the appropriate client's Service Delivery Manager/Client Services Manager for any sad responses returned. 

[View on github](https://rengro46.github.io/CSS/)

---

<p style="font-size:11px"></p>
<!-- Remove above link if you don't want to attibute -->
