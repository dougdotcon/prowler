# ProwlerPlatform

<p align="center">
  <img align="center" src="https://github.com/prowler-cloud/prowler/blob/master/docs/img/prowler-logo-black.png#gh-light-mode-only" width="50%" height="50%">
  <img align="center" src="https://github.com/prowler-cloud/prowler/blob/master/docs/img/prowler-logo-white.png#gh-dark-mode-only" width="50%" height="50%">
</p>

<p align="center">
  <b><i>ProwlerPlatform</b> is the open-source cloud security platform trusted by thousands to automate security and compliance in any cloud environment. With hundreds of ready-to-use checks and compliance frameworks, it delivers real-time, customizable monitoring and seamless integrations, making cloud security simple, scalable, and cost-effective for organizations of any size.</p>

<p align="center">
<b>Learn more at <a href="https://prowler.com">prowler.com</i></b>
</p>

<p align="center">
<a href="https://goto.prowler.com/slack"><img width="30" height="30" alt="Prowler community on Slack" src="https://github.com/prowler-cloud/prowler/assets/38561120/3c8b4ec5-6849-41a5-b5e1-52bbb94af73a"></a>
  <br>
  <a href="https://goto.prowler.com/slack">Join our Prowler community!</a>
</p>

<hr>

<p align="center">
  <a href="https://goto.prowler.com/slack"><img alt="Slack Shield" src="https://img.shields.io/badge/slack-prowler-brightgreen.svg?logo=slack"></a>
  <a href="https://pypi.org/project/prowler/"><img alt="Python Version" src="https://img.shields.io/pypi/v/prowler.svg"></a>
  <a href="https://pypi.python.org/pypi/prowler/"><img alt="Python Version" src="https://img.shields.io/pypi/pyversions/prowler.svg"></a>
  <a href="https://pypistats.org/packages/prowler"><img alt="PyPI Prowler Downloads" src="https://img.shields.io/pypi/dw/prowler.svg?label=prowler%20downloads"></a>
  <a href="https://hub.docker.com/r/toniblyx/prowler"><img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/toniblyx/prowler"></a>
  <a href="https://hub.docker.com/r/toniblyx/prowler"><img alt="Docker" src="https://img.shields.io/docker/cloud/build/toniblyx/prowler"></a>
  <a href="https://hub.docker.com/r/toniblyx/prowler"><img alt="Docker" src="https://img.shields.io/docker/image-size/toniblyx/prowler"></a>
  <a href="https://gallery.ecr.aws/prowler-cloud/prowler"><img width="120" height="19" alt="AWS ECR Gallery" src="https://user-images.githubusercontent.com/3985464/151531396-b6535a68-c907-44eb-95a1-a09508178616.png"></a>
  <a href="https://codecov.io/gh/prowler-cloud/prowler"><img src="https://codecov.io/gh/prowler-cloud/prowler/graph/badge.svg?token=OflBGsdpDl"/></a>
</p>

<p align="center">
  <a href="https://github.com/prowler-cloud/prowler"><img alt="Repo size" src="https://img.shields.io/github/repo-size/prowler-cloud/prowler"></a>
  <a href="https://github.com/prowler-cloud/prowler/issues"><img alt="Issues" src="https://img.shields.io/github/issues/prowler-cloud/prowler"></a>
  <a href="https://github.com/prowler-cloud/prowler/releases"><img alt="Version" src="https://img.shields.io/github/v/release/prowler-cloud/prowler"></a>
</p>

## 📋 Overview

ProwlerPlatform is a comprehensive open-source tool designed for security auditing, monitoring, and compliance assessment in cloud environments. It supports AWS, Azure, GCP, and Kubernetes, providing hundreds of checks to ensure your infrastructure adheres to best practices and regulatory standards.

Key capabilities include:
- **Multi-Cloud Support**: Seamlessly audit AWS, Azure, GCP, and Kubernetes clusters.
- **Compliance Frameworks**: Pre-built mappings for CIS, NIST 800-53, NIST CSF, CISA, FedRAMP, PCI-DSS, GDPR, HIPAA, FFIEC, SOC2, GXP, Well-Architected Security, ENS, and more.
- **Real-Time Monitoring**: Continuous checks with customizable alerts and reporting.
- **Incident Response & Forensics**: Tools for quick triage and readiness.

## 🚀 Quick Start

### Prerequisites
- Python 3.9+
- AWS CLI (for AWS scans)
- Azure CLI (for Azure scans)
- GCloud CLI (for GCP scans)
- kubectl (for Kubernetes scans)

### Installation

Install via pip:
bash
pip install prowler


Or use Docker:
bash
docker pull toniblyx/prowler


### Basic Usage

Run a full AWS audit:
bash
prowler aws


Run a specific compliance check (e.g., CIS AWS Foundations Benchmark):
bash
prowler aws --compliance cis_aws_v1


Generate an HTML report:
bash
prowler aws -M html


For detailed usage, see the [Documentation](https://docs.prowler.com).

## 🌟 Features

- **Extensible Architecture**: Easy to add custom checks and compliance frameworks.
- **Modular Design**: Select specific services or regions to scan.
- **Output Formats**: JSON, CSV, HTML, and integrations with SIEM tools.
- **Remediation Guidance**: Detailed findings with actionable steps.
- **Community Driven**: Active Slack community and contributions.

## 🤝 Contributing

We welcome contributions! Please check our [Contributing Guide](https://github.com/prowler-cloud/prowler/blob/master/CONTRIBUTING.md) to get started.

## 📊 Security & Compliance

ProwlerPlatform itself is developed with security in mind. For reporting vulnerabilities, please email security@prowler.com or use the [GitHub Security Advisory](https://github.com/prowler-cloud/prowler/security/advisories/new).

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/prowler-cloud/prowler/blob/master/LICENSE) file for details.

---

<p align="center">
  <i>Built with ❤️ by the Prowler community.</i>
</p>