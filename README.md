<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Santhosh%20Venkatachalam&fontSize=40&fontColor=fff&animation=twinkling&fontAlignY=35&desc=DevOps%20Engineer%20%7C%20AWS%20%7C%20Microsoft%20Azure%20%7C%20Terraform%20%7C%20Kubernetes&descAlignY=55&descSize=18)

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=700&lines=Provisioning+AWS+infrastructure+with+Terraform...;Automating+CI%2FCD+pipelines+with+GitHub+Actions...;Building+real-time+observability+dashboards...;Deploying+containers+to+Kubernetes+on+EKS...;Enforcing+IAM+least-privilege+security...;Alerts+firing+in+15+seconds+on+production+errors...;1%2B+year+shipping+production+cloud+systems." alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/santhosh173/)&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://santhosh-folio.netlify.app)&nbsp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:santhosh.rv173@gmail.com)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/santhosh-v-173)

<br/>

![Visits](https://komarev.com/ghpvc/?username=santhosh-v-173&label=Profile+Views&color=0e75b6&style=flat-square)
![AWS SAA](https://img.shields.io/badge/AWS_SAA--C03-In_Progress-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Open to Work](https://img.shields.io/badge/Status-Open_to_Work-2ea44f?style=flat-square)

</div>

---

## Who Am I

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1000&color=58A6FF&width=500&lines=DevOps+Engineer+%7C+Cloud+%7C+IaC+%7C+Observability" alt="Typing SVG" />

```yaml
name       : Santhosh Venkatachalam
role       : DevOps Engineer
experience : 1+ year
location   : Coimbatore, Tamil Nadu, India
company    : Gravity AI Technologies Pvt. Ltd.
learning   : AWS Solutions Architect Associate (SAA-C03) — In Progress 2026
superpower : Zero infra -> Production-grade system in days
mindset    : Build it observable, secure, and self-healing.
```

---

## Impact at a Glance

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1000&color=F8A000&width=500&lines=Real+metrics+from+real+production+systems." alt="Typing SVG" />

<div align="center">

| Metric | Result |
|--------|--------|
| Deployment time reduced | **~70%** via GitHub Actions CI/CD |
| Incident detection (MTTD) cut | **~55%** via Lambda alert system |
| Infrastructure provisioning faster | **~65%** via Terraform automation |
| Server operational overhead reduced | **~40%** via serverless microservices |
| Manual log triage eliminated | **~60%** via Power BI Streaming Dashboard |
| Critical alert response time | **15 seconds** via Telegram bot |

</div>

---

## Work Experience

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1000&color=3FB950&width=600&lines=Gravity+AI+Technologies+Pvt.+Ltd.,+Coimbatore" alt="Typing SVG" />

<details>
<summary><b>Full-Time &nbsp;·&nbsp; Junior Associate DevOps &nbsp;·&nbsp; AUG 2025 – FEB 2026</b></summary>
<br/>

| Area | What I Shipped |
|------|----------------|
| **Infrastructure** | Terraform — ALB, Auto Scaling, EC2, VPC, ACM, SNS; S3 state + DynamoDB lock — **65% faster** provisioning |
| **Security** | IAM least-privilege across all AWS services — zero over-permissioned roles |
| **Alerting** | Lambda + CloudWatch — Telegram bot in **15 sec** for 503/fatal/socket errors — MTTD down **55%** |
| **Observability** | Power BI Streaming Dashboard — Sentry + PostHog + Mixpanel via Lambda — log triage down **60%** |
| **Reliability** | Elasticsearch snapshot DR + heartbeat monitoring across all production nodes |
| **Platform** | Self-hosted n8n, OpenWebUI, cal.com on EC2 + Nginx reverse proxy |
| **Auth** | Auth0 Actions — pre-registration blocking + post-login email skip for verified users |
| **DNS & CDN** | Cloudflare DNS routing + CDN caching for all production endpoints |
| **Process** | Agile 2-week sprints (Jira) + complete Notion documentation per deployment |

</details>

<details>
<summary><b>Internship &nbsp;·&nbsp; Junior Associate DevOps &nbsp;·&nbsp; JAN 2025 – JUL 2025</b></summary>
<br/>

| Area | What I Shipped |
|------|----------------|
| **Serverless** | Lambda + API Gateway + S3 via CloudFormation — server overhead down **40%** |
| **CI/CD** | GitHub Actions + SonarQube + ESLint + Lighthouse multi-stage pipelines — deploy time down **70%** |
| **Code Quality** | Self-hosted SonarQube on EC2 — static analysis + CI quality gates |
| **Observability** | Sentry + PostHog + Mixpanel — incident resolution down **50%** |
| **Search** | Self-hosted Elasticsearch on EC2 — custom index schema + structured data ingestion |
| **Auth** | Auth0 social login (Google, Facebook, LinkedIn) + custom branded UI |
| **Notifications** | SES + Lambda email templates + WhatsApp message parser |
| **Architecture** | Full production architecture mapped in draw.io — observability gaps identified and fixed |

</details>

---

## Featured Projects

### System Monitoring App — CI/CD on AWS EKS

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=2000&color=A5D6FF&width=700&lines=From+git+push+to+pods+running+in+production+%7C+Zero+manual+steps" alt="Typing SVG" />

```
  git push
     |
     v
 GitHub Webhook ------> Jenkins Pipeline triggers on EC2
                               |
              .----------------+----------------.
              v                v                v
        Docker Build      Tag image with    Push to
        (Flask App)       BUILD_NUMBER      AWS ECR
                               |
                               v
                       Helm deploys to AWS EKS
                               |
                    .----------+----------.
                    v                     v
               Pod 1 (Running)      Pod 2 (Running)
```

**The App** — Real-time CPU and Memory dashboard

```
CPU  45%  [========--------]  Normal
CPU  72%  [=============---]  Warning
CPU  85%  [================]  Critical  <- Auto alert banner fires
```

**Stack:** `Python Flask` `Psutil` `Plotly` `Docker` `AWS ECR` `AWS EKS` `Helm 3` `Jenkins on EC2` `GitHub Webhooks`

**Key learnings:**
- `BUILD_NUMBER` image tagging strategy for versioning and rollbacks
- Helm `values.yaml` templating for environment-specific configs
- `kubeconfig` setup inside Docker containers
- GitHub webhook IP whitelisting for secure pipeline triggers
- Pod debugging with `kubectl logs` and `kubectl describe`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github)](https://github.com/santhosh-v-173/system-monitoring-app)

---

### FuturX — Production-Grade Cloud Platform

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=2000&color=A5D6FF&width=700&lines=AI-powered+SaaS+%7C+Sole+DevOps+Engineer+%7C+Full+ownership+from+day+one" alt="Typing SVG" />

```
.---------------------------------------------------------------.
|               FuturX Cloud Architecture                       |
|-------------.-------------.---------------.-------------------|
| Infra (IaC) |   CI/CD     | Observability |  Security & Auth  |
|             |             |               |                   |
| Terraform   | GitHub      | Sentry        | Auth0             |
| EC2 + VPC   | Actions     | PostHog       | IAM Policies      |
| ALB + ASG   | SonarQube   | Mixpanel      | Cloudflare DNS    |
| Lambda + S3 | ESLint      | Power BI      | Nginx Proxy       |
| ACM + SNS   | Lighthouse  | CloudWatch    | Elasticsearch     |
.-------------.-------------.---------------.-------------------.
```
[Website Link](https://futurx.app)

---

### Employee Management System (EMS) — Azure Container Deployment

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=2000&color=A5D6FF&width=700&lines=Containerized+PHP+Application+Deployment+on+Microsoft+Azure" alt="Typing SVG" />

```text
GitHub Actions
       |
       v
Docker Build & Push
       |
       v
Azure Container Registry (ACR)
       |
       v
Azure Container Apps
       |
       v
Azure Database for MySQL
```

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github)](https://github.com/santhosh-v-173/php-ems-azure)

---

## Tech Stack

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1000&color=D2A8FF&width=435&lines=Tools+I+use+in+production." alt="Typing SVG" />

<div align="center">

**Cloud and Infrastructure**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure Container Apps](https://img.shields.io/badge/Azure_Container_Apps-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure Container Registry](https://img.shields.io/badge/Azure_ACR-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**CI/CD and Containers**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)

**Monitoring and Observability**

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

**Security and Networking**

![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Auth0](https://img.shields.io/badge/Auth0-EB5424?style=for-the-badge&logo=auth0&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

**Scripting and Tools**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

</div>

---

## Certifications and Achievements

```
.----------------------------------------------------------------.
|                                                                |
|  AWS Solutions Architect Associate (SAA-C03)                  |
|  [##########..........] In Progress — 2026                    |
|                                                                |
|----------------------------------------------------------------|
|                                                                |
|  Workshop Speaker — Build Cloud with Terraform   Jan 2026     |
|  Hands-on IaC: real-world AWS provisioning + best practices   |
|                                                                |
|  Workshop Speaker — DevOps and SRE Workshop      Nov 2025     |
|  AWS · CloudFormation · Grafana · Prometheus · Cloudflare     |
|                                                                |
.----------------------------------------------------------------.
```

---

## GitHub Stats

<div align="center">

![GitHub followers](https://img.shields.io/github/followers/santhosh-v-173?style=for-the-badge&logo=github&logoColor=white&color=0e75b6)
&nbsp;
![GitHub stars](https://img.shields.io/github/stars/santhosh-v-173?style=for-the-badge&logo=github&logoColor=white&color=0e75b6)

<br/><br/>

<img src="https://streak-stats.demolab.com?user=santhosh-v-173&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" height="170"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=santhosh-v-173&theme=tokyo-night&hide_border=true&area=true" width="95%"/>

</div>

<br/><br/>

---

## Education

**B.Sc. Computer Science with Data Analytics** · `2022 – 2025`
Dr. N.G.P Arts and Science College *(Autonomous)*, Affiliated to Bharathiar University · Coimbatore, Tamil Nadu

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=15&pause=1500&color=58A6FF&center=true&vCenter=true&width=600&lines=Open+to+DevOps+%7C+Cloud+%7C+SRE+roles;Let%27s+build+something+reliable+together.;Reach+out+at+santhosh.rv173%40gmail.com" alt="Typing SVG" />

<br/><br/>

[![Connect on LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/santhosh173/)
&nbsp;
[![View Portfolio](https://img.shields.io/badge/View_Portfolio-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://santhosh-folio.netlify.app)

<br/>

![footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer)

</div>
