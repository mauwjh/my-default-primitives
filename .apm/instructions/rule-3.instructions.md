---
description: AWS CDK infrastructure as code patterns
applyTo: "**/*stack*.ts"
---

# AWS CDK Guidelines

- Organize stacks by logical concerns (compute, storage, networking)
- Use environment variables for configuration (region, account)
- Apply consistent tagging strategy across all resources
- Export stack outputs for cross-stack references
- Use L3 constructs when available for opinionated best practices
- Enable removal policies explicitly (DESTROY for dev, RETAIN for prod)
- Document IAM permissions and principle of least privilege
- Use AWS Secrets Manager for sensitive configuration
- Implement proper error handling and validation
