# AGENT SKILLS

AI 코딩 에이전트를 위한 스킬 모음입니다. 스킬은 에이전트의 역량을 확장하는 패키지된 지침과 스크립트입니다.
이 레포지토리는 [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills/)의 react-best-practices를 한국어로 번역한 내용입니다.

스킬은 [Agent Skills](https://agentskills.io/) 형식을 따릅니다.

## 사용 가능한 스킬

### react-best-practices

Vercel Engineering의 React 및 Next.js 성능 최적화 가이드라인입니다. 영향도에 따라 우선순위를 둔 8개 카테고리의 40개 이상 규칙을 포함합니다.

**다음 상황에서 사용:**

- 새로운 React 컴포넌트 또는 Next.js 페이지 작성
- 데이터 페칭 구현(클라이언트 또는 서버 사이드)
- 성능 문제 코드 리뷰
- 번들 크기 또는 로딩 시간 최적화

**포함된 카테고리:**

- 워터폴 제거 (Critical)
- 번들 크기 최적화 (Critical)
- 서버 사이드 성능 (High)
- 클라이언트 사이드 데이터 페칭 (Medium-High)
- 리렌더 최적화 (Medium)
- 렌더링 성능 (Medium)
- JavaScript 마이크로 최적화 (Low-Medium)

### composition-patterns

확장 가능한 React composition 패턴입니다. compound 컴포넌트, 상태 끌어올리기, 내부 구성으로 boolean prop 남발을 피하도록 돕습니다.

**다음 상황에서 사용:**

- 불리언 prop이 많은 컴포넌트 리팩터링
- 재사용 가능한 컴포넌트 라이브러리 구축
- 유연한 API 설계
- 컴포넌트 아키텍처 리뷰

**포함된 패턴:**

- compound 컴포넌트 추출
- prop을 줄이기 위한 상태 끌어올리기
- 유연성을 위한 내부 구성
- prop drilling 방지
