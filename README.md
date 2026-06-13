# Roadmap_Cloud_Devops_SRE

# 🚀 Prem's Learning Hub — AWS · DevOps · SRE · AI

> A comprehensive training hub to brush up skills across AWS, DevOps, SRE, and AI — built for a 3.8 YOE SRE professional transitioning from monitoring/ticketing to full-stack reliability engineering.

## 📂 Structure

```
prem-learning-hub/
├── 01-roadmap/              # Structured study roadmap with timelines
├── 02-cheatsheets/          # Quick reference guides for each domain
├── 03-hands-on-projects/    # Real-world projects to practice
└── 04-daily-practice/       # Daily drills, interview questions, labs
```

## 🎯 Goals

- **AWS**: From basics to Solutions Architect level (associate)
- **DevOps**: Master CI/CD, IaC, containers, and GitOps
- **SRE**: Go beyond monitoring — own reliability, SLIs/SLOs, incident management
- **AI**: Understand ML fundamentals and apply AI/ML in SRE workflows (AIOps)

## 🗓️ Suggested Timeline: 16 Weeks

| Phase | Weeks | Focus |
|-------|-------|-------|
| Phase 1 | 1-4 | AWS Core Services + DevOps Fundamentals |
| Phase 2 | 5-8 | Advanced AWS + CI/CD Pipelines + IaC |
| Phase 3 | 9-12 | SRE Deep Dive + Observability + Incident Mgmt |
| Phase 4 | 13-16 | AI/ML Fundamentals + AIOps + Capstone Project |

## 💡 How to Use This Hub

1. Start with the **roadmap** to understand the learning path
2. Keep **cheatsheets** handy for quick reference during practice
3. Work through **hands-on projects** — they're designed to build real skills
4. Use **daily practice** for consistent skill sharpening

---

*Built with ❤️ by Cline SR for Prem*


# 📋 16-Week Study Roadmap: AWS · DevOps · SRE · AI

> Designed for Prem — 3.8 YOE SRE @ Altimetrik (Samsung client), currently in monitoring/ticketing role, looking to level up to full-stack reliability engineering.

---

## 🏗️ Phase 1: Foundation (Weeks 1-4)
### AWS Core Services + DevOps Fundamentals

| Week | AWS Topics | DevOps Topics | Hands-On Lab |
|------|-----------|---------------|--------------|
| **1** | AWS Overview, IAM, AWS CLI, SDK | Linux fundamentals, Shell scripting | Create IAM users/groups/policies via CLI |
| **2** | EC2, VPC, Security Groups, Key Pairs | Git deep dive (branching, rebasing, hooks) | Launch EC2 in custom VPC with bash provisioning |
| **3** | S3, EBS, EFS, RDS, DynamoDB | Docker basics (images, containers, Dockerfile) | Deploy a web app on EC2 with S3 static assets |
| **4** | CloudWatch, CloudTrail, ALB/NLB | Docker Compose, Container networking | Multi-container app with CloudWatch monitoring |

### 📚 Resources — Phase 1
- **AWS**: [AWS Free Tier](https://aws.amazon.com/free/) — Sign up and practice daily
- **AWS**: [AWS Certified Solutions Architect - Associate Study Guide](https://www.amazon.com/dp/1119138558)
- **Linux**: [Linux Journey](https://linuxjourney.com/)
- **Docker**: [Docker Official Tutorial](https://docs.docker.com/get-started/)
- **Git**: [Pro Git Book](https://git-scm.com/book/en/v2)

### ✅ Phase 1 Milestone Checklist
- [ ] Can create and manage AWS resources via CLI and Console
- [ ] Understand VPC networking (subnets, route tables, IGW, NAT)
- [ ] Can write shell scripts for automation
- [ ] Comfortable with Git workflows
- [ ] Can containerize a simple application with Docker

---

## ⚡ Phase 2: Intermediate (Weeks 5-8)
### Advanced AWS + CI/CD Pipelines + Infrastructure as Code

| Week | AWS Topics | DevOps Topics | Hands-On Lab |
|------|-----------|---------------|--------------|
| **5** | Lambda, API Gateway, Step Functions | Jenkins/GitHub Actions — CI/CD basics | Serverless API with Lambda + API Gateway |
| **6** | ECS, ECR, Fargate | Terraform fundamentals (providers, resources, state) | Deploy containers on ECS Fargate with Terraform |
| **7** | CloudFormation, CDK | Terraform modules, remote state, workspaces | IaC for full VPC + ECS cluster |
| **8** | Route53, CloudFront, ACM | ArgoCD, GitOps principles, Helm basics | CI/CD pipeline: GitHub → ECR → ECS with GitOps |

### 📚 Resources — Phase 2
- **Terraform**: [HashiCorp Learn](https://learn.hashicorp.com/terraform)
- **Jenkins**: [Jenkins Official Documentation](https://www.jenkins.io/doc/)
- **GitHub Actions**: [GitHub Actions Docs](https://docs.github.com/en/actions)
- **ArgoCD**: [ArgoCD Getting Started](https://argo-cd.readthedocs.io/en/stable/getting_started/)
- **AWS Lambda**: [AWS Lambda Docs](https://docs.aws.amazon.com/lambda/)

### ✅ Phase 2 Milestone Checklist
- [ ] Can build and deploy serverless applications
- [ ] Can write Terraform configs to provision AWS infrastructure
- [ ] Understand CI/CD pipeline design and implementation
- [ ] Can deploy containerized apps on ECS/Fargate
- [ ] Familiar with GitOps and ArgoCD workflows

---

## 🔥 Phase 3: Advanced SRE (Weeks 9-12)
### SRE Deep Dive + Observability + Incident Management

| Week | SRE Topics | Observability Topics | Hands-On Lab |
|------|-----------|---------------------|--------------|
| **9** | SLIs, SLOs, SLAs, Error Budgets | Prometheus + Grafana setup | Define SLOs for a sample service + Prometheus metrics |
| **10** | Incident Management, Postmortems, Blameless Culture | Alerting strategies, PagerDuty/OpsGenie | Simulate incident + write postmortem |
| **11** | Capacity Planning, Load Testing, Chaos Engineering | Distributed Tracing (Jaeger/X-Ray), Log aggregation (ELK) | Chaos experiment with AWS Fault Injection Simulator |
| **12** | On-call best practices, Runbook automation | Correlating metrics, logs, traces | Build observability dashboard for microservices |

### 📚 Resources — Phase 3
- **SRE Book**: [Google SRE Book (Free)](https://sre.google/sre-book/table-of-contents/)
- **SRE Workbook**: [Google SRE Workbook (Free)](https://sre.google/workbook/table-of-contents/)
- **Prometheus**: [Prometheus Docs](https://prometheus.io/docs/introduction/overview/)
- **Grafana**: [Grafana Tutorials](https://grafana.com/tutorials/)
- **Chaos Eng**: [Principles of Chaos Engineering](https://principlesofchaos.org/)

### ✅ Phase 3 Milestone Checklist
- [ ] Can define and track SLIs/SLOs for a service
- [ ] Understand error budget policies and their impact on release velocity
- [ ] Can lead a blameless postmortem
- [ ] Can set up Prometheus + Grafana monitoring stack
- [ ] Understand the three pillars of observability (metrics, logs, traces)
- [ ] Can design and run chaos experiments

---

## 🤖 Phase 4: AI + AIOps (Weeks 13-16)
### AI/ML Fundamentals + AIOps + Capstone Project

| Week | AI/ML Topics | AIOps Topics | Hands-On Lab |
|------|-------------|--------------|--------------|
| **13** | Python for ML, NumPy, Pandas basics | Anomaly detection in metrics | Build anomaly detector for time-series metrics |
| **14** | Supervised/Unsupervised learning, Scikit-learn | Log clustering and pattern detection | ML model to classify incident severity from logs |
| **15** | Deep Learning basics, Neural Networks, TensorFlow/PyTorch intro | Predictive auto-scaling, Intelligent alerting | Predictive scaling model based on traffic patterns |
| **16** | LLMs, Prompt Engineering, RAG basics | AI-assisted incident response, ChatOps | **CAPSTONE**: AI-powered SRE assistant |

### 📚 Resources — Phase 4
- **ML General**: [Andrew Ng's Machine Learning Course](https://www.coursera.org/learn/machine-learning)
- **Python ML**: [Hands-On ML with Scikit-Learn & TensorFlow](https://www.amazon.com/dp/1098125975)
- **FastAI**: [Practical Deep Learning](https://course.fast.ai/)
- **LLMs**: [LangChain Docs](https://docs.langchain.com/)
- **AIOps**: [AIOps Wikipedia](https://en.wikipedia.org/wiki/AIOps) + Gartner reports

### ✅ Phase 4 Milestone Checklist
- [ ] Can build basic ML models with Python/Scikit-learn
- [ ] Understand anomaly detection for time-series data
- [ ] Can apply ML to SRE problems (alert noise reduction, incident classification)
- [ ] Understand LLMs and prompt engineering basics
- [ ] Complete capstone project: AI-powered SRE assistant

---

## 🏆 Capstone Project: AI-Powered SRE Assistant

**Goal**: Build an application that demonstrates all 4 domains

```
Architecture:
┌─────────────┐     ┌──────────────┐     ┌─────────────┐
│  React UI    │────▶│  API Gateway  │────▶│  Lambda/AI  │
│  Dashboard   │     │  (AWS)        │     │  Service    │
└─────────────┘     └──────────────┘     └─────────────┘
                           │                     │
                    ┌──────▼──────┐      ┌───────▼───────┐
                    │ CloudWatch   │      │  ML Model     │
                    │ Monitoring   │      │  (Anomaly Det)│
                    └─────────────┘      └───────────────┘
                           │                     │
                    ┌──────▼──────────────────────▼──────┐
                    │         Terraform IaC               │
                    │    (VPC, ECS, Lambda, S3, RDS)     │
                    └────────────────────────────────────┘
```

**Features**:
- Real-time anomaly detection on system metrics
- AI-powered incident classification and runbook suggestions
- Automated SLO tracking dashboard
- Infrastructure provisioned entirely via Terraform
- CI/CD pipeline with GitHub Actions + ArgoCD

---

## 📅 Daily Study Routine (Suggested)

| Time | Activity | Duration |
|------|----------|----------|
| Morning | Theory / Reading / Video courses | 1-1.5 hrs |
| Afternoon | Hands-on lab / Practice | 1-2 hrs |
| Evening | Review + Cheat sheet updates + Daily drill | 30 min |

> 💡 **Pro Tip**: Spend 70% of your time on hands-on practice and 30% on theory. SRE is a doing discipline!

---

*Built with ❤️ by Cline SR for Prem*
