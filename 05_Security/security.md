# Security Layer

Essential security concepts for DevSecOps engineers.

## Core Topics

- **OWASP Top 10**: Common web vulnerabilities and mitigations.
- **IAM & Least Privilege**: Role design, policy crafting, permission boundaries.
- **Secrets Management**: Vault, AWS Secrets Manager, environment secret injection.
- **Static Application Security Testing (SAST)**: Code analysis tools, integration into CI.
- **Dynamic Application Security Testing (DAST)**: Runtime scanning, fuzzing, web app scanners.
- **Software Composition Analysis (SCA)**: Dependency scanning, SBOM generation, license compliance.
- **Vulnerability Management**: CVE tracking, patching cadence, risk scoring.
- **Threat Modeling**: STRIDE, attack trees, identifying assets and threats.
- **Incident Response Basics**: Preparation, detection, containment, eradication, recovery, lessons learned.

## Study Tips

1. **Hands‑On** – Run OWASP ZAP against a vulnerable app. Generate an SBOM with `syft`.
2. **Policy as Code** – Write Rego policies for OPA to enforce least‑privilege IAM.
3. **Practice Incident Playbooks** – Simulate a breach and document steps.

## Study Material References
- **OWASP Top 10**: Official OWASP Project – https://owasp.org/www-project-top-ten/
- **DevSecOps Basics**: What is DevSecOps? (Red Hat) – https://www.redhat.com/en/topics/devops/what-is-devsecops
- **SCA Tools**: OWASP Dependency-Check – https://owasp.org/www-project-dependency-check/
- **Threat Modeling**: OWASP Threat Modeling – https://owasp.org/www-community/Threat_Modeling
