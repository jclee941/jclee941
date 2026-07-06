# 이재철 · JAECHEOL LEE

> 인프라 & 보안 엔지니어 · 홈랩 GitOps 운영자
> Infrastructure & Security Engineer · homelab GitOps operator

[![GitHub](https://img.shields.io/badge/GitHub-jclee941-181717?style=flat-square&logo=github)](https://github.com/jclee941)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)
[![Profile README](https://img.shields.io/badge/type-profile--README-blueviolet?style=flat-square)](README.md)

## 한국어 요약

Proxmox 홈랩을 Terraform으로 IaC화하고 FortiGate 로그를 Splunk로 수집·분석하는 9년차 인프라·보안 엔지니어입니다. 16개 레포지토리를 단일 `.github` 레포에서 GitOps로 관리하며, Cloudflare Workers 기반 PWA와 Formula Student Driverless 자율주행 프로젝트도 함께 진행합니다.

## Quick-glance status

| 항목 | 값 |
|------|-----|
| 종류 | GitHub 프로필 레포지토리 (단일 README) |
| 코드 실행 | 없음 — 정적 Markdown |
| 진입점 | `README.md` |
| 외부 위젯 | shields.io, github-readme-stats.vercel.app |
| 유지보수 | 활성 (수동 동기화) |
| 라이선스 | 저장소 `LICENSE` 참조 |

## 운영 흐름

1. `README.md` 편집 → 커밋 → `main` 푸시
2. GitHub가 프로필 페이지에 자동 렌더링
3. 통계 카드는 `github-readme-stats.vercel.app`에서 주기적 갱신
4. 새 프로젝트는 `주요 프로젝트` 표에 행 추가
5. 다음 운영 액션: 변경 후 푸시하여 프로필 반영 확인

## 목차 / Contents

- [패키지 구성](#패키지-구성--package-contents)
- [상태](#상태--status)
- [첫 번째로 읽을 파일](#첫-번째로-읽을-파일--first-files-to-read)
- [진입점](#진입점--entry-points)
- [빠른 시작](#빠른-시작--quickstart)
- [기술 스택](#기술-스택--tech-stack)
- [주요 프로젝트](#주요-프로젝트--featured-projects)
- [활동](#활동--activity)
- [기여](#기여--contributing)
- [유지보수자](#유지보수자--maintainer)
- [라이선스](#라이선스--license)

## 패키지 구성 / Package contents

| 경로 | 설명 |
|------|------|
| [`README.md`](README.md) | 프로필 페이지를 렌더링하는 유일한 진입점 |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | 이슈·PR 작성 가이드 |
| [`LICENSE`](LICENSE) | 라이선스 전문 |

## 상태 / Status

| 항목 | 값 |
|------|-----|
| 프로덕션 준비 | 정적 페이지 — 즉시 사용 가능 |
| 자동화 | 없음 (GitHub Actions 미사용) |
| 의존성 | shields.io 배지, github-readme-stats 위젯 |
| 폐기 여부 | 활성 유지 |
| 보조 문서 | `CONTRIBUTING.md` |

## 첫 번째로 읽을 파일 / First files to read

| 순서 | 파일 | 목적 |
|------|------|------|
| 1 | [`README.md`](README.md) | 프로필 카드, 기술 스택, 프로젝트 링크 |
| 2 | [`CONTRIBUTING.md`](CONTRIBUTING.md) | 외부 기여 절차 |
| 3 | [`LICENSE`](LICENSE) | 사용·재배포 조건 |

## 진입점 / Entry points

| 진입점 | 용도 |
|--------|------|
| [`README.md`](README.md) | GitHub 프로필 페이지의 유일한 렌더링 진입점 |
| shields.io 배지 | 기술 스택 시각화 |
| github-readme-stats 카드 | 활동 통계 시각화 |

## 빠른 시작 / Quickstart

이 레포는 코드가 없는 프로필 레포지토리입니다. 별도 설치 없이 GitHub 프로필 페이지에서 바로 렌더링됩니다.

```bash
# 로컬에서 확인하려면 클론
git clone https://github.com/jclee941/jclee-bot
cd jclee941
```

프로필을 수정하려면 [`README.md`](README.md)를 편집해 커밋·푸시합니다. 변경 사항은 GitHub 프로필 페이지에 자동으로 반영됩니다. 새 프로젝트는 `주요 프로젝트` 표에 행을 추가하세요.

## 기술 스택 / Tech stack

| 분야 | 도구 |
|------|------|
| 언어 | Python, Go, TypeScript |
| 인프라 | Terraform, Proxmox, Docker |
| 보안 | Splunk, FortiGate |
| 웹 | Cloudflare Workers, Hono, D1 |
| 자동화 | PR-Agent (fork), n8n, FastAPI |
| ML / 자율주행 | Formula Student Driverless |

## 주요 프로젝트 / Featured projects

| 레포 | 설명 |
|------|------|
| [terraform](https://github.com/jclee941/terraform) | Proxmox 홈랩 IaC 모노레포 |
| [splunk](https://github.com/jclee941/splunk) | FortiGate SIEM 보안 모니터링 앱 |
| [safetywallet](https://github.com/jclee941/safetywallet) | 현장 작업자 안전 PWA (Cloudflare Workers) |
| [.github](https://github.com/jclee941/jclee-bot) | 16개 레포 GitOps 자동화 |

## 활동 / Activity

| 카드 | 소스 | 비고 |
|------|------|------|
| GitHub Stats | github-readme-stats.vercel.app | 서드파티, 일시 지연 가능 |
| Top Languages | github-readme-stats.vercel.app | 서드파티, 일시 지연 가능 |

```html
<!-- 아래 위젯은 서드파티 서비스를 통해 렌더링됩니다. -->
<img height="160" src="https://github-readme-stats.vercel.app/api?username=jclee941&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jclee941&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
```

## 기여 / Contributing

이 레포는 개인 프로필을 위한 저장소로, 외부 코드 기여를 받지 않습니다. 오타 수정이나 깨진 링크는 이슈로 제보해 주세요. 절차는 [`CONTRIBUTING.md`](CONTRIBUTING.md)를 참조하세요.

## 유지보수자 / Maintainer

| 역할 | 연락처 |
|------|--------|
| Owner | 이재철 (JAECHEOL LEE) |
| GitHub | <https://github.com/jclee941> |

도움이 필요하면 GitHub 이슈를 개설하세요.

## 라이선스 / License

본 레포의 사용·재배포 조건은 [`LICENSE`](LICENSE) 파일을 참조하세요.