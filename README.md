# 이재철 · JAECHEOL LEE

> 인프라 & 보안 엔지니어 · 홈랩 GitOps 운영자
> Infrastructure & Security Engineer · Homelab GitOps Operator

[![GitHub](https://img.shields.io/badge/GitHub-jclee941-181717?style=flat-square&logo=github)](https://github.com/jclee941)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)
[![Profile README](https://img.shields.io/badge/type-profile--README-blueviolet?style=flat-square)](README.md)

## 한국어 요약

9년차 인프라·보안 엔지니어입니다. Proxmox 홈랩을 Terraform으로 IaC화하고 FortiGate 로그를 Splunk로 수집·분석합니다. 16개의 GitHub 레포지토리를 단일 `.github` 레포에서 GitOps로 관리하며, Cloudflare Workers 기반 PWA와 Formula Student Driverless 자율주행 프로젝트도 함께 진행합니다.

## English summary

Infrastructure & security engineer with nine years of experience. Operates a Proxmox homelab as IaC with Terraform, ships FortiGate logs into Splunk for detection and analysis, and manages sixteen GitHub repositories through a single `.github` repo driven by GitOps. Also builds Cloudflare Workers PWAs and contributes to a Formula Student Driverless autonomous-driving project.

## 빠른 상태 / Quick glance

| 항목 | 값 |
|------|-----|
| 저장소 종류 | GitHub 프로필 레포지토리 (단일 README) |
| 코드 실행 | 없음 — 정적 Markdown |
| 진입점 | [`README.md`](README.md) |
| 보조 문서 | [`CONTRIBUTING.md`](CONTRIBUTING.md) |
| 라이선스 | [`LICENSE`](LICENSE) (MIT) |
| 외부 위젯 | shields.io, github-readme-stats |
| 자동화 | 없음 (GitHub Actions 미사용) |
| 상태 | 활성 유지 |

## 운영 흐름 / Operator flow

1. [`README.md`](README.md) 편집 후 커밋 → `main` 푸시
2. GitHub가 프로필 페이지에 자동 렌더링
3. shields.io 배지와 github-readme-stats 카드가 외부에서 주기적 갱신
4. 새 프로젝트는 `주요 프로젝트` 표에 행 추가
5. 다음 액션: 변경 후 `git push`하여 프로필 반영 확인

## 목차 / Contents

- [패키지 구성 / Package contents](#패키지-구성--package-contents)
- [상태 / Status](#상태--status)
- [첫 번째로 읽을 파일 / First files to read](#첫-번째로-읽을-파일--first-files-to-read)
- [진입점 / Entry points](#진입점--entry-points)
- [빠른 시작 / Quickstart](#빠른-시작--quickstart)
- [기술 스택 / Tech stack](#기술-스택--tech-stack)
- [주요 프로젝트 / Featured projects](#주요-프로젝트--featured-projects)
- [활동 지표 / Activity](#활동-지표--activity)
- [기여 안내 / Contributing](#기여-안내--contributing)
- [유지보수자 / Maintainer](#유지보수자--maintainer)
- [라이선스 / License](#라이선스--license)
- [추가 문서 / Further documentation](#추가-문서--further-documentation)

## 패키지 구성 / Package contents

| 경로 | 종류 | 설명 |
|------|------|------|
| [`README.md`](README.md) | Markdown | 프로필 페이지를 렌더링하는 유일한 진입점 |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Markdown | 이슈·PR 작성 가이드 |
| [`LICENSE`](LICENSE) | Text | 라이선스 전문 (MIT) |

## 상태 / Status

| 항목 | 값 |
|------|-----|
| 프로덕션 준비 | 정적 페이지 — 즉시 사용 가능 |
| 자동화 | 없음 (GitHub Actions 미사용) |
| 외부 의존성 | shields.io 배지, github-readme-stats 위젯 |
| 폐기 여부 | 활성 유지 |
| 동기화 방식 | 수동 (git push) |

## 첫 번째로 읽을 파일 / First files to read

| 순서 | 파일 | 목적 |
|------|------|------|
| 1 | [`README.md`](README.md) | 프로필 카드, 기술 스택, 프로젝트 링크 |
| 2 | [`CONTRIBUTING.md`](CONTRIBUTING.md) | 협업 규약 및 PR 가이드 |
| 3 | [`LICENSE`](LICENSE) | 라이선스 조건 확인 |

## 진입점 / Entry points

| 진입점 | 위치 | 용도 |
|--------|------|------|
| 프로필 렌더링 | [`README.md`](README.md) | GitHub `https://github.com/jclee941` 페이지 출력 |
| 협업 규약 | [`CONTRIBUTING.md`](CONTRIBUTING.md) | 이슈/PR 작성 절차 |
| 라이선스 | [`LICENSE`](LICENSE) | MIT 조건 확인 |

## 빠른 시작 / Quickstart

| 단계 | 명령 | 설명 |
|------|------|------|
| 1 | 저장소 클론 | `git clone https://github.com/jclee941/jclee-bot` |
| 2 | README 수정 | [`README.md`](README.md) 편집기로 열기 |
| 3 | 변경 적용 | 편집 후 `git add README.md` |
| 4 | 커밋 | `git commit -m "Update profile"` |
| 5 | 푸시 | `git push origin main` |
| 6 | 확인 | `https://github.com/jclee941` 프로필 페이지 새로고침 |

> 별도의 빌드 단계나 런타임 의존성이 없습니다. 정적 Markdown만 푸시하면 GitHub가 즉시 렌더링합니다.

## 기술 스택 / Tech stack

| 분류 | 사용 도구 |
|------|-----------|
| 가상화 / 클라우드 | Proxmox VE, Terraform |
| 네트워크 보안 | FortiGate, 방화벽 정책, VPN |
| 관측 가능성 | Splunk, 로그 파이프라인 |
| 엣지 / 웹 | Cloudflare Workers, PWA |
| 운영 방식 | GitOps, `.github` 중앙 레포 관리 |
| 기타 | Formula Student Driverless (자율주행) |

## 주요 프로젝트 / Featured projects

| 프로젝트 | 분야 | 설명 |
|----------|------|------|
| 홈랩 IaC | 인프라 | Proxmox 홈랩을 Terraform으로 코드화 |
| FortiGate → Splunk | 보안 | FortiGate 로그 수집·상관분석 파이프라인 |
| Cloudflare Workers PWA | 웹 | Workers 기반 정적 PWA |
| Formula Student Driverless | 자율주행 | Perception·Planning 스택 협업 |
| `.github` GitOps | 운영 | 16개 레포를 단일 레포에서 정책·Actions로 통합 관리 |

## 활동 지표 / Activity

| 위젯 | 소스 | 갱신 주기 |
|------|------|-----------|
| GitHub 통계 카드 | github-readme-stats | 일·주 단위 (외부 서비스) |
| shields.io 배지 | shields.io | 실시간 |
| 프로필 README | 본 저장소 | 푸시 시 즉시 |

> 통계 카드의 정확한 수치는 외부 위젯 서비스에서 결정됩니다. 본 레포에는 카드를 캐시하지 않습니다.

## 기여 안내 / Contributing

이 저장소는 개인 프로필을 위한 단일 README 레포입니다. 일반적인 협업 대상은 아니지만, 오탈자·링크 수정 제안은 환영합니다.

| 단계 | 안내 |
|------|------|
| 1 | [`CONTRIBUTING.md`](CONTRIBUTING.md) 숙지 |
| 2 | Issue 생성 또는 Fork 후 PR 제출 |
| 3 | 변경 근거를 PR 본문에 명시 |

PR 자동화나 봇 운영 정책은 본 레포에 존재하지 않습니다.

## 유지보수자 / Maintainer

| 항목 | 값 |
|------|-----|
| 이름 | 이재철 / JAECHEOL LEE |
| 역할 | 인프라·보안 엔지니어, 홈랩 GitOps 운영자 |
| GitHub | https://github.com/jclee941 |
| 문의 채널 | GitHub Issues 또는 Discussions |

## 라이선스 / License

본 저장소는 [`LICENSE`](LICENSE) 파일의 조건에 따라 배포됩니다. 별도 표기가 없는 한 MIT 라이선스가 적용됩니다.

| 항목 | 값 |
|------|-----|
| 라이선스 종류 | MIT |
| 적용 범위 | 본 저장소 내 모든 파일 |
| 외부 자산 | shields.io, github-readme-stats는 각 서비스의 약관을 따름 |

## 추가 문서 / Further documentation

| 문서 | 용도 |
|------|------|
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | 협업 절차 및 PR 규약 |
| [`LICENSE`](LICENSE) | 라이선스 전문 |
| GitHub 프로필 페이지 | https://github.com/jclee941 |

> 운영·보안 정책, 아키텍처 다이어그램, 모듈별 상세 문서는 본 프로필 레포에서 관리하지 않습니다. 해당 내용은 각 프로젝트 레포의 README와 위키에서 제공됩니다.