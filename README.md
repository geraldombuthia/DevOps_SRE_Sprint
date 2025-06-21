# DEVOPS and SRE LEARNING SPRINT
## DevOps & SRE Sprint Checklist

- **Master essential DevOps and SRE concepts, tools, and workflows**
- **Complete the 4-week sprint (2–3 hours per week)**
- **Participate in reading, hands-on labs, and group discussions**
- **Finish all project deliverables:**
    - [ ] GallantStore [Go]: Multi-tenant e-commerce backend
    - [ ] Io-connecT [Node.js]: Real-time IoT data processing and device management
    - [ ] GallantSMS [Node.js]: Real-time SMS gateway
    - [ ] CMake-based C++ project: Firmware build with CMake

    ### **Weekly Progress**

    #### Week 1: CI/CD, Docker, and CMake Pipelines
    1. [ ] Linux Fundamentals: Permissions, journald, `systemctl`, `htop`, `lsof`
        - [ ] Understand Linux file permissions and user management
        - [ ] Learn basic system monitoring and troubleshooting tools
        - [ ] Explore systemd and service management
    2. [ ] Bash Scripting: Automate backups, log rotation, and scrubbing
        - [ ] Write reusable shell scripts
        - [ ] Schedule tasks with cron
        - [ ] Handle logs and automate routine tasks
    3. [ ] Docker Basics: Build and run GallantStore Go backend in a container
        - [ ] Learn Dockerfile syntax and best practices
        - [ ] Understand container lifecycle and networking
        - [ ] Use Docker Compose for multi-container setups
    4. [ ] Dockerizing Node.js: Create Dockerfile for Io-connecT, manage `.env`
        - [ ] Handle environment variables securely
        - [ ] Optimize Node.js images for production
        - [ ] Debug and troubleshoot container issues
    5. [ ] CMake + CI: Use GitHub Actions to build/test C++ firmware
        - [ ] Understand CMake basics and project structure
        - [ ] Set up automated builds and tests in CI
        - [ ] Integrate code quality checks
    6. [ ] CI for Go/Node: GitHub Actions for test/lint on GallantStore and Io-connecT
        - [ ] Write and maintain CI pipelines
        - [ ] Automate linting, testing, and code coverage
        - [ ] Manage secrets in CI/CD workflows
    7. [ ] Reflection: Document CI/CD setup in README
        - [ ] Practice clear technical documentation
        - [ ] Summarize CI/CD pipeline design and decisions

    #### Week 2: Cloud & Infrastructure as Code
    8. [ ] AWS Intro: Launch EC2, configure SSH keys, set up Security Groups
        - [ ] Understand basic AWS services and IAM
        - [ ] Secure cloud resources with best practices
        - [ ] Manage SSH access and key rotation
    9. [ ] System Automation: Install Nginx and Docker via bash and `cloud-init`
        - [ ] Automate server provisioning
        - [ ] Use cloud-init for initial configuration
        - [ ] Harden server security
    10. [ ] Terraform Basics: Deploy EC2 and assign Elastic IP
        - [ ] Learn Terraform syntax and state management
        - [ ] Use modules and variables for reusable code
        - [ ] Understand infrastructure lifecycle
    11. [ ] Provisioning: Use Terraform for S3, IAM, and RDS setup
        - [ ] Manage cloud storage and databases as code
        - [ ] Apply least-privilege IAM policies
        - [ ] Automate resource provisioning and teardown
    12. [ ] Service Deployment: Deploy Dockerized GallantStore on EC2 with Terraform
        - [ ] Combine IaC and containerization
        - [ ] Automate end-to-end deployments
        - [ ] Monitor and troubleshoot deployments
    13. [ ] CI + Terraform: GitHub Action triggers Terraform apply on main
        - [ ] Integrate Terraform with CI/CD
        - [ ] Manage secrets and state securely in pipelines
        - [ ] Implement approval workflows
    14. [ ] Documentation: Write infra architecture doc with Terraform outputs
        - [ ] Visualize infrastructure with diagrams
        - [ ] Document resource relationships and dependencies

    #### Week 3: Observability, Secrets, and Logging
    15. [ ] Prometheus: Run locally, expose node metrics
        - [ ] Understand metrics, exporters, and scraping
        - [ ] Instrument applications for observability
        - [ ] Query metrics with PromQL
    16. [ ] Grafana: Visualize app/container metrics
        - [ ] Build dashboards for key metrics
        - [ ] Set up data sources and alerts
        - [ ] Share and version dashboards
    17. [ ] Alerting: Configure basic alerts with Alertmanager
        - [ ] Define alert rules and notification channels
        - [ ] Integrate with email, Slack, or PagerDuty
        - [ ] Tune alert thresholds to reduce noise
    18. [ ] Loki Logging: Collect Docker logs with Loki and promtail
        - [ ] Centralize and search logs efficiently
        - [ ] Structure logs for better analysis
        - [ ] Set up log retention and rotation
    19. [ ] Secrets Management: Use `.env`, Kubernetes secrets, AWS Secrets Manager
        - [ ] Store and rotate secrets securely
        - [ ] Avoid secrets in code and logs
        - [ ] Audit and monitor secret usage
    20. [ ] Runbooks: Draft runbooks for API outage and high CPU
        - [ ] Write actionable incident response guides
        - [ ] Document escalation and communication steps
        - [ ] Review and test runbooks regularly
    21. [ ] Refactor: Add dashboards/logs to apps; write observability guide
        - [ ] Integrate monitoring into app code
        - [ ] Maintain up-to-date documentation

    #### Week 4: Kubernetes, Incident Response, and Wrap-Up
    22. [ ] Local K8s: Install k3d/Minikube, deploy Nginx Pod
        - [ ] Understand Kubernetes architecture and objects
        - [ ] Deploy and manage pods, services, and namespaces
        - [ ] Troubleshoot deployments and networking
    23. [ ] Helm: Create Helm chart for GallantStore
        - [ ] Package and version Kubernetes applications
        - [ ] Use values files for configuration
        - [ ] Share charts via repositories
    24. [ ] Storage & Scaling: Add persistent storage and autoscaling to Io-connecT
        - [ ] Configure PersistentVolumes and Claims
        - [ ] Set up Horizontal Pod Autoscaler
        - [ ] Monitor resource usage and scaling events
    25. [ ] Ingress & TLS: Set up ingress-nginx and Let’s Encrypt for dev
        - [ ] Manage ingress resources and routing
        - [ ] Automate TLS certificate provisioning
        - [ ] Secure traffic with HTTPS
    26. [ ] CI Deploy: GitHub Action deploys Helm chart to k3s
        - [ ] Automate Kubernetes deployments via CI/CD
        - [ ] Roll back failed releases safely
        - [ ] Manage deployment secrets and configs
    27. [ ] Chaos Engineering: Simulate failures, observe recovery, trigger alerts
        - [ ] Practice fault injection and resilience testing
        - [ ] Analyze system behavior under stress
        - [ ] Improve incident response based on findings
    28. [ ] Portfolio: Final README for each app with CI/CD, k8s, and monitoring docs
        - [ ] Summarize project learnings and outcomes
        - [ ] Highlight key DevOps/SRE skills demonstrated
        - [ ] Prepare documentation for sharing or interviews

## Folder Structure
```
devops-sre-sprint/
├── week1_ci_cd/
├── week2_terraform/
├── week3_monitoring/
├── week4_kubernetes/
├── runbooks/
├── dashboards/
└── README.md
```
## Resources
- Roadmap: [DevOps Roadmap](https://roadmap.sh/devops)
- [Linux Internals]: (https://linuxcommand.org/tlcl.php)
- Github Actions: [GitHub Actions Documentation](https://docs.github.com/en/actions)
- Cmake Documentation: [CMake Documentation](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)
- Books: 
  - [Site Reliability Engineering](https://landing.google.com/sre/books/)
  - TryHackMe / Katacoda labs – Hands-on with cloud & automation
  - [Prometheus and Grafana docs ](https://grafana.com/tutorials/grafana-fundamentals/)