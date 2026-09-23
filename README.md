## Sukesh Avula

Platform engineer in Bengaluru. I've spent the last ~5.5 years running AWS infrastructure, most recently as Senior Lead – Platform at Aparajitha Corporate Services, looking after the AWS setup behind a compliance product used by 2,000+ people.

Day to day that means EC2/VPC/IAM/RDS, Jenkins pipelines (Maven, Nexus, GitHub), CloudFormation, a lot of Linux, and keeping the AWS bill under control.

A few things I've done at work:
- Moved MySQL 5.7 and legacy apps onto AWS (8.0 on RDS) using DMS, without breaking uptime (99.9%)
- Cut monthly AWS spend by ~30% with Reserved Instances, rightsizing and budgets
- Reworked our Jenkins CI/CD, and deployments went up by ~35%
- Tightened IAM and access controls, and security incidents dropped by ~25%

### What's here

Work code stays at work, so these repos are my own labs. I'm using them to get properly hands-on with Terraform and Kubernetes, and to rebuild patterns I already use in CloudFormation.

- [aws-cloudformation-vpc-3tier](https://github.com/sukeshavula/aws-cloudformation-vpc-3tier): VPC + ALB + Auto Scaling + RDS in one CloudFormation template
- [terraform-aws-infra](https://github.com/sukeshavula/terraform-aws-infra): a similar setup in Terraform, with modules and S3/DynamoDB remote state
- [k8s-multi-container-app](https://github.com/sukeshavula/k8s-multi-container-app): a small Flask + Redis app on Minikube that I use to break things and see what happens

### Contact

avulasukeshaws@gmail.com
