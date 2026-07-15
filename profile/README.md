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
| [aura-bloom](https://github.com/overtura/aura-bloom) | Web / Generative Art | 문장을 브라우저 로컬 임베딩으로 해석해 결정적 3D 오라로 피워 내는 프라이버시 우선 시각화 도구 |
| [digital-sigil](https://github.com/overtura/digital-sigil) | Web / Local AI | [디지털 시길](https://digital-sigil.vercel.app/) — 단어나 짧은 문구의 의미를 브라우저 안에서 결정적인 추상 기하 SVG와 PNG로 만드는 로컬 디지털 아트 도구 |
| [mood-bloom](https://github.com/overtura/mood-bloom) | Web / Generative Garden | [무드 블룸](https://mood-bloom-seven.vercel.app/) — 하루의 한 문장을 기기 안에서 결정적 디지털 식물로 피우는 개인 정원 |
| [today-shagal-explosion](https://github.com/okorion/today-shagal-explosion) | Web / Local AI | [오늘의 샤갈 폭발](https://today-shagal-explosion.vercel.app/) — 짜증나는 한 줄을 로컬 분석과 결정론적 캔버스 폭발 포스터로 바꾸는 밈 도구 |
| [shagal-court](https://github.com/overtura/shagal-court) | Web / Local AI | [샤갈 재판소](https://shagal-court.vercel.app/) — 억울한 한 줄을 브라우저 안에서 판결하고, 동의한 사건만 익명으로 공유하는 개인정보 보호 중심 밈 재판소 |
| [living-shader-gallery](https://github.com/overtura/living-shader-gallery) | Web / Visualization | React Three Fiber 기반 인터랙티브 셰이더 갤러리와 self-improving visual PR 실험 |
| [github-activity-galaxy](https://github.com/overtura/github-activity-galaxy) | Web / Visualization | GitHub 활동 데이터를 은하처럼 시각화하는 3D activity map 실험 |
| [shagal-monster-dex](https://github.com/overtura/shagal-monster-dex) | Web / Local AI | [샤갈 몬스터 도감](https://shagal-monster-dex.vercel.app/) — 한국어 문장을 브라우저에서 분석해 결정론적 SVG 몬스터로 만드는 로컬 도감 |
| [css-only-escape-room](https://github.com/overtura/css-only-escape-room) | No-JS / Game | HTML/CSS만으로 만드는 퍼즐형 escape room 실험 |
| [css-scroll-odyssey](https://github.com/overtura/css-scroll-odyssey) | No-JS / Story | JavaScript 없이 CSS scroll-driven animation으로 만드는 인터랙티브 스토리 |
| [native-html-ui-kit](https://github.com/overtura/native-html-ui-kit) | No-JS / UI Kit | `popover`, `details`, `commandfor` 등 native HTML 중심 UI kit |
| [no-js-visual-lab](https://github.com/overtura/no-js-visual-lab) | No-JS / UI Lab | 최신 HTML/CSS만으로 인터랙티브 UI를 만드는 visual lab |
| [repo-health-bot](https://github.com/overtura/repo-health-bot) | CLI / Automation | 저장소 건강 상태 점검과 Codex 자가 개선 루프 실험용 Python CLI |
| [action-ledger](https://github.com/overtura/action-ledger) | CLI / Report | Markdown 작업 항목을 스캔하고 한국어 유지보수 보고서를 생성하는 Python CLI |
| [template-web](https://github.com/overtura/template-web) | Template | 브라우저 앱, 디자인 툴, WebGPU UI 실험용 React/Vite starter |
| [template-node](https://github.com/overtura/template-node) | Template | CLI, 라이브러리, API, 운영 도구용 TypeScript Node starter |
| [.github](https://github.com/overtura/.github) | Ops | 공통 issue/PR template, profile README, 조직 기본 규칙 |

## Vercel 배포 현황

아래 열두 개 웹 프로젝트는 `vercel.json` 기반 Vite 정적 배포 설정을 갖는다. build command는 `pnpm build`, output directory는 `dist`다.

| 저장소 | 배포 상태 | 비고 |
|---|---|---|
| Aura Bloom | [배포 완료](https://aura-bloom-overtura.vercel.app/) | 브라우저 로컬 임베딩·결정적 3D 오라 생성 |
| 디지털 시길 | [배포 완료](https://digital-sigil.vercel.app/) | 한국어 문구·브라우저 로컬 분석·결정적 추상 기하 SVG/PNG 생성 |
| 무드 블룸 | [배포 완료](https://mood-bloom-seven.vercel.app/) | 한국어 문장·결정적 디지털 식물·브라우저 로컬 저장 |
| 오늘의 샤갈 폭발 | [배포 완료](https://today-shagal-explosion.vercel.app/) | 한국어 로컬 분석·결정론적 캔버스 폭발·브라우저 로컬 저장 |
| 샤갈 재판소 | [배포 완료](https://shagal-court.vercel.app/) | 한국어 로컬 판결·개인정보 보호 중심·Cloudflare 공개 기능 분리 |
| living-shader-gallery | 준비 완료, URL 대기 | Vercel CLI 로그인 또는 `VERCEL_TOKEN` 설정 후 production 배포 |
| github-activity-galaxy | 준비 완료, URL 대기 | Vercel CLI 로그인 또는 `VERCEL_TOKEN` 설정 후 production 배포 |
| no-js-visual-lab | 준비 완료, URL 대기 | no-JS dist 검증 후 production 배포 |
| css-scroll-odyssey | 준비 완료, URL 대기 | no-JS dist 검증 후 production 배포 |
| native-html-ui-kit | 준비 완료, URL 대기 | no-JS dist 검증 후 production 배포 |
| css-only-escape-room | 준비 완료, URL 대기 | no-JS dist 검증 후 production 배포 |
| 샤갈 몬스터 도감 | [배포 완료](https://shagal-monster-dex.vercel.app/) | 한국어 로컬 분석·결정론적 SVG 몬스터 도감 |

배포 URL이 확정된 프로젝트는 상태 링크에서 바로 서비스를 확인할 수 있다. URL 대기 프로젝트는 Vercel CLI 로그인 또는 `VERCEL_TOKEN` 설정 후 production 배포한다.

## 자가 개선 운영 원칙

- 중앙 control plane: [`okorion/self-improving-maintainer-bot`](https://github.com/okorion/self-improving-maintainer-bot)
- 각 레포는 자기 README, DESIGN 문서, 소스 구조, 최근 병합 PR만 기준으로 독립적인 개선 후보를 찾는다.
- 다른 레포의 최근 PR 주제를 따라 하거나 병렬 실행 순서 때문에 같은 주제로 수렴하지 않도록 target profile에 project concept, improvement focus, avoid topics를 둔다.
- 공개 PR 본문과 댓글에는 로컬 절대경로, patch/risk/red-team report, scheduler log를 남기지 않는다.
- 가능한 경우 변경 전/후 캡처를 Codex capture-artifacts manifest에 보존하고, PR에는 파일명과 보존 여부만 기록한다.

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
