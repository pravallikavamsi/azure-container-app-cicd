Azure Container App Monitoring & Automated Lifecycle Management
Overview

This project demonstrates an automated monitoring and remediation workflow for an Azure Container App using Azure native monitoring and automation services.

The solution monitors container resource utilization using Azure Monitor, visualizes metrics through Azure Workbooks, triggers alerts using Action Groups, and automatically performs container lifecycle operations using Azure Automation Runbooks.

The goal of this project is to demonstrate cloud observability, alert-driven automation, and operational self-healing concepts used in DevOps and SRE environments.

Architecture
                 Users
                   |
                   |
            Azure Container App
              (pravcontapp)
                   |
                   |
          Azure Monitor Metrics
                   |
                   |
            Azure Workbook
        (Dashboard & Visualization)
                   |
                   |
             Alert Rule
        (CPU Threshold Monitoring)
                   |
                   |
             Action Group
                   |
                   |
        Azure Automation Account
                   |
                   |
             PowerShell Runbook
                   |
                   |
        Container App Lifecycle Action
        
Resources thatare used in Azure are:
Azure Container Apps---	Host containerized application
Azure Monitor---	Collect container metrics
Azure Workbooks---	Monitoring dashboard and visualization
Azure Monitor Alerts---	Detect resource conditions
Action Groups	Trigger--- automation workflows
Azure Automation Account---	Execute operational scripts
PowerShell Runbook---	Automate container operations
Azure Managed Identity---	Secure authentication
Azure RBAC---	Permission management
