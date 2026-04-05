# Contributing

## 기본 작업 원칙
- 1 thread = 1 PR
- issue 하나 = PR 하나
- 작은 범위로 먼저 완성
- 코드 스타일 논쟁보다 broken flow, regression, failure handling 누락을 우선 수정

## PR 열기 전 필수
- 가능한 범위에서 lint / typecheck / test / build 수행
- README의 실행 방법과 핵심 동작 갱신
- PR 본문을 한국어로 작성
- 검증 방법을 재현 가능하게 작성

## Commit / Branch
- branch: `feat/<issue-number>-<slug>`, `fix/<issue-number>-<slug>`
- commit: conventional commits
  - `feat(scope): 설명`
  - `fix(scope): 설명`
  - `docs(scope): 설명`
  - `chore(scope): 설명`

## Review focus
리뷰는 아래 순서로 본다.
1. 기능 회귀
2. 깨진 사용자 flow
3. 실패/빈 상태 누락
4. 타입/빌드 오류 가능성
5. 테스트 누락
