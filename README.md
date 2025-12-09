# gov-cyber-pipeline-k12

The Sentry Initiative: K-12 Federal Cyber Pipeline

Project Status: Active Pilot (Washington D.C. Capital Region)
Framework Alignment: NIST NICE (SP 800-181), MITRE ATLAS, OWASP LLM

1. Executive Summary

The Sentry Initiative is a specialized workforce development curriculum designed to address the critical shortage of cybersecurity professionals within the U.S. federal government. Unlike general IT education programs, this initiative focuses exclusively on the skills required to defend National Critical Infrastructure (NCI).

The curriculum is engineered to serve as a direct talent pipeline for federal agencies (CISA, NSA, DOE) by training high-potential K-12 students in the National Capital Region (NCR). A primary deliverable of the program is the student-led development of two proprietary defense assets: "The Sovereign Data Vault" (secure cloud infrastructure) and "The Sentinel App" (AI anomaly detection).

2. Strategic Objectives

The initiative supports Executive Order 14110 (Safe, Secure, and Trustworthy Development and Use of Artificial Intelligence) by establishing three core competencies in the pre-collegiate workforce:

Data Segregation Doctrine: Architecting cloud environments that enforce strict separation between public, private, and classified data assets.

AI Defense: Operationalizing the MITRE ATLAS framework to detect and mitigate adversarial attacks on machine learning models.

Federal Compliance: Familiarizing students with FedRAMP, NIST SP 800-53, and other government-specific security controls.

3. Curriculum Architecture

The pedagogy is divided into three progressive modules, each mapping to specific Knowledge, Skills, and Abilities (KSAs) defined in the NIST NICE Workforce Framework.

Module 01: Cloud Data Sovereignty

Focus: Secure Infrastructure Design

Topic 1.1: Virtual Private Cloud (VPC) Architecture for Classified Workloads.

Topic 1.2: Identity and Access Management (IAM) and Principle of Least Privilege.

Topic 1.3: Implementation of FedRAMP High Baseline controls in simulated environments.

Core Project: Construction of "The Sovereign Data Vault" — Students architect and deploy a fully air-gapped cloud environment designed to store classified data, implementing zero-trust egress rules and strict IAM policies.

NICE Role Alignment: Cyber Defense Infrastructure Support Specialist (PR-INF-001).

Module 02: AI Counter-Adversarial Operations

Focus: Machine Learning Security (MLSec)

Topic 2.1: Introduction to the MITRE ATLAS Matrix (Adversarial Threat Landscape for AI Systems).

Topic 2.2: Detection of Model Inversion and Membership Inference Attacks.

Topic 2.3: Data Sanitization pipelines to prevent Training Data Poisoning.

Core Project: Development of "The Sentinel App" — Students engineer a local Python-based AI agent capable of detecting and flagging adversarial inputs in real-time network traffic.

NICE Role Alignment: Research & Development Specialist (SP-TRD-001).

Module 03: Large Language Model (LLM) Governance

Focus: Generative AI Security

Topic 3.1: Mitigation of Prompt Injection and Jailbreaking attempts (OWASP LLM01).

Topic 3.2: Prevention of Sensitive Information Disclosure in Government Chatbots (OWASP LLM06).

Topic 3.3: Developing "System Constitutions" for AI alignment.

4. Implementation Methodology

This repository serves as the central knowledge base for the curriculum. Educators and technical leads can deploy the modules using the following structure:

/curriculum/labs: Jupyter Notebooks containing Python-based defense simulations.

/curriculum/policy: PDF templates for System Security Plans (SSP) and Incident Response plans.

/curriculum/capstone: Scenario packets for the "Sector Defense" simulation (Energy, Finance, Healthcare).

5. Usage and Contribution

This project is open-source to encourage collaboration among educators, federal workforce directors, and industry partners.

For Educators

Clone this repository to access the raw lesson plans and lab environments. All materials are designed to be deployed in standard educational Learning Management Systems (LMS) or GitHub Codespaces.

For Federal Partners

Agencies wishing to propose new modules based on emerging threats should submit a Pull Request or open an Issue titled "Curriculum Alignment Request."

6. License

This project is licensed under the MIT License.
Copyright (c) 2024 The Sentry Initiative. All Rights Reserved.
