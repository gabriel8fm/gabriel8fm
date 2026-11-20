<h1 align="center">Hi, I'm Gabriel Miranda 👋</h1>
<h3 align="center">Senior Cloud / Platform Engineer · Specializing in DataOps</h3>

<h3> :man_technologist: About Me </h3>

- :bulb:          &nbsp; 15+ years turning fragile infrastructure into reliable, self-service platforms, with DevOps and platform roles since 2018.
- :briefcase:     &nbsp; Working across Platform Engineering Architecture roles.
- :cloud:         &nbsp; Deep hands-on experience designing and running multi-cloud (AWS & GCP) production systems for food service, retail, payments, e-commerce and climate tech.
- :earth_americas: &nbsp; Fully remote with US-based teams since 2020.
- :bar_chart:     &nbsp; Specializing in DataOps on Google Cloud: tested, observable and replayable data pipelines.
- :mortar_board:  &nbsp; Postgraduate student in Applied AI Software Engineering (expected 2028).
- :books:         &nbsp; Always learning Cloud Architecture, Infrastructure as Code, Kubernetes, and applied AI tooling.

<h3> :rocket: Experience Highlights </h3>

- :whale: &nbsp; **Kubernetes since 2020.** Private, regional GKE clusters built with Terraform (private endpoint, Workload Identity, Cloud NAT) and EKS clusters, with platform components delivered through Helm and ArgoCD: cert-manager, Traefik, OPA Gatekeeper and OpenCost.
- :arrows_counterclockwise: &nbsp; **Migrations.** Moved VM workloads to GKE with Helm charts, improving deployment efficiency by 30% (measured with DORA metrics), and moved applications from a PaaS to private GKE clusters with Cloud SQL.
- :hammer_and_wrench: &nbsp; **Infrastructure as Code.** Reusable Terraform/OpenTofu modules with one tfvars file per environment, locked remote state, and a plan on every pull request.
- :zap: &nbsp; **CI/CD.** Redesigned GitLab pipelines with a job dependency graph, caching and parallel stages, cutting average duration by 15%+. Keyless deployments with OIDC federation.
- :package: &nbsp; **Data delivery.** Built a Python deploy tool for data jobs with check, plan, apply and pull commands: content hashes prove production matches git, drift stops the deploy, and each apply records versions for a one-step rollback.
- :incoming_envelope: &nbsp; **Event pipelines.** Event-driven order pipelines with two dead-letter layers, redrive policies and error tagging, so failed messages are kept and can be replayed.
- :telescope: &nbsp; **Observability.** Grafana alert rules, synthetic checks and scrape jobs managed as code. Supporting development teams with OpenTelemetry collectors and Grafana Alloy. Datadog, New Relic and Prometheus in earlier roles.
- :lock: &nbsp; **Security.** Least-privilege IAM, centralized secrets management, WAF rule sets, private clusters, and PCI-DSS certification for a payments platform.
- :busts_in_silhouette: &nbsp; **Leadership.** Led a six-person team, and hired and mentored three engineers.

<h3> :bar_chart: Current Focus: DataOps on Google Cloud </h3>

DataOps applies DevOps practices to data: small, automated and tested changes to code and to data, with the health of the data measured like a service.

- :page_with_curl: &nbsp; **Data contracts** per source: schema, grain, freshness target and owner, versioned and checked in CI.
- :card_file_box: &nbsp; **Immutable raw data and layered models** (raw, staging, validated), so any table can be rebuilt by replaying raw data.
- :repeat: &nbsp; **Idempotent, partition-scoped loads** in BigQuery, so a backfill is just a re-run over a date range and a retry never duplicates rows.
- :white_check_mark: &nbsp; **Write, audit, publish:** quality assertions gate what consumers read, and a failed check keeps the last good data in place.
- :mag_right: &nbsp; **Data observability:** freshness, volume, schema, distribution and lineage, alongside pipeline health and cost.
- :moneybag: &nbsp; **BigQuery cost control** with partitioning, clustering, byte limits and job labels.

Portfolio project: [gcp-dataops-runbook-assistant](https://github.com/gabriel8fm/gcp-dataops-runbook-assistant), an incident-data pipeline on BigQuery with idempotent loads, replay, eight Dataform assertions, Terraform built on `terraform-google-modules`, and offline CI in GitHub Actions.

Next on my list: Cloud Composer (Airflow) orchestration and Dataflow.

<h3> :mortar_board: Education </h3>

- Postgraduate Specialization in Applied AI Software Engineering (in progress, expected 2028)
- Technologist degree in Computer Networks

<h3> :scroll: Certifications </h3>

- [AWS Certified Cloud Practitioner](https://www.credly.com/badges/b21c882e-3ac8-41aa-b091-ddc56b815cc1/public_url)
- [Google Cloud Certified - Associate Cloud Engineer](https://www.credential.net/b6e10198-8792-44db-9e24-0984a00a61f3)
- [Container Expert](https://www.credential.net/6982e389-9cd3-4f2d-a46e-c49430d9a31c#gs.dc8hak)
- [DevOps Bootcamp by Estabilis](https://www.credential.net/046041f5-07fe-421c-aa57-b26381dea512)
- [Uncomplicating Istio](https://www.credential.net/cb5d3059-bdbb-4861-a9fe-d42429d8919d)
- [Uncomplicating Docker](https://www.credential.net/0f5e5bc7-7763-41bb-bc88-9fd6b6ec44cb#gs.kmca4c)
- [Uncomplicating Kubernetes](https://www.credential.net/39b4c1c8-86f8-4292-adb6-89cc3e1c605f#gs.kmccr3)

<h3> :robot: AI-Assisted Engineering </h3>

Over the last year I've been integrating AI coding assistants and LLM-based tooling directly into infrastructure and platform workflows, rather than treating them as a novelty:

- :zap: &nbsp; Using AI pair-programming to accelerate authoring of Terraform/OpenTofu modules, Kubernetes manifests, and CI/CD pipeline configuration.
- :mag: &nbsp; Automating first-pass code review and static analysis to catch misconfigurations and security drift before they reach production.
- :page_facing_up: &nbsp; Generating and maintaining runbooks and operational documentation directly from infrastructure code and incident context.
- :bulb: &nbsp; Using LLM-assisted root-cause analysis to speed up triage of cross-cutting issues across networking, auth, and service connectivity.
- :handshake: &nbsp; Sharing these workflows with teams to shorten iteration cycles and spread infrastructure knowledge beyond a single engineer.

<h3> :toolbox: Tech Stack</h3>

- :cloud:             &nbsp; AWS | GCP
- :whale:             &nbsp; Docker | Kubernetes (EKS, GKE) | Helm | ArgoCD
- :hammer_and_wrench: &nbsp; Terraform | OpenTofu | Atlantis | Ansible | Packer
- :recycle:           &nbsp; GitLab CI | GitHub Actions | CircleCI | Jenkins
- :card_file_box:     &nbsp; BigQuery | Dataform | Pub/Sub | AWS Glue | PostgreSQL | MySQL
- :bar_chart:         &nbsp; Grafana | Grafana Alloy | OpenTelemetry | Prometheus | Datadog | New Relic | CloudWatch | Elastic | Fluentd
- :lock:              &nbsp; IAM | Workload Identity | OIDC federation | Secrets Manager | WAF | OPA Gatekeeper
- :keyboard:          &nbsp; Python | Bash | SQL
- :robot:             &nbsp; Claude Code | LLM-assisted infrastructure & operations tooling

[![Gabriel's GitHub Stats](https://github-readme-stats.vercel.app/api?username=gabriel8fm&show_icons=true)](https://github.com/gabriel8fm)<br>

<h3> :handshake: Connect with Me </h3>

<p align="center">
<a href="mailto:contato@gabrielmiranda.me"><img alt="Email" src="https://img.shields.io/badge/Email-contato[at]gabrielmiranda[dot]me-blue?style=flat-square&logo=gmail"></a>
</p>
<p align="center">
<a href="mailto:gabriel8fm@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-gabriel8fm[at]gmail[dot]com-blue?style=flat-square&logo=gmail"></a>
</p>
