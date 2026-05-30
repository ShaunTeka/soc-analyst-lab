# Microsoft Sentinel Incident Response & Automation Lab

## Overview

This lab demonstrates the configuration of Microsoft Sentinel analytics rules, automation workflows, playbooks, and data connectors to enhance threat detection, incident response, and security operations automation.

The project focused on implementing Microsoft Sentinel SIEM capabilities, integrating Defender XDR playbooks, and configuring Azure Activity monitoring for improved security visibility.

---

# Technologies Used

- Microsoft Sentinel
- Microsoft Defender XDR
- Azure Logic Apps
- Azure Activity Logs
- Microsoft Security Operations (SecOps)
- Security Orchestration, Automation and Response (SOAR)

---

# Objectives

- Create Microsoft Sentinel analytics rules
- Configure incident creation rules
- Deploy Defender XDR playbooks
- Configure automation rules
- Integrate Azure Activity data connectors
- Enable automated threat response workflows
- Enhance security monitoring capabilities

---

# Lab Activities

## 1. Microsoft Sentinel Analytics Rules

Configured Microsoft Sentinel analytics rules to automate incident creation and improve threat detection capabilities.

### Activities Performed

- Navigated to Microsoft Sentinel
- Accessed **Configuration → Analytics**
- Created a new Microsoft Security Incident Rule
- Successfully deployed the incident creation rule

### Screenshots

![Microsoft Sentinel Workspace](./screenshots/01-sentinel-workspace.png)

![Creating Analytics Rule](./screenshots/02-create-analytics-rule.png)

![Analytics Rule Wizard](./screenshots/03-analytics-rule-wizard.png)

![Incident Rule Created](./screenshots/04-incident-rule-created.png)

---

## 2. Microsoft Sentinel SOAR Playbooks

Configured Security Orchestration, Automation and Response (SOAR) capabilities using Defender XDR playbook templates.

### Activities Performed

- Accessed Microsoft Sentinel Content Hub
- Installed Sentinel SOAR Essentials content
- Selected Defender XDR Playbook Templates
- Created an initial ransomware response playbook

### Screenshots

![Content Hub](./screenshots/05-content-hub.png)

![Defender XDR Templates](./screenshots/06-defender-xdr-templates.png)

![Creating Playbook](./screenshots/07-create-playbook.png)

![Logic App Designer](./screenshots/08-logic-app-designer.png)

---

## 3. Playbook Configuration & Connection Management

Configured and updated playbook connections within the Microsoft Sentinel workspace.

### Activities Performed

- Navigated to **Configuration → Automation**
- Updated active playbooks
- Modified playbook connections
- Added a new Azure connection
- Authenticated using Azure administrator credentials
- Saved updated configurations

### Screenshots

![Automation Configuration](./screenshots/09-automation-configuration.png)

![Edit Playbook](./screenshots/10-edit-playbook.png)

![Add Connection](./screenshots/11-add-connection.png)

![Azure Authentication](./screenshots/12-azure-authentication.png)

![Connection Successful](./screenshots/13-connection-successful.png)

---

## 4. Automation Rule Creation

Created automated workflows to improve incident response efficiency within Microsoft Sentinel.

### Activities Performed

- Created a new automation rule
- Configured automated response actions
- Successfully deployed the automation workflow

### Screenshots

![Create Automation Rule](./screenshots/14-create-automation-rule.png)

![Automation Rule Created](./screenshots/15-automation-rule-created.png)

---

## 5. Azure Activity Data Connector Integration

Integrated Azure Activity Logs into Microsoft Sentinel to improve monitoring and security visibility.

### Activities Performed

- Accessed Data Connectors
- Selected Azure Activity
- Opened connector configuration page
- Launched Azure Policy Assignment Wizard
- Assigned and deployed Azure monitoring policies

### Screenshots

![Azure Activity Connector](./screenshots/16-azure-activity-connector.png)

![Connector Configuration](./screenshots/17-connector-configuration.png)

![Policy Assignment Wizard](./screenshots/18-policy-assignment-wizard.png)

![Policy Assigned](./screenshots/19-policy-assigned.png)

---

# Skills Demonstrated

- Microsoft Sentinel Administration
- SIEM Configuration
- Security Analytics
- Incident Management
- Security Automation
- SOAR Implementation
- Defender XDR Integration
- Azure Security Monitoring
- Logic App Configuration
- Threat Detection & Response

---

# Lessons Learned

This lab strengthened my understanding of:

- Microsoft Sentinel architecture
- Security incident management
- Automated threat response
- SOAR workflows
- Azure security monitoring
- Security playbook deployment
- Data connector integration
- Enterprise security operations

---

# Future Improvements

Planned future enhancements include:

- Advanced Threat Hunting
- KQL Query Development
- Incident Investigation Workflows
- MITRE ATT&CK Mapping
- Threat Intelligence Integration
- Automated Incident Remediation
- Security Dashboard Development
