# Terraform Lab

A hands-on Terraform lab for learning Infrastructure as Code through practical cloud provisioning and repeatable infrastructure workflows.

## Overview

This project demonstrates how to use Terraform to provision infrastructure in a consistent, automated, and version-controlled way. It is designed as a learning lab and portfolio piece for Infrastructure/Ops and cloud engineering.

## Goals

- Learn Terraform fundamentals.
- Practice Infrastructure as Code workflows.
- Build repeatable cloud infrastructure.
- Document the process in Markdown.
- Create a portfolio-ready project.

## Tech Stack

- Terraform
- Git
- Linux
- Bash
- Cloud provider of choice
- Optional: GitHub Actions

## What This Lab Covers

- Providers and resources.
- Variables and outputs.
- State management.
- Plan and apply workflow.
- Module basics.
- Remote state concepts.
- Common IaC best practices.

## Repository Structure

```text
.
├── README.md
├── main.tf
├── variables.tf
├── outputs.tf
├── versions.tf
├── modules/
├── notes/
├── scripts/
└── docs/
```

## Setup

1. Install Terraform.
2. Configure cloud credentials.
3. Initialize the project.
4. Review the plan.
5. Apply the configuration.

```bash
terraform init
terraform plan
terraform apply
```

## Usage

Use this lab to test infrastructure ideas safely and learn how Terraform manages state and resources.

## Validation

- Confirm resources were created successfully.
- Check Terraform state.
- Review outputs.
- Verify connectivity or service availability.

## Lessons Learned

- What Terraform manages well.
- Where state can become risky.
- Why modular design matters.
- How to reduce drift and mistakes.

## Next Steps

- Add modules.
- Add remote state.
- Add CI/CD checks.
- Improve variable structure.
- Add tagging and cost controls.

## Notes

Related learning notes can be stored in `notes/` as Markdown files.

## License

Add a license if you want to allow reuse.
