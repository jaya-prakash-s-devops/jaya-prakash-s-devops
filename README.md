
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:70A5FD,100:BF91F3&height=200&section=header&text=Jaya%20Prakash%20S&fontSize=48&fontColor=ffffff&animation=fadeIn&desc=DevOps%20Engineer%20%7C%20AWS%20%7C%20Kubernetes%20%7C%20Terraform%20%7C%20CI%2FCD%20Automation&descSize=18&descAlignY=75" width="100%"/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/jaya-prakash-s-1ba6442bb)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/jaya-prakash-s-devops)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jayasmasher1993@gmail.com)
[![AWS Certified](https://img.shields.io/badge/AWS_Certified-Cloud_Practitioner-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/certified-cloud-practitioner/)

</div>

---

## About

DevOps Engineer with hands-on experience building end-to-end infrastructure automation pipelines and containerized application platforms on AWS. Proven track record delivering production-grade systems using Terraform, Ansible, Kubernetes, Docker, and GitHub Actions. AWS Certified Cloud Practitioner with a focus on IaC, CI/CD automation, monitoring, and zero-touch deployment workflows.

---

## 🚀 Featured Projects

### Kubernetes-Based DevOps Task Management Platform
> `Kubernetes` · `Prometheus` · `Grafana` · `GitHub Actions` · `Docker` · `Flask` · `MySQL` · `Nginx`

**[🔗 View Repository](https://github.com/jaya-prakash-s-devops/devops-task-platform)**

Built and deployed a production-grade containerized multi-tier platform on Kubernetes with full observability stack.

| Area | Implementation |
|------|---------------|
| **Orchestration** | Kubernetes Deployments, Services, Secrets, Ingress, PVCs, ServiceMonitors |
| **CI Pipeline** | GitHub Actions — automated Docker image build, versioning, and push to Docker Hub |
| **Monitoring** | Prometheus + Grafana + MySQL Exporter — pod metrics and Flask application metrics |
| **Stack** | Flask backend · MySQL database · Nginx reverse proxy · Docker containers |

**Key outcomes:** Fully automated image delivery pipeline; centralized metrics dashboards via Grafana; persistent data across pod restarts via PVCs.

---

### End-to-End Infrastructure Automation Pipeline
> `Terraform` · `Ansible` · `GitHub Actions` · `AWS` · `Docker` · `S3 Remote Backend`

**[🔗 View Repository](https://github.com/jaya-prakash-s-devops/Terraform-and-Ansible-infrastructure-automation-project)**

A single `git push` triggers the complete pipeline — from infrastructure provisioning to a live running application, with zero manual steps.

```
Git Push → GitHub Actions → Terraform (init/validate/plan/apply)
        → AWS (VPC · Subnets · IGW · Security Groups · EC2 · Elastic IP · S3 Backend)
        → Ansible (Docker install · repo clone · Docker Compose up)
        → Application Live
```

| Engineering Decision | Rationale |
|----------------------|-----------|
| S3 Remote Backend | Centralized Terraform state — team-safe, no local drift |
| Elastic IP reuse | Stable addressing across destroy/recreate cycles |
| Terraform + Ansible separation | Clear concerns: provisioning vs. configuration management |
| GitHub Actions orchestration | No CI server required; secrets-managed credentials |
| Idempotent Ansible playbooks | Safe to re-run at any stage of the pipeline |

**Key outcomes:** Reduced manual server setup from ~45 min to under 5 min; 90%+ deployment automation coverage.

---

## 🛠️ Tech Stack

**☁️ Cloud — AWS**

![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=flat-square&logo=amazonaws&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-8C4FFF?style=flat-square&logo=amazonaws&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazoncloudwatch&logoColor=white)
![Route53](https://img.shields.io/badge/Route_53-8C4FFF?style=flat-square&logo=amazonroute53&logoColor=white)
![SNS](https://img.shields.io/badge/SNS-FF4F8B?style=flat-square&logo=amazonaws&logoColor=white)

**⚙️ Infrastructure as Code & Configuration Management**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

**🔄 CI/CD & Containers**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**📡 Monitoring & Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazoncloudwatch&logoColor=white)

**🖥️ OS, Scripting & Networking**

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**🔧 Version Control & Databases**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

---

## 🏅 Certifications

| Certification | Issuer | Year |
|--------------|--------|------|
| ☁️ **AWS Certified Cloud Practitioner** (CLF-C02) | Amazon Web Services | Nov 2025 · Valid until Nov 2028 |
| 🚀 **AWS re/Start Graduate** | AWS & TNSkills | Sep 2025 |
| 🏗️ **Terraform: Managing Infrastructure as Code** | Packt | May 2026 |
| 📦 **100 Days of DevOps Bootcamp** | Udemy | Mar 2026 |

---

## 📊 GitHub Stats

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=jaya-prakash-s-devops&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=70a5fd&icon_color=bf91f3&text_color=c9d1d9&border_radius=10"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jaya-prakash-s-devops&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=70a5fd&text_color=c9d1d9&langs_count=8&border_radius=10"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=jaya-prakash-s-devops&theme=tokyonight-duo&hide_border=true&background=0D1117&ring=70A5FD&fire=BF91F3&currStreakLabel=70A5FD&sideLabels=38BDAE&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9&stroke=0D1117&border_radius=10"/>
</div>

---

<div align="center">

**Chennai, Tamil Nadu, India · Open to relocation across India**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/jaya-prakash-s-1ba6442bb)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/jaya-prakash-s-devops)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jayasmasher1993@gmail.com)

*Seeking full-time roles in DevOps Engineering · Cloud Engineering · Platform Engineering · SRE · Infrastructure Engineering*

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:BF91F3,100:70A5FD&height=120&section=footer&animation=twinkling" width="100%"/>
