<!-- You can override this template by creating a `.github/PULL_REQUEST_TEMPLATE.md` file in the repository root. -->

### Description
<!-- Briefly summarize the changes and their purpose. -->

### Additional Notes
<!-- Provide any additional information that might help the reviewer. -->

### Creator Checklist
<!-- You can check the items now by adding an "x" within the brackets or check them by clicking when the PR is created. -->

#### General
- [ ] **Testing**
  - Changes have been tested locally or in an appropriate environment.
- [ ] **Security**
  - Secrets (e.g., credentials, keys) are not hardcoded or exposed.
  - Changes adhere to security best practices (e.g., IAM policies, input validation, OWASP Top 10).
- [ ] **Logging**
  - Logs are securely stored and do not contain sensitive information (e.g., PII, secrets).
- [ ] **Dependencies**
  - Are from trusted sources.
  - Have versions pinned to avoid unexpected changes.
  - Have been vetted for licensing and security issues.
- [ ] **Documentation**
  - Relevant documentation (e.g., API docs, usage instructions, examples) has been updated.

#### Software-Specific
- [ ] Unit, integration and/or end-to-end tests have been added or updated.
- [ ] Query parameterization and other security best practices have been implemented where necessary.

#### Infrastructure-Specific
- [ ] Terraform plans or infrastructure configurations have been reviewed.
- [ ] IAM roles and policies follow the principle of least privilege.
- [ ] Sensitive resources (e.g., buckets) are secured, and public exposure is restricted.

### Reviewer Checklist

#### General
- [ ] **Testing**
  - Changes are appropriately tested and validated in the required environments.
- [ ] **Security**
  - All security considerations have been addressed, including:
    - No sensitive data or secrets are exposed.
    - Logging and access controls follow best practices.
- [ ] **Dependencies**
  - Dependencies are trusted, pinned, and free from vulnerabilities.

#### Software-Specific
- [ ] Tests cover the changes adequately.
- [ ] OWASP Top 10 principles are followed.

#### Infrastructure-Specific
- [ ] Terraform plans or infrastructure changes align with best practices.
- [ ] IAM and resource configurations follow the principle of least privilege and are appropriately secured.
