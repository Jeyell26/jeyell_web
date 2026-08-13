# John Louise Bungay — Software Engineer Portfolio

Personal developer portfolio website showcasing software engineering experience, AWS cloud architecture, IoT microservices, agentic AI workflows, and web application development.

## Live Links & Hosted Applications

- **Personal Portfolio Website:** [https://jeyell26.github.io/jeyell_web/](https://jeyell26.github.io/jeyell_web/)
- **GitHub Profile:** [https://github.com/Jeyell26](https://github.com/Jeyell26)
- **LinkedIn Profile:** [https://www.linkedin.com/in/jeyellbungay/](https://www.linkedin.com/in/jeyellbungay/)

### Public Project Access Points:
- **LogPulse (CloudCompanion) Interactive Demo (GitHub Pages):** [https://jeyell26.github.io/CloudCompanion/](https://jeyell26.github.io/CloudCompanion/)
- **LogPulse Live AWS Production App (EC2):** [http://3.89.224.215](http://3.89.224.215)
- **LogPulse GitHub Repository:** [https://github.com/Jeyell26/CloudCompanion](https://github.com/Jeyell26/CloudCompanion)
- **Serverless Log Generator (tiny) Subdirectory:** [https://github.com/Jeyell26/CloudCompanion/tree/main/tiny](https://github.com/Jeyell26/CloudCompanion/tree/main/tiny)

---

## Featured Engineering Projects

1. **LogPulse (CloudCompanion):** Multi-tenant AWS CloudWatch Log SaaS using Cross-Account IAM Role Assumption (`sts:AssumeRole`) with 1-hour temporary STS tokens.
2. **CrewAI Agentic Troubleshooting Workflow:** Intelligent multi-agent diagnostic workflow using CrewAI and LiteLLM authorization gateway to automate root-cause log analysis *(Enterprise Internal)*.
3. **Serverless Log Stream Generator:** Infrastructure-as-Code microservice utilizing AWS SAM (Lambda, API Gateway, S3) with SigV4 authentication and duration guardrails.
4. **DLSU Course Slot Tracking Platform:** High-throughput class registration platform maintaining 100% uptime during peak enrollment surges of 45,710 unique daily visitors *(Organization Internal)*.

---

## Automated Deployment (GitHub Actions)

Pushes to the `main` branch trigger `.github/workflows/deploy.yml` to automatically build and deploy static assets directly to **GitHub Pages**.
