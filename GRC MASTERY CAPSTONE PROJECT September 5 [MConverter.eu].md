**GRC MASTERY CAPSTONE PROJECT September 5, 2024**

[Oscorp Cyber Security Assessment utilizing NIST Cybersecurity framework
(CSF) 2.0.]{.underline}

The CSF Core Functions --- GOVERN, IDENTIFY, PROTECT, DETECT, RESPOND,
and RECOVER --- organize cybersecurity outcomes at their highest level.

- **GOVERN** The organization's cybersecurity risk management strategy,
  expectations, and policy are established, communicated, and monitored.

- **IDENTIFY** The organization's current cybersecurity risks are
  understood.

- **PROTECT** Safeguards to manage the organization's cybersecurity
  risks are used.

- **DETECT** Possible cybersecurity attacks and compromises are found
  and analyzed.

- **RESPOND** Actions regarding a detected cybersecurity incident are
  taken.

- **RECOVER** Assets and operations affected by a cybersecurity incident
  are restored.

The rigor of an organization's cybersecurity risk governance and
management practices can be categorized according to a table of tiers as
outlined in CSF 2.0 Profiles and Tiers. (See Fig. 1)

![](media/image2.png){width="5.024192913385827in"
height="2.459978127734033in"}

A Current Profile specifies the Core outcomes that an organization is
currently achieving (or attempting to achieve) and characterizes how or
to what extent each outcome is being achieved.

**[Oscorp's current profile is identified as Tier 1:
Partial.]{.underline}**

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 41%" />
<col style="width: 40%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Tier</strong></th>
<th><strong>Cybersecurity Risk Governance</strong></th>
<th><strong>Cybersecurity Risk Management</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Tier 1: Partial</td>
<td><p>Application of the organizational cybersecurity risk strategy is
managed in an ad hoc manner.</p>
<p>Prioritization is ad hoc and not formally based on objectives or
threat environment.</p></td>
<td><p>There is limited awareness of cybersecurity risks at the
organizational level.</p>
<p>The organization implements cybersecurity risk management on an
irregular, case-by-case basis.</p>
<p>The organization may not have processes that enable cybersecurity
information to be shared within the organization.</p>
<p>The organization is generally unaware of the cybersecurity risks
associated with its suppliers and the products and services it acquires
and uses.</p></td>
</tr>
</tbody>
</table>

\*\*\*\*\*\*Tier 2 and 3 synopses omitted for brevity\*\*\*\*\*\*

A Target Profile specifies the desired outcomes that an organization has
selected and prioritized for achieving its cybersecurity risk management
objectives. A Target Profile considers anticipated changes to the
organization's cybersecurity posture, such as new requirements, new
technology adoption, and threat intelligence trends.

**[Oscorp 3-year roadmap security posture Target Profile is Tier 4:
Adaptive.]{.underline}**

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 41%" />
<col style="width: 40%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Tier</strong></th>
<th><strong>Cybersecurity Risk Governance</strong></th>
<th><strong>Cybersecurity Risk Management</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Tier 4: Adaptive</td>
<td><p>There is an organization-wide approach to managing cybersecurity
risks that uses risk-informed policies, processes, and procedures to
address potential cybersecurity events. The relationship between
cybersecurity risks and organizational objectives is clearly understood
and considered when making decisions. Executives monitor cybersecurity
risks in the same context as financial and other organizational risks.
The organizational budget is based on an understanding of the current
and predicted risk environment and risk tolerance. Business units
implement executive vision and analyze system-level risks in the context
of the organizational risk tolerances.</p>
<p>Cybersecurity risk management is part of the organizational culture.
It evolves from an awareness of previous activities and continuous
awareness of activities on organizational systems and networks. The
organization can quickly and efficiently account for changes to
business/mission objectives in how risk is approached and
communicated.</p></td>
<td><p>The organization adapts its cybersecurity practices based on
previous and current cybersecurity activities, including lessons learned
and predictive indicators. Through a process of continuous improvement
that incorporates advanced cybersecurity technologies and practices, the
organization actively adapts to a changing technological landscape and
responds in a timely and effective manner to evolving, sophisticated
threats.</p>
<p>The organization uses real-time or near real-time information to
understand and consistently act upon the cybersecurity risks associated
with its suppliers and the products and services it acquires and
uses.</p>
<p>Cybersecurity information is constantly shared throughout the
organization and with authorized third parties.</p></td>
</tr>
</tbody>
</table>

At all times the question should be asked whether data is kept
[Confidential]{.underline}, its [Integrity]{.underline} is upheld, and
is readily [Available]{.underline} and what risks and vulnerabilities
present a danger to this '**CIA Triad**'.

![](media/image3.png){width="2.3157884951881016in"
height="1.7105260279965004in"}

Utilizing CSF Core functions as a guide, an assessment of Oscorp
identified many deficiencies.

![Exclamation mark with solid fill](media/image4.png){width="0.2in"
height="0.2in"}Recommendations will be provided after each subcategory.

**IDENTIFY**

**Asset Management:**

- *Physical devices and systems within the organization ARE properly
  inventoried, HOWEVER no IP address identified.* No access agents
  identified. This prohibits a vulnerability scanner from authenticating
  and accessing the device and limits the scope of the scanner.

- *External information systems are NOT properly catalogued.* Although
  third-party contracts are being tracked, there is no third-party risk
  management or IT involvement.

- *Resources (e.g., hardware, devices, data and software) are NOT
  prioritized based on their classification, criticality and business
  value.* There is no asset classification process based in sensitivity
  and criticality.

- *Cybersecurity roles and responsibilities for the entire workforce and
  third-party stakeholders (e.g., suppliers, customers, partners) are
  NOT established.*

![Exclamation mark with solid fill](media/image4.png){width="0.2in"
height="0.2in"}A vulnerability management policy needs to be
implemented. Vulnerabilities need to be classified and prioritized. It
is recommended an access agent is installed on all permanent and
non-permanent network connected devices in order to authenticate the
scan. Utilizing an access agent in conjunction with a vulnerability
scanner will greatly improve the scope of the scans.  
Third-party risk management policy needs to be implemented and IT
department needs third-party service provider involvement.  
Assets need to be labeled with a sensitivity or criticality
classification determined by the Maximum Tolerable Outage matrix. See
figure below for
example.![](media/image6.png){width="5.228069772528434in"
height="2.5875in"}

(RPO=recovery point objective, RTO=recovery time objective, WRT=working
recovery time)

Cybersecurity roles and responsibilities for the entire workforce and
third-party stakeholders (e.g., suppliers, customers, partners) need to
be established and implemented.

**Business Environment:**

- *The organization's role in the supply chain is NOT identified and
  communicated.*

![Exclamation mark with solid fill](media/image4.png){width="0.2in"
height="0.2in"}The organization needs clear documentation outlining
their role within their own supply chain when it comes to cyber
security. Mapping of third-party suppliers, classifying suppliers based
on criticality and sensitivity.

**Governance:**

- *Organizational information security policy is NOT established.*

- *Information security roles and responsibilities are NOT coordinated
  and aligned with internal roles and external partners.* No security
  roles and policies have been documented and communicated.

- *Legal and regulatory requirements regarding cybersecurity, including
  privacy and civil liberties obligations, are NOT understood and
  managed.* No legal and regulatory responsibilities have been
  documented.

- *Governance and risk management processes DO NOT address cybersecurity
  risk.* There is no process or oversight implemented to manage cyber
  security risk.

![Exclamation mark with solid fill](media/image4.png){width="0.2in"
height="0.2in"}A formal Cyber and Information Security policy needs to
be established.  
Information security, legal and regulatory roles and responsibilities
need to be outlined, documented and communicated with internal and
external stakeholders.  
A comprehensive set of processes and procedures to manage cyber security
risks need to be established with direct board member oversight of
security issues.

**Risk Assessment and Risk Management Strategy:**

- *Asset vulnerabilities are NOT identified and documented.* Scans are
  merely conducted ad-hoc without regularity. No established procedures
  for analysis and documentation.

- *Threat and vulnerability information is NOT received from information
  sharing forums and sources.*

- *Threats, both internal and external, are NOT identified and
  documented.*

- *Potential business impacts and likelihoods are NOT identified.*

- *Threats, vulnerabilities, likelihoods and impacts are NOT used to
  determine risk.*

- *Risk responses are NOT identified and prioritized.*

- *Risk management processes are NOT established, managed and agreed to
  by organizational stakeholders.*

- *Organizational risk tolerance is undetermined and NOT clearly
  expressed.*

![Exclamation mark with solid fill](media/image4.png){width="0.2in"
height="0.2in"}A full-scale Cyber Security Risk Management policy needs
to be implemented utilizing the **OWASP** (Open Worldwide Application
Security Project) secure design principles. Use of NIST 800-53v3
implemented to test and verify the policy. Complete a document that
outlines strategies for managing potential risks that could impact the
organization. Utilizing a **Risk Matrix** to establish risk tolerance
and priority. Tangible and non-tangible asset identification and
categorization.

**PROTECT**

**Access Controls:  
**

- *Identities and credentials are NOT adequately managed for authorized
  devices and users.* No use of Multi-Factor Authentication. No
  specified off-boarding procedures. No periodic access reviews
  established.

- *Physical access to assets is NOT managed and protected.* No verified
  entry/exit logs. No biometrics implemented. No access management
  policy in place.

- *Remote access is NOT adequately managed.* No Two-Factor
  Authentication for VPN.

<!-- -->

- *Access permissions are NOT managed, incorporating the principles of
  least privilege and separation of duties.* No Access management policy
  in place. Least privilege and Separation of Duties implementation
  inadequate.

![Exclamation mark with solid fill](media/image4.png){width="0.2in"
height="0.2in"}Identity and Access Management (IAM) policy needs to be
established and implemented to determine access to resources and assets
based on identity verification, validation, authentication and
authorization of the subject (user, group, device, etc.) for a specific
period of time.

Policy should cover Multi-Factor Authentication (MFA), Access control
lists (ACL), Roll-based access control, On- and Off-boarding procedures,
Remote access directives to include 2FA.

**Awareness Training:**

- *All users are NOT informed and trained.* No regular training.
  Insufficient onboarding training. No Third-Party Training protocol
  established.

- *Privileged users DO NOT understand roles and responsibilities.* No
  Privileged access management in place.

- *Third-party stakeholders (e.g., suppliers, customers, partners) DO
  NOT understand roles and responsibilities.* No Third-Party Training
  protocol or Risk Management established.

- *Senior executives DO NOT understand roles and responsibilities.* No
  dedicated executive security and board member awareness training
  established.

- *Physical and information security personnel DO NOT understand roles
  and responsibilities.* No roles or responsibilities established.

![Exclamation mark with solid fill](media/image4.png){width="0.2in"
height="0.2in"}Training and Education program needs established and
implemented. Program needs to be ran periodically and kept up to date.
Effectiveness needs to be verified. Training should be extended to
Third-Party providers through the TPRM. Cyber Security roles and
responsibilities need established and implemented. Establish dedicated
training for executives and board members.

**Data Security:**

- *Data-at-rest is NOT adequately protected.* Although data is kept by
  Azure, the organization has not classified or labeled any data. No DLP
  strategy is implemented.

- *Data-in-transit is NOT adequately protected.* No USB data transfer
  limitations are established.

- *Assets are NOT formally managed throughout removal, transfers and
  disposition.* No policies regarding asset offboarding or data disposal
  implemented.

- *No protections against data leaks are implemented.* No DLP strategy
  implemented.

![](media/image1.png)A Data Loss Prevention method needs to be
configured. Data needs to be classified and labeled for it to be
effective. Movement and exfiltration of data (USB downloads) need to be
monitored. Asset and data disposal policies need to be implemented.

**Information Protection Processes and Procedures:**

- *No configuration change control processes are in place.* No change
  management or documented policies in place.

- *Policy and regulations regarding the physical operating environment
  for organizational assets are NOT met.* Physical protection protocols
  are in place, yet no policies are defined.

- *Data is NOT destroyed according to policy.* No data disposal policy
  in place.

- *Effectiveness of protection technologies is NOT shared with
  appropriate parties.*

- *Inadequate Cybersecurity in human resources practices. (e.g.,
  deprovisioning, personnel screening).* No offboarding procedures in
  place.

- *NO vulnerability management plan is developed or implemented.* No
  effective or formally managed Vulnerability Management program
  implemented.

![Exclamation mark with solid fill](media/image4.png){width="0.2in"
height="0.2in"}Configuration change protocols need to be implemented and
documented. Physical security policies need to be defined. Data disposal
policy needs implemented. Data protection information sharing should be
considered. Personnel offboarding procedures and policy needs
implemented. Although vulnerability scans are occasionally performed, a
formal and effective program and policy needs to be implemented.

**Protective Technology:**

- *Audit/log records are NOT determined, documented, implemented or
  reviewed in accordance with policy.* No event or log management is
  performed. No SIEM in place.

- *Removable media is NOT protected and its use restricted according to
  policy.* No data exfiltration policy in place.

- *Communications and control networks are NOT adequately protected.*
  Network traffic is not monitored adequately.

![Exclamation mark with solid fill](media/image4.png){width="0.2in"
height="0.2in"}A Security Information and Event Management (SIEM) needs
to be implemented and aligned with industry standard framework (MITRE
ATT&CK). Policy needs to be established and personnel appointed for
monitoring.

\*\*\*\*\*\*After discussion with Abed on Discord, for the remaining
categories of DETECT, RESPOND, RECOVER, further analyses will be
documented more concisely.\*\*\*\*\*\*

**DETECT**

**Anomalies and Events:**

Implement a SIEM to capture and monitor network traffic. Monitor logs
and events, analyze threats, classify low/medium/high impact events
based on criticality and establish escalation points.

**Security Continuous Monitoring:**

Implement a SIEM to capture and monitor network traffic. Merely
monitoring traffic and alerts through Microsoft Defender is critically
inadequate. Scope of monitoring needs to be defined. Implement detection
and response procedures and capabilities. Implement proper Third-Party
Risk Management Policy. Implement a formal Vulnerability Management
Policy and run scan periodically according to policy.

**Detection Processes:**

Detection and response capabilities need to be established. Roles and
responsibilities need to be defined and implemented. Separation of
duties between IT department and Cyber security department need to be
considered. Use periodic Penetration Test to verify robustness of
security posture.

**RESPOND**

**Response Planning:**

A Cybersecurity response process and policy needs to be established.

**Communications:**

Incident response activities need to be determined and communicated with
internal and external stakeholders. Include all contact details and
establish thresholds and escalation points. Communicate with proper
authorities when necessary and share findings with industry peers

**Analysis:**

Ensure analysis is conducted to determine adequate response and support
recovery activities. Document criticality of incidents. Consider the
ability for forensic investigations when needs.

**Mitigation:**

1\. Ensure Incident response plans follow a standard that ensure that
incidents are contained and mitigated. (SANS incident response plans).
Establish Vulnerability Management Program to aid in identifying and
categorizing new, known and unknown vulnerabilities. Establish a process
for dealing with 'Zero-day' vulnerabilities.

**Improvements:** Analyze, test and update incident response plans
continuously.

**RECOVER**

**Communications:**

Coordinate restoration activities with internal and external parties,
such as coordinating centers, Internet Service Providers, owners of
attacking systems, victims, other CSIRTs and vendors. Consider need for
reputational damage mitigation policy.

![Exclamation mark with solid fill](media/image4.png){width="0.2in"
height="0.2in"}

![Exclamation mark with solid fill](media/image4.png){width="0.2in"
height="0.2in"}
