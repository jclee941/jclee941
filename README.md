# <Repository Name>

[![License](LICENSE)](LICENSE)
[![Contributing](CONTRIBUTING.md)](CONTRIBUTING.md)
[![Status: Draft](https://img.shields.io/badge/status-draft-lightgrey)](#status)

> 한국어 우선 안내: 이 저장소는 현재 표준 협업 문서(`CONTRIBUTING.md`, `LICENSE`, `README.md`)만 포함하는 최소 골격(minimal skeleton) 상태입니다. 본 README는 향후 제품 본체가 추가될 때를 위한 이중 언어 안내문으로, 운영·개발자가 빠르게 상태를 확인하고 다음 행동을 정할 수 있도록 설계되었습니다.

> English summary: This repository currently ships only the standard community files (`CONTRIBUTING.md`, `LICENSE`, `README.md`). This bilingual README acts as the landing page that describes ownership, current state, and the next operator action until the product source lands.

## Status

| 항목 / Item | 값 / Value |
| --- | --- |
| 제품 본체 / Product source | 미포함 (소스 트리 비어 있음) / Not yet present |
| 문서 / Documentation | `CONTRIBUTING.md`, `LICENSE`, `README.md` 만 존재 / Only community docs |
| 배포 산출물 / Release artifacts | 없음 / None |
| 안정성 단계 / Stability tier | Draft (1.x 이전) / Pre-1.0 draft |
| 라이선스 / License | `LICENSE` 파일 참조 / See `LICENSE` |
| 보조 채널 / Support channel | 저장소 이슈 트래커 / Repository issues |

## 운영 요약 / Operator Flow

1. 저장소 클론 후 `README.md` → `CONTRIBUTING.md` → `LICENSE` 순으로 정독.
2. 제품 본체 디렉터리가 추가되면 본 README의 “구성 요소 / Package Contents” 표를 갱신.
3. 변경 요청은 `CONTRIBUTING.md`의 절차에 따라 PR로 제출.

## Table of Contents

- [Purpose / 목적](#purpose--목적)
- [Package Contents / 구성 요소](#package-contents--구성-요소)
- [First Files to Read / 처음 읽을 파일](#first-files-to-read--처음-읽을-파일)
- [Quickstart / 빠른 시작](#quickstart--빠른-시작)
- [Maintainers / 유지보수](#maintainers--유지보수)
- [Further Documentation / 추가 문서](#further-documentation--추가-문서)
- [Contributing / 기여](#contributing--기여)
- [License / 라이선스](#license--라이선스)

## Purpose / 목적

**한국어:** 이 저장소는 협업 표준 문서만을 보관하는 골격 저장소입니다. 향후 애플리케이션, 라이브러리, 도구, 또는 문서 본체가 추가될 때의 기준점 역할을 하며, 기여 절차와 라이선스 조건을 명확히 제시합니다. 현재 시점에서는 “비어 있는” 상태를 정직하게 알리고, 다음 행동을 안내하는 것이 1차 목적입니다.

**English:** This repository is a skeleton that holds only the standard collaboration documents. It serves as the baseline for an upcoming application, library, tool, or documentation body, and pins down contribution rules and license terms up front. For now, its primary purpose is to disclose the empty state honestly and to point operators to their next action.

## Package Contents / 구성 요소

| 경로 / Path | 유형 / Type | 역할 / Role |
| --- | --- | --- |
| `README.md` | 문서 / Doc | 이중 언어 진입 페이지 / Bilingual landing page |
| `CONTRIBUTING.md` | 문서 / Doc | 기여 절차·코딩 규약·PR 정책 / Contribution guide |
| `LICENSE` | 문서 / Doc | 사용·배포 조건 / Usage & redistribution terms |
| (예정 / Pending) | 코드·자산 / Code or assets | 제품 본체, 향후 추가 / Product body, added later |

## First Files to Read / 처음 읽을 파일

1. `README.md` (본 파일 / this file) — 저장소의 위치와 다음 행동 안내.
2. `CONTRIBUTING.md` — PR 정책, 리뷰 절차, 커밋 규약.
3. `LICENSE` — 사용·배포·재라이선싱 조건.

## Quickstart / 빠른 시작

```bash
# 저장소 클론 / Clone
git clone <repository-url>
cd <repository-directory>

# 현재 포함된 문서 확인 / Inspect current contents
ls -la
# 출력 기대값: CONTRIBUTING.md, LICENSE, README.md, .git/
```

**다음 단계 / Next step:** 제품 본체가 추가되면 본 README의 구성 요소 표와 본 절을 갱신하고, 빌드·실행 명령을 함께 기록합니다.

## Maintainers / 유지보수

| 역할 / Role | 책임 / Responsibility |
| --- | --- |
| 저장소 소유자 / Repository owner | 승인·릴리스 권한 / Approvals & release authority |
| 메인테이너 / Maintainers | PR 리뷰, 이슈 트리아지 / PR review & issue triage |
| 컨택 / Contact | 저장소 `CODEOWNERS` 또는 이슈 트래커 / `CODEOWNERS` or issues |

**English:** Maintenance duties and on-call expectations live in `CONTRIBUTING.md` once the project adds a governance section. In the meantime, use the repository issue tracker.

## Further Documentation / 추가 문서

- 협업 절차 / Contribution workflow — `CONTRIBUTING.md`
- 법적 조건 / Legal terms — `LICENSE`
- 외부 참고 / External references — 추후 `docs/` 또는 위키에 추가 예정 / To be added under `docs/` or wiki later

## Contributing / 기여

PR을 보내기 전에 `CONTRIBUTING.md`를 반드시 읽어 주세요. 표준 절차·리뷰 SLA·커밋 메시지 규약이 정리되어 있습니다.

Please read `CONTRIBUTING.md` before opening a pull request. It documents the standard flow, review SLA, and commit message conventions.

## License / 라이선스

본 저장소는 `LICENSE` 파일에 명시된 조건 하에 배포됩니다. 라이선스 전문을 확인한 후 사용해 주세요.

This repository is distributed under the terms stated in the `LICENSE` file. Review the full text before use.