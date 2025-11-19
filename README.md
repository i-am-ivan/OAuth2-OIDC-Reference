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

### How to?
1. Fork this repo
2. Enable GitHub Actions
3. Add your cloud OIDC role
→ Done. Your pipeline is now more secure than 98 % of startups.

### Stacks
![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
