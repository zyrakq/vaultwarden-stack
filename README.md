# 🔐 Vaultwarden Stack

Complete Docker-based Vaultwarden deployment with SSL certificate management for production and development environments.

## 📦 Components

### 🔑 [Vaultwarden Service](src/vaultwarden/)

Lightweight Bitwarden server implementation with modular configuration system, multiple deployment modes, and comprehensive password management capabilities.

### 🌐 [Let's Encrypt Manager](src/ssl-automation/letsencrypt-manager/)

Automatic SSL certificate generation and renewal using Let's Encrypt for production deployments with internet access.

### 🔒 [Step CA Manager](src/ssl-automation/step-ca-manager/)

Self-signed trusted certificate authority for virtual Docker networks without internet access. Automatically manages and distributes CA certificates within isolated environments.

## 🚀 Quick Start

Each component has its own README with detailed setup instructions. Choose the certificate management solution that fits your deployment scenario.

## 📋 Requirements

- Docker & Docker Compose
- Domain name (for production deployments)
- Email address (for Let's Encrypt)

## 📄 License

This project is dual-licensed under:

- [Apache License 2.0](LICENSE-APACHE)
- [MIT License](LICENSE-MIT)
