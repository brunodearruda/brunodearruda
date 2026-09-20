# Bruno Arruda

**Cloud Security & Infrastructure Professional**

AWS • Cloud Security • Secure Architecture • DevSecOps

Dublin, Ireland

[Website](https://brunoarruda.com) · [Cloud Security Portfolio](https://github.com/brunodearruda/brunoarruda.com) · [LinkedIn](https://www.linkedin.com/in/brunodearruda)

## About

Cloud Security & Infrastructure Professional with 15+ years of experience across technology, infrastructure, enterprise systems, project and governance environments, and information security. I am currently deepening my specialization in AWS Cloud Security through certification study, hands-on architecture, security labs, and technical documentation.

My work connects an infrastructure foundation with security controls, governance requirements, and practical AWS implementation.

## Current Focus

- AWS Cloud Security and secure AWS architecture
- Identity and access management
- Cloud logging, monitoring, and auditability
- Secure CI/CD and DevSecOps practices
- Security architecture decisions and trade-offs

## Featured Cloud Security Project

### AWS Security Portfolio — brunoarruda.com

A security-first personal website and technical portfolio built with Astro and deployed on AWS. Beyond the website itself, the project is a hands-on Cloud Security case study documenting architecture decisions, implemented controls, deployment identity, monitoring, and operational trade-offs.

[Live Website](https://brunoarruda.com) · [Architecture Article](https://brunoarruda.com/blog/how-i-designed-a-security-first-aws-architecture/) · [Hands-on LAB](https://brunoarruda.com/labs/building-securing-static-website-aws/) · [Source Repository](https://github.com/brunodearruda/brunoarruda.com)

**Architecture at a glance**

- Public delivery: `User → Route 53 / DNSSEC → CloudFront → Origin Access Control → private S3 origin`
- Deployment identity: `GitHub Actions → OIDC → AWS STS → scoped IAM role → S3 deployment / CloudFront invalidation`

**Implemented controls include:**

- Private S3 origin with S3 Block Public Access and CloudFront Origin Access Control
- Route 53, DNSSEC, TLS, security headers, and Content Security Policy
- AWS WAF operating in monitor mode
- CloudWatch and SNS for monitoring and notifications
- CloudTrail for audit visibility into configured management events
- GitHub Actions OIDC and AWS STS for temporary deployment credentials through a scoped IAM role

## Technical Focus

### Cloud & AWS

AWS architecture, Amazon S3, Amazon CloudFront, Amazon Route 53, IAM, AWS STS, CloudWatch, CloudTrail, and AWS WAF.

### Security

Cloud security architecture, identity and access, security controls, logging and monitoring, auditability, security governance, and vulnerability management.

### DevSecOps

GitHub Actions, OIDC federation, temporary AWS credentials, secure deployment workflows, and CI/CD security validation.

## Background & Certifications

- Project Management Professional (PMP), achieved in 2025
- Previous certifications include CompTIA Security+ and AWS Certified Cloud Practitioner; these credentials are no longer active

## Currently Learning

- AWS Certified Solutions Architect – Associate — current focus
- AWS Certified Security – Specialty — planned next specialization
- Hands-on AWS security architecture and lab implementation

## Contact

- Website: [brunoarruda.com](https://brunoarruda.com)
- LinkedIn: [linkedin.com/in/brunodearruda](https://www.linkedin.com/in/brunodearruda)
- GitHub: [github.com/brunodearruda](https://github.com/brunodearruda)
- Email: [contato@brunoarruda.com](mailto:contato@brunoarruda.com)
