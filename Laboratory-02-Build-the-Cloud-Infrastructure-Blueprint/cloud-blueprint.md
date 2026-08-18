# Laboratory 2: Build the Cloud Infrastructure Blueprint

## Cloud Infrastructure Blueprint Documentation

### 1. System Overview
This blueprint outlines a scalable, high-availability multi-tier cloud infrastructure designed to support enterprise-grade web applications with automated failover, secure network isolation, and optimized resource management.

### 2. Service Models Breakdown
* **Infrastructure as a Service (IaaS):** Virtual compute instances (e.g., AWS EC2 / Azure VMs) hosting core business logic with customizable operating systems and compute parameters.
* **Platform as a Service (PaaS):** Fully managed database engines (e.g., AWS RDS / Azure SQL) handling automated backups, patching, and multi-region replication.
* **Software as a Service (SaaS):** Integrated identity and monitoring solutions (e.g., Microsoft Entra ID, Datadog) for enterprise operations.

### 3. Architecture & Security Requirements
* **Deployment Model:** Public Cloud with Virtual Private Cloud (VPC) subnets isolating database tiers from public-facing web layers.
* **Security & Governance:** Strict Identity & Access Management (IAM) role policies, mandatory multi-factor authentication (MFA), and TLS 1.3 data encryption in transit and at rest.
