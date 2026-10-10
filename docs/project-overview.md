# 현재 프로젝트 개요

## P1 · 세계여행 영어회화 + AI 동반자

- 경험: 뉴욕 카페에서 AI 친구와 음성으로 대화하고 학습 오류를 다음 장면의 복습에 반영
- AI: faster-whisper 기반 STT, LLM 대화, Piper TTS, 대화 기억 RAG, 오류 진단
- OSS: faster-whisper, Ollama, Piper, Chroma/FAISS, LangGraph, Godot
- 증명할 역량: 음성 파이프라인 통합, WER·응답 지연·오류 탐지 F1 측정과 개선
- 저장소: [`scene-speak-ai`](https://github.com/jngbnss/scene-speak-ai)

## P2 · AI 추리 수사 + 방탈출

- 경험: 고정된 사건 진실 위에서 용의자를 자유 심문하고 증거를 모아 범인을 추리
- AI: 인물별 지식 경계를 가진 에이전트, 증거 RAG, 누설 방지, 추리 근거 검증
- OSS: LangGraph, Ollama, Chroma, Pydantic, Godot
- 증명할 역량: 모순율·비밀 누설률·증거 일치율을 평가하고 프롬프트와 검색 구조 개선
- 저장소: [`caseforge-ai`](https://github.com/jngbnss/caseforge-ai)

## P3 · AI 문학 세계 탐험

- 경험: 문학 작품 장면 속에서 등장인물과 대화하고 원문 근거와 AI 창작 분기를 구분
- AI: 원문 RAG, 인물 말투 제어, 선택형 분기 생성, 관계·주제 분석
- OSS: Ollama, Chroma, LangGraph, spaCy, NetworkX
- 증명할 역량: 원작 일치율·환각률·인물 일관성 평가와 근거 추적
- 저장소: [`litverse-ai`](https://github.com/jngbnss/litverse-ai)

## P4 · 제스처 홀로그램 + AI 공학 연구실

- 경험: 손동작으로 로봇팔과 기어를 조립·분해하고 실제 해석 결과를 AI가 설명
- AI: 손 랜드마크와 제스처 분류, 해석 도구 호출, 결과 설명, 센서 이상 탐지
- OSS: MediaPipe, Three.js, Rapier, Blender, CalculiX/OpenFOAM, Ollama
- 증명할 역량: 제스처 F1·조작 지연·도구 성공률·공학 결과 검증
- 저장소: [`holoforge-ai-lab`](https://github.com/jngbnss/holoforge-ai-lab)

## P5 · AI 2D→3D 인터랙티브 월드

- 경험: 그림을 배경에서 분리해 3D 캐릭터로 만들고 교육용 세계에서 조작
- AI: 객체 분할, 단일 이미지 3D 생성, 포즈 추정, 리깅 보조, 메시 오류 탐지
- OSS: TripoSR, SAM 계열, MMPose, Blender, Godot/Three.js
- 증명할 역량: 생성 시간·메시 오류율·리깅 성공률을 분리 측정하고 후처리 개선
- 저장소: [`draw2world-ai`](https://github.com/jngbnss/draw2world-ai)

## P6 · AI 쥬라기 생태계

- 경험: 포식자와 피식자가 사냥·도주·휴식을 반복하며 정책에 따른 생태계 변화를 관찰
- AI: 행동 트리와 학습 정책 비교, 다중 에이전트 강화학습, 개체수 시계열 예측
- OSS: Godot, LimboAI, Gymnasium, PettingZoo, RLlib, scikit-learn
- 증명할 역량: 생존율·사냥 성공률·학습 보상·처리량 비교
- 저장소: [`paleosphere-ai`](https://github.com/jngbnss/paleosphere-ai)

## P7 · AI 디지털 트윈 + 조종 시뮬레이터

- 경험: 굴착기를 조종하며 장애물, 센서 이상, 작업 성과를 실시간으로 확인
- AI: 위험 객체 탐지, 진동·센서 이상 탐지, 조종 정책 또는 다음 상태 예측
- OSS: ROS 2, Gazebo, OpenCV, YOLO 계열, Stable-Baselines3
- 증명할 역량: 위험 재현율·오경보율·동기화 지연 측정과 시뮬레이터 어댑터 개발
- 저장소: [`twinpilot-ai`](https://github.com/jngbnss/twinpilot-ai)

## P8 · AI 레이싱 게임 + 주행 에이전트

- 경험: 브라우저 레이싱 게임에서 규칙 기반 상대와 학습형 상대의 주행을 비교
- AI: PPO/SAC 주행 정책, 텔레메트리 분석, 코너·충돌 원인 분석
- OSS: Three.js, Rapier, Gymnasium, Stable-Baselines3, OpenStreetMap
- 증명할 역량: 완주율·랩타임·충돌률을 기준으로 정책의 개선 결과 비교
- 저장소: [`f1`](https://github.com/jngbnss/f1)
- 실행: [레이싱 게임](https://jngbnss.github.io/f1/)

## 현재 우선순위

가중 총점 기준 순서는 P2 → P1 → P4 → P7 → P6 → P5 → P3 → P8입니다. 다만 P8은 실제 동작하는 게임 기반이 있다는 장점이 있고, AI 핵심성이 아직 증명되지 않았기 때문에 보수적으로 평가했습니다.

