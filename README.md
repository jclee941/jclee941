# 안녕하세요, JAECHEOL LEE 👋
# Hello, JAECHEOL LEE 👋

> 인프라 & 보안 엔지니어 · 9년차 · 홈랩 GitOps 운영자
> Infrastructure & Security Engineer · 9 yrs · Home-lab GitOps operator

![Profile: jclee941](https://img.shields.io/badge/GitHub-jclee941-181717?style=flat-square&logo=github&logoColor=white)
![Focus: Infra & Security](https://img.shields.io/badge/Focus-Infra%20%26%20Security-4A90E2?style=flat-square)
![Home-lab: Proxmox](https://img.shields.io/badge/Home--lab-Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Edge: Cloudflare](https://img.shields.io/badge/Edge-Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)

9년차 인프라·보안 엔지니어가 운영하는 개인 프로필 레포입니다. Proxmox 홈랩을 Terraform으로 코딩하고, Splunk + FortiGate로 SIEM을 구성하며, Cloudflare Workers + Hono + D1로 엣지 앱을 배포하고, 한양사이버대 자율주행 경진대회에서 ML 파이프라인을 운영합니다. 단일 `.github` 레포에서 16개 레포를 GitOps로 자동화합니다.

Personal profile of a 9-year infra & security engineer. Spans a Terraform-coded Proxmox home-lab, a Splunk + FortiGate SIEM, Cloudflare Workers + Hono + D1 edge apps, and an ML pipeline for the Hanyang Cyber University autonomous-driving contest. A single `.github` repo drives GitOps across 16 repositories.

## 빠른 현황 / Quick Status

| 항목 / Item | 값 / Value |
|---|---|
| 역할 / Role | 인프라 & 보안 엔지니어 / Infra & Security Engineer |
| 경력 / Experience | 9년차 / 9 years |
| 핵심 도메인 / Domains | IaC, SIEM, GitOps, Edge, ML |
| 활성 레포 수 / Active repos | 16 |
| IaC 백엔드 / IaC backend | Terraform + Proxmox |
| 보안 파이프라인 / Security pipeline | Splunk + FortiGate |
| 에지 런타임 / Edge runtime | Cloudflare Workers + D1 + Hono |
| 자동화 백본 / Automation backbone | 단일 `.github` 레포 / Single `.github` repo |
| 프로필 진입점 / Profile entry | 이 README / This README |
| 운영 준비도 / Production-ready | 홈랩·자동화·보안 모니터링 운영 중 / Home-lab, automation, SIEM in operation |

## 한눈에 보기 / At a Glance

이 레포의 "제품"은 README 한 페이지입니다. 다른 16개 레포의 인덱스이자 외부에 보이는 표면이며, 신규 방문자가 기술 스택과 관심사를 빠르게 파악하도록 구성되어 있습니다.

The "product" of this repo is a single README page — the public surface and index to 16 other repositories, designed so visitors can scan the stack and interests at a glance.

## 목차 / Contents

- [프로젝트 개요 / Overview](#overview)
- [패키지 구성 & 먼저 읽을 파일 / Package Contents & First Files to Read](#contents)
- [핵심 역량 / Core Competencies](#core)
- [기술 스택 / Tech Stack](#stack)
- [주요 프로젝트 / Featured Projects](#projects)
- [아키텍처 / Architecture](#architecture)
- [로컬 개발 / Local Development](#local)
- [기여 가이드 / Contributing](#contributing)
- [라이선스 / License](#license)
- [연락처 / Contact](#contact)
- [운영 메모 / Operator Notes](#ops)

<a id="overview"></a>
## 프로젝트 개요 / Overview

- 🏗️ **Infra-as-Code** — Proxmox + Terraform 홈랩, 16개 레포를 단일 `.github`에서 GitOps로 관리
- 🛡️ **Security** — Splunk + FortiGate SIEM 파이프라인, IP 위협 인텔리전스, 버그바운티 자동화
- 🤖 **Automation** — PR-Agent fork 기반 자체 CI/CD 봇, n8n + FastAPI 워크플로
- 🌐 **Web** — Cloudflare Workers + Hono + D1 (SafetyWallet PWA, 포트폴리오)
- 🏎️ **ML** — Formula Student Driverless 자율주행 (한양사이버대 경진대회 우수상 2026)

방문자는 이 표면에서 도메인을 식별한 뒤, 각 도메인의 전용 레포로 위임됩니다. README가 곧 운영 진입점이며, 별도의 API·CLI는 노출하지 않습니다.

<a id="contents"></a>
## 패키지 구성 & 먼저 읽을 파일 / Package Contents & First Files to Read

| 경로 / Path | 종류 / Type | 용도 / Purpose |
|---|---|---|
| `README.md` | 표면 / Surface | 프로필 렌더링 및 16개 레포 인덱스 / Profile render & index |
| `CONTRIBUTING.md` | 정책 / Policy | 외부 기여 절차 / External contribution rules |
| `LICENSE` | 라이선스 / License | 이 레포 콘텐츠 사용 조건 / Terms for this repo's content |

먼저 읽을 순서: `README.md` → 관심 도메인의 연결된 레포 → 각 레포의 자체 `README.md` 및 `LICENSE`.

Read in this order: `README.md` → the linked repo for the domain you care about → that repo's own `README.md` and `LICENSE`.

<a id="core"></a>
## 핵심 역량 / Core Competencies

| 영역 / Area | 설명 / Description |
|---|---|
| 홈랩 IaC / Home-lab IaC | Proxmox 위에 Terraform으로 VM·LXC·네트워크를 선언적으로 구성 |
| 보안 모니터링 / Security monitoring | FortiGate 로그를 Splunk로 수집·상관분석, 위협 인텔리전스 운영 |
| GitOps 자동화 / GitOps automation | 단일 `.github` 레포로 워크플로·정책·메타데이터를 중앙 관리 |
| 엣지 앱 / Edge apps | Cloudflare Workers + Hono + D1로 저지연 PWA·API 구축 |
| ML 파이프라인 / ML pipeline | 자율주행 콘테스트용 perception·planning 실험·배포 |

<a id="stack"></a>
## 기술 스택 / Tech Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Proxmox](https://img.shields.io/badge/-Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Splunk](https://img.shields.io/badge/-Splunk-000000?style=flat-square&logo=splunk&logoColor=white)

<a id="projects"></a>
## 주요 프로젝트 / Featured Projects

| 레포 / Repo | 설명 / Description |
|---|---|
| [terraform](https://github.com/jclee941/terraform) | Proxmox 홈랩 IaC 모노레포 / Proxmox home-lab IaC monorepo |
| [splunk](https://github.com/jclee941/splunk) | FortiGate SIEM 보안 모니터링 앱 / FortiGate SIEM monitoring app |
| [safetywallet](https://github.com/jclee941/safetywallet) | 현장 작업자 안전 PWA (Cloudflare Workers) / Field-worker safety PWA |
| [.github](https://github.com/jclee941/jclee-bot) | 16개 레포 GitOps 자동화 허브 / GitOps automation hub |

### GitHub 통계 / GitHub Stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=jclee941&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jclee941&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

<a id="architecture"></a>
## 아키텍처 / Architecture

단일 페이지 표면이지만, 뒤쪽에는 16개 레포로 분산된 자산이 있습니다. 진입점에서 도메인별 레포로 위임되는 단순한 인덱스 구조입니다.

1. 방문자 → 이 README → 도메인별 핵심 레포로 이동
2. GitHub Actions는 `.github` 레포에서 중앙 정의되고, 각 레포로 재사용됨
3. 홈랩의 인프라 변경은 Terraform PR로 검토 후 Proxmox에 적용
4. 보안 이벤트는 FortiGate → Splunk로 흐르고, 알림은 n8n/FastAPI로 라우팅
5. 엣지 앱은 Cloudflare Workers에서 실행되고 데이터는 D1에 저장

| 계층 / Layer | 책임 / Responsibility | 예시 / Example |
|---|---|---|
| 표면 / Surface | 프로필 렌더링·인덱싱 | 이 README |
| 자동화 / Automation | 워크플로·정책 중앙화 | `.github` 레포 |
| 인프라 / Infrastructure | 홈랩 선언적 구성 | `terraform` 레포 |
| 보안 / Security | 로그 수집·상관분석 | `splunk` 레포 |
| 엣지 / Edge | 저지연 웹·API | `safetywallet` 레포 |

<a id="local"></a>
## 로컬 개발 / Local Development

이 레포는 정적 프로필 페이지이므로 별도의 빌드 단계가 없습니다. 변경 후 GitHub에 push하면 프로필이 즉시 갱신됩니다.

```bash
# 1) 클론
git clone https://github.com/jclee941/jclee-bot
cd jclee941

# 2) 마크다운 미리 보기 (선택)
# VS Code: Markdown Preview All  or  Markdown Preview Enhanced
# CLI: npx markdownlint-cli2 README.md

# 3) 커밋 & 푸시
git add README.md
git commit -m "docs: update profile"
git push origin main
```

스타일을 조정할 때는 기존 배지·이모지·테마 색상(tokyonight)을 그대로 유지하고, "빠른 현황 / Quick Status" 표가 첫 화면에서 항상 보이도록 보존합니다.

When adjusting style, keep the existing badges, emojis, and tokyonight theme, and preserve the Quick Status table so it always renders in the first viewport.

<a id="contributing"></a>
## 기여 가이드 / Contributing

외부 이슈·PR은 환영하지만, 이 레포는 개인 프로필 표면이므로 변경 범위가 제한적입니다. 텍스트 오탈자, 깨진 링크, 사실 관계 오류만 이슈로 등록해 주세요. 자세한 절차는 [CONTRIBUTING.md](CONTRIBUTING.md)를 참조하세요.

External issues and PRs are welcome, but since this is a personal profile surface, the scope of changes is limited. Please open issues only for typos, broken links, or factual errors. See [CONTRIBUTING.md](CONTRIBUTING.md) for the full procedure.

<a id="license"></a>
## 라이선스 / License

이 레포의 콘텐츠는 [LICENSE](LICENSE)에 명시된 조건에 따라 공개됩니다. 다른 16개 레포의 라이선스는 각 레포를 확인하세요.

The contents of this repository are released under the terms in [LICENSE](LICENSE). For the other 16 repositories, check each project's own license.

<a id="contact"></a>
## 연락처 / Contact

- GitHub: [@jclee941](https://github.com/jclee941)
- 이메일·기타 채널은 GitHub 프로필 bio에서 확인하세요.

GitHub: [@jclee941](https://github.com/jclee941). For email or other channels, see the GitHub profile bio.

<a id="ops"></a>
## 운영 메모 / Operator Notes

| 항목 / Item | 상태 / Status |
|---|---|
| 프로필 표면 / Profile surface | 활성 / Active |
| GitOps 자동화 / GitOps automation | 운영 중 / In operation |
| 보안 모니터링 / Security monitoring | 운영 중 / In operation |
| 홈랩 / Home-lab | 운영 중 / In operation |
| ML 콘테스트 / ML contest | 시즌 종료, 코드 아카이브 보존 / Season ended, code archived |
| 폐기 예정 / Deprecated | 없음 / None |

추가 문서는 각 연결 레포의 `docs/` 또는 위키를 참조하세요. 이 레포 자체에는 외부 API·CLI가 노출되지 않습니다.

For deeper documentation, see the `docs/` directory or wiki in each linked repo. This repository exposes no external API or CLI of its own.