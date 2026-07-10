# Repository Entry Guide / 저장소 진입 안내

## 한 줄 요약

`CONTRIBUTING.md`와 `LICENSE`만 포함된 최소 골격 저장소입니다. 애플리케이션·라이브러리·도구의 본체는 아직 커밋되지 않았으며, 본 README는 향후 소스가 채워질 때까지의 진입 안내문으로 작동합니다.

## One-line Summary

A minimal skeleton repository containing only `CONTRIBUTING.md` and `LICENSE`. The application, library, or tool body has not been committed yet; this README acts as an entry guide until source content is added.

## 상태 / Status

| 구성 요소 / Component | 상태 / Status |
| --- | --- |
| `README.md` | 포함 / Included |
| `CONTRIBUTING.md` | 포함 / Included |
| `LICENSE` | 포함 / Included |
| 소스 코드 / Source code | 미포함 / Not included |
| 빌드 구성 / Build config | 없음 / None |
| 테스트 / Test suite | 없음 / None |
| 릴리스 / Release | 없음 / None |
| 지속 통합 / CI | 없음 / None |

## 운영 흐름 / Operator Flow

1. `README.md`로 저장소 의도를 파악합니다. / Read `README.md` first.
2. `CONTRIBUTING.md`에서 기여 절차와 규약을 확인합니다. / Review rules in `CONTRIBUTING.md`.
3. `LICENSE`의 사용·배포 조건을 확인합니다. / Check terms in `LICENSE`.
4. 변경 후 표준 절차로 PR을 제출합니다. / Submit a PR per the standard process.

---

## 목차 / Table of Contents

1. 목적 / Purpose
2. 패키지 구성 / Package Contents
3. 처음 읽을 파일 / First Files to Read
4. 진입점 / Entry Points
5. 빠른 시작 / Quickstart
6. 구성 / Configuration
7. 명령어 / Commands
8. 로컬 개발 / Local Development
9. 테스트 / Testing
10. 기여 / Contributing
11. 유지보수 / Maintainers
12. 추가 문서 / Further Documentation
13. 라이선스 / License

---

## 1. 목적 / Purpose

이 저장소는 메타 파일만으로 구성된 초기 단계 골격입니다. 핵심 본체(소스·빌드·테스트)는 아직 없으며, 본 문서는 본체가 추가되기 전의 자리표시이자 안내문입니다.

*This repository is an early-stage skeleton of meta files only. The core body (source, build, tests) is not yet present, and this document serves as a placeholder and guide.*

## 2. 패키지 구성 / Package Contents

| 경로 / Path | 종류 / Type | 역할 / Role |
| --- | --- | --- |
| `README.md` | 문서 / Doc | 저장소 진입 안내 / Entry guide |
| `CONTRIBUTING.md` | 정책 / Policy | 기여 절차 및 규약 / Contribution rules |
| `LICENSE` | 라이선스 / License | 사용·배포 조건 / Terms |

## 3. 처음 읽을 파일 / First Files to Read

| 순서 / Order | 파일 / File | 권장 이유 / Why read first |
| --- | --- | --- |
| 1 | `README.md` | 저장소 개요 / Repository overview |
| 2 | `CONTRIBUTING.md` | PR 절차·코딩 규약 / PR and coding policy |
| 3 | `LICENSE` | 법적 사용 범위 / Legal scope |

## 4. 진입점 / Entry Points

현재 소스 진입점은 존재하지 않습니다. 향후 본체가 추가될 경우 다음 위치 중 하나가 표준 진입점이 되는 것이 일반적입니다.

*No source entry point exists yet. The following are common conventions for the eventual entry:*

| 후보 / Candidate | 일반 용도 / Typical role |
| --- | --- |
| `src/index.*` | 라이브러리 진입 / Library entry |
| `cmd/<name>/main.*` | CLI 진입 / CLI entry |
| `app.*` / `server.*` | 서비스 진입 / Service entry |
| `bin/<name>` | 실행 스크립트 / Executable script |

## 5. 빠른 시작 / Quickstart

1. 저장소를 클론합니다.
   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```
2. `CONTRIBUTING.md`와 `LICENSE`를 읽습니다.
3. 변경 사항을 작업 브랜치에서 만들고 표준 절차로 PR을 엽니다.

소스가 추가되기 전까지 별도의 빌드·실행 단계는 없습니다.

*No build or run step exists until source is added.*

## 6. 구성 / Configuration

구성 파일이 없습니다. 향후 다음 위치 중 하나에 추가될 수 있습니다.

*No configuration file is present. Common locations once added:*

- `config/`, `.env.example`, `settings.yaml`
- 언어별 매니페스트(`pyproject.toml`, `package.json`, `Cargo.toml`, `go.mod`, …)

## 7. 명령어 / Commands

명령어 카탈로그는 본체가 추가된 뒤 작성됩니다. 그때까지 빌드·테스트·실행 명령은 없습니다.

*The command catalog will be written once the body lands. No build/test/run commands exist today.*

## 8. 로컬 개발 / Local Development

| 단계 / Step | 안내 / Guidance |
| --- | --- |
| 브랜치 생성 / Branch | 작업별로 새 브랜치를 사용 / Use one branch per change |
| 규약 / Conventions | `CONTRIBUTING.md` 우선 / Follow `CONTRIBUTING.md` |
| 커밋 / Commit | 메시지 정책은 `CONTRIBUTING.md` 참조 / See `CONTRIBUTING.md` |
| PR 제출 / PR | 저장소 표준 절차 사용 / Use repository standard process |

## 9. 테스트 / Testing

테스트 코드는 아직 없습니다. 추가 시 다음 명령이 일반적입니다.

*No tests exist yet. Common runners once added:*

| 스택 / Stack | 일반 명령 / Common command |
| --- | --- |
| Python | `pytest` |
| Node.js | `npm test` |
| Go | `go test ./...` |
| Rust | `cargo test` |

## 10. 기여 / Contributing

본 README는 `CONTRIBUTING.md`의 내용을 중복 기술하지 않습니다. 모든 정책의 원본은 `CONTRIBUTING.md`입니다.

*This README does not duplicate `CONTRIBUTING.md`. All policy originates there.*

## 11. 유지보수 / Maintainers

저장소 메타 파일에 별도의 유지보수자 명단이 없습니다. 책임 주체를 확인하려면 저장소 설정의 Code owners / Teams를 참조하거나 이슈 트래커에서 메인테이너를 태그하십시오.

*No maintainer roster is in this tree. Check the repository Code owners / Teams settings, or tag a maintainer via the issue tracker.*

## 12. 추가 문서 / Further Documentation

| 위치 / Location | 내용 / Content |
| --- | --- |
| `CONTRIBUTING.md` | 기여 절차 / Contribution procedure |
| `LICENSE` | 라이선스 본문 / License text |

새 문서가 추가되면 본 섹션에 저장소 상대 경로로 등재합니다.

*New documents will be listed here with repository-relative paths once added.*

## 13. 라이선스 / License

본 저장소는 `LICENSE` 파일에 명시된 조건 하에 배포됩니다.

*Distributed under the terms stated in `LICENSE`.*