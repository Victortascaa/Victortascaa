<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2500&pause=800&color=58A6FF&center=true&vCenter=true&width=560&lines=status%3A+operational;uptime%3A+9+anos+em+produção;incident+count%3A+0+ambientes+derrubados;deploy%3A+cloud+%2B+iac+%2B+automação" alt="typing" />

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

<div align="center">
<a href="https://github.com/Victortascaa/projeto_noticias_telegram">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Victortascaa&repo=projeto_noticias_telegram&theme=transparent&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" height="120" />
</a>
<a href="https://github.com/Victortascaa/vaultscore-mvp">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Victortascaa&repo=vaultscore-mvp&theme=transparent&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" height="120" />
</a>
<a href="https://github.com/Victortascaa/aether-empires">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Victortascaa&repo=aether-empires&theme=transparent&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" height="120" />
</a>
</div>

<details>
<summary><strong>📋 Changelog dos repositórios públicos</strong></summary>
<br/>

- **projeto_noticias_telegram** — scraping + monitoramento + Telegram para rádios FM (Python)
- **vaultscore-mvp** / **aether-empires** — experimentos em TypeScript
- **Betel-APP** — app React Native (projeto de faculdade)
- **Trabalho-de-Extensão-Python01** — app voluntário para pequena comerciante

</details>

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

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api?username=Victortascaa&show_icons=true&theme=transparent&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9&ring_color=58A6FF" height="165" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Victortascaa&layout=compact&theme=transparent&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" height="165" alt="Top languages" />

<br/>

```text
$ tail -f victor.log
[OK] sempre construindo o próximo playbook
```

</div>
