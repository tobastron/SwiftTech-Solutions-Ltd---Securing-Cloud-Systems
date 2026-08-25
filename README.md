# 🔐 SwiftTech Solutions — Cloud Security & Infrastructure Governance

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white)
![ISO 27001](https://img.shields.io/badge/ISO%2027001-blue)
![IAM](https://img.shields.io/badge/IAM-Policies-orange)
![VPN](https://img.shields.io/badge/VPN-OpenVPN-green)

A comprehensive cloud security and governance project for a UK-based technology company transitioning to a remote-first, cloud-based network. Includes IAM policies, risk assessments, ISO 27001 alignment, VPN configuration, and service management documentation.

> **📄 Short Description:** SDesigned and implemented a segregated AWS network for a remote-first UK company. Single VPC split into 3 public / 3 private subnets, with a public Apache web server, bastion host, and OpenVPN gateway (static Elastic IP) as the sole route into private resources — verified live by showing a browser request to a private resource time out, then succeed once tunnelled through the VPN. Deployed two redundant Active Directory Domain Controllers with OU/Group Policy enforcing least-privilege access, tested live against both an admin and a locked-down standard-user profile. Data layer on DynamoDB (customer, employee, product tables) with automated snapshot backups replicated to a versioned, encrypted S3 bucket. Security Groups scoped to VPN-only access, with VPC Flow Logs streamed to CloudWatch for continuous auditing. 
> **🎥 Project Walkthrough Video:** (https://youtu.be/ayghhTJwezU)
> 
> TIMESTAMPS & TIMELINE ARCHITECTURE

00:00 - Foundational Network Topology & 6-Subnet VPC

01:31 - Isolated Private Backends & Directory Redundancy

03:41 - Secure Boundary Verification & VPN Edge Routing

06:21 - Active Directory Object Controls & Group Policies (GPOs)

11:31 - User Persona Validation & Access Logic Controls

14:11 - Stateful Port Hardening & DynamoDB Backup Pipelines

---

## 📁 Repository Structure
├── docs/
│ ├── cloud-framework/ # Cloud architecture & framework docs
│ │ └── Cloud Framework for Swifttech.docx
│ ├── security/ # Security policies & ISO documents
│ │ ├── Cloud Security Framework.pptx
│ │ ├── Information Security Objectives & Policy Statement
│ │ ├── Securing Cloud Systems
│ │ └── ISO27KSOA.xlsx
│ ├── risk-management/ # Risk assessments & treatment plans
│ │ ├── risk assessment table
│ │ ├── risks.xlsx
│ │ └── Residual Risk Treatment Plan
│ ├── service-management/ # Service design & agreements
│ │ ├── Service design.docx
│ │ ├── Service Management Practices
│ │ ├── Service Control Processes.pdf
│ │ └── Flashcards- Relationship and agreement processes^.docx
│ └── appendices/
│ ├── Appendices Spreadsheet.xlsx
│ ├── SDE.1 SPC.1 SPC.2.xlsx
│ └── Asset ID
├── iam/
│ ├── iam policy # IAM policy documents
│ ├── iam.jpeg
│ ├── iam1.jpeg
│ └── iam3.webp
├── network/
│ └── default2.ovpn # OpenVPN configuration
├── presentations/
│ ├── 503 presentation.pptx
│ ├── Cloud Security Framework for SwiftTech Solutions Ltd.pptx
│ ├── Leadership (Top01).pptx
│ └── COM.07 to COM.11.pptx
├── diagrams/
│ └── 503 diagram.png
├── research/
│ ├── Mongodb vs Dynamodb
│ └── RapidEx Agenda.docx
├── screenshots/ # Screenshots of configurations
│ ├── Screenshot 2023-10-19 at 12.09.16
│ ├── Screenshot 2023-10-19 at 14.30.30
│ └── Screenshot 2023-11-23 at 16.44.53
└── README.md



---

## 🛡️ Key Project Components

### 1. Cloud Security & ISO 27001 Alignment
- Developed a **Cloud Security Framework** tailored to a remote workforce
- Aligned security objectives with **ISO 27001** controls (SOA, risk treatment)
- Created IAM policies following least‑privilege principles
- Addressed BYOD security through policy and technical controls

### 2. Risk Management
- Conducted a full **risk assessment** and created a **Residual Risk Treatment Plan**
- Documented asset identification and control implementation

### 3. Networking & VPN
- Configured **OpenVPN** (`default2.ovpn`) for secure remote access
- Designed network segmentation to isolate remote, nomadic, and on-site traffic

### 4. Service Management
- Defined service design, control processes, and supply‑demand management
- Applied ITIL‑aligned practices for incident, change, and service level management

### 5. Documentation & Presentations
- Multiple executive and technical presentations (Leadership, Security Framework, COM series)
- Reflective reports and spreadsheet analysis of controls and processes

---

## 🧠 What This Project Demonstrates

- Understanding of **cloud security governance** for a distributed workforce
- Hands‑on experience with **IAM policies** and **VPN configurations**
- Application of **ISO 27001** and risk management frameworks
- Ability to create professional security documentation and presentations
- Integration of **service management** best practices in a cloud environment

---
 
**💼 LinkedIn:** [(https://www.linkedin.com/in/oluwatobiastron/)](https://www.linkedin.com/in/oluwatobiastron/)

---


