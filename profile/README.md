
# SoftBank Hackathon 2026

> **powered by KOREC & Progate**  
> **Theme: One Action, Infinite Clouds.**

안녕하세요! 팀 **orchid**입니다.

## 👥 Team InfraMorph

<table>
  <tr>
    <td align="center" width="20%">
      <a href="https://github.com/Ohjackson">
        <img src="https://avatars.githubusercontent.com/Ohjackson?s=200" width="100" height="100" alt="Ohjackson"/>
      </a><br/>
      <b>A · AWS · PM</b><br/>
      <a href="https://github.com/Ohjackson">@Ohjackson</a><br/>
      <sub>AWS Adapter · Infrastructure</sub>
    </td>
    <td align="center" width="20%">
      <a href="https://github.com/nomellc">
        <img src="https://avatars.githubusercontent.com/nomellc?s=200" width="100" height="100" alt="nomellc"/>
      </a><br/>
      <b>B · Schema</b><br/>
      <a href="https://github.com/nomellc">@nomellc</a><br/>
      <sub>Schema · Repo Mapper · Planner</sub>
    </td>
    <td align="center" width="20%">
      <a href="https://github.com/Nobles3689">
        <img src="https://avatars.githubusercontent.com/Nobles3689?s=200" width="100" height="100" alt="Nobles3689"/>
      </a><br/>
      <b>C · Analysis · AI </b><br/>
      <a href="https://github.com/Nobles3689">@Nobles3689</a><br/>
      <sub>Analyzer · Code Patch Agent</sub>
    </td>
    <td align="center" width="20%">
      <a href="https://github.com/fl0wizy">
        <img src="https://avatars.githubusercontent.com/fl0wizy?s=200" width="100" height="100" alt="fl0wizy"/>
      </a><br/>
      <b>D · Core · Frontend</b><br/>
      <a href="https://github.com/fl0wizy">@fl0wizy</a><br/>
      <sub>Control Plane · Web UI</sub>
    </td>
    <td align="center" width="20%">
      <a href="https://github.com/kwongwangjae">
        <img src="https://avatars.githubusercontent.com/kwongwangjae?s=200" width="100" height="100" alt="kwongwangjae"/>
      </a><br/>
      <b>E · Build / Runtime · Policy</b><br/>
      <a href="https://github.com/kwongwangjae">@kwongwangjae</a><br/>
      <sub>Policy Gate · Builder · Local Adapter</sub>
    </td>
  </tr>
</table>

## ☁️ InfraMorph

>배포 환경을 몰라도, github 레포 URL 하나와 버튼 한 번으로 On-premises (local)과 AWS에 배포

InfraMorph는 애플리케이션의 소스 코드와 구조를 분석하고, 배포에 필요한 계획과 패치를 생성하여  
검증 및 승인 과정을 거친 뒤 로컬 또는 AWS 환경에 배포하는 AI 기반 배포 플랫폼입니다.

### Key Features

- **AI Repository Analysis**: Codex CLI 또는 OpenAI API 기반 소스 코드 분석
- **Deployment Planning**: 환경별 배포 계획과 필요한 코드 패치 생성
- **Policy & Approval Gate**: 정책 검사와 사용자 승인을 통과한 배포만 실행
- **Local & AWS Deployment**: 동일한 Control Plane에서 로컬 및 AWS 배포 관리
- **Safe Recovery**: 변경 감지, 재배포, 검증, 재시도 및 롤백 지원
- **Web Control Plane**: 프로젝트와 대상별 배포 상태를 Web UI에서 확인

### service Architecture

<img width="3800" height="1480" alt="InfraMorph — 서비스 아키텍처(간결)" src="https://github.com/user-attachments/assets/f87a93cb-9eaf-4ca4-92ee-f7d4dcd9b35d" />


## 🔧 Tech Stack

### Core / AI

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" height="24" alt="Python"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" height="24" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" height="24" alt="Pydantic"/>
  <img src="https://img.shields.io/badge/Codex_CLI-000000?style=for-the-badge&logo=openai&logoColor=white" height="24" alt="Codex CLI"/>
  <img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white" height="24" alt="OpenAI API"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" height="24" alt="SQLite"/>
</p>

### Frontend

<p>
  <img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" height="24" alt="React"/>
  <img src="https://img.shields.io/badge/Vite_7-646CFF?style=for-the-badge&logo=vite&logoColor=white" height="24" alt="Vite"/>
  <img src="https://img.shields.io/badge/Mermaid-FF3670?style=for-the-badge&logo=mermaid&logoColor=white" height="24" alt="Mermaid"/>
</p>

### Cloud / Infrastructure

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" height="24" alt="AWS"/>
  <img src="https://img.shields.io/badge/Terraform_1.10+-844FBA?style=for-the-badge&logo=terraform&logoColor=white" height="24" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" height="24" alt="Docker"/>
  <img src="https://img.shields.io/badge/Amazon_ECS-FF9900?style=for-the-badge&logo=amazonecs&logoColor=white" height="24" alt="Amazon ECS"/>
  <img src="https://img.shields.io/badge/Amazon_ECR-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" height="24" alt="Amazon ECR"/>
  <img src="https://img.shields.io/badge/Amazon_RDS_PostgreSQL-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white" height="24" alt="Amazon RDS PostgreSQL"/>
  <img src="https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white" height="24" alt="Amazon S3"/>
  <img src="https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazoncloudwatch&logoColor=white" height="24" alt="Amazon CloudWatch"/>
</p>

### DevOps

<p>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" height="24" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" height="24" alt="Git"/>
</p>

## 📦 Repositories

| Repository | Description |
|---|---|
| [inframorph](https://github.com/Team-InfraMorph/inframorph) | AI 분석, 배포 계획, Control Plane, Local/AWS Adapter를 포함한 핵심 플랫폼 |
| [demo-app](https://github.com/Team-InfraMorph/demo-app) | Local 및 AWS 배포 흐름을 검증하기 위한 Web/API·Worker 샘플 애플리케이션 |
| [redteam-repo](https://github.com/Team-InfraMorph/redteam-repo) | 비신뢰 입력 경계와 GitHub 협업·자동화 정책을 검증하기 위한 테스트 저장소 |

---

<p align="center">
  <b>Team InfraMorph · SoftBank Hackathon 2026</b>
</p>
