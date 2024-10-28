# Cyber Security Assessment utilizing NIST Cybersecurity framework (CSF) 2.0

## Introduction

For this project I was tasked with analyzing an Organization's ('Oscorp') cybersecurity status and designing a comprehensive cybersecurity program utilizing the NIST CSF 2.0 to uplift Oscorp's security posture. I was given a 'current status' report, much like one that would be compiled after initial investigations and interviews with employees and stakeholders. Using the NIST CSF, I conducted a pass/fail assesment and presented recommendations for improvement. I decided to start with a short presentation to stakeholders to explain the framework and roadmap and ended with presenting them with a comprehensive list of recomendations and procedures to be implemented.

## CSF Core Functions
The CSF Core Functions — GOVERN, IDENTIFY, PROTECT, DETECT, RESPOND, and RECOVER — organize cybersecurity outcomes at their highest level.

| Core Functions  | Description
| --------------- | -----
| Govern          | The organization’s cybersecurity risk management strategy, expectations, and policy are established, communicated, and monitored.
| Identify        | The organization’s current cybersecurity risks are understood.
| Protect         | Safeguards to manage the organization’s cybersecurity risks are used.
| Detect          | Possible cybersecurity attacks and compromises are found and analyzed.
| Respond         | Actions regarding a detected cybersecurity incident are taken.
| Recover         | Assets and operations affected by a cybersecurity incident are restored.


The rigor of an organization’s cybersecurity risk governance and management practices can be categorized according to a table of tiers as outlined in CSF 2.0 Profiles and Tiers. (See Fig. 1)

![image](https://github.com/user-attachments/assets/60704a33-4b7f-4925-8eef-4084d5fa484c)

A Current Profile specifies the Core outcomes that an organization is currently achieving (or attempting to achieve) and characterizes how or to what extent each outcome is being achieved. 
Oscorp’s current profile is identified as Tier 1: Partial.
|Tier           | Cybersecurity Risk Governance      | Cybersecurity Risk Management
|---------------|------------------------------------|------------------------------
|Tier 1: Partial | Application of the organizational cybersecurity risk strategy is managed in an ad hoc manner. Prioritization is ad hoc and not formally based on objectives or threat environment. | There is limited awareness of cybersecurity risks at the organizational level. The organization implements cybersecurity risk management on an irregular, case-by-case basis. The organization may not have processes that enable cybersecurity information to be shared within the organization. The organization is generally unaware of the cybersecurity risks associated with its suppliers and the products and services it acquires and uses. 
 
A Target Profile specifies the desired outcomes that an organization has selected and prioritized for achieving its cybersecurity risk management objectives. It considers anticipated changes to the organization’s cybersecurity posture, such as new requirements, new technology adoption, and threat intelligence trends. Target profile for Oscorp: Tier 4:

|Tier           | Cybersecurity Risk Governance                                                    | Cybersecurity Risk Management
|---------------|----------------------------------------------------------------------------------|------------------------------
|Tier 4: Adaptive | There is an organization-wide approach to managing cybersecurity risks that uses risk-informed policies, processes, and procedures to address potential cybersecurity events. The relationship between cybersecurity risks and organizational objectives is clearly understood and considered when making decisions. Executives monitor cybersecurity risks in the same context as financial and other organizational risks. The organizational budget is based on an understanding of the current and predicted risk environment and risk tolerance. Business units implement executive vision and analyze system-level risks in the context of the organizational risk tolerances. Cybersecurity risk management is part of the organizational culture. It evolves from an awareness of previous activities and continuous awareness of activities on organizational systems and networks. The organization can quickly and efficiently account for changes to business/mission objectives in how risk is approached and communicated. | The organization adapts its cybersecurity practices based on previous and current cybersecurity activities, including lessons learned and predictive indicators. Through a process of continuous improvement that incorporates advanced cybersecurity technologies and practices, the organization actively adapts to a changing technological landscape and responds in a timely and effective manner to evolving, sophisticated threats. The organization uses real-time or near real-time information to understand and consistently act upon the cybersecurity risks associated with its suppliers and the products and services it acquires and uses. Cybersecurity information is constantly shared throughout the organization and with authorized third parties.

At all times the question should be asked whether data is kept Confidential, its Integrity is upheld, and is readily Available and what risks and vulnerabilities present a danger to this ‘CIA Triad’. 

![image](https://github.com/user-attachments/assets/5b8e35de-2c04-4de8-a82c-bb526a3f6f5c)

Utilizing CSF Core functions as a guide, an assessment of Oscorp identified many deficiencies. Recommendations will be provided after each subcategory. 

## IDENTIFY

![Screenshot 2024-10-27 205100](https://github.com/user-attachments/assets/586dd539-f042-4bea-b9d2-290b8e445571)
![Screenshot 2024-10-27 205255](https://github.com/user-attachments/assets/c0c4e42a-7736-48b1-ac59-92604fef17ca)
Asset Management:
-	Physical devices and systems within the organization ARE properly inventoried, HOWEVER no IP address identified. No access agents identified. This prohibits a vulnerability scanner from authenticating and accessing the device and limits the scope of the scanner.
-	External information systems are NOT properly catalogued. Although third-party contracts are being tracked, there is no third-party risk management or IT involvement.
-	Resources (e.g., hardware, devices, data and software) are NOT prioritized based on their classification, criticality and business value. There is no asset classification process based in sensitivity and criticality.
-	Cybersecurity roles and responsibilities for the entire workforce and third-party stakeholders (e.g., suppliers, customers, partners) are NOT established.

A vulnerability management policy needs to be implemented. Vulnerabilities need to be classified and prioritized. It is recommended an access agent is installed on all permanent and non-permanent network connected devices in order to authenticate the scan. Utilizing an access agent in conjunction with a vulnerability scanner will greatly improve the scope of the scans. 
Third-party risk management policy needs to be implemented and IT department needs third-party service provider involvement.
Assets need to be labeled with a sensitivity or criticality classification determined by the Maximum Tolerable Outage matrix. See figure below for example.
![image](https://github.com/user-attachments/assets/0fd3f160-1f11-4da1-a781-d0837b1115c7)
(RPO=recovery point objective, RTO=recovery time objective, WRT=working recovery time)
Cybersecurity roles and responsibilities for the entire workforce and third-party stakeholders (e.g., suppliers, customers, partners) need to be established and implemented.

Business Environment:
-	The organization’s role in the supply chain is NOT identified and communicated.

The organization needs clear documentation outlining their role within their own supply chain when it comes to cyber security. Mapping of third-party suppliers, classifying suppliers based on criticality and sensitivity. 

Governance:
-	Organizational information security policy is NOT established.
-	Information security roles and responsibilities are NOT coordinated and aligned with internal roles and external partners. No security roles and policies have been documented and communicated.
-	Legal and regulatory requirements regarding cybersecurity, including privacy and civil liberties obligations, are NOT understood and managed. No legal and regulatory responsibilities have been documented.
-	Governance and risk management processes DO NOT address cybersecurity risk. There is no process or oversight implemented to manage cyber security risk.

A formal Cyber and Information Security policy needs to be established.
Information security, legal and regulatory roles and responsibilities need to be outlined, documented and communicated with internal and external stakeholders.
A comprehensive set of processes and procedures to manage cyber security risks need to be established with direct board member oversight of security issues.

Risk Assessment and Risk Management Strategy:
-	Asset vulnerabilities are NOT identified and documented. Scans are merely conducted ad-hoc without regularity. No established procedures for analysis and documentation.
-	Threat and vulnerability information is NOT received from information sharing forums and sources. 
-	Threats, both internal and external, are NOT identified and documented.
-	Potential business impacts and likelihoods are NOT identified.
-	Threats, vulnerabilities, likelihoods and impacts are NOT used to determine risk.
-	Risk responses are NOT identified and prioritized.
-	Risk management processes are NOT established, managed and agreed to by organizational stakeholders.
-	Organizational risk tolerance is undetermined and NOT clearly expressed.

A full-scale Cyber Security Risk Management policy needs to be implemented utilizing the OWASP (Open Worldwide Application Security Project) secure design principles. Use of NIST 800-53v3 implemented to test and verify the policy. Complete a document that outlines strategies for managing potential risks that could impact the organization. Utilizing a Risk Matrix to establish risk tolerance and priority. Tangible and non-tangible asset identification and categorization. 

![Screenshot 2024-09-06 155149](https://github.com/user-attachments/assets/88309da8-792e-4e3d-a6ed-d7c293cfc655)
