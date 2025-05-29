# MLflow + OpenID Connect 🔐

> **OIDC Plugin for MLflow: Establishing SSO and Permission Management**

Welcome to the **mlflow-oidc** organization! We provide a comprehensive solution for integrating OpenID Connect (OIDC) authentication and authorization with MLflow tracking servers, enabling enterprise-grade Single Sign-On (SSO) and permission management.

## 🚀 What We Offer

Our organization maintains a complete ecosystem of tools to secure your MLflow deployments:

### 🔌 Core Plugin
- **[mlflow-oidc-auth](https://github.com/mlflow-oidc/mlflow-oidc-auth)** - The main OIDC authentication plugin for MLflow tracking servers
  - Full OpenID Connect integration with group-based authorization
  - Supports major identity providers (Okta, Microsoft Entra ID, and more)
  - Built-in permission management system

### 🐳 Docker Solutions
- **[mlflow-tracking-server-docker](https://github.com/mlflow-oidc/mlflow-tracking-server-docker)** - Pre-configured Docker image
  - Ready-to-use MLflow tracking server with OIDC authentication
  - Automated daily builds with latest MLflow and OIDC plugin versions
  - Semantic versioning: `MLflow-version_OIDC-version_Build-date`

### ☸️ Kubernetes Deployment
- **[helm](https://github.com/mlflow-oidc/helm)** - Helm charts for Kubernetes deployment
  - Production-ready Kubernetes deployments
  - 📦 **12 releases** available
  - Easy configuration and scaling

### 🧪 Development & Testing
- **[oidc-provider-mock-docker](https://github.com/mlflow-oidc/oidc-provider-mock-docker)** - Mock OIDC provider
  - Dockerized mock OpenID provider for development and testing
  - Simplifies local development workflow

## 🛠️ Quick Start

### Installation
```bash
# Full version with MLflow and all dependencies
pip install mlflow-oidc-auth[full]

# Skinny version (MLflow installed separately)
pip install mlflow-oidc-auth
```

### Supported Identity Providers
- **Okta** - Full integration with group support
- **Microsoft Entra ID** - Advanced group membership detection
- **Generic OIDC** - Any OpenID Connect compliant provider

### Key Features
- 🔐 **Single Sign-On (SSO)** - Seamless authentication experience
- 👥 **Group-based Authorization** - Role-based access control
- 🔒 **Session Management** - Secure session handling (filesystem/Redis)
- 🌐 **Multi-provider Support** - Works with major identity providers
- 🎛️ **Admin Interface** - Permission management UI
- 📊 **Production Ready** - Battle-tested in enterprise environments


## 🔗 Links

- 📦 **PyPI Package**: [mlflow-oidc-auth](https://pypi.org/project/mlflow-oidc-auth/)
- 📖 **Documentation**: [mlflow-oidc-auth](https://mlflow-oidc.github.io/mlflow-oidc-auth/#/)
- 🐛 **Issues**: Report bugs and feature requests in respective repositories
- 💬 **Discussions**: Community discussions welcome

## 🏢 Enterprise Ready

This solution is designed for enterprise environments requiring:
- Centralized authentication management
- Compliance with security policies
- Scalable MLflow deployments
- Integration with existing identity infrastructure


## 💼 Commercial Support

Need enterprise-grade support for your MLflow OIDC deployment? We offer comprehensive commercial services to ensure your success.

### 🛠️ What We Provide

- **🚀 Implementation Support** - Expert guidance for setup and configuration
- **🔧 Custom Integration** - Tailored solutions for your specific infrastructure
- **📞 Priority Support** - Dedicated support channels with guaranteed SLA
- **🎓 Training & Onboarding** - Team training sessions and best practices
- **🔒 Security Auditing** - Security assessment and compliance verification
- **⚡ Performance Optimization** - Scaling and performance tuning services

### 🏆 Enterprise Benefits

- **Guaranteed Response Times** - 4-hour response for critical issues
- **Direct Developer Access** - Work directly with the core development team
- **Custom Feature Development** - Priority development of enterprise-specific features
- **Long-term Maintenance** - Extended support for legacy versions

### 📧 Get Started

Ready to discuss your enterprise needs? Contact our team:

**📩 Email:** [mlflow-oidc-support@technicaldomain.xyz](mailto:mlflow-oidc-support@technicaldomain.xyz)

*We typically respond within 24 hours for enterprise inquiries.*
