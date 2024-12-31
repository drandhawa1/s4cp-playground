# S4CP 

This Project is part of the S4CP Training accessible at [https://rohitsalecha.com/s4cp/](https://rohitsalecha.com/s4cp/)

## Features of the Project

### 1. 🔐 IAM as Code

- Automate IAM setup for users, groups, and roles via code.  

### 2. 🌐 Centralized AWS Organizations  

- Identity account as a jump account for cross-account access.  

### 3. 🤝 GitHub Actions + AWS  

- Integrate seamlessly using OIDC for secure CI/CD workflows.  

### 4. 🛠️ Multi-Environment Setup  

- Isolate testing, staging, and production environments.  

### 5. 🔍 Security Scans  

- **Semgrep**: Detect OWASP Top 10.  
- **Dependency-Checker**: Find vulnerable dependencies.  
- **Gitleaks**: Scan for secrets in commits.  

### 6. 🐳 Container Security  

- Build Golden Docker images and scan with **Trivy**.  
- Deploy Docker images to ECR via CI/CD.  

### 7. ☸️ AWS EKS Deployment  

- Use Load Balancer, Ingress, and RBAC for secure Kubernetes clusters.  

### 8. 🔑 Secrets Management  

- Store in **AWS Secrets Manager** and access dynamically in EKS.  

### 9. 🛡️ Kubernetes Policies & Networking  

- Enforce trusted containers with **Kyverno**.  
- Restrict communication using **Calico**.  

### 10. 📜 Governance Policies  

- Enforce encrypted EBS/RDS, restrict EC2/DB types, and deny user creation outside identity account.  

### 11. ⚖️ Policy as Code  

- Use **OPA** to enforce IMDSv2, monitor admin access, and secure security groups.