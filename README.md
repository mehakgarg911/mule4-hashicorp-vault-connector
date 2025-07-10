# Mule-HashiCorp Vault Custom Connector

This is a custom Mule 4 connector that enables secure integration with **HashiCorp Vault**, allowing you to read, write, and delete secrets directly from your Mule applications.

Built using **Java 17**, **Spring Vault**, and the **Mule SDK**, this connector is designed for enterprise-grade secret management workflows within the MuleSoft ecosystem.

---

## 📦 Features

- 🔐 Authenticate to Vault using Token-based Auth
- 📤 Write/update secrets to KV v2 engine
- 📥 Read secrets securely
- 🧹 Delete secrets by path
- ✅ Built with Java 17 and compatible with Mule Runtime 4.4+
- 🔄 Easy deployment to Anypoint Exchange

---

## 🚀 Prerequisites

| Requirement        | Version           |
|--------------------|-------------------|
| Mule Runtime        | 4.9.0 or higher    |
| Java                | 17                |
| Maven               | 4.0.0+            |
| Mule SDK API        | 0.11.1            |
| Spring Vault        | 3.2.0             |
| Mule Maven Plugin   | 4.2.0             |

---

## 🛠️ Setup & Build

### 1. Clone the Project

```bash
git clone https://github.com/your-org/mule-hashicorp-vault.git
cd mule-hashicorp-vault

### 2. Configure Maven
Ensure your settings.xml contains credentials for Anypoint Exchange, if you plan to deploy.

### 3. Build Locally
```bash
mvn clean install

### 4. Deploy to Anypoint Exchange
mvn deploy
Ensure the distributionManagement section in pom.xml points to your organization's Exchange repo.

### 5. Use in Projects:
Add this dependency to your application pom.xml

```bash
<groupId>{orgId}</groupId>
<artifactId>mule-hashicorp-vault</artifactId>
<version>1.0.0</version>
<classifier>mule-plugin</classifier>
```
### Author
**Mehak Garg**
Certified in:
*MuleSoft Certified Integration Architect*
*MuleSoft Certified Platform Architect*
*MuleSoft Certified Developer Level 1*
*MuleSoft Certified Developer Level 2*
*Boomi Associate Integration Developer*
*Salesforce AI Associate*
*Salesforce AI Specialist*
*Workato Automation Pro I*

🔗 Connect with me on LinkedIn https://www.linkedin.com/in/mehakgarg911



