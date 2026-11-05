![DevOps & Infrastructure Studio](./assets/devops-infrastructure-studio-banner.png)

<div align="center">

[![Master Skill](https://img.shields.io/badge/Master_Skill-1-F95C2F?style=flat-square)](https://github.com/TheMamunZx/devops-infrastructure-studio) [![Internal Modules](https://img.shields.io/badge/Internal_Modules-9-F95C2F?style=flat-square)](#internal-specialist-modules) [![Claude Code](https://img.shields.io/badge/Claude_Code-Compatible-5865F2?style=flat-square)](https://claude.ai/code) [![OpenCode](https://img.shields.io/badge/OpenCode-Compatible-5865F2?style=flat-square)](https://github.com/lastmile-ai/opencode)

**[Quick Start](#quick-start)** • **[Architecture](#master-skill-architecture)** • **[Workflow](#devops-engineering-workflow)** • **[Installation](#claude-code-installation)** • **[Documentation](#documentation-and-resources)**

</div>

---

## About DevOps & Infrastructure Studio

DevOps & Infrastructure Studio is a comprehensive Master Skill for building production-ready cloud infrastructure, container orchestration, CI/CD pipelines, and distributed systems with repeatable workflows, deployment safety, cost awareness, and recovery planning.

This repository provides one discoverable Master Skill that coordinates nine internal specialist modules automatically based on your infrastructure requirements.

### Project Overview and Statistics

| Metric | Value |
|--------|-------|
| **Master Skills** | 1 |
| **Internal Specialist Modules** | 9 |
| **Human-Centered Design Modules** | 3 |
| **Workflow Coverage** | Infrastructure Architecture → Container Engineering → CI/CD → Monitoring → Deployment |
| **Cloud Providers** | AWS, Azure, Google Cloud (configuration required) |
| **Container Platforms** | Docker, Kubernetes (configuration required) |
| **CI/CD Platforms** | GitHub Actions, GitLab CI, Jenkins, CircleCI (configuration required) |

---

## What Can You Build?

DevOps & Infrastructure Studio enables you to create:

- **Cloud Infrastructure Architecture** — design scalable, resilient, and cost-optimized cloud environments
- **Infrastructure as Code** — automate infrastructure provisioning and configuration management
- **Docker and Container Engineering** — build production-ready container images and orchestration
- **CI/CD Pipelines** — implement automated build, test, and deployment workflows
- **Distributed Systems** — design fault-tolerant, scalable distributed architectures
- **Performance Optimization** — analyze and improve system performance and resource utilization
- **Reliability Engineering** — implement monitoring, alerting, incident response, and disaster recovery
- **Observability Infrastructure** — deploy comprehensive logging, metrics, and tracing systems
- **Developer Operations Dashboards** — create human-centered monitoring and operational interfaces

---

## Master Skill Architecture

This repository contains **one discoverable Master Skill**:

```
devops-infrastructure-studio
```

Users select only this Master Skill. It coordinates the appropriate internal specialist modules automatically based on your infrastructure requirements.

**You do not need to select individual modules manually.**

The Master Skill:
- Analyzes your infrastructure requirements
- Loads relevant specialist playbooks from `references/`
- Coordinates the complete workflow from architecture to deployment
- Ensures consistent quality gates across all phases

---

## Internal Specialist Modules

The Master Skill coordinates these nine internal specialist modules:

| Module | Capability |
|--------|-----------|
| **devops-engineer** | Infrastructure architecture, deployment automation, environment management |
| **docker-engineer** | Container image design, Docker configuration, container orchestration |
| **cloud-engineer** | Cloud infrastructure planning, resource provisioning, cost optimization |
| **cicd-engineer** | Pipeline design, automated testing, deployment workflows |
| **distributed-systems-engineer** | Distributed architecture, fault tolerance, scalability patterns |
| **performance-engineer** | Performance analysis, optimization, resource utilization |
| **human-centered-product-design** | User-centered design principles for operational interfaces |
| **design-quality-critic** | Design review, quality assessment, consistency validation |
| **product-experience-engineer** | Dashboard and monitoring interface engineering |

**Note:** Internal modules are reference playbooks loaded automatically by the Master Skill, not separate discoverable skills.

---

## DevOps Engineering Workflow

```mermaid
graph TD
    A[User Request] --> B[Requirements Analysis]
    B --> C[Infrastructure Architecture]
    C --> D[Cloud and Platform Selection]
    D --> E[Environment Planning]
    E --> F[Container and CI/CD Design]
    F --> G[Infrastructure Implementation]
    G --> H[Automated Testing]
    H --> I[Security and Configuration Review]
    I --> J[Deployment]
    J --> K[Monitoring and Validation]
    K --> L{Validation Success?}
    L -->|Yes| M[Complete]
    L -->|No| N[Rollback]
    N --> O[Incident Analysis]
    O --> G
```

---

## Cloud Infrastructure Engineering

Build production-ready cloud infrastructure with:

- **Architecture Design** — design scalable, resilient cloud topologies
- **Resource Provisioning** — automate infrastructure deployment with IaC tools
- **Networking Configuration** — VPC, subnets, load balancers, security groups
- **Identity and Access Management** — least-privilege IAM policies and role design
- **Cost Optimization** — right-sizing, reserved capacity, budget controls
- **Disaster Recovery Planning** — backup strategies, multi-region failover

**Supported Cloud Providers** (configuration required):
- Amazon Web Services (AWS)
- Microsoft Azure
- Google Cloud Platform (GCP)

---

## Infrastructure Automation

Automate infrastructure management with:

- **Infrastructure as Code** — Terraform, CloudFormation, Pulumi, Bicep
- **Configuration Management** — Ansible, Chef, Puppet
- **Environment Provisioning** — automated staging, production, and test environments
- **Secrets Management** — secure credential handling and rotation
- **Compliance Automation** — policy enforcement and audit trails

---

## Docker and Container Engineering

Design and deploy production-ready containers:

- **Dockerfile Optimization** — multi-stage builds, layer caching, minimal base images
- **Container Security** — vulnerability scanning, rootless containers, read-only filesystems
- **Image Registry Management** — private registries, image signing, provenance tracking
- **Container Orchestration** — Kubernetes, Docker Swarm, ECS, AKS, GKE
- **Resource Limits** — CPU, memory, and storage constraints
- **Health Checks** — liveness and readiness probes

---

## CI/CD Pipeline Development

Build automated delivery pipelines:

- **Pipeline Design** — build, test, deploy workflow automation
- **Automated Testing** — unit, integration, end-to-end test execution
- **Artifact Management** — versioning, signing, and distribution
- **Deployment Strategies** — blue-green, canary, rolling deployments
- **Environment Promotion** — automated staging to production progression
- **Pipeline Security** — secret scanning, dependency vulnerability checks

**Supported CI/CD Platforms** (configuration required):
- GitHub Actions
- GitLab CI/CD
- Jenkins
- CircleCI
- Azure DevOps
- AWS CodePipeline

---

## Automated Build and Deployment

Implement reliable deployment workflows:

- **Build Automation** — reproducible builds with version pinning
- **Deployment Orchestration** — staged rollouts with validation gates
- **Rollback Procedures** — automated failure detection and recovery
- **Database Migrations** — safe schema changes with rollback support
- **Configuration Management** — environment-specific settings injection
- **Approval Gates** — manual approval for production deployments

---

## Distributed Systems Engineering

Design fault-tolerant distributed architectures:

- **System Architecture** — microservices, event-driven, service mesh patterns
- **Service Communication** — REST APIs, gRPC, message queues
- **Load Balancing** — traffic distribution and health-based routing
- **Fault Tolerance** — circuit breakers, retries, timeouts, bulkheads
- **Data Consistency** — eventual consistency, distributed transactions
- **Service Discovery** — dynamic service registration and discovery

---

## Performance and Reliability Engineering

Optimize system performance and reliability:

- **Performance Profiling** — CPU, memory, I/O bottleneck identification
- **Load Testing** — capacity planning and stress testing
- **Resource Optimization** — right-sizing compute and storage resources
- **Caching Strategies** — application, database, and CDN caching
- **Database Optimization** — query tuning, indexing, connection pooling
- **Scalability Planning** — horizontal and vertical scaling strategies

---

## Monitoring, Logging and Observability

Implement comprehensive observability:

- **Metrics Collection** — Prometheus, CloudWatch, Datadog, Grafana
- **Logging Infrastructure** — structured logging, log aggregation, retention policies
- **Distributed Tracing** — OpenTelemetry, Jaeger, Zipkin
- **Alerting Systems** — threshold-based and anomaly detection alerts
- **Dashboards** — real-time operational visibility
- **Runbooks** — incident response procedures and escalation paths

---

## Human-Centered Operations Experience

Build professional developer and operations interfaces with three dedicated design modules:

### human-centered-product-design
Apply user-centered design principles to operational interfaces:
- Clear information hierarchy for monitoring dashboards
- Meaningful status indicators and health visualizations
- Accessible controls and navigation
- User research and usability testing for operational tools

### design-quality-critic
Review operational interface quality:
- Visual consistency validation
- Design pattern adherence
- Information density optimization
- Alert and error state clarity

### product-experience-engineer
Implement professional operational experiences:
- Readable monitoring dashboards with clear metrics
- Useful alerts with actionable context
- Efficient operational workflows
- Responsive and accessible interfaces

**Human-centered operations ensure your infrastructure monitoring and management tools are professional, clear, and efficient.**

---

## Design Quality Review

The Master Skill enforces quality gates throughout the workflow:

- ✅ Requirements map to implemented behavior or documented non-goals
- ✅ Projects build and run with available dependencies, or blockers are stated with evidence
- ✅ Tests cover critical flows or subsystem invariants
- ✅ Security, privacy, accessibility, performance, and failure states are considered
- ✅ Documentation matches the delivered implementation
- ✅ No capability is described as complete unless verified

---

## Quick Start

### 1. Install the Master Skill

**For Claude Code:**

```bash
# Navigate to your project
cd your-project

# Install the DevOps & Infrastructure Studio Master Skill
# (Installation command depends on your Claude Code setup)
```

**For OpenCode:**

```bash
# Install globally
opencode skills install https://github.com/TheMamunZx/devops-infrastructure-studio

# Or install project-level
cd your-project
opencode skills install https://github.com/TheMamunZx/devops-infrastructure-studio --local
```

### 2. Use the Master Skill

In Claude Code or OpenCode, invoke:

```
/devops-infrastructure-studio
```

The Master Skill will:
1. Analyze your infrastructure requirements
2. Load relevant specialist modules automatically
3. Coordinate the complete workflow from architecture to deployment
4. Apply quality gates and validation at each phase

### 3. Example Use Cases

**Build a containerized application with CI/CD:**
```
/devops-infrastructure-studio Create a Docker container for my Node.js API with GitHub Actions CI/CD pipeline
```

**Design cloud infrastructure:**
```
/devops-infrastructure-studio Design AWS infrastructure for a high-availability web application with auto-scaling
```

**Implement monitoring and observability:**
```
/devops-infrastructure-studio Add Prometheus metrics, structured logging, and Grafana dashboards to my service
```

---

## Claude Code Installation

Claude Code is Anthropic's official CLI for Claude, running within the Claude Agent SDK.

**Install Claude Code:**

Follow the official installation guide at [claude.ai/code](https://claude.ai/code)

**Available Platforms:**
- CLI (terminal)
- Desktop app (Mac/Windows)
- Web app (claude.ai/code)
- IDE extensions (VS Code, JetBrains)

**After installation:**

```bash
# Verify installation
claude --version

# Navigate to your project
cd your-infrastructure-project

# Use the Master Skill
claude /devops-infrastructure-studio
```

---

## OpenCode Installation

OpenCode is an open-source alternative for running Claude skills.

**Install OpenCode:**

```bash
npm install -g opencode
```

**Install DevOps & Infrastructure Studio:**

```bash
# Global installation
opencode skills install https://github.com/TheMamunZx/devops-infrastructure-studio

# Project-level installation
cd your-project
opencode skills install https://github.com/TheMamunZx/devops-infrastructure-studio --local
```

**Use the Master Skill:**

```bash
opencode /devops-infrastructure-studio
```

---

## Supported Platforms and Technologies

### Cloud Providers (configuration required)

| Provider | Services |
|----------|----------|
| **AWS** | EC2, ECS, EKS, Lambda, RDS, S3, CloudFormation, CloudWatch |
| **Azure** | VMs, AKS, Azure Functions, Azure SQL, Blob Storage, ARM Templates, Azure Monitor |
| **Google Cloud** | Compute Engine, GKE, Cloud Functions, Cloud SQL, Cloud Storage, Deployment Manager, Cloud Monitoring |

### Container Platforms (configuration required)

- **Docker** — container image building and local orchestration
- **Kubernetes** — production container orchestration
- **Amazon ECS/EKS** — AWS container services
- **Azure AKS** — Azure Kubernetes Service
- **Google GKE** — Google Kubernetes Engine

### CI/CD Platforms (configuration required)

- **GitHub Actions** — GitHub-native CI/CD
- **GitLab CI/CD** — GitLab-integrated pipelines
- **Jenkins** — self-hosted automation server
- **CircleCI** — cloud-based CI/CD
- **Azure DevOps** — Microsoft CI/CD platform
- **AWS CodePipeline** — AWS-native CI/CD

### Infrastructure as Code Tools

- **Terraform** — cloud-agnostic IaC
- **AWS CloudFormation** — AWS IaC
- **Azure Resource Manager (ARM)** — Azure IaC
- **Google Cloud Deployment Manager** — GCP IaC
- **Pulumi** — multi-cloud IaC with programming languages
- **Ansible** — configuration management

### Monitoring and Observability

- **Prometheus** — metrics collection and alerting
- **Grafana** — metrics visualization
- **OpenTelemetry** — distributed tracing
- **Jaeger** — tracing backend
- **ELK Stack** — Elasticsearch, Logstash, Kibana
- **Datadog** — cloud monitoring platform
- **New Relic** — application performance monitoring

**Note:** These technologies are documented workflows. Actual usage requires installation, configuration, and credentials for each service.

---

## Cloud Provider Configuration

### AWS Configuration

```bash
# Configure AWS credentials
aws configure

# Set environment variables
export AWS_ACCESS_KEY_ID=your_access_key
export AWS_SECRET_ACCESS_KEY=your_secret_key
export AWS_DEFAULT_REGION=us-east-1
```

### Azure Configuration

```bash
# Login to Azure
az login

# Set subscription
az account set --subscription "your-subscription-id"
```

### Google Cloud Configuration

```bash
# Authenticate with Google Cloud
gcloud auth login

# Set project
gcloud config set project your-project-id
```

**Security Warning:** Never commit cloud credentials to source control. Use environment variables, secret managers, or credential files with restricted permissions.

---

## Container and Deployment Configuration

### Docker Configuration

```dockerfile
# Multi-stage build example
FROM node:18-alpine AS builder
WORKDIR /app
COPY package*.json ./
RUN npm ci --only=production

FROM node:18-alpine
WORKDIR /app
COPY --from=builder /app/node_modules ./node_modules
COPY . .
EXPOSE 3000
CMD ["node", "server.js"]
```

### Kubernetes Configuration

```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: api-deployment
spec:
  replicas: 3
  selector:
    matchLabels:
      app: api
  template:
    metadata:
      labels:
        app: api
    spec:
      containers:
      - name: api
        image: your-registry/api:latest
        ports:
        - containerPort: 3000
        resources:
          requests:
            memory: "128Mi"
            cpu: "100m"
          limits:
            memory: "256Mi"
            cpu: "200m"
```

### Environment Variables

```bash
# .env.example (commit this)
DATABASE_URL=postgresql://localhost:5432/dbname
API_PORT=3000
LOG_LEVEL=info

# .env (never commit this)
DATABASE_URL=postgresql://user:password@prod-db:5432/production
API_KEY=your_secret_api_key
JWT_SECRET=your_jwt_secret
```

---

## Security and Secret Management

### Secure Credential Management

- **Never commit secrets to source control**
- Use environment variables for configuration
- Use cloud provider secret managers (AWS Secrets Manager, Azure Key Vault, Google Secret Manager)
- Rotate credentials regularly
- Use least-privilege IAM policies

### Infrastructure Security Review

The Master Skill reviews:
- IAM policies and role permissions
- Network security groups and firewall rules
- Exposed services and endpoints
- Container image vulnerabilities
- Secrets in code and configuration
- Supply chain security and image provenance

### Network Security

- Private subnets for backend services
- Security groups with minimal inbound rules
- TLS/SSL for all external communication
- VPN or bastion hosts for remote access
- Network segmentation and isolation

### Container Security

- Scan images for vulnerabilities
- Use minimal base images (alpine, distroless)
- Run containers as non-root users
- Read-only filesystems where possible
- Image signing and provenance tracking

---

## Testing and Validation

### Infrastructure Testing

```bash
# Terraform validation
terraform validate
terraform plan

# CloudFormation validation
aws cloudformation validate-template --template-body file://template.yaml
```

### Container Testing

```bash
# Build and test Docker image
docker build -t api:test .
docker run --rm api:test npm test

# Scan for vulnerabilities
docker scan api:test
```

### Deployment Testing

- **Unit tests** — test individual components
- **Integration tests** — test service interactions
- **End-to-end tests** — test complete workflows
- **Load tests** — validate performance under load
- **Smoke tests** — verify deployment health after rollout

---

## Deployment and Rollback Workflows

### Deployment Strategies

**Blue-Green Deployment:**
- Deploy new version alongside old version
- Switch traffic to new version
- Keep old version running for quick rollback

**Canary Deployment:**
- Deploy to small percentage of infrastructure
- Monitor metrics and error rates
- Gradually increase traffic to new version

**Rolling Deployment:**
- Replace instances incrementally
- Maintain service availability throughout deployment

### Rollback Procedures

```bash
# Kubernetes rollback
kubectl rollout undo deployment/api-deployment

# Docker Swarm rollback
docker service rollback api-service

# AWS ECS rollback
aws ecs update-service --cluster prod --service api --task-definition api:previous-version
```

### Deployment Approval Gates

**Require explicit approval before:**
- Production deployments
- Database schema changes
- Infrastructure modifications that affect live services
- Destructive operations (data deletion, resource termination)

---

## Output Structure and Deliverables

The Master Skill produces:

```
infrastructure/
├── architecture-diagram.md      # System architecture documentation
├── terraform/                   # Infrastructure as Code
│   ├── main.tf
│   ├── variables.tf
│   └── outputs.tf
├── docker/                      # Container configuration
│   ├── Dockerfile
│   └── docker-compose.yml
├── ci-cd/                       # Pipeline configuration
│   ├── .github/workflows/
│   └── deployment-pipeline.yml
├── monitoring/                  # Observability configuration
│   ├── prometheus.yml
│   ├── grafana-dashboards/
│   └── alerts.yml
├── docs/                        # Documentation
│   ├── deployment-guide.md
│   ├── rollback-procedures.md
│   ├── runbooks/
│   └── cost-analysis.md
└── security-review.md           # Security and compliance review
```

---

## Troubleshooting and FAQ

### Common Issues

**Issue: Cloud credentials not configured**
```
Solution: Configure cloud provider CLI and verify authentication
AWS: aws sts get-caller-identity
Azure: az account show
GCP: gcloud auth list
```

**Issue: Docker build fails**
```
Solution: Check Dockerfile syntax, base image availability, and network access
docker build --no-cache -t api:debug .
```

**Issue: Kubernetes deployment fails**
```
Solution: Check pod logs and events
kubectl get pods
kubectl logs <pod-name>
kubectl describe pod <pod-name>
```

**Issue: CI/CD pipeline fails**
```
Solution: Review pipeline logs, verify secrets and environment variables
Check test failures, build errors, deployment permissions
```

### FAQ

**Q: Do I need to select individual modules?**
A: No. Select only the `devops-infrastructure-studio` Master Skill. It loads specialist modules automatically.

**Q: Which cloud provider should I use?**
A: The Master Skill supports AWS, Azure, and Google Cloud. Choice depends on your requirements, existing infrastructure, and team expertise.

**Q: How do I handle secrets and credentials?**
A: Use environment variables for local development, cloud secret managers for production. Never commit secrets to source control.

**Q: Can I use this for production deployments?**
A: Yes, but always review generated infrastructure code, test in staging environments first, and require manual approval for production changes.

**Q: What if a deployment fails?**
A: The Master Skill designs rollback procedures for each deployment. Follow the generated rollback documentation to restore the previous working state.

---

## Documentation and Resources

### Master Skill Documentation

- [Master Skill Entry Point](./.claude/skills/devops-infrastructure-studio/SKILL.md)
- [Internal Specialist Modules](./.claude/skills/devops-infrastructure-studio/references/)
- [Skill Manifest](./skill-manifest.json)
- [Agent Operating Guide](./AGENTS.md)

### External Resources

**Cloud Providers:**
- [AWS Documentation](https://docs.aws.amazon.com/)
- [Azure Documentation](https://docs.microsoft.com/azure/)
- [Google Cloud Documentation](https://cloud.google.com/docs)

**Container Platforms:**
- [Docker Documentation](https://docs.docker.com/)
- [Kubernetes Documentation](https://kubernetes.io/docs/)

**CI/CD Platforms:**
- [GitHub Actions Documentation](https://docs.github.com/actions)
- [GitLab CI/CD Documentation](https://docs.gitlab.com/ee/ci/)

**Infrastructure as Code:**
- [Terraform Documentation](https://www.terraform.io/docs)
- [AWS CloudFormation Documentation](https://docs.aws.amazon.com/cloudformation/)

**Monitoring and Observability:**
- [Prometheus Documentation](https://prometheus.io/docs/)
- [Grafana Documentation](https://grafana.com/docs/)
- [OpenTelemetry Documentation](https://opentelemetry.io/docs/)

---

<div align="center">

**DevOps & Infrastructure Studio**

Build production-ready infrastructure with repeatable workflows, deployment safety, and recovery planning.

**[Get Started](#quick-start)** • **[View Architecture](#master-skill-architecture)** • **[Read Documentation](#documentation-and-resources)**

</div>
