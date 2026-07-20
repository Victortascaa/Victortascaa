<div align="center">

<img src="./assets/banner.svg" alt="status: operational" width="700" />

<br/>

# 🟢 victor-tasca `/ status-page`

**Analista de Cloud & Automação** — Castelo Branco, PT
Monitorando infraestrutura crítica desde 2015. Zero downtime aceitável.

<a href="https://www.linkedin.com/in/victor-tasca"><img src="https://img.shields.io/badge/LinkedIn-Victor_Tasca-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/Victortascaa"><img src="https://img.shields.io/badge/GitHub-Victortascaa-181717?style=flat-square&logo=github&logoColor=white" /></a>
<img src="https://img.shields.io/badge/status-operational-brightgreen?style=flat-square" />

</div>

<br/>

## 📟 System Status

```diff
+ Azure ............... operational
+ AWS .................. operational
+ Oracle Cloud ......... operational
+ Terraform (IaC) ...... operational
+ n8n / automação ...... operational
+ pfSense / VPN ........ operational
+ SIEM (Wazuh) ......... monitoring
! trabalho manual ...... deprecated — sunset em progresso
```

<br/>

## 🔍 Root Cause Analysis (por que eu automatizo diferente)

A maioria dos profissionais de automação parte da superfície: veem um processo repetitivo e o transformam em script. Eu não.

Antes de escrever a primeira linha de Terraform, eu **sustentei** o que estava por trás — AD, M365, firewall, VPN, SIEM. Isso significa que quando eu automatizo, eu já sei onde o processo pode quebrar, porque já fui eu quem apagou o incêndio às 3h da manhã.

```text
outros:  processo manual → identifica dor → automatiza
eu:      diagnostico → penso em IAM/custo/governança → aí sim, automatizo
```

<br/>

## 🧰 Stack (component health)

<div align="center">

| Camada | Componentes |
|---|---|
| **☁️ Cloud** | ![Azure](https://img.shields.io/badge/-Azure-0089D6?style=flat-square&logo=microsoftazure&logoColor=white) ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![OCI](https://img.shields.io/badge/-Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white) |
| **🏗️ IaC** | ![Terraform](https://img.shields.io/badge/-Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) |
| **⚙️ Automação** | ![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PowerShell](https://img.shields.io/badge/-PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) |
| **🔐 Identity** | ![AD](https://img.shields.io/badge/-Active_Directory-0078D4?style=flat-square&logo=windows&logoColor=white) ![Entra](https://img.shields.io/badge/-Entra_ID-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![M365](https://img.shields.io/badge/-M365-D83B01?style=flat-square&logo=microsoft365&logoColor=white) ![Google Workspace](https://img.shields.io/badge/-Google_Workspace-4285F4?style=flat-square&logo=googleworkspace&logoColor=white) |
| **🛡️ Security** | ![pfSense](https://img.shields.io/badge/-pfSense-212121?style=flat-square&logo=pfsense&logoColor=white) ![Wazuh](https://img.shields.io/badge/-Wazuh-3AB7E9?style=flat-square&logo=wazuh&logoColor=white) ![Netskope](https://img.shields.io/badge/-Netskope-00A98F?style=flat-square) |

</div>

<br/>

## 📈 Postmortem: linha do tempo de incidentes resolvidos (a.k.a. carreira)

```mermaid
timeline
    title Trajetória — de hands-on a multi-cloud
    2015 : Hardware & suporte hands-on
    2022 : TIC · infraestrutura · operações
    2023 : Suporte global · Azure · M365 · AD
    2024 : N2/N3 · firewall · SIEM · automação de TI
    2026 : Cloud & Automação · Terraform · n8n · multi-cloud
```

> Formação: **Análise e Desenvolvimento de Sistemas** (UniMetrocamp) · Técnico em Manutenção e Suporte (Senac-SP)

<br/>

## 🚀 Deployments em destaque

| Repositório | Descrição |
|---|---|
| [**projeto_noticias_telegram**](https://github.com/Victortascaa/projeto_noticias_telegram) | Scraping + monitoramento + Telegram para rádios FM (Python) |
| [**vaultscore-mvp**](https://github.com/Victortascaa/vaultscore-mvp) | Experimento em TypeScript |
| [**aether-empires**](https://github.com/Victortascaa/aether-empires) | Experimento em TypeScript |
| [**Betel-APP**](https://github.com/Victortascaa/Betel-APP) | App React Native (projeto de faculdade) |
| [**Trabalho-de-Extens-o-Python01**](https://github.com/Victortascaa/Trabalho-de-Extens-o-Python01) | App voluntário para pequena comerciante |

<br/>

## 💬 Incident response policy

```text
> não automatizo caos.
> primeiro estabilizo o ambiente.
> depois — e só depois — transformo processo em pipeline.
```

Se você precisa de alguém que liga **Cloud + IaC + Automação** sem perder o chão da infraestrutura, abre um chamado 👇

<div align="center">

<a href="https://www.linkedin.com/in/victor-tasca">
  <img src="https://img.shields.io/badge/Contato-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="https://github.com/Victortascaa">
  <img src="https://img.shields.io/badge/GitHub-Victortascaa-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br/>

```text
$ tail -f victor.log
[OK] sempre construindo o próximo playbook
```

</div>
