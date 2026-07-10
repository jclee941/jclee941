# <Project Name>

[![Status: Bootstrap](https://img.shields.io/badge/status-bootstrap-yellow)](#quick-glance-status)
[![License](https://img.shields.io/badge/license-see%20LICENSE-blue)](./LICENSE)
[![Contributors](https://img.shields.io/badge/contributions-welcome-brightgreen)](./CONTRIBUTING.md)

## 요약

이 저장소는 **LICENSE**, **CONTRIBUTING.md**, 그리고 본 **README.md** 로만 구성된 문서 우선 단계의 저장소입니다.  
아직 소스 코드, 진입점, 패키지 레이아웃이 정의되지 않았으므로, 첫 번째 PR 이전에 프로젝트의 목적과 핵심 산출물을 README와 함께 정리해야 합니다.

> Korean-first overview. English summary follows below.

This repository currently ships only the bootstrap documentation: a license file, a contribution guide, and this README. The product surface, entry points, and packaging are not yet defined and need to be authored alongside the first code drop.

---

## Quick-Glance Status

| 항목 | 값 | 비고 |
| --- | --- | --- |
| 저장소 상태 | Bootstrap | 소스/제품 미정 |
| 라이선스 | [LICENSE](./LICENSE) | 저장소 최상위에 위치 |
| 기여 가이드 | [CONTRIBUTING.md](./CONTRIBUTING.md) | 첫 PR 전 필독 |
| 코드 진입점 | 없음 | 정의 필요 |
| 빌드 명령 | 없음 | 정의 필요 |
| 테스트 명령 | 없음 | 정의 필요 |
| 유지보수자 | 미지정 | 아래 "Maintainers" 참고 |

## 빠른 흐름 (Operator Flow)

1. 저장소를 클론합니다 (`git clone <repository-url>`).
2. [CONTRIBUTING.md](./CONTRIBUTING.md) 의 절차와 정책을 확인합니다.
3. [LICENSE](./LICENSE) 의 조건을 검토합니다.
4. 본 README 의 "Purpose" 와 "First Files to Read" 를 함께 갱신합니다.

English flow mirrors the steps above; see [Quickstart](#quickstart--usage) for the detailed walkthrough.

---

## 목차 (Table of Contents)

- [Purpose](#purpose)
- [Package Contents](#package-contents)
- [Status](#status)
- [First Files to Read](#first-files-to-read)
- [API or Entry Points](#api-or-entry-points)
- [Quickstart / Usage](#quickstart--usage)
- [Configuration](#configuration)
- [Commands Reference](#commands-reference)
- [Local Development](#local-development)
- [Testing](#testing)
- [Contribution Guide](#contribution-guide)
- [Maintainers / Points of Contact](#maintainers--points-of-contact)
- [Further Documentation](#further-documentation)
- [License](#license)

---

## Purpose

이 저장소가 **무엇을 하는지**, **왜 유용한지**, 그리고 **누가 사용하는지** 를 명시하는 섹션입니다.  
현재는 부트스트랩 단계이므로, 아래 항목을 채워 넣어 주십시오.

- **문제 정의 (Problem)**: 이 저장소가 해결하려는 문제를 한두 문장으로 기술합니다.
- **대상 사용자 (Audience)**: 라이브러리 사용자, CLI 호출자, 서비스 운영자 등.
- **주요 가치 (Value)**: 기존 대안 대비 어떤 이점을 제공하는지.

> English: state the problem, audience, and unique value in two to three short lines.

## Package Contents

현 저장소 최상위 레이아웃은 다음과 같습니다.

| 경로 | 종류 | 역할 |
| --- | --- | --- |
| `README.md` | 문서 | 저장소 개요 및 운영 가이드 |
| `CONTRIBUTING.md` | 문서 | 기여 절차, PR 규칙, 리뷰 정책 |
| `LICENSE` | 법적 문서 | 사용·배포·수정 조건 |

향후 `src/`, `apps/`, `packages/`, `docs/` 같은 하위 디렉터리가 추가되면 본 표를 갱신합니다.

## Status

- **상태**: Bootstrap (코드/제품 미정).
- **안정성**: 본 README 의 다른 주장을 신뢰하지 마십시오. 첫 릴리스 태그 이전까지 모든 항목은 초안입니다.
- **지원 채널**: "Maintainers" 섹션 참고.

## First Files to Read

운영자/기여자가 가장 먼저 열어야 할 문서와 그 순서입니다.

1. [LICENSE](./LICENSE) — 사용·배포 조건.
2. [CONTRIBUTING.md](./CONTRIBUTING.md) — PR, 커밋, 리뷰 절차.
3. 본 README 의 [Purpose](#purpose) 와 [Quickstart](#quickstart--usage) — 프로젝트 목적과 실행 방법.

## API or Entry Points

현재 정의된 진입점은 없습니다. 제품이 결정되면 다음 표를 채웁니다.

| 진입점 종류 | 경로/심볼 | 사용 맥락 | 비고 |
| --- | --- | --- | --- |
| CLI | `bin/<tool>` | 셸에서 직접 실행 | 미정의 |
| 라이브러리 | `import <pkg>` | 다른 코드에서 호출 | 미정의 |
| HTTP | `GET <endpoint>` | 서비스 운영 | 미정의 |
| 설정 파일 | `<config-path>` | 부트스트랩/런타임 | 미정의 |

## Quickstart / Usage

부트스트랩 단계이므로, 아래 절차는 향후 정형화될 패턴입니다.

### 1. 사전 요구사항

- Git (최신 안정 버전)
- 프로젝트가 채택할 언어 런타임 (예: Node.js, Python, Go 등 — 결정 후 기재)

### 2. 클론

```bash
git clone <repository-url>
cd <repository-directory>
```

### 3. 기여 절차 진입

1. [CONTRIBUTING.md](./CONTRIBUTING.md) 를 읽고 절차와 코딩 규칙을 확인합니다.
2. 이슈 또는 작업 항목을 등록한 뒤 브랜치를 생성합니다.
3. 변경 후 PR 을 열고 체크리스트를 통과합니다.

English equivalent: clone, read CONTRIBUTING, open an issue, branch, and submit a PR per the contribution guide.

## Configuration

현재 외부 설정 파일, 환경 변수, 플래그가 정의되어 있지 않습니다.  
향후 도입 시 다음 표를 사용합니다.

| 키 | 기본값 | 필수 여부 | 설명 |
| --- | --- | --- | --- |
| `<KEY>` | `<default>` | 예/아니오 | 효과/용도 |

## Commands Reference

명령이 정의되어 있지 않습니다. 향후 추가 시 다음 표를 갱신합니다.

| 명령 | 용도 | 예시 |
| --- | --- | --- |
| `build` | 산출물 생성 | `pnpm build` 등 |
| `test` | 테스트 실행 | `pnpm test` 등 |
| `lint` | 정적 분석 | `pnpm lint` 등 |
| `format` | 포맷 적용 | `pnpm format` 등 |

## Local Development

로컬 개발 환경은 프로젝트가 정해지는 대로 다음 순서로 확장합니다.

- 의존성 설치 명령 (예: `npm install`, `pip install -r requirements.txt`).
- 환경 변수 템플릿(`.env.example`) 제공.
- 사전 커밋 훅(`pre-commit`, `lefthook` 등) 정의.
- IDE 권장 설정 (`.editorconfig`, `.vscode/settings.json`).

## Testing

테스트 전략은 제품이 정해진 뒤 결정합니다. 일반적으로 다음 항목을 채웁니다.

- 단위 테스트 프레임워크와 실행 명령.
- 통합/E2E 테스트 도구와 실행 명령.
- 커버리지 목표치와 산출 위치(`coverage/` 등).
- CI 의 테스트 트리거 조건.

## Contribution Guide

모든 기여 절차, PR 규칙, 리뷰 SLA, 코딩 스타일은 [CONTRIBUTING.md](./CONTRIBUTING.md) 에서 관리합니다.  
본 README 는 기여 절차의 요약만 다루며, 충돌 시 CONTRIBUTING.md 가 우선합니다.

### 요약 체크리스트

- [ ] 이슈를 먼저 등록하거나 연결했습니다.
- [ ] 브랜치 명명 규칙을 따랐습니다.
- [ ] 로컬에서 빌드/테스트를 통과했습니다.
- [ ] PR 본문에 변경 요약과 테스트 방법을 기재했습니다.
- [ ] 리뷰어 지정 및 라벨 부착을 완료했습니다.

## Maintainers / Points of Contact

현 저장소에는 공식 유지보수자가 지정되어 있지 않습니다. 첫 번째 메인테이너가 합류하면 본 섹션을 다음 표 형식으로 갱신합니다.

| 역할 | 책임 | 연락 채널 | 응답 SLA |
| --- | --- | --- | --- |
| Owner | 릴리스/로드맵 | <이메일 또는 핸들> | 미정 |
| Maintainer | 코드 리뷰 | <이메일 또는 핸들> | 미정 |
| Triage | 이슈 분류 | <이메일 또는 핸들> | 미정 |

도움을 받을 수 있는 채널 (예: 이슈 트래커, 디스코드, 메일링 리스트) 도 본 섹션에 함께 기재합니다.

## Further Documentation

부가 문서 디렉터리(`docs/`) 가 아직 존재하지 않습니다. 향후 다음 문서를 분리 보관할 수 있습니다.

- 아키텍처 개요 (`docs/architecture.md`).
- 운영 런북 (`docs/runbook.md`).
- 보안 정책 (`SECURITY.md`).
- 변경 이력 (`CHANGELOG.md`).

추가 시 본 README 의 "First Files to Read" 에서 우선순위를 다시 정합니다.

## License

본 저장소는 [LICENSE](./LICENSE) 의 조건에 따라 배포됩니다.  
LICENSE 파일이 명시한 범위와 예외 조항을 PR, 배포, 2차 저작 전에 반드시 검토하십시오.