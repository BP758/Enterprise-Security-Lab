# Enterprise Security Lab
BP Technologies
--------------------------------------------------------------------------------
Welcome to BP Technologies.
--------------------------------------------------------------------------------
This project chronicles the transformation of enterprise network hardware into a fully segmented, hybrid security engineering environment. Every phase, from password recovery on a Nexus switch to centralized logging across on-prem and cloud platforms, is documented as if deployed in production.

The objective is simple: build, break, harden, and detect using the same operational discipline expected in a real security team.

This is not a virtual machine lab built for demonstration. It is a structured, evolving infrastructure designed to simulate real-world security architecture, detection engineering, and hybrid network operations.

Each configuration decision is intentional. Each service is secured. Each layer is observable.

Architecture Overview
--------------------------------------------------------------------------------
The lab is designed to simulate a hybrid enterprise environment that includes physical infrastructure, virtualization, and cloud integration.
--------------------------------------------------------------------------------
Core components include:
--------------------------------------------------------------------------------
Cisco Nexus 3548-XL (NX-OS)

Windows 11 host with Hyper-V

Ubuntu Server (SOC backend)

Wazuh SIEM

Splunk Enterprise

Microsoft Sentinel

Entra ID (Azure AD)

VLAN segmentation 

Centralized logging architecture
--------------------------------------------------------------------------------
The design models real-world enterprise patterns including management isolation, secure remote access, tiered administration, and layered monitoring.
--------------------------------------------------------------------------------
An architecture diagram will be maintained in the /architecture directory.

Hardware and Software Stack
--------------------------------------------------------------------------------
Hardware
--------------------------------------------------------------------------------
Cisco Nexus 3548-XL

Lenovo ThinkCentre

Dell OptiPlex (Intel vPro)

HP Server (for future hypervisor expansion)

Operating Systems
--------------------------------------------------------------------------------
NX-OS 9.2.2

Windows 11 Pro

Windows Server (planned for AD integration)

Ubuntu Server 24.04 LTS

Security and Monitoring
--------------------------------------------------------------------------------
Wazuh

Splunk Enterprise

Microsoft Sentinel

Sysmon

SSH-based secure management

VLAN segmentation

Cloud Integration
--------------------------------------------------------------------------------
Microsoft Entra ID

Microsoft Sentinel

Hybrid identity and telemetry pipelines

Project Objectives
--------------------------------------------------------------------------------
Recover and harden decommissioned enterprise hardware.

Design a segmented network architecture using VLANs.

Deploy a multi-SIEM monitoring stack.

Implement centralized logging across network, server, and endpoint layers.

Simulate real-world security operations workflows.

Integrate on-prem infrastructure with cloud detection platforms.

Develop detection engineering and threat simulation capabilities.


Maintain disciplined documentation throughout every phase.

Skills Demonstrated
--------------------------------------------------------------------------------
Network Engineering
--------------------------------------------------------------------------------
NX-OS recovery and configuration

VLAN segmentation and management isolation

Secure remote access via SSH

Default routing and management plane design

Systems Engineering
--------------------------------------------------------------------------------
Hyper-V deployment

Linux server deployment and hardening

Windows endpoint telemetry configuration

Security Engineering
--------------------------------------------------------------------------------
Multi-SIEM deployment (Wazuh, Splunk, Sentinel)

Log ingestion and normalization

Secure service configuration

Detection engineering workflows

Cloud Security
--------------------------------------------------------------------------------
Entra ID integration

Microsoft Sentinel configuration

Hybrid telemetry architecture

Operational Discipline
--------------------------------------------------------------------------------
Structured documentation

Credential tiering strategy

Configuration persistence

Secure service exposure decisions

Repository Structure
--------------------------------------------------------------------------------
architecture/
Network diagrams and topology documentation

phase-1-nexus-recovery/
NX-OS recovery and secure baseline configuration

phase-2-virtualization/
Hyper-V deployment and Ubuntu SOC configuration

phase-3-siem/
Wazuh and Splunk deployment

phase-4-cloud/
Microsoft Sentinel and hybrid logging integration

phase-5-segmentation/
VLAN design and routing strategy

Project Philosophy
--------------------------------------------------------------------------------
This repository is maintained as a living engineering document.
--------------------------------------------------------------------------------
All configurations are intentional.
All services are secured before exposed.
All architectural decisions are documented.

The goal is not to simulate security.
The goal is to practice it at infrastructure depth.
