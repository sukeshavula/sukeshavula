## Sukesh Avula

DevOps Engineer · Bengaluru, India

I work on AWS infrastructure and delivery pipelines: EC2, VPC, IAM, RDS, Jenkins (Maven, Nexus, GitHub), CloudFormation, Terraform, Docker, Kubernetes, and a lot of Linux.

Some things I've done:
- Migrated MySQL 5.7 and legacy apps to AWS (8.0 on RDS) using DMS, keeping 99.9% uptime
- Cut monthly AWS spend by ~30% with Reserved Instances, rightsizing and budgets
- Reworked Jenkins CI/CD, increasing deployment frequency by ~35%
- Tightened IAM and access controls, reducing security incidents by ~25%

### Projects

- [aws-cloudformation-vpc-3tier](https://github.com/sukeshavula/aws-cloudformation-vpc-3tier): VPC + ALB + Auto Scaling + RDS in one CloudFormation template
- [terraform-aws-infra](https://github.com/sukeshavula/terraform-aws-infra): a similar setup in Terraform, with reusable modules and S3/DynamoDB remote state
- [k8s-multi-container-app](https://github.com/sukeshavula/k8s-multi-container-app): Flask + Redis on Kubernetes with Ingress, persistent storage and failure scenarios
- [jenkins-multibranch-pipeline](https://github.com/sukeshavula/jenkins-multibranch-pipeline): multibranch Jenkins pipeline (branches, PRs, tags) with a shared library, SonarQube quality gate, Nexus, approvals and auto-rollback; Jenkins itself configured as code
- [monitoring-stack](https://github.com/sukeshavula/monitoring-stack): Prometheus, Alertmanager and Grafana with provisioned dashboards and alert rules for hosts, containers and endpoints
- [eks-gitops-platform](https://github.com/sukeshavula/eks-gitops-platform): EKS with Terraform (IRSA, KMS, Spot node group), apps and add-ons deployed by Argo CD from Git with Helm
- [github-actions-ecs-deploy](https://github.com/sukeshavula/github-actions-ecs-deploy): GitHub Actions to ECS Fargate via OIDC, Trivy image scan, CodeDeploy blue/green canary with automatic rollback
- [aws-lambda-automation](https://github.com/sukeshavula/aws-lambda-automation): scheduled Python Lambdas for EC2 office-hours scheduling, EBS snapshot cleanup and a weekly cost report to Slack
- [ansible-server-setup](https://github.com/sukeshavula/ansible-server-setup): Ansible roles for hardened Ubuntu servers (SSH, ufw, fail2ban), nginx + Tomcat, MySQL with Vault, node_exporter, EC2 dynamic inventory

### Contact

avulasukeshaws@gmail.com
