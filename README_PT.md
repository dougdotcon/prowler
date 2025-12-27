# ProwlerPlatform

<p align="center">
  <img align="center" src="https://github.com/prowler-cloud/prowler/blob/master/docs/img/prowler-logo-black.png#gh-light-mode-only" width="50%" height="50%">
  <img align="center" src="https://github.com/prowler-cloud/prowler/blob/master/docs/img/prowler-logo-white.png#gh-dark-mode-only" width="50%" height="50%">
</p>

<p align="center">
  <b><i>ProwlerPlatform</b> é a plataforma de segurança em nuvem open source confiada por milhares para automatizar a segurança e conformidade em qualquer ambiente de nuvem. Com centenas de verificações prontas para uso e frameworks de conformidade, ela oferece monitoramento em tempo real, personalizável e integrações perfeitas, tornando a segurança em nuvem simples, escalável e econômica para organizações de qualquer tamanho.</p>

<p align="center">
<b>Saiba mais em <a href="https://prowler.com">prowler.com</i></b>
</p>

<p align="center">
<a href="https://goto.prowler.com/slack"><img width="30" height="30" alt="Comunidade Prowler no Slack" src="https://github.com/prowler-cloud/prowler/assets/38561120/3c8b4ec5-6849-41a5-b5e1-52bbb94af73a"></a>
  <br>
  <a href="https://goto.prowler.com/slack">Junte-se à nossa comunidade Prowler!</a>
</p>

<hr>

<p align="center">
  <a href="https://goto.prowler.com/slack"><img alt="Escudo Slack" src="https://img.shields.io/badge/slack-prowler-brightgreen.svg?logo=slack"></a>
  <a href="https://pypi.org/project/prowler/"><img alt="Versão Python" src="https://img.shields.io/pypi/v/prowler.svg"></a>
  <a href="https://pypi.python.org/pypi/prowler/"><img alt="Versão Python" src="https://img.shields.io/pypi/pyversions/prowler.svg"></a>
  <a href="https://pypistats.org/packages/prowler"><img alt="Downloads PyPI Prowler" src="https://img.shields.io/pypi/dw/prowler.svg?label=prowler%20downloads"></a>
  <a href="https://hub.docker.com/r/toniblyx/prowler"><img alt="Pulls Docker" src="https://img.shields.io/docker/pulls/toniblyx/prowler"></a>
  <a href="https://hub.docker.com/r/toniblyx/prowler"><img alt="Docker" src="https://img.shields.io/docker/cloud/build/toniblyx/prowler"></a>
  <a href="https://hub.docker.com/r/toniblyx/prowler"><img alt="Docker" src="https://img.shields.io/docker/image-size/toniblyx/prowler"></a>
  <a href="https://gallery.ecr.aws/prowler-cloud/prowler"><img width="120" height="19" alt="Galeria AWS ECR" src="https://user-images.githubusercontent.com/3985464/151531396-b6535a68-c907-44eb-95a1-a09508178616.png"></a>
  <a href="https://codecov.io/gh/prowler-cloud/prowler"><img src="https://codecov.io/gh/prowler-cloud/prowler/graph/badge.svg?token=OflBGsdpDl"/></a>
</p>

<p align="center">
  <a href="https://github.com/prowler-cloud/prowler"><img alt="Tamanho do Repo" src="https://img.shields.io/github/repo-size/prowler-cloud/prowler"></a>
  <a href="https://github.com/prowler-cloud/prowler/issues"><img alt="Issues" src="https://img.shields.io/github/issues/prowler-cloud/prowler"></a>
  <a href="https://github.com/prowler-cloud/prowler/releases"><img alt="Versão" src="https://img.shields.io/github/v/release/prowler-cloud/prowler"></a>
</p>

## 📋 Visão Geral

O ProwlerPlatform é uma ferramenta open source abrangente projetada para auditoria de segurança, monitoramento e avaliação de conformidade em ambientes de nuvem. Ele suporta AWS, Azure, GCP e Kubernetes, fornecendo centenas de verificações para garantir que sua infraestrutura esteja aderente às melhores práticas e padrões regulatórios.

Capacidades principais incluem:
- **Suporte Multi-Nuvem**: Audite sem esforço AWS, Azure, GCP e clusters Kubernetes.
- **Frameworks de Conformidade**: Mapeamentos pré-construídos para CIS, NIST 800-53, NIST CSF, CISA, FedRAMP, PCI-DSS, GDPR, HIPAA, FFIEC, SOC2, GXP, Well-Architected Security, ENS e mais.
- **Monitoramento em Tempo Real**: Verificações contíneas com alertas e relatórios personalizáveis.
- **Resposta a Incidentes e Forense**: Ferramentas para triagem rápida e prontidão.

## 🚀 Início Rápido

### Pré-requisitos
- Python 3.9+
- AWS CLI (para varreduras na AWS)
- Azure CLI (para varreduras na Azure)
- GCloud CLI (para varreduras na GCP)
- kubectl (para varreduras no Kubernetes)

### Instalação

Instale via pip:
bash
pip install prowler


Ou use Docker:
bash
docker pull toniblyx/prowler


### Uso Básico

Execute uma auditoria completa na AWS:
bash
prowler aws


Execute uma verificação de conformidade específica (ex: CIS AWS Foundations Benchmark):
bash
prowler aws --compliance cis_aws_v1


Gere um relatório HTML:
bash
prowler aws -M html


Para uso detalhado, veja a [Documentação](https://docs.prowler.com).

## 🌟 Funcionalidades

- **Arquitetura Extensível**: Fácil adicionar verificações e frameworks de conformidade personalizados.
- **Design Modular**: Selecione serviços ou regiões específicas para escanear.
- **Formatos de Saída**: JSON, CSV, HTML e integrações com ferramentas SIEM.
- **Orientação de Remediação**: Descobertas detalhadas com passos acionáveis.
- **Comunidade Ativa**: Slack ativo e contribuições de desenvolvedores.

## 🤝 Contribuindo

Seja bem-vindo! Consulte nosso [Guia de Contribuição](https://github.com/prowler-cloud/prowler/blob/master/CONTRIBUTING.md) para começar.

## 📊 Segurança e Conformidade

O ProwlerPlatform é desenvolvido com segurança em mente. Para reportar vulnerabilidades, envie um email para security@prowler.com ou use o [GitHub Security Advisory](https://github.com/prowler-cloud/prowler/security/advisories/new).

## 📜 Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](https://github.com/prowler-cloud/prowler/blob/master/LICENSE) para detalhes.

---

<p align="center">
  <i>Construído com ❤️ pela comunidade Prowler.</i>
</p>