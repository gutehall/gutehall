# Mathias Gutehall

Principal Solution Architect. I help organizations turn a cloud decision into a platform their teams can run, on AWS and Azure, and on GCP where that is already the estate.

The work runs from the architecture through the implementation: account structure, identity, guardrails, and a path teams can ship on. Infrastructure as code, containers, and automation are the usual means. The tool follows the estate.

## Public work

- [aws-arch-agent](https://github.com/gutehall/aws-arch-agent) reviews CDK, CloudFormation, and Terraform locally, against the Well-Architected pillars. It needs no AWS credentials.
- [StackWise](https://github.com/gutehall/StackWise) scans a live AWS account read-only, checks the resources against rules for security, cost, reliability, and performance, and can ask a local model for what the rules miss. The data stays on the machine.
- [aws-org-reference](https://github.com/gutehall/aws-org-reference) lands a client AWS organization from that client's own account list. A log archive and a security account are required. Shared network is a separate apply. The decisions are written down.
- [rds-dump-restore](https://github.com/gutehall/rds-dump-restore) copies PostgreSQL from RDS or Aurora in one AWS account into a database in another. A Fargate task streams the dump to S3, and the restore account loads the latest object.

Next in public: a local gateway that meters coding agents and keeps their API keys on the machine.

## Elsewhere

- [dm3.io](https://dm3.io)
- [LinkedIn](https://www.linkedin.com/in/mathias-gutehall)
