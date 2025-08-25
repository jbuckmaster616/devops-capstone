
---

### `ci/README.md`
```markdown
# CI/CD Workflows

This directory contains GitHub Actions workflows for automated builds and deployments.

## Features
- Lint + unit tests
- Docker image build + push to ECR
- Terraform plan/apply (with manual approval for production)
- Helm deploy to EKS

## Workflow
1. On PR → lint/test
2. On merge → build Docker + push to ECR
3. Terraform plan → approval → apply
4. Helm upgrade release

