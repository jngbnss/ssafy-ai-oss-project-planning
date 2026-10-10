# SSAFY 3차 AI·OSS 프로젝트 설계 보고서

SSAFY 3차 프로젝트의 주제를 선정하기 위해 AI 역량, 오픈소스 활용, 구현 가능성, 시연 경쟁력을 기준으로 프로젝트 후보를 비교한 저장소입니다.

주제는 아직 확정되지 않았습니다. 점수는 정답이 아니라 팀 토론을 돕기 위한 가중 평가 초안입니다.

## 발표 장표 실행

저장소를 클론한 뒤 루트의 [`index.html`](./index.html)을 Chrome 또는 Edge로 열면 됩니다. 별도 설치나 빌드 과정은 없습니다.

```bash
git clone https://github.com/jngbnss/ssafy-ai-oss-project-planning.git
cd ssafy-ai-oss-project-planning
```

발표 화면 조작:

- 방향키, `Page Up`, `Page Down`, `Space`: 장표 이동
- `F`: 전체 화면
- 4번 장표의 프로젝트 카드: 마우스를 올리면 SWOT 표시
- 프로젝트별 `데모 실행`: P1~P7은 내장된 프론트엔드 데모, P8은 배포된 레이싱 게임 실행
- 마지막 장표: 팀 회의 안건 확인

## 현재 프로젝트 후보

| ID | 프로젝트 | 저장소 | 가중 총점 |
|---|---|---|---:|
| P1 | 세계여행 영어회화 + AI 동반자 | [scene-speak-ai](https://github.com/jngbnss/scene-speak-ai) | 477 |
| P2 | AI 추리 수사 + 방탈출 | [caseforge-ai](https://github.com/jngbnss/caseforge-ai) | 502 |
| P3 | AI 문학 세계 탐험 | [litverse-ai](https://github.com/jngbnss/litverse-ai) | 421 |
| P4 | 제스처 홀로그램 + AI 공학 연구실 | [holoforge-ai-lab](https://github.com/jngbnss/holoforge-ai-lab) | 473 |
| P5 | AI 2D→3D 인터랙티브 월드 | [draw2world-ai](https://github.com/jngbnss/draw2world-ai) | 448 |
| P6 | AI 쥬라기 생태계 | [paleosphere-ai](https://github.com/jngbnss/paleosphere-ai) | 460 |
| P7 | AI 디지털 트윈 + 조종 시뮬레이터 | [twinpilot-ai](https://github.com/jngbnss/twinpilot-ai) | 472 |
| P8 | AI 레이싱 게임 + 주행 에이전트 | [f1](https://github.com/jngbnss/f1) · [실행](https://jngbnss.github.io/f1/) | 408 |

## 문서

- [현재 프로젝트 개요](./docs/project-overview.md)
- [평가 기준과 가중치](./docs/evaluation-framework.md)
- [작업 및 결정 기록](./docs/work-log.md)
- [팀 회의 안건](./docs/meeting-agenda.md)
- [최초 기획 컨텍스트](./docs/archive/PROJECT_CONTEXT-original.md)

## 핵심 원칙

AI 모델을 직접 학습하는 것만 AI 역량은 아닙니다. 문제에 맞는 모델을 비교·선택하고, 검색·프롬프트·추론·도구 연결을 개선하며, 같은 조건에서 결과를 측정하는 과정도 AI 엔지니어링 역량입니다.

OSS 역량은 단순 설치보다 라이선스와 구조를 이해하고, 여러 프로젝트를 하나의 흐름으로 통합하며, 발견한 문제를 테스트·문서·모듈 또는 PR로 다시 기여하는 과정으로 평가합니다.

