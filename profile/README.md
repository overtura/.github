# Overtura

작고 병렬적인 Codex 기반 사이드 프로젝트를 모으는 개인 실험 조직입니다.
Overtura는 작은 아이디어를 실행 가능한 도구, 템플릿, 시각 실험, 워크플로 실험으로 빠르게 옮겨 보는 공간입니다.

## 이 조직의 방향

- 작은 MVP를 빠르게 만들고 실제로 실행되는 흐름을 우선합니다.
- 각 실험은 작게 나누고 리뷰 가능한 범위로 유지합니다.
- 완벽한 아키텍처보다 사용자가 눌러 보고 확인할 수 있는 결과를 먼저 둡니다.
- Codex-assisted development를 기본 작업 방식으로 사용합니다.
- 내부 실험 중 외부에서도 쓸모 있는 부분만 공개 저장소로 승격합니다.

## 공개 저장소

| 저장소 | 유형 | 설명 |
|---|---|---|
| [living-shader-gallery](https://github.com/overtura/living-shader-gallery) | Web / Visualization | React Three Fiber 기반 인터랙티브 셰이더 갤러리와 self-improving visual PR 실험 |
| [github-activity-galaxy](https://github.com/overtura/github-activity-galaxy) | Web / Visualization | GitHub 활동 데이터를 은하처럼 시각화하는 3D activity map 실험 |
| [css-only-escape-room](https://github.com/overtura/css-only-escape-room) | No-JS / Game | HTML/CSS만으로 만드는 퍼즐형 escape room 실험 |
| [css-scroll-odyssey](https://github.com/overtura/css-scroll-odyssey) | No-JS / Story | JavaScript 없이 CSS scroll-driven animation으로 만드는 인터랙티브 스토리 |
| [native-html-ui-kit](https://github.com/overtura/native-html-ui-kit) | No-JS / UI Kit | `popover`, `details`, `commandfor` 등 native HTML 중심 UI kit |
| [no-js-visual-lab](https://github.com/overtura/no-js-visual-lab) | No-JS / UI Lab | 최신 HTML/CSS만으로 인터랙티브 UI를 만드는 visual lab |
| [repo-health-bot](https://github.com/overtura/repo-health-bot) | CLI / Automation | 저장소 건강 상태 점검과 Codex 자가 개선 루프 실험용 Python CLI |
| [action-ledger](https://github.com/overtura/action-ledger) | CLI / Report | Markdown 작업 항목을 스캔하고 한국어 유지보수 보고서를 생성하는 Python CLI |
| [template-web](https://github.com/overtura/template-web) | Template | 브라우저 앱, 디자인 툴, WebGPU UI 실험용 React/Vite starter |
| [template-node](https://github.com/overtura/template-node) | Template | CLI, 라이브러리, API, 운영 도구용 TypeScript Node starter |
| [.github](https://github.com/overtura/.github) | Ops | 공통 issue/PR template, profile README, 조직 기본 규칙 |

## 프로젝트가 공개되기까지

1. 작은 비공개 실험으로 시작합니다.
2. 첫 번째 runnable flow를 만듭니다.
3. README와 PR 노트에는 실행 방법과 검증 방법을 먼저 적습니다.
4. 외부에서도 재사용할 수 있는 부분만 공개 저장소로 전환합니다.
5. 공개 이후에는 작은 PR 단위로 문서, 검증, 사용자 흐름을 계속 정리합니다.

## 작업 방식

- 1 thread = 1 PR
- 작은 범위 먼저
- 한국어 리뷰 기본
- 빠른 검증, 빠른 정리
- 막연한 진행 상황보다 재현 가능한 검증 기록 우선
