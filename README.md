# cloud-learning-roadmap
My cloud learning roadmap – feedback welcome
# 🧱 Cloud Learning Plan — DevOps & Cloud Engineering Journey

This roadmap is designed to build skills step by step, from Linux basics to full Cloud/DevOps engineering.  
Each phase includes goals, resources, and mandatory projects.

---

## PHASE 0 — SETUP (Week 0–1)

🎯 **Goal:** Prepare environment like a real engineer  

**Do this once:**
- Install Linux (WSL Ubuntu or native)
- Create GitHub account
- Create tech-only Gmail
- Install VS Code, Git, Python

**Learn:**
- VS Code basics
- Terminal inside VS Code

❌ No course  
❌ No cert  
👉 Just setup  

---

## PHASE 1 — LINUX + GIT + EDITORS (Months 0–3)

⏱️ 5 hrs/week  
🎯 **Goal:** Terminal-first mindset  

**What to Learn:**
- Linux commands  
- File permissions  
- Users & processes  
- SSH  
- Git basics  
- Editors: nano + vim (basic)  

**Free Resources (in order):**
1. [Linux for Beginners – Full Course (freeCodeCamp)](https://www.youtube.com/watch?v=...)  
2. [Linux Journey](https://linuxjourney.com) → Basics → Command Line → Permissions  
3. [Git & GitHub for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=...)  
4. [Vim Basics (freeCodeCamp)](https://www.youtube.com/watch?v=...)  

**Mandatory Project — Linux Survival**
- Create users & folders  
- Set permissions  
- SSH into own machine  
- GitHub README:  
  - 10 commands you use daily  
  - chmod explained  
  - SSH explained simply  

👉 Do this BEFORE next phase  

---

## PHASE 1.5 — BASH SCRIPTING (Months 3–4)

⏱️ 5 hrs/week  
🎯 **Goal:** Real DevOps automation  

**What to Learn:**
- Variables  
- if / else  
- loops  
- functions  
- `.sh` files  
- cron jobs  

**Free Resource:**  
- [Bash Scripting Full Course – freeCodeCamp](https://www.youtube.com/watch?v=...)  

**Mini Project — Bash Automation**
- Disk usage checker  
- Log cleanup script  
- Backup script  
- Run via cron  

---

## PHASE 2 — PYTHON + SQL + APP START (Months 4–7)

⏱️ 5 hrs/week  
🎯 **Goal:** Automation + reusable app  

**What to Learn:**
- Python basics  
- Files & OS automation  
- Flask basics  
- SQL basics  

**Free Resources:**
1. [Python for Beginners – freeCodeCamp](https://www.youtube.com/watch?v=...)  
2. [Automate the Boring Stuff](https://www.youtube.com/watch?v=...)  
3. [SQL for Beginners – freeCodeCamp](https://www.youtube.com/watch?v=...)  

**Projects:**
- 🧪 Project 2 — Automation Script  
  - Rename files  
  - Log output  
  - Run via terminal  
- 🧪 Project 2.5 — Core App (IMPORTANT)  
  - Simple Flask API  
  - `/health` endpoint  
  - Logs to file  
  - 👉 This ONE APP will be reused till Phase 8  

---

## PHASE 3 — NETWORKING + SECURITY BASICS (Months 8–10)

⏱️ 5 hrs/week  
🎯 **Goal:** Understand how cloud REALLY works  

**What to Learn:**
- IP, DNS, HTTP  
- Ports  
- Load balancer (concept)  
- Firewalls  
- SSH security  
- TLS (high level)  

**Free Resource:**  
- [Computer Networking Full Course – freeCodeCamp](https://www.youtube.com/watch?v=...)  

**Project — Explain the Internet**
- README:  
  - What happens when typing google.com  
  - DNS  
  - Port 443  
  - Firewall role  

---

## PHASE 4 — AWS CORE + COST + SECURITY (Months 11–18)

⏱️ 5 hrs/week  
🎯 **Goal:** Real cloud engineer foundations  

**What to Learn:**
- EC2, S3  
- IAM (Policies!)  
- VPC (basic)  
- AWS CLI  
- Cloud costs  
- CloudWatch basics  

**Free Resources:**
1. AWS Skill Builder → *AWS Cloud Practitioner Essentials* (FREE)  
2. [AWS Hands-On Full Course – freeCodeCamp](https://www.youtube.com/watch?v=...)  

**Cert Milestone 🏅**  
✅ AWS Cloud Practitioner  

**Projects:**
- 🧪 Project 4 — EC2 + SSH  
  - Secure EC2  
  - SSH  
  - Install Nginx  
- 🧪 Project 5 — S3 Website  
  - Static site  
  - CLI + console  
- 🧪 Cost Task  
  - Estimate monthly cost of your setup  

---

## PHASE 5 — DOCKER + docker-compose (Months 19–24)

⏱️ 8–10 hrs/week  
🎯 **Goal:** Container mastery  

**What to Learn:**
- Dockerfile  
- Images vs containers  
- docker-compose (multi-service)  
- Logging in containers  

**Free Resource:**  
- [Docker Full Course – freeCodeCamp](https://www.youtube.com/watch?v=...)  

**Project — Containerized App**
- Flask app  
- Dockerfile  
- docker-compose (app + nginx)  

---

## PHASE 6 — TERRAFORM + STATE (Months 25–30)

⏱️ 8–10 hrs/week  
🎯 **Goal:** Infrastructure as Code  

**What to Learn:**
- Providers  
- Variables  
- State  
- Remote state (concept)  

**Free Resource:**  
- [Terraform From Zero – freeCodeCamp](https://www.youtube.com/watch?v=...)  

**Project — Terraform AWS**
- EC2 + SG  
- Variables  
- Destroy & recreate  

---

## PHASE 7 — CI/CD + TESTING + SECRETS (Months 31–36)

🎯 **Goal:** Production pipelines  

**What to Learn:**
- GitHub Actions  
- Testing basics  
- Linting  
- Secrets management  

**Free Resource:**  
- [GitHub Actions Full Course – freeCodeCamp](https://www.youtube.com/watch?v=...)  

**Project — CI/CD**
- On push:  
  - Test app  
  - Build Docker  
  - Push image  

---

## PHASE 8 — KUBERNETES + MONITORING + INCIDENTS (Months 37–48)

🎯 **Goal:** Job-ready Cloud/DevOps Engineer  

**What to Learn:**
- Kubernetes core  
- Helm  
- Prometheus  
- Grafana  
- Logs  
- Incident response  
- Multi-cloud awareness (concept)  

**Free Resources:**
- [Kubernetes Full Course – freeCodeCamp](https://www.youtube.com/watch?v=...)  
- Prometheus + Grafana (YouTube)  

**Final Project 🧨 — Real-World System**
- Flask app  
- Docker  
- Kubernetes  
- CI/CD  
- Monitoring dashboard  
- AWS hosting  

**Cert Milestones 🏅**
- AWS Solutions Architect Associate  
- (Optional) CKA later  

---

## 🤝 How to Contribute

I’m a beginner learning cloud engineering and I’d love your feedback or help!  
Here’s how you can contribute:

1. **Suggestions / Feedback**  
   - Open an **Issue** on this repo and write your advice or suggestions.

2. **Edit the Roadmap**  
   - Fork the repo  
   - Make your changes  
   - Create a **Pull Request** so I can review and merge them

3. **Share Resources**  
   - If you know good tutorials, videos, or guides, please suggest them in an issue.

Thank you for helping me grow! 🙏
