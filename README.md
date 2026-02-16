# cloud-support-labs (AWS)

This repository is my **Cloud Support / Cloud Operations hub**.

It documents how I troubleshoot AWS infrastructure issues using:
- structured runbooks
- incident reports (RCA)
- operational checklists
- small automation tools

This repo focuses on **process and decision-making**.  
Each linked lab repo demonstrates those skills in practice.

---

## What this hub contains

### 🔧 Runbooks
Step-by-step guides for common Cloud Support incidents:
- what to check first
- where issues usually hide
- how to confirm a fix

Examples:
- ALB targets unhealthy
- EC2 instance unreachable
- IAM AccessDenied errors

Location: `/runbooks`

---

### 📄 Incident Reports (RCA)
Root Cause Analysis templates and sample writeups showing:
- impact
- timeline
- root cause
- prevention

Location: `/incident-reports`

---

### ✅ Troubleshooting Checklists
Fast triage lists used during live incidents:
- EC2 connectivity checklist
- ALB / Target Group checklist
- VPC routing checklist

Location: `/checklists`

---

### 🗺 Diagrams
Simple architecture sketches used to reason about failures.

Location: `/diagrams`

---

### 📘 Docs
General documentation such as onboarding notes and support workflows.

Location: `/docs`

---

## Labs (hands-on proof)

Each lab below contains real AWS builds, intentional failures, evidence, and fixes.

- **Monitoring & Alerting**  
  CloudWatch metrics, alarms, and SNS notifications  
  👉 https://github.com/Boluendowed/aws-monitoring-alerting

- **VPC Connectivity & Troubleshooting**  
  Public vs private subnets, IGW, NAT, route tables, SG/NACL issues  
  👉 https://github.com/Boluendowed/aws-vpc-connectivity-lab

- **ALB + Auto Scaling Operations**  
  Target group health checks, security group failures, ASG self-healing  
  👉 https://github.com/Boluendowed/aws-elb-autoscaling-ops

- **IAM Least Privilege**  
  Support-View vs Support-Operator roles, AccessDenied troubleshooting  
  👉 https://github.com/Boluendowed/iam-least-privilege

- **Automation Scripts**  
  Small diagnostic scripts used during Cloud Support incidents  
  👉 https://github.com/Boluendowed/automation-scripts

---

## How to read this repo (as a recruiter)
1. Start here to understand **how I think**
2. Open a lab repo to see **proof**
3. Read a runbook or RCA to see **real troubleshooting behavior**