# Musfira AI Security advisory permissions are now generally available - By Musfira AI

> Curated, written, and published by **Musfira AI**.

## Overview

Security advisories have always been a critical component of software development, allowing users to understand and mitigate potential vulnerabilities in their systems. Traditionally, repository owners had to grant security advisory access to specific individuals, either by making them repository administrators or by assigning them custom roles. This approach was cumbersome and often led to inefficiencies and security risks.

However, with the recent changes, organization owners can now let people work on repository security advisories through custom repository roles. This means that developers, security analysts, and other stakeholders can collaborate on security advisories without the need for administrative privileges. This shift is significant because it empowers teams to quickly address vulnerabilities and improve security without compromising the overall stability of the repository.

**Source reference:** [https://github.blog/changelog/2026-11-20-security-advisory-permissions-are-now-generally-available](https://github.blog/changelog/2026-11-20-security-advisory-permissions-are-now-generally-available)
**Published:** 2026-11-23

## Key Features

Five Descriptions of Capabilities

1. **Custom Role Assignment**: Users can now be assigned specific security advisory roles within the repository, enabling them to access and contribute to security advisories without needing to be full repository administrators.
2. **Private Vulnerability Reports**: Organizations can securely share and manage private vulnerability reports directly within the repository, ensuring that sensitive information is not shared with unauthorized parties.
3. **Enhanced Collaboration**: This new feature promotes better collaboration among developers, security analysts, and other stakeholders, leading to more comprehensive security coverage and faster issue resolution.
4. **Improved Security Compliance**: By facilitating secure and efficient collaboration on security advisories, this change helps organizations meet security compliance requirements more effectively.
5. **Increased Accountability**: Custom roles allow for more precise accountability, ensuring that all security advisories are reviewed and approved by the appropriate team members, thereby enhancing the overall security posture of the repository.

## Use Cases

Three Real-World Use Cases

1. **Team Collaboration on a High-Security Project**: A team working on a critical project involving a highly sensitive database must collaborate closely on security advisories. By setting up a custom role specifically for them, this team can easily access and contribute to security advisories without needing administrative privileges.
2. **Addressing a Security Incident**: In the event of a security incident, a developer can quickly work on a security advisory to prevent further breaches. With the ability to create and manage security advisories through custom roles, they can quickly address the issue without needing administrative access.
3. **Enhanced Security Reporting**: A security analyst can easily create a private vulnerability report and share it with the team for review and discussion. This streamlined process ensures that all team members are aware of and can contribute to the security advisories, leading to better security outcomes.

## Quickstart

### Python

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python main.py
```

### n8n Workflow

Import `workflow.json` into your n8n instance via **Workflows > Import from File**.

### Local LLM (Ollama)

```bash
ollama pull llama3
ollama run llama3
```



## FAQ

To implement this new feature and start using custom roles for security advisories, follow these steps:

1. **Navigate to the Repository Role Management Panel**: Log in to your organization's repository management system and access the panel where you can manage roles and permissions.
2. **Create a New Role**: Within the panel, create a new custom role specifically for security advisories. Assign the necessary permissions, such as viewing, creating, and approving advisories.
3. **Assign Users to the Role**: Once the role is created, assign it to the appropriate users within your team. This could be developers, security analysts, or any other stakeholders involved in security advisories.
4. **Access and Work on Security Advisories**: Users with the custom security advisory role will now be able to access and contribute to security advisories within the repository, eliminating the need for administrative privileges and improving overall security collaboration.

This change in security advisory permissions represents a significant improvement in security practices, allowing for more efficient collaboration, enhanced accountability, and better security outcomes for your organization.

## Repository Structure

```
.
├── main.py
├── requirements.txt
├── workflow.json
├── ui/
│   └── index.html
└── README.md
```

## About Musfira AI

Musfira AI builds automation systems, AI agents, and YouTube automation pipelines for
creators and businesses across Pakistan and India.

- 🌐 Website: [https://musfiraai.com](https://musfiraai.com)
- ▶️ YouTube: [Automate With Musfira AI](https://www.youtube.com/@automatewithmusfiraai)
- 💼 LinkedIn: [https://www.linkedin.com/in/musfira-ai-b3218b39b](https://www.linkedin.com/in/musfira-ai-b3218b39b)
- 📸 Instagram: [https://instagram.com/musma_n55](https://instagram.com/musma_n55)
- 📍 Location: [Google Maps](https://share.google/kJchUsfQyABVLghSF)
- 💬 WhatsApp: [Chat with us](https://wa.me/923217358096)
- 📞 Call: [+923217358096](tel:+923217358096)

---

*This repository is part of Musfira AI's daily AI trend tracking series. Star ⭐ this repo
and follow the links above for daily updates on AI models, n8n workflows, and local LLM tools.*
