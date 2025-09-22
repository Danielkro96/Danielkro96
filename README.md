# Daniel Krochero

DevOps & Cloud Engineer focused on **AWS**, **Infrastructure as Code**, and **platform reliability** in regulated, enterprise environments (banking/fintech). I design, automate, and harden delivery pipelines and data flows end-to-end—from Git workflows and CI/CD to observability, cost, and security.

> “Ship fast, stay secure, measure everything.”

---

## 🔧 Core stack

- **Git & Platforms:** Git, **Bitbucket**, **GitLab**, GitHub
- **CI/CD:** **Jenkins** (Groovy pipelines), GitLab CI, GitHub Actions
- **IaC & Cloud:** **Terraform**, **AWS** (IAM, KMS/BYOK & replicas, S3, VPC, ALB/NLB, ECS/EKS, RDS, **Lambda**, Budgets/Cost filters)
- **Containers & Orchestration:** **Docker**, **Kubernetes**, **OpenShift**, **GitOps** (declarative envs & promotions)
- **Automation & Scripting:** **Python**, **Linux** & **Bash** (tooling, packaging, glue code)
- **Observability:** **Splunk**, **Dynatrace** (dashboards, alerts, SLO/SLA wiring)
- **Data:** **SQL Server**, PostgreSQL, **MongoDB/DocumentDB**, DynamoDB
- **Testing:** **Selenium** (UI smoke/regression), infra validation, pipeline tests
- **Environment Orchestration:** **Quali Torque** (blueprints, grains, ephemeral envs)

---

## 🧭 What I’m good at

- **IaC at scale:** reusable Terraform modules, opinionated defaults, variable validation, dynamic blocks, multi-env patterns.
- **Secure delivery:** IAM least-privilege, KMS/BYOK (multi-region replicas), certificate chains & ACM flows, S3/KMS policies.
- **AWS serverless:** Lambda (container images & zip), event sources (S3/SQS/Kinesis), logging, KMS-encrypted log groups, cost & performance guardrails.
- **Git-driven workflows:** trunk-based or protected-branch models, PR templates, checks, and promotion gates.
- **K8s/OpenShift platforms:** build/run images, sealed secrets, namespace templates, ingress, health/readiness, autoscaling.
- **Observability you can act on:** Splunk + Dynatrace dashboards, alerts, runbooks, and SLOs tied to CI gates.
- **Data plumbing:** schema (SQL & Mongo/DocumentDB), dumps/restores with TLS/CA bundles, least-privilege access.
- **Quali Torque:** blueprints for on-demand full-stack environments; inputs/outputs, cost controls, teardown reliability.

---

## 🧪 Favorite patterns

- **GitOps everywhere:** declarative state + automated reconciliations for infra and apps.
- **Pipelines as product:** shared libraries, reusable steps, policy-as-code.
- **Cost awareness:** budgets with granular filters, usage tags, and early-warning alerts wired to chat/email.
- **“Golden” module/library approach:** one place to fix, many places to benefit.

---

## 📦 Example building blocks (abridged)

- **Terraform**
  - ALB/NLB modules with listeners/rules, target groups, per-env tags/labels.
  - KMS BYOK primary/replica with aliasing, deletion windows, key policies.
  - VPC endpoints for OpenSearch, S3, STS; private subnets, routing.
  - RDS Postgres (IAM auth option), DocumentDB clusters, DynamoDB tables.
  - Lambda (ECR image / zip), env vars, ephemeral storage, log groups (KMS).

- **Jenkins**
  - Multi-stage pipelines (build → test → security scans → package → deploy).
  - ECR login & image promotion by tag; branch/PR policies; chat notifications.

- **Python/Bash**
  - Data movers (S3↔DB), CSV→Markdown transforms, batch writes to DynamoDB.
  - Cert/PKI helpers (PFX/JKS conversions), CA bundle validation.

- **Observability**
  - Splunk correlation searches for noisy flows → actionable alerts.
  - Dynatrace service maps, SLOs, release dashboards tied to pipeline metadata.

---

## 🔍 Tools I reach for

`Terraform` · `awscli` · `kubectl` · `oc` · `helm` · `kustomize` · `docker` · `jq` · `yq` · `psql` · `mongodump`/`mongorestore` · `pytest` · `Selenium` · `pre-commit` · `tflint` · `checkov`

---

## 📚 Selected topics (quick links)

- **Git / Bitbucket / GitLab:** branching models, protected branches, PR templates, codeowners, commit conventions.  
- **IaC (Terraform):** modules > stacks, workspaces, remote state, drift detection, `for_each`, `dynamic`, validation blocks.  
- **Splunk & Dynatrace:** env tagging strategy, dashboards per service, noise reduction, runbooks.  
- **SQL Server & Postgres:** IAM auth (where applicable), connection tooling, least-privilege roles.  
- **Docker & OpenShift/Kubernetes:** image hardening, resource requests/limits, readiness/liveness, secrets handling.  
- **GitOps:** desired state repos, automated promotions, policy gates in CI.  
- **Selenium:** smoke packs for critical user journeys post-deploy.  
- **Quali Torque:** ephemeral envs for feature branches; inputs/outputs wired to pipelines.  
- **AWS & Lambda:** event-driven patterns, DLQs, structured logging, KMS encryption, budget alerts.  
- **Linux & Bash:** reliable scripts with `set -Eeuo pipefail`, traps, and safe temp handling.  
- **Jenkins:** shared libraries, parameterized pipelines, environment matrices.  
- **Python:** CLI tools, data transforms, AWS SDK (boto3), testing and packaging.  
- **MongoDB/DocumentDB:** indexes, migrations, TLS/CA, backups/restores.

---

## 🗂️ Pinned ideas (add repos when public)

- `terraform-aws-*` — opinionated modules (KMS BYOK, ALB/NLB, Lambda, VPC endpoints, budgets).  
- `jenkins-shared-lib` — reusable steps (ECR, OPA/Checkov gates, Slack, Git semver).  
- `lambda-utils` — Python helpers (structured logging, env parsing, S3/KMS wrappers).  
- `quali-torque-blueprints` — blueprints for ephemeral test/stage envs.  

---

## 🗣️ Languages

- English, Hebrew (בקרה, תיעוד, והרצה יומיומית)

> תקציר בעברית: אני עוסק ב-DevOps/Cloud עם דגש על Terraform ו-AWS, CI/CD (Jenkins/GitLab), קונטיינרים (Docker, Kubernetes/OpenShift), תצפיות (Splunk/Dynatrace), ו-Data (SQL Server, Mongo/DocumentDB). אוהב אוטומציה מאובטחת, GitOps, ומודולים לשימוש חוזר.

---

## 🤝 Connect

- Open to collaboration on **Terraform modules**, **Jenkins/GitOps templates**, and **AWS Lambda/serverless** patterns.  
- PRs, issues, and discussions welcome—if it automates or clarifies, I’m in.

---
