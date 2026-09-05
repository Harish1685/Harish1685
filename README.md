<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&text=Harish%20Kumar&fontSize=50&fontAlignY=38&animation=twinkling&fontColor=ffffff&color=0:020617,35:1E3A8A,70:2563EB,100:38BDF8"/>

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=23&duration=3200&pause=1100&color=93C5FD&center=true&vCenter=true&width=800&lines=DevOps+%26+Cloud+Engineer+%E2%80%A2+Fresher;I+Automate+Infrastructure+and+Ship+Apps+with+CI%2FCD;Open+to+DevOps+Internships+%26+Entry-Level+Roles"/>

<br>

<a href="https://github.com/Harish1685"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://linkedin.com/in/harishkumar168"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:kumarharish01685@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

---

# 👋 Hi, I'm Harish Kumar

A **DevOps & Cloud Engineering fresher** from Hyderabad. I learn by doing: I take full-stack apps, **containerize them**, build the AWS infrastructure with **Terraform**, and ship them through **CI/CD and GitOps** — then I break things on purpose and fix them until I understand them.

> ### 🎯 Actively looking for a **DevOps Internship** or **Entry-Level DevOps Engineer** role.

| 📍 **Hyderabad, India** | ⚡ **Open to Remote / Hybrid / Office** | ✈️ **Open to Relocating** |
|---|---|

---

# 🛠️ Skills

**☁️ Cloud & Infrastructure as Code**
<img src="https://skillicons.dev/icons?i=aws,terraform"/>

**🐳 Containers & Orchestration**
<img src="https://skillicons.dev/icons?i=docker,kubernetes"/>

**🔄 CI/CD & GitOps**
<img src="https://skillicons.dev/icons?i=jenkins,githubactions,argo"/>

**📊 Monitoring**
<img src="https://skillicons.dev/icons?i=prometheus,grafana"/>

**💻 Languages & Databases** *(used hands-on in my 3-tier projects)*
<img src="https://skillicons.dev/icons?i=python,bash,mysql,mongodb"/>

**🐧 Fundamentals**
<img src="https://skillicons.dev/icons?i=linux,git"/> <img src="https://img.shields.io/badge/Networking%20Basics-1E3A8A?style=flat-square"/>

> *Everything above is something I've actually used hands-on in a project — not just watched in a tutorial.*

**☁️ AWS services I've provisioned:** EC2 · VPC · EKS · EBS · S3 · DynamoDB · IAM

---

# 📌 Featured Projects

## ☁️ 1. Easy-Shop — Cloud-Native Deployment on AWS EKS

> **What I did:** took a full-stack Next.js + MongoDB storefront and built the whole production deployment around it — **the infrastructure & delivery work is mine.**

- 🏗️ **Terraform**: VPC, EC2, **Amazon EKS** cluster
- 🔨 **Jenkins** CI with **Trivy** image scanning
- 🔄 GitOps delivery with **Argo CD** (auto-sync, single repo)
- 📊 **Prometheus & Grafana** monitoring + HTTPS via cert-manager
- 🐛 Debugged real problems: GitOps sync loops, private-subnet LoadBalancer, immutable Job sync hooks

<a href="https://github.com/Harish1685/Easy-Shop-E-commerce"><img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<p align="center"><img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/> <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/> <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white"/> <img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white"/> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/></p>

*Also used here: Prometheus · Trivy · cert-manager · ingress-nginx (see "What I did" above)*

---

## ⚙️ 2. Student–Teacher Portal — Modular IaC + Self-Verifying CI/CD

> **What I did:** designed **reusable Terraform modules** and a pipeline that actually *proves* the deploy works — it never just claims "deploy OK".

- 🧱 Modular **Terraform** (VPC, EC2, security groups) with **remote state** (S3 + DynamoDB)
- 🐳 React + Node + **MySQL** running on **Docker Compose** — restart policies + real healthchecks
- 🔄 **GitHub Actions**: pulls new images first → waits for healthy services → smoke-tests the site & API. Bad code fails **loudly**, the old app stays up.
- 🐛 Fixed a real bug: a lazy DB pool meant retries could never detect a dead database — now it runs a real `SELECT 1`

<a href="https://github.com/Harish1685/Student-Teacher-Portal"><img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<p align="center"><img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/> <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/></p>

---

## ⚡ 3. DevOps Utilities API

> **What I did:** built a small FastAPI service that automates everyday ops tasks over REST.

- ⚡ System health endpoints · ☁️ AWS S3 automation with Boto3 · 🐳 Dockerized

<a href="https://github.com/Harish1685/devops-utilities-api"><img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<p align="center"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white"/></p>

---

# 🌱 How I Learn

> *"The best way to learn DevOps is by building, breaking, fixing, and automating real projects."*

I keep a daily practice block: I explain my own project's architecture out loud as if I'm in an interview, then I break something on purpose — kill a running container, drop a database, let a deploy fail — and fix it using logs and documentation before I reach for AI. If I can't explain the fix back in my own words, I haven't learned it yet, so it becomes the next day's lesson.

---

# 🤝 Let's Talk

<div align="center">

If you're hiring for a **DevOps / Cloud** role — or want to talk infrastructure, automation, or breaking things on purpose — reach out.

<a href="https://github.com/Harish1685"><img src="https://img.shields.io/badge/GitHub-Harish1685-181717?style=for-the-badge&logo=github"/></a>
<a href="https://linkedin.com/in/harishkumar168"><img src="https://img.shields.io/badge/LinkedIn-Harish%20Kumar-0A66C2?style=for-the-badge&logo=linkedin"/></a>
<a href="mailto:kumarharish01685@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail"/></a>

<br>
<br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:0F172A,100:2563EB"/>

<br>

<img src="https://komarev.com/ghpvc/?username=Harish1685&color=1E3A8A&style=flat-square" alt="Profile views"/>

</div>
