# Secure CI/CD Template (Just Fork & Go)

Production-ready secure pipeline I use for every microservice at Jovicorp.

### What it does automatically
- SAST (Semgrep)
- SCA (Trivy + Dependabot)
- Container scanning
- Secrets detection
- Terraform plan + security check
- OIDC authentication to Azure/AWS (no long-lived credentials)
- Automatic PR security gating

### How to use
1. Fork this repo
2. Enable GitHub Actions
3. Add your cloud OIDC role
→ Done. Your pipeline is now more secure than 98 % of startups.

### Badges
![Security Scan](https://github.com/i-am-ivan/secure-cicd-template/actions/workflows/security.yml/badge.svg)
![Terraform](https://github.com/i-am-ivan/secure-cicd-template/actions/workflows/terraform.yml/badge.svg)

Used daily by 40+ internal services. MIT licensed.
