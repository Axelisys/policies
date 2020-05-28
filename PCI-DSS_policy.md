---
layout: page
title: "Payment Card and Payment Application Policy (PCI-DSS)"
permalink: /pci_dss_policy/
---

# Payment Card Protection Digital Security Standard Policy

## 1. Policy Statement

1. All card processing activities and related technologies must comply with the Payment Card Industry Data Security Standard (PCI-DSS) in its entirety. Card processing activities must be conducted as described herein and in accordance with the standards and procedures listed in the Related Documents section of this Policy. No activity may be conducted nor any technology employed that might obstruct compliance with any portion of the PCI-DSS.
2. This policy shall be reviewed at least annually and updated as needed to reflect changes to business objectives or the risk environment.

## 2. Applicability and Availability

1. This policy applies to all employees. Relevant sections of this policy apply to vendors, contractors, and business partners. The most current version of this policy is available via our head office which can be contacted The Company Address. 


## 3. Adherence to Standards

1. Configuration standards must be maintained for applications, network components, critical servers, and wireless access points. These standards must be consistent with industry-accepted hardening standards as defined, for example, by SysAdmin Assessment Network Security Network (SANS), National Institute of Standards Technology (NIST), International Organization for Standardization (ISO) such as ISO27001, and Center for Internet Security (CIS).
2. Configuration standards must include

  1. Updating of anti-virus software and definitions, perfom periodic scans, and generate audit logs
  2. Identify new security vulnerabilities and assigns risking rankings that identifies all &quot;high risk&quot; and &quot;critical&quot; vulnerabilities based on reputable outside sources.
  3. Provision for installation of all relevant new security patches within 30 days, and all vendor supplied security patches within an appropriate time frame.
  4. Authentication mechanisms are assigned to individual accounts and are not shared, and physical and/or logical controls ensure only the attend account can gain access.

## 4. Handling of Cardholder Data

1. Distribution, maintenance, and storage of media containing cardholder data, must be avoided altogether. Only in exceptional circumstances will special dispensation be granted. Any such dispensation will be logged and signed for by an executive at Axelisys, any third-party contractor, subcontractor or their agent, including that distributed to individuals. Procedures must include periodic media inventories in order to validate the effectiveness of these controls. listings of devices must be maintained along with periodic inspections of devices for signs of tampering. Training mechanisms must be place to alert staff when device tampering is evident.
2. Procedures for data retention and disposal must be maintained by each department and must include the following:
  1. Legal, regulatory, and business requirements for data retention, including specific requirements for retention of cardholder data
  2. Provisions for disposal of data when no longer needed for legal, regulatory, or business reasons, including disposal of cardholder data
  3. A programmatic (automatic) process to remove, at least on a quarterly basis, stored cardholder data that exceeds business retention requirements, or, alternatively, an audit process, conducted at least on a quarterly basis, to verify that stored cardholder data does not exceed business retention requirements
  4. Destruction of media when it is no longer needed for business or legal reasons as follows:
    1. Cross-cut shred, incinerate, or pulp hardcopy materials
    2. Purge, degauss, shred, or otherwise destroy electronic media such that data cannot be reconstructed
3. Credit card numbers must be masked when displaying cardholder data. The principle of this policy is that at no point, should there ever be a need to see full credit card information. In the event of a query by a customer, they must be informed that we do not have access to the full information for security purposes, and if they wished to change their details, I is our policy to require them to resubmit credit card information through a secure channel. No exception to this rule will normally be allowed, without special dispensation.
4. Unencrypted Primary Account Numbers may not be sent via email, instant messaging, SMS, chat. Etc. nor written down on paper at any point, during any engagement with customers.

## 5. Access to Cardholder Data

1. A &quot;walled garden&quot; approach will be taken to card data at all times with a preference for transfer of risk to third-party, dedicated security and tokenisation service providers compliant with PCI-A and PCI-DSS standards.
2. Credit card information will not be stored within the bounds of the organisation if at all possible, to mitigate the risk of non-compliance. Steps will be taken by all employees to ensure compliance with the Axelisys Business Continuity Policy, including enforcement of contractual duty by all suppliers, subcontractors and vendors for overall security.
3. Procedures for data control must be maintained and executed by each function, team or department and must incorporate the following:
  1. Access rights to privileged User IDs are restricted to least privileges necessary to perform job responsibilities
  2. Assignment of privileges is based on individual personnel&#39;s job classification and function
  3. Requirement for an auditable authorization by management that specifies required privileges
  4. Define access needs and privileges for each job role.

## 6. Employee-facing Technologies

1.For critical employee-facing technologies, departmental procedures shall require:
  1. Explicit management approval to use the devices
  2. That all device use is authenticated with username and password or other authentication item (for example, token)
  3. A list of all devices and personnel authorized to use the devices
  4. Labeling of devices with owner, contact information, and purpose
  5. Automatic disconnect of modem sessions after a specific period of inactivity
  6. Activation of remote access technologies used by vendors only when needed by vendors, with immediate deactivation after use
  
2.Functional usage standards shall include:
  1. Acceptable uses for the technology in accordance with our acceptable use policy.
  2. Acceptable network locations for the technology
  3. A list of company-approved products, aligned to our service and application catalogues.
  4. A prohibition of the storage of cardholder data onto local hard drives, floppy disks, or other external media when accessing such data remotely via remote access technologies
  5. Controlled use of cut-and-paste and print functions during remote desktop sessions.

## 7. Roles and Responsibilities
1. Will maintain daily operational security procedures consistent with this the PCI-DSS, including administrative and technical procedures for each of the requirements:
2. Chief Security Officer (or equivalent) is responsible for overseeing all aspects of information security, including but not limited to:
  1. Creating and distributing security policies and procedures
  2. Monitoring and analyzing security alerts and distributing information to appropriate information security and business unit management personnel
  3. Monitoring service providers PCI compliance at least annually
  4. creating and distributing security incident response and escalation procedures that include:
    1. Roles, responsibilities, and communication
    2. Coverage and responses for all critical system components
    3. Notification, at a minimum, of credit card associations and acquirers
    4. Strategy for business continuity post compromise
    5. Reference or inclusion of incident response procedures from card associations
    6. Analysis of any legal requirements for reporting compromises
    7. Annual testing
    8. Designation of personnel to monitor for intrusion detection, intrusion prevention, and file integrity monitoring alerts on a 24/7 basis
    9. Plans for periodic training
    10. A process for evolving the incident response plan according to lessons learned and in response to industry developments

  5. Maintaining a formal security awareness program for all employees that provides multiple methods of communicating awareness and educating employees (for example, posters, letters, meetings) and training (Cybersecurity Essentials)
  6. Review non-urgent security logs at least weekly and follow-up on exceptions
  7. The Information Technology Office (or equivalent) and all teams shall maintain daily administrative and technical operational security procedures that are consistent with the PCI-DSS (for example, user account maintenance procedures, and log review procedures).

3. System and Application Administrators shall
  1. Monitor and analyse security alerts and information and distribute to appropriate personnel
  2. Administer user accounts and manage authentication
  3. Monitor and control all access to data
  4. Maintain a list of connected entities
  5. Perform due diligence prior to connecting an entity, with supporting documentation
  6. Verify that the entity is PCI-DSS compliant, with supporting documentation
  7. Establish a documented procedure for connecting and disconnecting entities
  8. Retain audit logs for at least one year
4. The Human Resources Office (or equivalent) is responsible for tracking employee participation in the security awareness program, including:
  1. Facilitating participation upon hire and at least annually
  2. Ensuring that employees acknowledge in writing that they have read and understand the company&#39;s information security policy
  3. Screen potential employees to minimize the risk of attacks from internal sources
  4. Internal Audit (or equivalent) is responsible for executing a (12.1.2) risk assessment process that identifies threats, vulnerabilities, and results in a formal risk assessment.

5. Where applicable, the Architecture Board for each project (or pertinent functional equivalent) will ensure that for service providers with whom cardholder information is shared:
  1. Contracts require adherence to PCI-DSS by the service provider
  2. Contracts include acknowledgement or responsibility for the security of cardholder data by the service provider


## 8. Standards

1. This PCI-DSS policy is designed to be applied in conjunction with the following standards:
2. PA-DSS standards: online (https://www.pcisecuritystandards.org). An offline copy is available in the employee handbook
3. PA-DSS standard for payment applications: online (https://www.pcisecuritystandards.org). An offline copy is available in the employee handbook.

## 9. Information security events, Weaknesses &amp; Incident Reporting
1. All information security events and suspected weaknesses are to be reported to the Data Protection officer or Chief Executive in their absence. All information security events shall be investigated to establish their cause and impacts with a view to avoiding similar events.
2. Where information has been deemed to be breached, the policy to re-establish a secure company and platforms shall include:
  1. Fixing the exposed vulnerability
  2. Resecuring the data
  3. Notifying affected clients in writing at the earliest opportunity (email and website included), including:
    1. Date and time of breach
    2. Any data suspected to have been lost
    3. Whether steps have been taken to fix any vulnerability
    4. Advice and appropriate courses of client action, if appropriate
    5. Any steps Axelisys will take in accordance with contractual obligations
