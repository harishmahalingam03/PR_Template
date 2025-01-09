# Pull Request Template for DevOps Changes

## Summary:
<!-- A brief summary of the changes you have made. Why was this change necessary? -->

- Example: Set up a CI/CD pipeline for deployment to AWS.
- Example: Updated Terraform scripts for provisioning resources.
- Example: Configured monitoring using Prometheus and Grafana.

---

## Change Details:
<!-- Describe the changes made in detail. Include any relevant information, such as: -->

1. **Infrastructure Changes**: 
   - E.g., Created/modified EC2 instance, VPC, or security group.
2. **CI/CD Pipeline**: 
   - E.g., Updated Jenkinsfile, GitLab CI configuration, etc.
3. **Monitoring/Logging**: 
   - E.g., Added Prometheus exporter to track app metrics.
4. **Script Changes**: 
   - E.g., Updated bash scripts, Terraform/CloudFormation templates.
5. **Configuration Files**: 
   - E.g., Modified Nginx/Apache/POSTGRES configurations, updated Dockerfiles.

---

## Screenshots / Logs / Output (If applicable):
<!-- Provide screenshots or log files to demonstrate the changes visually. These may include: -->

1. **CI/CD Pipeline Run Output**:
   - Screenshot of the successful pipeline run (if applicable).
2. **Before and After Configuration**:
   - Screenshots of configuration changes (e.g., Terraform plan output, Dockerfile diff, Jenkins dashboard, etc.).
3. **Error Logs / Debugging Information** (if any): 
   - Logs from failed deployment attempts or troubleshooting sessions.

---

## Checklist:
Before submitting the PR, make sure to:

- [ ] Code is well-documented (if applicable).
- [ ] Configuration files are tested (e.g., Terraform plan, Kubernetes YAML files, Ansible playbooks).
- [ ] Changes have been validated in a **staging or development environment**.
- [ ] Updated the **README** or documentation (if applicable).
- [ ] Tested the changes manually (if applicable).
- [ ] All relevant configuration files or scripts are included in the PR (e.g., Jenkinsfile, Dockerfile, Terraform script).
- [ ] **Security**: Ensure sensitive information (e.g., passwords, API keys) is properly handled (e.g., using Vault, AWS Secrets Manager, or environment variables).
- [ ] **Backup**: If making changes to production infrastructure, ensure backup and rollback plans are defined.

---

## Related Issues:
<!-- Link any issues, tickets, or user stories that this PR addresses. -->
- Resolves: [#123](link_to_issue) 
- Closes: [#456](link_to_issue)

---

## Testing Instructions:
<!-- Describe the testing steps necessary to validate the changes. -->
1. **For CI/CD Pipelines**:
   - Run the pipeline and confirm that it completes successfully.
2. **For Infrastructure Changes**:
   - Confirm the infrastructure changes via AWS console, Terraform output, etc.
3. **For Scripts or Configurations**:
   - Run the scripts in a test environment and validate the expected behavior.

---
